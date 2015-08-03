# Deploy Button Help

[![Join the chat at https://gitter.im/deploybutton/wiki](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/deploybutton/wiki?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Add a Github Postcommit Hook

### What are webhooks?

Webhooks were created to allow web applications to become more extensible, customizable, and ultimately more useful. Webhooks let you develop "instant" push notifications. A push notification is simply a HTTP POST, that is triggered by some action. In this case, the action is checking into a particular branch of your source code repository over at Github.  In order to set webhooks for your repository, you need to be the owner (**administrator**) of the repository.  Please check and make sure you are the admin on your repository before sending us a support ticket.

### Step-by-step

Visit the repository you're trying to set up deploy hooks for in Github or your source code versioning tool.

![Visit the admin section of your repository](http://deploy-button.s3.amazonaws.com/wiki/deploy-1.png)

From the left hand sidebar menu, select "**Service Hooks**".

![](http://deploy-button.s3.amazonaws.com/wiki/deploy-2.png)

From the Available Service hooks, choose "**Webhook URLs**"

![](http://deploy-button.s3.amazonaws.com/wiki/deploy-3.png)

Enter the correct Webhook URL from your [**DeployButton**](http://deploybutton.com/) page.

![](http://deploy-button.s3.amazonaws.com/wiki/deploy-4.png)


You're all set to automatically deploy as soon as you've pushed to the **correct branch** of your repository that your DeployButton is set to.


## Integrate with Hubot

(Coming soon)


