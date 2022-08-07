# android-client-server
Describes a simple Android Client Server Application

<h3>How to Run?</h3>

The repo contains two android projects. One is Server Application and the other is Client.<br/>
Run both applications on your devices.<br/>
For running locally, Find the IP of the device which is running the Server Application.<br/>
Change the <b>SERVER_IP</b> in the Client Application inside ClientActivity.<br/>

 <b>public static final String SERVER_IP = "192.168.1.155";</b>
 
<i>Make sure both devices are on the same network and are using the same PORT.</i><br/>
Go to the Client Application and tap "Connect Server"<br/>
It should show connected and now tap "Send Message to Server".<br/>

Open Server Application to see the message from Client.

If you are connecting to a Server, make sure the PORT you specified in the code is allowed to accept incoming socket connections.
<br/>Specify custom messages by entering the message in the TextField on both Applications.

<h3>Video Tutorial:</h3>
https://www.youtube.com/watch?v=xIWnFQ68Fco&ab_channel=MobileProgrammer
<br />
<h3>Written Article:</h3>
https://www.coderzheaven.com/2017/05/01/client-server-programming-in-android-send-message-to-the-client-and-back/
<br />
<h4>Server</h4>
<br />
<a href=""><img src="https://github.com/MrVipinVijayan/android-client-server/blob/main/Screenshots/server.png?raw=true" alt="drawing" style="width:300px;"/></a>
<h4>Client</h4>
<br />
<a href=""><img src="https://github.com/MrVipinVijayan/android-client-server/blob/main/Screenshots/client.png?raw=true" alt="drawing" style="width:300px;"/></a>
