# Sender-Receiver-IPC
<b>CPSC 351 - 01 Project 1</b>

<ins>Team Members: </ins>
<br>Ricardo Rodriguez - rvrodriguez2000@gmail.com
<br>Bonnie Yang - bonnie121024@csu.fullerton.edu
<br>James Ruiz - jruiz21@csu.fullerton.edu
<br>Kristin Valido - kristinvalido@csu.fullerton.edu 

<b>Project Description: </b>
<br>Using our knowledge of shared memory and message queues in order to implement an application which synchronously transfers files between two processes. Implementing two related programs: a sender program and the receiver program.

<b> How to run it: </b>

<ol>
  <li>Download the git folder - Design of Sender and Receiver, and make sure you're in the folder. If you do ls you should have Makefile, msg.h, recv.cpp, sender.cpp</li>
  <li>Open another terminal and do the same thing. This is important because one is the receiver and one is the sender.</li>
  <li>In one terinal you type ./recv and you'll see that nothing has changed. But if go to the second terminal and type ls you'll see there's a keyfile.txt</li>
  <li>In the second terminal, you'll type ./sender keytext.file , then you'll get "The number of bytes sent is 11"</li>
  <li>After this you can go back to your first terminal and control C to terminate the program</li>
</ol>
