### How to edit PostNL email templates.


#### PostNL online editor
- Open passwordstate
- Goto 'Team Shpping & Delivery' ; subfolder 'Carrier Systems'
- Open entry 'PostNL Email Templates'
 - tab 'notes' contains url to connect to and klantnaam to enter
 - user/pw as usual.

#### Where is my content?
- Tab 'Content'; subblad 'direct emails'	

#### Sending a test mail
- From Tripolis: in the edit screen, look for button 'Test publication' just 
  above template name.
- Select 'Quick test', verify correct email address.

#### Images
- Image source can be found on Github, repo 'vanessa-coolblue-email-templates '
- To avoid encoding issues when adding new images, change the name:
 - change spaces to '-'
 - accents with non-accented letter
- Review is not required, just merge it :-)


#### Deployment of images
- Run https://teamcity.coolblue.eu/project.html?projectId=Aws_Applications_VanessaEMailTemplates
- Note:
	Deploy to acceptance is automatic from github.
	But deploy to production must be done manually -and- is sometimes far behind acceptance.



The Readme.md from the github repo is worth reading.
As link to the image, use https://email-assets.coolblue.nl/
