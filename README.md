![image](https://user-images.githubusercontent.com/75273945/135919026-94a4c5da-6c4b-466b-98a4-60609444965d.png)

<b><h3>General explanation of the program:</h3></b>
<h4>
<br>
1.Inside an ARP SPOOFER file configured 2 addresses one ip represents the address of the target you want to show it as the router, the other address will represent the router we want to update at a different physical address than it had in association with the same computer we are attacking.
<br>
2.When you run the program you will send an ARP request to the two specified targets, the router and the target computer, because the ARP protocol does not validate, we succeed to change the MAC association to IP in such a way that we can impersonate the router as an end machine and the target computer.
<br>
3.We create an object that can connect to the available services of the computer and enable the activation of the service called ROUTING AND REMOTE ACCESS.This is a service that allows us to impersonate a router in front of a target computer in a way that will not provoke or damage the connection between the target computer and the Internet.
<br>
4.When a KEYBOARD INTERRUPT exception is received, a process is started that corrects the values of the ARP table on the two devices that were damaged during the impersonation.
</h4>
