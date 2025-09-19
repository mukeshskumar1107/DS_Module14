# Ex10 Applications of Queue – FCFS
## DATE: 16-03-2025
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1. Start with process, burst time, and waiting time arrays. 
2. Loop through each process from i = 0 to n-1. 
3. Compute tat[i] = burst_time[i] + wait_time[i]. 
4. End the algorithm.  

## Program:
```c
/*
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
Developed by: MUKESH KUMAR S
RegisterNumber: 212223240099
*/

/*#include <stdio.h>*/
int turnaroundtime(int proc[], int n, int burst_time[], int wait_time[], int tat[])
{
    // calculating turnaround time by adding
    // burst_time[i] + wait_time[i]
    int i;
    for (i = 0; i < n; i++)
    {
        tat[i] = burst_time[i] + wait_time[i];
    }
    return 0;
}
```

## Output:
<img width="901" height="774" alt="image" src="https://github.com/user-attachments/assets/763838ee-5b6f-4f9d-b829-54e9e5a39f14" />



## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
