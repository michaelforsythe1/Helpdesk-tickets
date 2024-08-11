<h1>Helpdesk ticket support</h1>

<h2>Description</h2>
In this lab, I made a demo of how to assist a user remotely, using Spicework’s remote support feature. Since I am on the free version, I had limited access to its features. 
<br />


<h2>Prerequisites</h2>

- *Windows 10 client- Virtual Machine*



<h2>Project walkthrough</h2>

<br/>Launch the Cloud-based helpdesk from the official Spicework website, spicework.com from the IT tools dropdown.
From the Remote Support page, ‘start remote session’ <br/>
 <br/>
<img src="https://i.postimg.cc/vTnRChFd/Remote-support.png" height="60%" width="60%" alt="remote support"/>
<br />
 <br/> The Start remote session generates a key, as a Support Technician, we provide the user with a session key, like the one shown below. <br/>
 <br/>
<img src="https://i.postimg.cc/Sxk0tcgw/Session-key.png" height="60%" width="60%" alt="session key"/>
<br />
<br />

Chad, a fictional character, will be the user. Chad goes to join.zoho.com/788898190, types the session keyin the session key, and allows the zoho to establish a connection.  <br/>
 <br/>
<img src="https://i.postimg.cc/rFzRRtG2/User-keys-in.png" height="60%" width="60%" alt="user joins session"/>
<br />
<br />
A connection has been established so we can start troubleshooting. <br/>
 <br/>
<img src="https://i.postimg.cc/0N98mTgK/User-connected.png" height="60%" width="60%" alt="connection established"/>
<br />

<h3>Exploring Features of Spiceworks</h3>

<br />
We can lock down the user’s system from here or view the Task Manager  <br/>
 <br/>
<img src="https://i.postimg.cc/vmpwhkkv/ctrl-alt-del.png" height="60%" width="60%" alt="lock screen option"/>
<br />
<br />
Launch the command line. <br />
<img src="https://i.postimg.cc/ZnHZDqbr/Screenshot-2024-07-28-153832.png" height="60%" width="60%" alt="allow IP and subnet"/>
<br />
<br />
View the Event viewer to see if any issues are logged <br />
 <br/>
<img src="https://i.postimg.cc/c4yMZhtb/Screenshot-2024-07-28-154130.png" height="60%" width="60%" alt="Deny ports"/>
<br />
<br />
Summary of configured rules  <br />
 <br/>
<img src="https://i.postimg.cc/hP14v4hq/Screenshot-2024-07-28-154251.png" height="60%" width="60%" alt="summary of rules"/>
<br />
<br />
Alternatively, the summary of configured rules can be viewed in numbered mode by using the command *‘sudo ufw status numbered’*. From here, we can easily delete a rule by specifying the rule number, e.g. *‘sudo ufw delete (2)’*  <br/>
 <br/>
<img src="https://i.postimg.cc/Yqjqy1F0/Screenshot-2024-07-28-154401.png" height="60%" width="60%" alt="specifying rule number"/>
<br />
<br />
Using rule specification  <br/>
 <br/>
<img src="https://i.postimg.cc/pdhpmNgY/Screenshot-2024-07-28-154608.png" height="60%" width="60%" alt="rule specs"/>
<br />
<br />
It is time to test the firewall rules from another system (Another VM hosting Linux Mint OS with the nmap utility installed). Nmap or Network Mapper is used for network discovery and security audits
 <br/>
<br/>
<img src="https://i.postimg.cc/sD5P2Nkh/Screenshot-2024-07-28-235330.png" height="80%" width="80%" alt="Test rules"/>
<br />

<h3>Conclusion</h3>
Document all rules you have added to UFW. This can be a simple text file listing each rule.
<br />
<br />
Document all added rules. This can be a simple text file listing each rule. 

This setup will help protect any network from unauthorised access and potential risks. 
However, a network administrator will continuously refine and reconfigure rules based on network needs.
<br />

