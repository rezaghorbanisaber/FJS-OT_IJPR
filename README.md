Data are structured as follow:

Section "Shifts":
Containing the indices of shifts

section "Duration of Shifts":
Containing the duration of the shifts (Parameter Delta), ordered based on shifts indices

Section "Jobs":
Containing the indices of jobs

Section "DueDates":
Containing the due dates of each job, respectively

Section "Weights":
Containing the relative weight of each job, respectively

Section "List of Machines":
Containing the indices of machines

Section "Operations per job":
Each line in this section indicates the indices of the operations of a job
Lines are ordered based on jobs indices

Section "Predecessors":
Each line in this section indicates the indices of predecessors of an operations
Lines are ordered baed on operations indices
Lines without any value indicate there is no predecessor

Section "Machines per operation":
Each line in this section indicates the indices of eligible machines for processing an operations
Lines are ordered baed on operations indices

Section "Processing Times":
The lines of the matrix in this section indicate operations and columns indicate machines. 
Value of cells are processing time of the correspinding operation on the corresponding machine (Zero means the operation cannot be processed on the machine)

Section "Worker":
Containing indices of workers

Section"workers-Machines":
Each line indicates the indices of machines that can be processed by a worker.
Lines are ordered based on worker indices
