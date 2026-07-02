# Entra ID Lab Tutorial

## Objectives

- Create and manage users in Microsoft Entra ID
- Assign roles and group membership to users
- Create and configure security groups
- Understand device management in Entra ID
- Add and configure Enterprise Applications with Single Sign-On (SSO)
- Explore key security features (Authentication Methods & Conditional Access)
- Understand Identity Governance concepts (Lifecycle workflows and Access Packages)

## Disclaimer

This is a personal learning lab/tutorial created for educational purposes only. 

**All names, screenshots, and configurations shown are fictional** and do not represent any real organization, company, or production environment. 

The steps and examples in this guide are meant for training in a test/lab Azure subscription only.

## Lab Overview

![Entra Lab Screenshot](entraidlab1.png)

Let’s begin by creating a User. Go to your Microsoft Azure account and click on Entra ID and then click on Users.

![Entra Lab Screenshot](entraidlab2.png)

Your Users tab

![Entra Lab Screenshot](entraidlab3.png)

Click on **Create new user**

![Entra Lab Screenshot](entraidlab4.png)

For the Basics Tab enter a User principal name and a Display name switch over to the Properties tab.

![Entra Lab Screenshot](entraidlab5.png)

In the Properties tab you can enter more details about the new user you are creating. Click on the Assignments tab once finished.

![Entra Lab Screenshot](entraidlab6.png)

Under Assignments, you can Add group or Add role to the new user.

![Entra Lab Screenshot](entraidlab7.png)

Specifically, in the Add role tab you have access to various default roles. For example, if you give this new user the Global Administrator role (not recommended), they can manage all aspects of your Entra ID. Move to the Review + create tab after.

![Entra Lab Screenshot](entraidlab8.png)

Click **Create**

![Entra Lab Screenshot](entraidlab9.png)

If you go back to All users, you should see the new user appear.

![Entra Lab Screenshot](entraidlab10.png)

If you click on the new user, you can see options such as editing their properties, deleting the user, resetting their password… etc.

![Entra Lab Screenshot](entraidlab11.png)

**Note:** If you delete a user you can go to the deleted tab to restore them, otherwise they will be permanently removed after 30 days.

## Groups

![Entra Lab Screenshot](entraidlab12.png)

Now we will learn about Groups. Click on the Microsoft Entra ID tab.

![Entra Lab Screenshot](entraidlab13.png)

Click on **Groups**

![Entra Lab Screenshot](entraidlab14.png)

You should have a tab opened that looks like this.

![Entra Lab Screenshot](entraidlab15.png)

Let’s say we want to create a new Group, click on **New group**.

![Entra Lab Screenshot](entraidlab16.png)

Add a Group name.

![Entra Lab Screenshot](entraidlab17.png)

You can select an owner for the group under the Owners tab.

![Entra Lab Screenshot](entraidlab18.png)

You can select a member to add for the group under the Members tab.

![Entra Lab Screenshot](entraidlab19.png)

Click **Create**.

![Entra Lab Screenshot](entraidlab20.png)

If you go back to the All groups tab, you can see your newly created group.

## Devices

![Entra Lab Screenshot](entraidlab21.png)

Next stop is understanding Devices. Click on the Entra ID tab and then click on **Devices**.

![Entra Lab Screenshot](entraidlab22.png)

You will see the device you have joined on display. Note there is not much in the way of managing devices through Entra ID — most of that is done through Intune.

## Enterprise Applications & SSO

![Entra Lab Screenshot](entraidlab23.png)

Next stop is understanding how to add applications and adopt features such as SSO (single-sign-on) on them. So go to all services, then click on **Identity**, and click on **Enterprise Applications**.

![Entra Lab Screenshot](entraidlab24.png)

Click on **Overview**.

![Entra Lab Screenshot](entraidlab25.png)

Click on **Total applications**.

![Entra Lab Screenshot](entraidlab26.png)

You should then be able to see all the different applications you have access through Microsoft Azure and Entra ID.

![Entra Lab Screenshot](entraidlab27.png)

You can also add/create a new application by clicking the **+ New application** tab on the top.

![Entra Lab Screenshot](entraidlab28.png)

You can create a new application.

![Entra Lab Screenshot](entraidlab29.png)

Or you can add an existing application such as Box (used for file sharing), and there is even a tutorial to help you integrate it.

![Entra Lab Screenshot](entraidlab30.png)

If you ask for a tutorial, it should give you something like this where it will show you how to configure the Single sign-on.

## Security

![Entra Lab Screenshot](entraidlab31.png)

Next stop, we are going to learn about Security in Entra ID. Click on the **Security** tab in the Entra ID tab.

![Entra Lab Screenshot](entraidlab32.png)

One of the most important security features in Entra ID would be the Authentication methods features. Click on the Authentication method under the manage tab...

![Entra Lab Screenshot](entraidlab33.png)

When you go into the Entra ID authentication method on the policy side, you will get a page like this. You can select the various authentication methods. For this lab, we will briefly look at Microsoft Authenticator (a solid choice for MFA).

![Entra Lab Screenshot](entraidlab34.png)

You can select whether to enable/disable, configure, include/exclude, target specific users/groups, and change the authentication mode.

![Entra Lab Screenshot](entraidlab35.png)

The next important feature to go over is **Conditional Access**. Go back to the Entra ID Security tab and click on **Conditional Access**.

![Entra Lab Screenshot](entraidlab36.png)

This allows you to set policies such as requiring MFA for admins, or for all users. And you can even set an authentication strength requirement for your policies such as having it be Phishing-resistant MFA.

## Identity Governance

![Entra Lab Screenshot](entraidlab37.png)

The next thing we are going to look at is **Identity Governance**. Click on the Identity Governance tab in the main Entra ID directory overview.

![Entra Lab Screenshot](entraidlab38.png)

One important feature to learn from Identity Governance is Lifecycle workflows. This will help with setting up step by step tasks for governance related organizational tasks such as onboarding and offboarding.

![Entra Lab Screenshot](entraidlab39.png)

Access packages can be used for granting access to third party individuals or organizations with a limited scope. If your company for example does a public facing project and wants involvement with people outside your company then access packages is a useful tool to utilize.
