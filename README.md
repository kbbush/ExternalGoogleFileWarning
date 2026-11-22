# ExternalGoogleFileWarning
This simple Chrome extension displays a popup, warning the user to exercise caution, inside Chrome whenever a user:
<ul>
  <li>opens an externally owned Google Drive file <i>(owned by a user outside their domain/organization)</i></li>
  <li>opens any Google Form</li>
</ul>
<br>
<br>
<h3>Notes</h3>
<ul>
  <li>in the case of Google Drive files, ensure you have <i><a href="https://admin.google.com/ac/managedsettings/55656082996/sharing">Apps > Google Workspace > Drive and Docs > Sharing settings</a> > Highlight external files</i> set to <b>ON</b> for all users <i>(required for this extension to function correctly!)</i><br>
    <img width="932" height="82" alt="image" src="https://github.com/user-attachments/assets/fffc5c99-41ba-4134-8854-0081e12a311e" /></li>
  <li>in the case of Forms, the popup will display where the Form is owned (your domain, another domain, or outside your domain)<br>
  <img width="932" height="82" alt="image" src="https://github.com/user-attachments/assets/b4788dd6-b535-4b6f-a32d-322c708af6d2" /></li>
</ul> 

<br>
<br>
<h3>To force-install this Chrome extension for your users</h3>
<ol>
  <li>In Google Admin, navigate to <i><a href="https://admin.google.com/ac/chrome/apps/user">Devices > Chrome > Apps & extensions > Users & browsers</a></i>
  <li>Locate the OU where you want to force-install the extension</li>
  <li>Click <i>Add (plus button) > Add Chrome app or extension by ID (grid button)</i><br>
  <img width="56" height="56" alt="image" src="https://github.com/user-attachments/assets/ba07a44b-ca54-4475-a3fe-1d14d96d855d" />   <img width="40" height="40" alt="image" src="https://github.com/user-attachments/assets/9cfc8c6e-267c-4b23-80cc-59eb736b5ad8" />

</li>
  <li>Enter <code>pnceacndhdehnfoeiaiejlddpbkbbipl</code> in the "Extension ID" field</li>
  <li>Select "From a custom URL" and enter <code>https://kbbush.github.io/ExternalGoogleFileWarning/update.xml</code><br>
  <img width="600" height="453" alt="image" src="https://github.com/user-attachments/assets/ca2aeed3-a41e-4f7f-8a1b-08cf7497abed" /></li>
  <li>Click <b>Save</b></li>
  <li>In the right side panel select:</li>
  <ul>
    <li>Installation policy = <b>Force install</b></li>
    <li>Incognito mode = <b>Extension is mandatory for Incognito ON</b></li>
    <li>Permissions and URL access = <b>Allow all permissions</b></li>
    <li>Update URL = <b>Installation URL (see above)</b><br>
    <img width="412" height="1890" alt="image" src="https://github.com/user-attachments/assets/a25b65c9-be44-46ca-aabe-5b129bc1326e" /></li>
  </ul></ol>
<br>
<br>
<h3>Disclaimer</h3>
This Chrome extension is provided "as is" and "as available," without any warranties of any kind, either express or implied. This Chrome extension was developed using Gemini 3.1 Pro and 4 Hydrogen.<br>
<br>
This extension operates strictly on a read-only basis and does not modify, alter, or manipulate data on any website. All processing occurs locally within your browser; this extension does not collect, transmit, or share any user or browsing data with the publisher/author(s) or any third parties.<br>
<br>
By installing and using this extension, you acknowledge and agree that you do so at your own risk. The author(s) and contributor(s) shall not be held liable for any direct, indirect, incidental, consequential, or special damages—including, but not limited to, data loss, browser instability, account restrictions, or any other negative impact—arising out of or in connection with the use or inability to use this software.<br> 
<br>
This project is not affiliated with, endorsed by, or sponsored by Google LLC or any third-party websites it interacts with. Users are solely responsible for ensuring their use of this extension complies with applicable laws and the Terms of Service of any websites they visit.
