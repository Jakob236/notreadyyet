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
-  installing different versions of Java and different versions of Matlab Runtime but the MCR Installer seems to need Java 5 but it still does not work
-  fixing this problem by notes from Thomas that he sent Jakob
