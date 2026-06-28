# Digital Data Submission thesis Homesickness
This repository contains all data, information, and additional files needed to gain a comprehensive overview of my thesis.
Data includes analysis and transcription notebooks, raw and cleaned anonymized datasets, all correlation results and listening task results, a Figma Prototype source file and walkthrough video, mp3s of all recordings used in listening tasks, and images of all Figma prototype screens.

## Data Analysis
Data analysis was done through the 01_data_analysis.ipynb script, by using cleaned_ListeningTaskFinalAnonymized and cleaned_PreQuestionnaireAnonymized, but in non-anonymized versions containing identifiers which will are included in this repository. 
Comprehensive comments in 01_data_analysis.ipynb show when, where, and why specific data cleaning was done

## Transcription
Transcription of all 11 participant interviews and 3 think-aloud sessions was done fully locally by using the 02_transcription_script.ipynb. As the comments in this script state, different languages for transcription could be specified, as well as the file names for the transcription of the correct file and storage under a specified name.

All 11 interview transcripts can be found under INTERVIEWTRANSCRIPT1.pdf through INTERVIEWTRANSCRIPT13.pdf. All 3 think-aloud transcripts can be found under THINKALOUDTRANSCRIPT1.pdf through THINKALOUDTRANSCRIPT3.pdf. The highlighted text (purple-ish), is of the interviewer. All other text, so the unhighlighted text, is of the interviewee.

## Recordings and their labels
Rec1.wav through Rec23.wav contain the audio of the 23 unique voice recordings used during the listening task within the interviews. The following descriptions correspond with those recordings:
\
Rec1 - Weather report about France, in French. \
Rec2 - Historical speech about France by Simone Veil, in French. \
Rec3 - Weather report about USA, in American English. \
Rec4 - Weather report about the Netherlands, in Dutch. \
Rec5 - Weather report about Bulgaria, in Bulgarian. \
Rec6 - Weather report about Iran, in Farsi. \
Rec7 - Weather report about Greece, in Greek. \
Rec8 - Weather report about Canada, in Canadian English. \
Rec9 - Weather report about Ireland, in Irish English. \
Rec10 - Historical speech about USA by John F. Kennedy, in American English, about going to the moon. \
Rec11 - Historical speech about the Netherlands by Queen Máxima der Nederlanden, in Dutch, about identification with the Netherlands. \
Rec12 - Historical speech about Bulgaria by Rumen Radev, in Bulgarian, about a progressive Bulgarian future. \
Rec13 - Historical speech about Iran by Ayatullah Khamenei, in Farsi, about assisting Palestine. \
Rec14 - Historical speech about Greece by Alexis Tsipras, in Greek, about the Greek government. \
Rec15 - Historical speech about Canada by Mark Carney, about stopping Canada's reliance on global institutions. \
Rec16 - Historical speech about Ireland by Mary Robinson, about her inauguration. \
Rec17 - National holiday video about Thanksgiving in the USA, in American English. \
Rec18 - National holiday video about Koningsdag in the Netherlands, in Dutch. \
Rec19 - National holiday video about Bulgarian Liberation Day, in Bulgarian. \
Rec20 - National holiday video about Iranian Nowruz, in Farsi. \
Rec21 - National holiday video about Greek Easter, in Greek. \
Rec22 - National holiday video about Canada Day, in Canadian English. \
Rec23 - National holiday video about St. Patrick's Day, in Irish English.

The means, variances, and standard deviations of each recording type for each variable, being personalness/genericness, meaningfulness, and supportiveness for coping with homesickness, can be seen in listening_task_means_sd_variance.csv.
### Extra note for correct interpretation of these results
listening_task_means_sd_variance.csv contains a column named 'Recording', which only contains the numbers 1 through 5; these correspond to recoring **categories**, not individual recordings as stated above. Each participant heard five recordings, one for each category. The recording categories are:
1. A speaker from a different country than your native country, talking in an unfamiliar language about the weather.
2. A speaker from a different country than your native country, giving a historical speech in an unfamiliar language.
3. A speaker from your native country, talking in your native language about the weather.
4. A speaker from your native country, talking in your native language about the weather.
5. A speaker from your native country, talking in your native language about the weather.

## Statistical Results
Correlation results between the average Utrecht Homesickness Scale scores and listening task results can be seen in UHS_correlation_results.csv. This csv contains columns Variable is, highlighting the specific variable the average UHS score is correlated with, Rho, containing the rho values, p-value, containing the p-values, and abs rho, containing the absolute rho values. In the column 'Variable is', if Rec is seen followed by a number (e.g. Rec 4), that means **category** of recording 4, not **specific** recording 4. The following variables are seen and correspond to these explanations in 'Variable is': \
avg_home_personalness - average personalness score for all three native recordings combined \
Rec 4 - Meaningfulness - average meaningfulness score for recording category 4 \
avg_personalness - average personalness score for all recordings combined \
Rec 3 - Supportiveness - average supportiveness for coping with homesickness score for recording category 4 \
avg_meaningfulness - average meaningfulness score for all recordings combined \
avg_home_meaningfulness - average meaningfulness score for all three native recordings combined \
Rec 5 - Meaningfulness - average meaningfulness score for recording category 5 \
avg_home_supportiveness - average supportiveness for coping with homesickness score for all three native recordings combined \
Rec 3 - Personalness - average personalness score for recording category 3 \
avg_supportiveness - average supportiveness for coping with homesickness score for all recordings combined

## Prototype
DiaryPrototypeWalkthrough shows interacting with all thirteen prototype screens. These screens can be statically seen in the images added to this repository under the same branch. 

### Prototype instructions
The prototype source file is found under the name DiaryPrototypeSource.fig. This can be ran through Figma, either online through their website or through the Figma app by downloading this file and opening it in Figma.






