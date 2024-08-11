<h1>Helpdesk ticket support</h1>

<h2>Description</h2>
In this lab, I made a demo of assisting a user remotely with Spicework’s remote support feature. Since I am on the free version, I had limited access to its features. 
<br />

<h2>Prerequisites</h2>
<i>Windows 10 client- Virtual Machine</i>
<br />
<br />
<h2>Walkthrough</h2>
Launch the Cloud-based helpdesk from the official Spicework website, spicework.com from the IT tools dropdown.
From the Remote Support page, ‘start remote session’ <br/>
 <br/>
<img src="https://i.postimg.cc/vTnRChFd/Remote-support.png" height="60%" width="60%" alt="remote support"/>
<br />
<br/> The Start remote session generates a key, as a Support Technician, we provide the user with a session key, like the one shown below. 
<br/>
<br/>
<img src="https://i.postimg.cc/Sxk0tcgw/Session-key.png" height="60%" width="60%" alt="session key"/>
<br />
<br />
Chad, a fictional character, will be the user. Chad goes to <b><i>join.zoho.com/788898190</i></b>, types the session key in the session key, and allows Zoho to establish a connection.  
<br/>
 <br/>
<img src="https://i.postimg.cc/rFzRRtG2/User-keys-in.png" height="60%" width="60%" alt="user joins session"/>
<br />
<br />
A connection has been established so we can start troubleshooting. <br/>
 <br/>
<img src="https://i.postimg.cc/0N98mTgK/User-connected.png" height="60%" width="60%" alt="connection established"/>
<br />
<h3><b>Exploring Features of Spiceworks</b></h3>
<br />
We can lock down the user’s system from here or view the Task Manager  <br/>
 <br/>
<img src="https://i.postimg.cc/vmpwhkkv/ctrl-alt-del.png" height="60%" width="60%" alt="lock screen option"/>
<br />
<br />
Launch the command line. 
<br />
<br />
<img src="https://i.postimg.cc/q769NQq6/Launch-cmd.png" height="60%" width="60%" alt="allow IP and subnet"/>
<br />
<br />
View the Event viewer to see if any issues are logged <br />
 <br/>
<img src="https://i.postimg.cc/L6Gmsq6X/Launch-event-viewer.png" height="60%" width="60%" alt="Deny ports"/>
<br />
<br />
Reboot into Safe Mode for advanced troubleshooting. A premium feature. 
 <br />
 <br/>
<img src="https://i.postimg.cc/9fC54y3W/Reboot-in-safe-mode-premium-feature.png" height="60%" width="60%" alt="summary of rules"/>
<br />
<br />
For those cases of escalating issues to a higher-tier technician  <br/>
 <br/>
<img src="https://i.postimg.cc/3JvPntY8/Escalate-to-Tier-2.png" height="60%" width="60%" alt="specifying rule number"/>
<br />
 <br/>
<img src="https://i.postimg.cc/6QYSySL0/Session-ended-user-sys.png" height="60%" width="60%" alt="specifying rule number"/>
<br />
<h3>Conclusion</h3>
There are various types of helpdesk ticketing systems out there, companies will have their preference but they have a function in common - to help users with their technical issues
This is not an actual live support project but a feature run-through of what a helpdesk ticketing system will look like<br/>
<br />



