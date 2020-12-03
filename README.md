# QOSF-Mentorship

The problem statement for the task can be found in the following google doc as Task 1: https://docs.google.com/document/d/1Ow3v8Y4rYBdgxXNxKV9ZUAM4bwL6211U6DWCcByZ4A4/edit 

The analysis of my code experiment is written here, as a quick way to analyse the results. It would help if you went through the Task1 notebook to understand the workflow. There is a python script which contains all the code mentioned in Task1.ipynb, please check the value of L before running the script.

I created 6 graphs to illustrate 6 scenarios, 
* Random Vector: 1010, Gates: Rx-Ry, Rx-Rz and Ry-Rz
* Random Vector: 1111, Gates: Rx-Ry, Rx-Rz and Ry-Rz
                                             
I did this because during my experimentation I noticed that the results were substantially different based on the symmetric nature of the given random vector. 
It speaks to the fact that it is difficult to generalize the output of the given circuit to a non-symmetric vector and easier for a symmetric vector. By symmetric vectors I'm referring
to |0000> and |1111>. 

The following graphs denote the scenarios mentioned above:

![Graphs](https://github.com/atagade/QOSF-Mentorship/blob/master/Graphs.png)

The graphs on top correspond to random vector |1010> and the ones on the bottom to |1111>, in the order of left to right Rx-Ry, Rx-Rz and Ry-Rz.
* For the purposes of the task, the middle row of graphs denote the scenario specified and we can see that the best results can be obtained on average with layers = 5. 
* In the case of Rx-Ry, the best result on average can be obtained with layers = 4. 
* In the case of Ry-Rz, the best result on average can be obtained with layers = 3.

It can also be seen that the epsilon values even in the worst case for the random vector |1010> are much higher than the ones with random vector as |1111>.
 

