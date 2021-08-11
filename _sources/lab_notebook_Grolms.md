# Lab Notebook Grolms
#### Week 1: 03.05. – 09.05.2021
- Starting a shared Zotero project together with Jakob and setting up a Git repository
- Discussing different research questions and methods that we are familiar with to find a topic for our project.
- searching for literature regarding the effects of psychotherapy and it’s effects on depression using fMRI

#### Week 2: 10.05. – 16.05.2021
-	Talking to Jakob how we approach the tasks for this week
-	Downloading the data and looking through it, needed multiple tries because the download stopped mid way through a few times
-	Setting up git kraken
-	Getting an overview again how pull requests work
-	Editing the data.md file
-	Searching for the full text of the published study from the data that we use to get missing information to fill out the preregistration
-	Filling out the pregregistration
-	Making hypothesis more precise but first we were not sure how similar our methods can be to the methods oft he published study.

#### Week 3: 17.05. – 23.05.2021
- asking Peer about the direction of the project and if it is acceptable if we replicate the analysis that was already done
- Discussing with Jakob if we want to try to replicate the findings in the original study and what we want to vary in comparison to the analysis that the authors did.
- While starting Docker an error accured that virtualization was not activated. Asking for help and contacting Thomas. Fixed it with him via Team Viewer. Something in the Docker Settings was not right.

#### Week 4: 24.05. – 30.05.2021
- doing literature search about replication studies and brain areas that are specific for depression

#### Week 5: 31.05. – 06.06.2021
- doing literature search about the effectiveness of psychotherapy

#### Week 6: 07.06. – 13.06.2021 
- Discussing with Jakob how we want to analyze the data, what in the original study is important for us and what information is still missing for us to start using the data.

#### Week 7: 14.06. – 20.06.2021
- having another error with Docker and contacting Thomas. This line and rebooting fixed it: bcdedit /set hypervisorlaunchtype off
- having a meeting with Christoph concerning the current status of the project and how we continue using mriqc
- trying to use mriqc
![jsondecodeerror](https://user-images.githubusercontent.com/83179199/129088201-c3a71c22-d2cb-4634-9a6b-51508c859423.PNG)
![Error docker quickstart](https://user-images.githubusercontent.com/83179199/129089823-713402e1-3c49-4cf2-930a-bb4a4b015201.PNG)

#### Week 8: 21.06. – 27.06.2021
- discussing data preprocessing with Christoph
- errror message in Docker occured while trying to use this line „docker run -it --rm -v <bids_dir>:/data:ro -v <output_dir>:/out poldracklab/mriqc:latest /data /out participant --participant_label sub-01“ with my file paths
- Seems like Docker cannot find the data
- tried to move the data to a different drive because my username on my laptop has a dash in it which could cause problems but it did not change anything.

#### Week 9: 28.06. – 04.07.2021
- writing with Thomas about the Docker error message.
- After trying a lot the same error message still occured.
- switching to Docker Desktop and deleting and installing Docker Toolbox again did not work.
- talking with Jakob about further steps in the data analysis
![Errormessage](https://user-images.githubusercontent.com/83179199/129087189-d9cc43ae-3421-49d2-870a-5f81d5d2dd48.PNG)
![Dash instead of underscore](https://user-images.githubusercontent.com/83179199/129087526-f0ee3f4c-6014-49bb-9bc7-ea5a9ac49d27.PNG)
![Dash instead of underscore correct](https://user-images.githubusercontent.com/83179199/129087535-d9357aa2-29f5-4252-9972-b3bf580b70d8.PNG)
![error without sub](https://user-images.githubusercontent.com/83179199/129087567-96fd0525-53d8-41d9-8995-c5f0ba03d933.PNG)
![data folder and dash](https://user-images.githubusercontent.com/83179199/129087859-921709f4-6fd0-4210-90f3-e4d8536956e6.PNG)
![moved to data](https://user-images.githubusercontent.com/83179199/129088543-5470f1f0-de78-4d6d-a441-d826b4c35780.PNG)
![data and dervivatives separated](https://user-images.githubusercontent.com/83179199/129087870-941769f3-9ea9-4dc5-8258-1da637bc86d9.PNG)
![fancy code from Thomas](https://user-images.githubusercontent.com/83179199/129087887-fd353fc2-9669-4241-9f41-9dca87c37510.PNG)
![without -v](https://user-images.githubusercontent.com/83179199/129088329-9401a453-668d-4828-84a3-fde51140cd86.PNG)

#### Week 10: 05.07. – 11.07.2021
- meeting with Christoph to discuss next steps with SPM/Nipype
- trying out Nipype
- going through the visual reports with Jakob and checking the data with regard to quality
- preparing a powerpoint presentation with the fMRI analysis steps that were done by the authors and how the data was obtained
- having another meeting with Christoph to check the quality of the data and plan the steps of the preprocessing with Nipype
- setting up a linux partition via virtual machine

#### Week 11: 12.07. - 18.07.2021
- installing the needed programs for linux
- trying mriqc, getting error messages that the "sub-01_task-rest_bold.nii.gz" file cannot be found, writing with Thomas but fixing it by myself by downloading the data again and not placing the derivatives folder into the same folder as the data.
-  trying to install spm and the MCR installer but getting the error message that no Java was found on this system
-  Searching in forums for people that had the same issue and how they fixed it.
-  Installing different versions of Java and different versions of Matlab Runtime but the MCR Installer seems to need Java 5 but it still does not work.
-  Fixing this problem by notes from Thomas that he sent Jakob.
![error linux file not found](https://user-images.githubusercontent.com/83179199/129088024-c8b563a2-cb32-4588-b2b7-ae941fe17464.PNG)
![Lunix file is there error message](https://user-images.githubusercontent.com/83179199/129088117-dd814910-a792-4763-b5cd-d64ff91d787d.PNG)


#### Week 12: 19.07. - 25.07.2021
- Meeting with Christoph to finish preprocessing, getting an error message and contacting Thomas.
- Fixing the error by myself by using a different version of spm and matlab runtime to run the notebook.
- Meeting with Christoph: checking the preprocessed data for plausibility, installing MRIcroGL and GIFT toolbox to do the ICA
- Trying to run the preprocessing but it crashed and by rebooting the virtual machine something went wrong and it was not possible to log in on linux anymore.
- Trying for a few hours to get the linux partition back.
- Getting the partition back with a slightly different layout.
- Trying out the ICA with the preprocessed data that Jakob sent me, intstalling GIPC for group comparisons
- Meeting with Christoph: doing the ICA with NILEARN and creating connectomes and correlation matrices
![error preprocessing LibGL error](https://user-images.githubusercontent.com/83179199/129087716-89816b0c-3fae-434b-978e-606d5376b77a.PNG)
![I broke linux](https://user-images.githubusercontent.com/83179199/129088765-e3151713-1e0f-4a5a-8b85-58d00661d09c.PNG)


#### Week 13: 26.07. - 01.08.2021
- Trying to add labels to the output of the correlation matrix
- Getting the error message the ICA was terminated because of excessive memory usage
- Meeting with Christoph again to finalize the labels of the output
- Contacting Thomas because of the error
- After trying a few things, increasing the swap file size fixed the issue.
- Working on poster design
- Adding commands in the notebook to save the output as jpg files
- Literature search about the replication crisis
- Writing introduction regarding the project and the relevancy
![memory error](https://user-images.githubusercontent.com/83179199/129088425-a481fa30-96d2-4d05-861d-375cc1da95e3.PNG)

#### Week 14 02.08. - 08.08.2021
- trying to change the size of the project logo
- working on the website
- evaluating our results, categorizing the brain areas into networks to compare the results to the results of the original study
- summarizing the results of the original study
- Literature search about brain networks and functions of certain areas that were relevant in our results
- Linux partition died again

![I broke linux](https://user-images.githubusercontent.com/83179199/129088845-476441fe-a21a-4c60-b639-d57d1184258f.PNG)


#### Week 15 09.08. - 15.08.2021
- Literature search
- working on poster
- discussing our results and comparing it to other studies
- writing conclusion
- creating memes
- preparing presentation for the talk
- updating minor things on the website
