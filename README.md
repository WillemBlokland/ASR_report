# ASR_report
Our code for the course 'Automatic speech recognition'

To look at the results for the first research question, stored in 'RQ1_ASR_FinalProject.ipynb' please obtain the 'Italian voice and speech' dataset from: https://huggingface.co/datasets/birgermoell/Italian_Parkinsons_Voice_and_Speech/tree/70d1714cf738b248d687b003551351cbe37e0298/italian_parkinson
which is required to be able to run the notebook.

For the results of the second notebook, which are stored in
'ASR_MDVR_KCL experiments_acoustic_features_chunks.ipynb'
'ASR_MDVR_KCL experiments_acoustic_features_mfcc_chunks.ipynb' and 
'ASR_MDVR_KCL_sel_features_chunks.ipynb' you can open them and see the results. 
Each file corresponds to one of the three experiments, which are 1. acoustic only features, 2. acoustic + mfcc and 3. top 10 selected features using ANOVA. To run them yourself, please make use of the repository from Toye and Kompalli (2021), which can be found here: https://github.com/aeesha-T/parkinsons_prediction_using_speech

Then add the notebooks in the 'Modelling' folder and run them.


To look at the code for the third research question, stored in 'RQ3_PD_Speech_Generalization.ipynb', first  obtain the Italian speech dataset from HuggingFace: https://huggingface.co/datasets/birgermoell/Italian_Parkinsons_Voice_and_Speech
Download the folder italian_parkinson containing:

/PD/... → Parkinson speakers
/Healthy/... → Healthy controls
Extract the .wav files locally and place them in a folder named:

/data/Italian_Healthy
/data/Italian_PD
Also make sure you include an English test set (the UCI Parkinson dataset, structured similarly:

/data/English_Healthy
/data/English_PD

