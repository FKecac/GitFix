## Add the deploy key (2 / 4)

CodeGrade allows you to submit your work directly via Git. This is done by setting up a <em>webhook</em>. As a result, every time you push the configured branch, the content of your current branch will be uploaded to CodeGrade. A good practice is to set up the GitLab CodeGrade configuration before starting to work on your assignment.

First, we need to add a <em>deploy key</em>. By adding this key, you allow CodeGrade to access the code in your repository, which is needed for CodeGrade to create a submission.

Start by going to the settings page of your repository. You can find the <em>settings</em> page in the Sidebar. [Don’t see the Settings page?](#missing-settings-page)
Now click on <em>Repository</em>. There you should see the Option "Deploy keys", expand it. After expanding the category you should see two input fields: <em>"Title"</em> and <em>"Key"</em>.
Now copy the contents of the text area given on CodeGrade. The given Key should start with <em>"ssh-rsa ..."</em>. Paste this in the <em>"Key"</em> field. Enter a title for the key (its exact value does not matter). Write access is not required. An expiry date is not required/ recommended. Now click the <em>"Add key"</em> button to save the key.



<br>
<br>
<br>
<br>

### Missing Settings Page

If you do not see the settings page, ensure that:
1. You have the correct permissions to access repository settings.
2. Your repository is set up correctly within your GitLab project.
Contact the repository administrator/ creator. They have to either grant you the fitting permissions or do it themseleves.
