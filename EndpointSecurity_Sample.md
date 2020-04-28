<html>
<body> 
<h1> XYZ Endpoint Security </h1>
<h2> Overview </h2>
<p> This document describes the use and process of enabling the Hours of Operation setting on the Patch and Remediation agents in the XYZ Endpoint Security environment. </p>
<h3> About </h3>
<p> The Hours of Operation setting determines the time blocks during which a patch agent is enabled on its host endpoint. </p>
<p>Once the agent is enabled, it can do the following:</p>
<ol>
<li> Complete DAU scans and report the results to server </li> 
<li> Receive patch content deployments from the server </li>
<li> Recognize and implement any changes in patch policies </li>
</ol>
<p> When the agent is disabled, it will not execute any of the above tasks, except checking with the server to report its status. </p>
<h3> Benefits </h3>
<p> Enabling the Hours of Operation setting has the following benefits: </p>
<ul>
<li> Allow agents to work at optimal hours.</li>
<li> Saves network bandwidth.</li>
<li> Provides uninterrupted working time for employees. </li>
</ul>
<h2> Checking the status </h2>
<p> To check the status, do the following: </p>
<ol> <li> Navigate to <b> Web Console </b>> <b> Manage </b> > <b> Endpoints page </b> > <b> Patch and Remediation </b> tab. </li> 
<li> Check the status in the Agent Status and PR status columns.</li> </ol> 
<p><b>Note:</b></p>
<ul>
<li>Hours of Operation setting is based on the agent’s local time on the endpoint and not on the server’s local time. </li>
<li> It impacts the processes related to patch module. </li>
<li> Even when the agent is sleeping, the Antivirus definition updates, module installations, and endpoint upgrades still run. </li> </ul>

<h2> Applying Hours of Operation in an Agent Policy Set </h2>

<p> To apply the Hours of Operation setting in an agent policy set, perform the following steps: </p>

<ol>
<li>On the <b>Endpoint Security</b> server, log in to <b>Web Console</b>.</li>
<li>On the navigation menu, select <b>Manage</b> > <b>Agent Policy Sets.</b></li>
<li>On the next window that appears, click <b>Create</b>.</li>
<li>On the Create Agent Policy Set window, click <b>Define</b>.</li>
<li>Optionally, click <b>Reset</b> to reset all the fields.</li>
<li>Click <b>OK</b>.</li>
<li>Click <b>Save</b> and the window will close.</li>
<p>On the Agent Policy Sets window, a new row with the created policy set will appear.</p>
</ol>
<p>Changing Hours of Operation will take effect during the next heartbeat interval. This is when your agent checks in with your Endpoints Security server.
</p>
</body>
</html>
