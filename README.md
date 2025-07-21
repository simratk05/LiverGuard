# LiverGuard
The main aim of this project is to develop a kit for early detection of liver diseases using non-inavsive methods. I with my other teammates developed a prototype and used that to collect data from real patients, we collected data from Old-Age Homes and College Students. Then from this data we trained ML-Models to predict the if the person has liver disease or not. The Models were then deployed on a StreamLit website. 

WEBSITE LINK= https://liverguardmustan.streamlit.app/#early-warning-signs-of-liver-problems

<img width="1147" height="638" alt="image" src="https://github.com/user-attachments/assets/8c494e64-7388-4da2-961c-9fa9629e823e" />

## Architecture

Our Project was divided into three main Phases-
1) Hardware and sensor integration
2) Dataset-Collection
3) Frontend- Integration

<img width="729" height="630" alt="image" src="https://github.com/user-attachments/assets/cbf856e8-3bf5-4904-955c-4bbfcf1f6b9e" />

<img width="1129" height="630" alt="image" src="https://github.com/user-attachments/assets/44d82cba-967b-4d61-bc4f-4a2ce79916fa" />

## Hardware and Data-Collection

### Sensors Used=
<img width="1167" height="550" alt="image" src="https://github.com/user-attachments/assets/e3f6dc63-dd85-4100-bd98-0ccf1a9e02fc" />

### Final Hardware
<img width="1143" height="634" alt="image" src="https://github.com/user-attachments/assets/796a934a-cc19-4eb2-a1bd-037068367c5d" />

## Datset Collection-

We went to Old- Age homes for Liver Disease patients and Our College Campus for Healthy subjects.
<img width="1123" height="626" alt="image" src="https://github.com/user-attachments/assets/f1f8a03d-4671-45ac-8747-6ed77b1eff19" />

<img width="1131" height="630" alt="image" src="https://github.com/user-attachments/assets/bdb938b5-252b-4aa6-bad7-1257237a565d" />

The Interface for data collection.
<img width="1115" height="624" alt="image" src="https://github.com/user-attachments/assets/2d477dbe-9a29-445b-b44b-1a16fc90ca8d" />


## Models and ML Architecture

The data collected, then was compiled into a csv file. Then we Augemented the dataset, applied Pre-Processing techniques and then Models were applied.
Models applied were-
1) Random Forest
2) SVM (Support vector machines)
3) XG Boost (Poly and RBF)
4) CatBoost
5) Logistic Regression
Then stacking and voting was done on these models and results were generated.

<img width="1007" height="618" alt="image" src="https://github.com/user-attachments/assets/6d03805c-977a-49e4-a813-48e5fe4e385b" />

## Results

The Stacked Model and Voting gave approximately same results i.e Accuracy of 95% and RO-AUC Score of 0.98 (approx.)

<img width="1139" height="637" alt="image" src="https://github.com/user-attachments/assets/08747203-de84-499f-a1ad-54175da68887" />

<img width="1108" height="632" alt="image" src="https://github.com/user-attachments/assets/9940b155-0dce-493d-a7c1-37bdd9a79a2d" />








