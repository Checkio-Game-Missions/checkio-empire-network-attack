We are given information about the connections in the network and the security level for each computer.
The security level is the time (in minutes) that is required for a virus to capture a machine.
Capture time is not related to the number of infected computers attacking the machine.
Infection begins with the 0th computer which was already infected at the start of the test.
Connections in the network are undirected. Security levels are not equal to zero (except for the infected).

Information about a network is represented as a matrix NxN in size, where  **N** is the number of computers.
If the **i**th computer connected with **j**th computer, then `matrix[i][j] == matrix[j][i] == 1`, else 0.
Security levels are placed in the main matrix diagonal, so matrix[i][i] is the security level for the **i**th computer.

You should calculate how much time is required to capture the whole network in minutes.
