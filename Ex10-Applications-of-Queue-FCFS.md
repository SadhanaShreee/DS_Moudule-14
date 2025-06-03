# Ex10 Applications of Queue – FCFS
## DATE: 12/03/2025
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.

## Algorithm
1. Start with process, burst time, and waiting time arrays.
2. Loop through each process from i = 0 to n-1.
3. Compute tat[i] = burst_time[i] + wait_time[i].
4. End the algorithm.
  

## Program:
```

Program to find and display the priority of the operator in the given Postfix expression
Developed by: SADHANA SHREE B
RegisterNumber: 212223230177

#include <stdio.h>
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) { 
   // calculating turnaround time by adding 
   // burst_time[i] + wait_time[i] 
   int i; 
   for ( i = 0; i < n ; i++) 
   tat[i] = burst_time[i] + wait_time[i]; 
   return 0; 

```

## Output:

![Screenshot 2025-05-18 120745](https://github.com/user-attachments/assets/333c5482-71ed-4d7d-bb35-85643d624387)




## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
