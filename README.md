# AIIB23 (Airway-Informed Quantitative CT Imaging Biomarker for Fibrotic Lung Disease-MICCAI2023)
![image](images/main.png)
## Context 
Airway-related quantitative imaging biomarkers (QIB) are crucial for examination, diagnosis, and prognosis in lung diseases, while the manual delineation of airway structures is unduly burdensome. Competitors are encouraged to devise automatic airway segmentation models with high robustness and generalization abilities. This challenge is an open-call challenge and new submissions are allowed after the conference.  
## How to participate in AIIB23?  
Register the challenge from https://codalab.lisn.upsaclay.fr/competitions/13076#participate  
**It is of note that you need to send the registeration form to the organizers.**
## How to pakage and submit docker files 
1. Prepare the dockerfiles as the following structure:
```
── Dockerdir
    ├── Dockerfile (this file includes your basic settings)
    └── requirements.txt (this file includes the list of your python packages)
    ├── ...
    └── predict.py
``` 
2. Build the docker  
```docker build -t YOUR_TEAM_NAME .```
3. Save the docker  
```docker save YOUR_TEAM_NAME:latest -o teamname.tar.gz```
4. Send the packed docker and instructions to the organizers, please test the container file first before sending to us.
