# CloudAssignment
Custom topology using mininet.<br>
Name: Vibhav Srivastava<br>
Roll No.: 201156030<br>

To Run:

sudo python topology.py <number of switches> <number of hosts per switch><br>
The topology gets loaded and mininet console is opened.<br>

On another console run:<br>
1. Move into the pox directory located in the home directory. <br>
2. Type ./pox forwarding.l2_pairs<br>
This starts the pox controller for learning mechanism.<br>

On the mininet console:<br>
1. Type pingall to see the ping responses. Odd nodes ping to odd numbered nodes and even nodes ping to even numbered nodes only.<br>
2. Type iperf h1 h3 to see the t bandwidth allocated to the link. For odd numbered nodes, it is set to 1Mbps and for even numbered nodes, it is set to 2Mbps.<br>
