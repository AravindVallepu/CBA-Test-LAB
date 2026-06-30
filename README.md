# CBA-Test-LAB
This Repo will guide how to setup the certifcate based Authentication with open ssl

Step-1:Install and downlaod the open ssl tool
Step-2:Run the script in Testfile in your device
Step-3:it will genrate the certificate
step-4:Uplaod the certicate in in Entra 
Step-5:Go to authetication method -select-Certificate based authention
Ste-p:configure ->
-->Microsoft advises turning on ‘Require CRL validation (recommended)’. This is off by default, but we will turn it on.
-->We turn on the checkbox for Issuer Hints so that only the valid certificates are shown during authentication.
-->We set the authentication levels to Multi-factor authentication and leave them at low. The other settings are default and we do not change them.

Once all done Wait atleast 20-30 minutes after that you can test it