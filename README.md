# ExternalGoogleFileWarning
This simple Chrome extension displays a popup inside Chrome whenever a user:
<ul>
  <li>opens an externally owned Google Drive file</li>
  <li>opens any Google Form</li>
</ul>
<br>
<br>
Notes:<br>
<ul>
  <li>in the case of Google Drive files, ensure you have <i><a href="https://admin.google.com/ac/managedsettings/55656082996/sharing">Apps > Google Workspace > Drive and Docs > Sharing settings</a> > Highlight external files</i> set to <b>ON</b> for all users <i>(required for this extension to function correctly!)</i></li>
  <li>in the case of Forms, the popup will display where the Form is owned (your domain, another domain, or outside your domain)</li>
</ul> 

<br>
<br>
<h3>To force-install this Chrome extension for your users</h3>
<ol>
  <li>In Google Admin, navigate to <i><a href="https://admin.google.com/ac/chrome/apps/user">Devices > Chrome > Apps & extensions > Users & browsers</a></i>
  <li>Locate the OU where you want to force-install the extension</li>
  <li>Click <i>Add (plus button) > Add Chrome app or extension by ID (grid button)</i></li>
  <li>Enter <code>pnceacndhdehnfoeiaiejlddpbkbbipl</code> in the "Extension ID" field</li>
  <li>Select "From a custom URL" and enter <code>https://kbbush.github.io/ExternalGoogleFileWarning/update.xml</code></li>
  <li>Click <b>Save</b></li>
  <li>In the right side panel select:</li>
  <ul>
    <li>Installation policy = <b>Force install</b></li>
    <li>Incognito mode = <b>Extension is mandatory for Incognito ON</b></li>
    <li>Permissions and URL access = <b>Allow all permissions</b></li>
    <li>Update URL = <b>Installation URL (see above)</b></li>
  </ul></ol>
