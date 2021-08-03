# Lab Notebook Thielmann

Week 1: 03.05. – 09.05.2021

Created a Zotero account and shared literature with Luca. Also created a repository on github.com.
We talked about different questions and methods, looking for a nice project we can manage and is not the same stuff we did before.
First idea of project was the effects of depression in combination with therapy in resting state. We searched for literature and data sets, without success.
So we decided to choose the resting state depression model without the therapy. 

Week 2: 10.05. – 16.05.2021

Talking to Luca how we approach the tasks for this week.
Downloading the data with some error and trials.
Setting up git kraken
Getting an overview again how pull requests work
Editing the .md files in our repository. Also with some trouble regarding to our push/pull in different branches. Took some time to solve.
Searching for the full text of the published study from the data that we use to get missing information to fill out the preregistration
Filling out the pregregistration with open questions regarding the statistics in the progress of processing the data.
Making hypothesis more precise but first we were not sure how similar our methods can be to the methods oft he published study.

Week 3: 17.05. – 23.05.2021

Asking Peer about the direction of the project and if it is acceptable if we replicate the analysis that was already done
Discussing with Luca if we want to try to replicate the findings in the original study and what we want to vary in comparison to the analysis that the authors did.

Week 4: 24.05. – 30.05.2021

Doing literature search about replication studies and brain areas that are specific for depression

Week 5: 31.05. – 06.06.2021

Doing literature search about the effectiveness of psychotherapy

Week 6: 07.06. – 13.06.2021

Discussing with Jakob how we want to analyze the data, what in the original study is important for us and what information is still missing for us to start using the data.

Week 7: 14.06. – 20.06.2021

Meeting with Christoph regarding to Lucas issues with docker and errors. 
After the meeting I tried to use mirqc, used different commands but every time issues with the bids system (on windows).
Changed to Linux OS, problems were firstly the same. Solved after move the data to the OS disk and not saved on any partition in the system. Maybe something with access rights, the real problem was not solved but on the Linux partition it worked.
So let run the mriqc, took some time and worked without errors.

Week 8: 21.06. – 27.06.2021

Got a short introduction in the results of mriqc with our data. 
Did the mriqc group analyse too and the mriqception with jupyter notebook. 
Worked also very well and showed a nice overview of the groupd parameters. 

Week 9: 28.06. – 04.07.2021

Talking with Luca about further steps in the data analysis

Week 10: 05.07. – 11.07.2021

Meeting with Christoph to discuss next steps with SPM/Nipype
Checked all participants in mriqc results to exlude maybe participants with artifacts or too much movements. 
Luca checked 1-36, I checked 37-72. Participant number 39 moved very much. Average movement by the other participants and I'm not sure where's the line to exclude or not. 
Question for our next meeting with Christoph.
Checked the SPM standalone version.
Downloaded nypipe for python in anaconda. Tried to add my SPM path to nypipe. Without success.
Much time with troubleshooting.
Thomas made a instruction to install Matlab Runtime without the MCRinstaller.bin (missing java environment) and so at the end Nipype was ready to run.

Week 11: 12.07. - 18.07.2021
Worked for a long time with Christoph on the preprocessing script.
Made a preprocessing for all subjects with gunzip, realign, slice timing, normalisation and smoothing (8mm).
Checked the results in mrcicron. Realigned .nii seems to be a bit squeezed, no idea why. Smoothed .nii are looking fine.


Week 12: 19.07. - 25.07.2021
Downloaded Gift 3.0 for group ICA. Made some analysis with Gift and checked the different components.
After meeting with Christoph we decided to use Nilearn instead of Gift 3.0. 
Created/copied the ICA Nilearn script and let it run on all, only healthy and only depressive participants. 
Checked the results.

Looking for a tool to compare these group analysis with each other, decided to use "9.4.7. Group Sparse inverse covariance for multi-subject connectome".
