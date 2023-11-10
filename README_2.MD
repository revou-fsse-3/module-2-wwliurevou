Welcome to my website.
Here are the instructions on how to deploy my website from github to the custom domain. 

## Table of contents

- Netlify Deployment
- Purchasing Custom Domain
- Connecting Netlify with the Custom Domain

Assignment : to create a readme file that includes relevant information about the deployment process, connecting to a custom domain, and any additional details or configurations.

## Netlify Site Deployment
1.Go to your team’s Sites page, open the Add new site menu, and select Import an existing project.
2.Select the Git provider where your project is hosted.
3.Select your project’s existing repository.
4.Adjust site and build settings if necessary.

##Purchasing Custom Domain
1.Go to Niagahoster
2.Enter the domain that you preferred. In this case I chose widyaliu.site
3.Proceed with the payment
4.You will receive a confirmation email from your domain registry

##Connecting Netlify with the Custom Domain
1.On your Netlify, go to "Setup your site" Section, click "Setup a Custom Domain"
2.Please enter the domain that you purchased from Niagahoster. e,g widyaliu.site then click "Verify"
3.Go back to Netlify Dashboard, Open your Project, Custom Domain. You will see your custom domain is pending for External DNS. 
4.Now go to domains, scroll down and look for Name Severs.
5.Copy all 4 Name server to point your domain’s name servers to Netlify, paste all these 4 to : 
You should be able to find this in Domains-> Manage ->Domain Overview -> Click change on Name servers
6.Congratulations! This is all completed! Please wait for up to 1x24 hours for your custom domain to be connected and hosted
  



