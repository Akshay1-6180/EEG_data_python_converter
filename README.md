# EEG_data_python_converter
The problem that many students face is that the eeg data is in .set and .fdf format and they have to implement everything in matlab ,and if students dont know matlab it becomes very hectic .So this repository is aimed at converting any eeg type format from matlab to python using collab

The following repository contains the steps for setting up ur workshop so that u can work on EEG data for ur projects.One of the 
major drawbacks is that code is written in matlab and hence,u have to implement it in matlab format.
So the raw eeg data is usually present in .cnt,.fdt and .set
so the .fdf in this current example had the processes eeg data after removing the unused channels.There are 69 channels in .cnt 
and after preprocesssing it has 62 channels in .cnt<br>
So the steps required are<br>
1)copy the .set and .fdt files in the same folder<br>
2)set up eeglab in matlab and open the .set files which opens up the .fdt files<br>
3)next the variables will be available in matlab and u could download those variables<br>
4)import those variables in google drive and open them using loadmat ,and they are usually present in a list of lists so u have 
to extract them accordingly<br>
5)the following repository gives a examples on how to do it,the process is usally the same for the other cases
