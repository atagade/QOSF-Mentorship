# QOSF-Mentorship

The analysis of my code experiment is written here, as a quick way to analyse the results. It would help if you went through the Task1 notebook to understand the workflow. 

I created 6 graphs to illustrate 6 scenarios, *Random Vector: 1010, Gates: Rx-Ry, Rx-Rz and Ry-Rz
                                              *Random Vector: 1111, Gates: Rx-Ry, Rx-Rz and Ry-Rz
                                             
I did this because during my experimentation I noticed that the results were substantially different based on the symmetric nature of the given random vector. 
It speaks to the fact that it is difficult to generalize the output of the given circuit to a non-symmetric vector and easier for a symmetric vector. By symmetric vectors I'm referring
to |0000> and |1111>. 

The following graphs denote the scenarios mentioned above:

![Random Vector 1010, Rx-Ry](https://github.com/atagade/QOSF-Mentorship/blob/master/rand_1010rxry.png)
![Random Vector 1111, Rx-Ry](https://github.com/atagade/QOSF-Mentorship/blob/master/rand_1111rxry.png)
![Random Vector 1010, Rx-Rz](https://github.com/atagade/QOSF-Mentorship/blob/master/rand_1010rxrz.png)
![Random Vector 1111, Rx-Rz](https://github.com/atagade/QOSF-Mentorship/blob/master/rand_1111rxrz.png)
![Random Vector 1010, Ry-Rz](https://github.com/atagade/QOSF-Mentorship/blob/master/rand_1010ryrz.png)
![Random Vector 1111, Ry-Rz](https://github.com/atagade/QOSF-Mentorship/blob/master/rand_1111ryrz.png)

The graphs on the left correspond to random vector |1010> and the ones on the right to |1111>, in the order of top to bottom Rx-Ry, Rx-Rz and Ry-Rz.
For the purposes of the task, the middle row of graphs denote the scenario specified and we can see that the best results can be obtained on average with layers = 5. 
In the case of Rx-Ry, the best result on average can be obtained with layers = 4. 
In the case of Ry-Rz, the best result on average can be obtained with layers = 3.


 

