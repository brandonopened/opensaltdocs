![image alt text](image_0.png)

OpenSALT v.2.1 - User Manual (draft)

**Revision History**

<table>
  <tr>
    <td>Name</td>
    <td>Organization</td>
    <td>Date</td>
    <td>Revision Notes</td>
    <td>Document Version</td>
  </tr>
  <tr>
    <td>J Kaufman</td>
    <td>PCG</td>
    <td>8/2017</td>
    <td>Original Draft for v1.0</td>
    <td>.0</td>
  </tr>
  <tr>
    <td>BDorman</td>
    <td>ACT</td>
    <td>11/2017</td>
    <td>Updating Import Guide</td>
    <td>.1</td>
  </tr>
  <tr>
    <td>Brandon Dorman</td>
    <td>ACT</td>
    <td>3/10/18</td>
    <td>2.1</td>
    <td></td>
  </tr>
</table>


**Table of Contents**

[[TOC]]

## Introduction

**CASE**

CASE establishes a new, global technical standard for the exchange of machine readable, linked data versions of state and national academic standards, local learning objectives and targets, or any workplace, military, or higher education competencies representing skills, knowledge, or abilities. To learn more please visit: [https://www.imsglobal.org/introduction-case-competencies-and-academic-standards-exchange-case](https://www.imsglobal.org/introduction-case-competencies-and-academic-standards-exchange-case)

**OpenSALT**

To support CASE, PCG Education (A national public sector consulting practice); ACT Inc and SchoolCity (both leading curriculum and assessment providers), partnered on the development of the open source project called OpenSALT, that provides a free, IMS-conformance certified tool that enables education organizations to manage and publish frameworks and crosswalks to other standards.

Developed as an open source project, OpenSALT provides for easy exchange of state standards data and provides for and enables alignment services to align educational content to learning standards, as well as correlate (Crosswalk) between different state standards and competency frameworks.

**Key features that distinguish OpenSALT:**

* Easily create derivative frameworks from national standards for use within States

* Create customized competency frameworks with connections to national and state frameworks as needed

* Set learning progressions within a framework

* Allow different views of a framework (For example, view the Standards of Engineering Practices in the NGSS framework separately from the DCI statements)

* Filter frameworks by keyword

* Enabled for the common alignment of resources and assessments to standards

* A Consistent digital format that can be easily integrated into ed-tech products and internal documents alike (Export to the standardized CASE Format as well as spreadsheets)



## 1.0  Audience

This document is intended as a complete guide for using OpenSALT. This document is specially designed for all users with advanced permissions or non-specialists who may find the document useful as a  point of reference. By reading this guide, you will learn how to use OpenSALT through the elements of the graphical user interface (GUI) and explanations of some of the advanced features to provide best practices. This guide will help you to navigate and easily use OpenSALT. The functions and features described in this guide will indicate any role restrictions or limitations as to what users can access or interact with the given system function.

### 1.1 Platform Requirements

The user interface is designed using current web standards and supports most modern browsers, in their current supported versions, on a variety of desktop and mobile devices.

The user interface requires JavaScript to be enabled and internet access to be available (no support for an offline mode is currently available).

The user interface should support the latest versions of the following web browsers on desktop and mobile devices:

* Chrome

* Internet Explorer

* Edge

* Safari

* Firefox

## 2.0  OpenSALT Structure and Access

OpenSALT is designed to be an open, publicly accessible, framework site that allows transparency in frameworks and crosswalks. By design users are able to traverse and view the published frameworks and content by accessing the main url for the given site. OpenSALT then utilizes a login that allows provisioned users to create, edit and otherwise interact with the frameworks for the site.

### 2.1 OpenSALT Structure

OpenSALT goes to the home page by default, and also has a document tree view. The Doc Tree View shows a framework and information about the framework on the right hand side, where logged in users with proper permissions can edit items, associate with other framework items, and copy other framework items into the current framework.

### 2.2 OpenSALT Home Page

The image below is an example of an OpenSALT site, OpenSALT.net hosted by PCG. When user launches opensalt.net in a browser, the user is presented with the open view of the site.  

![image alt text](image_1.png)

This is a view of an OpenSALT site hosted by ACT, located at frameworks.act.org

![image alt text](image_2.png)

All public, non-provisioned users are able to view the frameworks and content with each form this view. Navigating the frameworks will be further discussed in a later section of this document.

### 2.3 Log into OpenSALT

For provisioned users the **_Sign in_** button will launch a login screen that will enable deeper system usage and open up available menus for further interaction with OpenSALT.  

![image alt text](image_3.png)

Provisioned users can enter in their *Username *(user’s email) and *Password* then click the **_Login_** button to access the admin functions for OpenSALT.

![image alt text](image_4.png)

After logging in a provisioned user will now see the *Sign In* button replaced by "Signed in as *username*" (email) with a menu icon  and two new buttons on the main frame of the page:  **_Create a new Framework_** and **_Import Framework_**

### 2.4 Log off from OpenSALT

All provisioned users should log out of OpenSALT when finished with their session. To logout, click on the expansion menu next to the user name and select **_Sign out_**.

![image alt text](image_5.png)

## 3.0  User Roles and Permissions

OpenSALT currently has five user roles with specified permissions for the tool:

1. Super User

2. Super Editor

3. Organization Administrator

4. Organization Editor

5. Organization Reviewer (Account in org but no role)

6. Public (non-authenticated)

The Chart below provides an overview of the users and their provisioned roles and detailed descriptions follow.  

![image alt text](image_6.png)

### 3.1 Super User

This is the top level in the user hierarchy for OpenSALT. A Super User has full permissions to the site and can create and manage organizations, manage users across all organizations, and manage all frameworks and content across all organizations.  

* view any framework

* download (export) any framework in *Draft* or *Published* modes

* change their password

* add new, import, and edit frameworks in all organizations:

    * Personal frameworks

        * only editable by the creator (by default)

        * access can be granted to other editors to edit the framework

    * Organizational  frameworks

        * editable by all editors/admins in the organization (by default), this includes Super Editors and Super Admins

        * can edit frameworks which they have permission to edit:

            * frameworks owned by any organization

            * other frameworks where the user has been explicitly been granted edit access

        * alter edit access to any frameworks

        * assign ownership of any personal framework created by an editor in any organization

* manage organizations in OpenSALT

    * add organizations

    * edit organizations

    * delete organizations

* add users to any organization (Super User, Super Editor, Organization Admin or Organization Editor)

    * suspend users in any organization (Super User, Super Editor, Organization Admin or Organization Editor)

    * unsuspend users in any organization (Super User, Super Editor, Organization Admin or Organization Editor)

* Note the Super Users cannot be excluded from edit access to a framework

### 3.2 Super Editor

Much like the Super User, the Super Editor has has permissions to work across organizations however this user is only permitted to manage all frameworks and content across all organizations. The Super Editor has no access to manage organizations, nor users.

The Organization Admin can manage users for their given organization, and manage and manage all frameworks and content for only their organization.

* view any framework

* download (export) any framework in *Draft* or *Published* modes

* change their password

* add new, import, and edit frameworks in all organizations:

    * Personal frameworks

        * only editable by the creator (by default)

        * access can be granted to other editors to edit the framework

    * Organizational  frameworks

        * editable by all editors/admins in the organization (by default), this includes Super Editors and Super Admins

        * can edit frameworks which they have permission to edit:

            * frameworks owned by any organization

            * other frameworks where the user has been explicitly been granted edit access

        * alter edit access to any frameworks

        * assign ownership of any personal framework created by an editor in any organization

* Note the Super Editor cannot be excluded from edit access to a framework

### 3.3 Organization Admin

The Organization Admin can manage users for their given organization, and manage and manage all frameworks and content for only their organization.

* view any framework

* download (export) any framework in *Draft* or *Published* modes

* change their password

* add new, import, and edit frameworks:

    * Personal frameworks

        * only editable by the creator (by default)

        * access can be granted to other editors to edit the framework

    * Organizational  frameworks

        * editable by all editors/admins in the organization (by default), this includes Super Editors and Super Admins

        * can edit frameworks which they have permission to edit:

            * frameworks owned by their organization open to all editors (no exclusions)

            * frameworks owned by their organization when the user is not in the exclusion list

            * other frameworks where the user has been explicitly been granted edit access

        * alter edit access to any frameworks owned by their organisation (personal frameworks)

        * assign ownership of any personal framework created by an editor in their organization

* add users to their organization (Organization Admin or Organization Editor)

    * suspend users in their organization (Organization Admin or Organization Editor)

    * unsuspend users in their organization (Organization Admin or Organization Editor)

### 3.4 Organization Editor

The Organization Editor has only access to its respective organization and is only permitted to manage frameworks and content with the assigned organization. An Organization Editor has no access to manage organizations, nor users. An Organization Editor can:

* view any framework

* download (export) any framework in *Draft* or *Published* modes

* change their password

* add new frameworks and import frameworks:

    * Personal frameworks

        * only editable by the creator (by default)

        * access can be granted to other editors to edit the framework

    * Organizational  frameworks

        * editable by all editors/admins in the organization (by default), this includes Super Editors and Super Admins

        * can edit frameworks which they have permission to edit:

            * frameworks owned by their organization open to all editors (no exclusions)

            * frameworks owned by their organization when the user is not in the exclusion list

            * other frameworks where the user has been explicitly been granted edit access

### 3.5 Organization Reviewer

The Organization Reviewer is an org member with no roles assigned. They can log in and access private draft frameworks in an organization. They can not edit or manage frameworks. An Organization Reviewer can:

* view any framework in an org, private or not

* download (export) any framework in *Draft* or *Published* modes

* change their password

* Add comments if comments are turned on

* They can **not** make personal frameworks.

### 3.6 Public User

The Public User is the default user for all who visit an OpenSALT site. This user has no provisioned credentials and therefore cannot log into the site to access administrative functionality Rather this user is able to navigate the published frameworks and content and has read-only rights to the information. The Public User can:

* view any framework

* download (export) any framework in *Draft* or *Published* modes

## 4.0 Organization Management

**_Audience: Super Users_**

As discussed in section 2.1 Open SALT is designed to b a multi-tenant environment housing multiple organizations and users, though keeping all securely separated. In order to establish the separation, the Super User will need to create and manage organizations.

To access the **_Manage Organization_** page, after logging in the user should click the triangular menu icon next to their user name in the header of the page. The menu will expand with several options depending on the user’s role. Click on **_Manage Organizations_** to open the page.

![image alt text](image_7.png)

The **_Organization List _** is the default page displayed when a Super User accesses the **_Manage Organization_** function of OpenSALT. The list will display all organizations that the are currently in the given instance of OpenSALT. The **_Organization List_** provides the OpenSALT unique ID number, the Organization Name, and Actions for the organizations (**_Show_** and **_Edit_**). The page also has a button to **_Add a new organization_**.

![image alt text](image_8.png)

### 4.1 Show Organizations

There are two ways to view an individual organization’s information beyond the **_Organization list_**  table view.

1. On the **_Organization List_** click on the linked **_ID_** number for the selected organization.

![image alt text](image_9.png)

2. On the **_Organization List_** click on the **_Show_** button in the **_Actions_** section of the Organization table for the selected organization.

![image alt text](image_10.png)

The **_Organization_** screen will display for the selected user.

![image alt text](image_11.png)

The Super User can see the Organization’s unique ID value and the Organization’s name.

From the **_Organization_** screen the Super User can:

* return the **_Organization List_** by clicking the **_Back to the list button_**

* edit the organization by clicking on the **_Edit_** button

* delete the organization by clicking on the **_Delete_** button

### 4.2 Add/Create Organization

To create a new user, click on the **_Add new user_** button at the bottom right of the **_User list_**.

![image alt text](image_12.png)

The Add an Organization page will display:

![image alt text](image_13.png)

The admin will need to enter in the following required fields:

*Name:* Type the Organization name

Then click on the **_Add_** button to create the organization.

If the Admin wants to cancel, and not create the organization, click the **_Back to the list _**button.**_ _**

### 4.3 Edit Organization

An Admin can access the **_Organization edit_** screen using two paths:

1. On the **_Organization List_** click on the **_Edit_** button in the **_Actions_** section of the Organization table for the selected organization. ![image alt text](image_14.png)

2. On the **_Organization_** screen click on the **_Edit_** button.

![image alt text](image_15.png)

The **_Organization edit_** screen will display and allow the Admin to update the user’s information.

![image alt text](image_16.png)The Admin can update/correct the following field:

*Name:* Type the Organization name

Then click on the **_Save_** button to save the changes.

If the Admin wants to cancel, and not edit the the organization, click the **_Back to the list _**button.**_ _**

The Admin can also delete the organization from this screen by clicking on the **_Delete_** button.

### 4.4 Delete Organization

If an organization  needs to be completed removed from OpenSALT, the Admin should delete the organization. There are two methods to delete an organization.

1. From the **_Organization List_** click on the **_Show_** button for the selected organization. The **_Organization_** page will be displayed and the Admin can click the **_Delete_** button to terminate the organization. Once deleted the organization cannot be restored. If the organization is needed, the Admin will need to create a new organization.  

![image alt text](image_17.png)

2. From the **_Organization List_** click on the **_Edit_** button for the selected organization. The **_Organization edit_** page will be displayed and the Admin can click the **_Delete_** button to terminate the organization. Once deleted the organization cannot be restored. If the organization is needed, the Admin will need to create a new organization.  

![image alt text](image_18.png)

## 5.0  User Management

### 5.1 Change Password

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

All provisioned users have the ability to change their password from the temporary one created by the Admin or as part of a good practice to regularly update their password to maintain a good security protocol.

To access the **_Change Password_** page, after logging in the user should click the triangular menu icon next to their user name in the header of the page. The menu will expand with several options depending on the user’s role. However all provisioned users will have the menu option: **_Change Password_**. Click on **_Change Password_** to open the page.

![image alt text](image_19.png)

On the **_Change Password_** page the user will enter in the following required fields:

![image alt text](image_20.png)

**_Old Password:_** Existing current password

**_New Password:_** Newly selected password

**_Repeat Password:_** Re-type the newly selected password

The user will then click the **_Change Password_** button.

If the entered values validate as correct, the old password is equal to the user’s current password and the new and repeat passwords are the same, the system will change the user's password to the newly selected value. If alny of the data is not validated, the system will prompt the user to correct the information before the change password can be completed.

### 5.2 Manage Users

**_Audience: Super Users and Organization Admins_**

User account management is controlled by the Super Users and the Organization Admins. To access the **_Manage Users_** page, after logging in the user should click the triangular menu icon next to their user name in the header of the page. Click on **_Manage Users_** to open the page.

![image alt text](image_21.png)

#### 5.2.1 View User

**_Audience: Super Users and Organization Admins_**

The **_User List_** is the default page displayed when a Super User or Organization Admin accesses the **_Manage User_** function of OpenSALT. The list will display all users that the are currently in the given instance of OpenSALT. Super Users will see all users in all organizations, whereas Organization Admins will only see the users within their organization.  The User List will display the OpenSALT unique ID for the user (as system generated incremented number), the Organization the user belongs to, the Username (email) The user's role, and available actions (**_show_**, **_edit_**, **_Suspend_**) for the user. The page also has a button to **_Add a new user_**.

![image alt text](image_22.png)

#### 5.2.2 Add/Create User

**_Audience: Super Users and Organization Admins_**

To create a new user, click on the **_Add new user_** button at the bottom right of the **_User list_**.

![image alt text](image_23.png)

The **_Add a User_** page will display:

![image alt text](image_24.png)

The admin will need to enter in the following required fields:

*Username*: Type the user’s email address

Password: Type in a temporary password for the user. This password will not be viewable after creating the user. The Admin needs to take note of the temporary password entered to share with the user and the user will need to enter this password to change their password to a non-temporary secure password.

*Role*: Select one role for the user and check the box accordingly

*Org*: Select the user’s organization (note Organization Admins will only have their organization displayed, whereas Super Users will see all Organizations within the given OpenSALT site)

Then click on the **_Add_** button to create the user.

If the Admin wants to cancel, and not create the user, click the **_Back to the list _**button.**_ _**

#### 5.2.3 Show User

**_Audience: Super Users and Organization Admins_**

There are two ways to view an individual user’s information beyond the **_User list_** table view.

3. On the **_User List_** click on the linked **_ID_** number for the selected user.

![image alt text](image_25.png)

4. On the **_User List_** click on the **_Show_** button in the **_Actions_** section of the User table for the selected user. ![image alt text](image_26.png)

The **_User_** screen will display for the selected user.

![image alt text](image_27.png)

The Super User or Organization Admin can see the user’s Organization, Username, and assigned Role.

From the **_User_** screen the Admin can:

*  return the **_User List_** by clicking the **_Back to the list button_**

* edit the user by clicking on the **_Edit_** button

* delete the user by clicking on the **_Delete_** button

#### 5.2.4 Edit User

**_Audience: Super Users and Organization Admins_**

An Admin can access the **_User edit_** screen using two paths:

3. On the **_User List_** click on the **_Edit_** button in the **_Actions_** section of the User table for the selected user. ![image alt text](image_28.png)

4. On the **_User_** screen click on the **_Edit_** button.

![image alt text](image_29.png)

The **_User edit_** screen will display and allow the Admin to update the user’s information.

![image alt text](image_30.png) The Admin can update/correct the following fields:

*Username*: If needed, type the user’s new email address. This will change the username that is entered when the user logs in.

Password: If needed, type in a new temporary password for the user. This password will not be viewable after creating the user. The Admin needs to take note of the temporary password entered to share with the user and the user will need to enter this password to change their password to a non-temporary secure password.

*Role*: If needed, select a new role for the user and uncheck the previous role.

*Org*: If needed, change the organization Select the user’s organization (note Organization Admins will only have their organization displayed, whereas Super Users will see all Organizations within the given OpenSALT site)

Then click on the **_Save_** button to save the changes.

If the Admin wants to cancel, and not edit the the user, click the **_Back to the list _**button.**_ _**

The Admin can also **_delete_** the user from this screen by clicking on the **_Delete_** button.

#### 5.2.5 Suspend User

**_Audience: Super Users and Organization Admins_**

If an admin needs to prevent the user from accessing the OpenSALT instance, but needs to maintain the user’s account  in the system ,the admin can **_Suspend_** the user’s account.   

To suspend an account the Admin will need to be on the User List page and select the **_Suspend_** button for the selected user.

![image alt text](image_31.png)

After clicking on the **_Suspend_** button, the user will be immediately suspended. The **_User list_** is updated to reflect the suspension and the account can now only be viewed through the **_Show_** button or unsuspended with the **_Unsuspend_** button.

![image alt text](image_32.png)

#### 5.2.6 Reinstate User

**_Audience: Super Users and Organization Admins_**

To reinstate a user’s account the Admin will access the **_User List_** and click on the **_Unsuspend_** button for the selected user. The **_User list_** will update and the account will be immediately unsuspended and the user can log in with the original credentials. If the user needs to have their password reset, the Admin can the edit the user by clicking the **_Edit_** button for the selected user and updated the password.

![image alt text](image_33.png)

#### 5.2.7 Delete User

**_Audience: Super Users and Organization Admins_**

If a user needs to be completed removed from OpenSALT, the Admin should delete the user. There are two methods to delete a user.

3. From the **_User List_** click on the **_Show_** button for the selected user. The **_User_** page will be displayed and the Admin can click the **_Delete_** button to terminate the user account. Once deleted the account cannot be restored. If the account is needed, the Admin will need to create a new user account.

![image alt text](image_34.png)

4. From the **_User List_** click on the **_Edit_** button for the selected user. The **_User edit_** page will be displayed and the Admin can click the **_Delete_** button to terminate the user account. Once deleted the account cannot be restored. If the account is needed, the Admin will need to create a new user account.

![image alt text](image_35.png)

## 6.0  Framework Management

### 6.1 Navigate and View Frameworks

OpenSALT is designed to be a simple application with few UI screens. The Application has two (2) primary screens for users to view and manger Frameworks and items:

1.  OpenSalt Home / Contents View Page

2. Framework Display Page

#### 6.1.1 OpenSalt Home / Contents View Page

##### 6.1.1.1 Public View

When a  user launches an OpenSALT instance through their browser they will reach the Public view of the OpenSALT site. The following images represent a few of the current OpenSALT sites in operation.

![image alt text](image_36.png)

![image alt text](image_37.png)

![image alt text](image_38.png)

![image alt text](image_39.png)

Note the default view has consistency from site to site. The variation is in the organization’s ability to add their organization logo and the content of the frameworks in the list.  

Public users can view all Organizations with Draft and Adopted Frameworks on the OpenSALT site.

The default view is for all of the Organizations to be listed and their frameworks to be collapsed.

![image alt text](image_40.jpg)

The user can expand the ORganizations to see all available Frameworks by clicking on either the arrow to the left of the Organization name or on the name itself.

![image alt text](image_41.jpg)

##### 6.1.1.2 Credentialed View

If a user has credentials and logs into OpenSALT they will have additional buttons on this page, depending on their role and permissions. Additionally they will be able to see all frameworks that are in a Private Draft status as well.  

![image alt text](image_42.jpg)

#### 6.1.2 Display Frameworks Page

When a user click on a framework on the **_OpenSalt Home / Contents View Page _**OpenSALT will open the **_Framework Display_** page for the select framework.

##### 6.1.2.1 Public View

![image alt text](image_43.jpg)

As a user clicks on a framework item, the Item Details frame will update to reflect the specifics for the selected item.

![image alt text](image_44.png)

##### 6.1.2.2 Credentialed View

Credentialed users will have additional administrative controls and functions on the Display Framework page, depending on their role and permissions.

![image alt text](image_45.jpg)

### 6.2 OpenSALT Frameworks

#### 6.2.1 Import Frameworks

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

OpenSALT has two methods for importing in an existing CASE-compliant framework into the site.  

1. Import from ASN

2. Import CASE-compliant file (JSON)

To import data the user must first log into OpenSALT. After login, the **_Import Framework_** button will be displayed at the top of the screen.

![image alt text](image_46.png)

Click on the **_Import Framework_** button to open the **_Import Framework_** window.  From this window the user can either **_Import an ANS Framework_** or **_Import a CASE-compliant JSON file, _***or***_ Import a Spreadsheet_** using the provided template.

![image alt text](image_47.png)



##### 6.2.1.1 Import from ASN

Achievement Standards Network (ASN), powered by D2L, is a collection of machine-readable representations of learning objectives. ASN was created through funding by the [National Science Foundation](http://www.nsf.gov/) and the [Bill & Melinda Gates Foundation](http://www.gatesfoundation.org/) and is now owned and operated by D2L. This source can provide users with a starting foundation for creating meaningful CASE-compliant frameworks. However the data in ASN may not be current nor accurate and complete. It is up to the individual users and organizations to determine the accuracy of any imported data into OpenSALT. However because of the ability to provide a good starting point for Frameworks content in OpenSALT, the application allows users to do a direct import from a given ASN url.

In a seperate browser window or tab navigate to ASN’s Standards: [http://www.achievementstandards.org/resources/ASNJurisdiction](http://www.achievementstandards.org/resources/ASNJurisdiction).

Select the correct Jurisdiction or Publishing Organization of Framework to be imported.

![image alt text](image_48.png)

Click on the Framework Document to be imported.

![image alt text](image_49.png)

When the ASN Framework Page displays, copy the URL in the browser window (Or just the ID number at the end), and return to your OpenSALT tab.

![image alt text](image_50.png)

On the**_ Import Framework_** window, paste the **_ASN URL_** into the box on the **_Import from ASN_** **_tab. _**Then**_ _**click **_Import Framework_**.

![image alt text](image_51.png)

If you do not want to import a framework, click on the Close button to return to the **_Frameworks Contents/OpenSALT Home_** page.

A new publisher will be created named: **_Imported form ASN_**. When expanded, the imported Framework will be displayed.

![image alt text](image_52.png)

When a Framework package is imported from ASN, the default for the **_Organization_** will be ‘**_Imported from ASN_**’. and the **_Adoption Status_** will be blank. When an **_Adoption Status_** is blank, the Framework package is by default publicly visible on the OpenSALT instance. However because the ASN data should be validated, the best practice is for the user that imported the Framework package to edit the Framework details and update both the **_Creator_** and the **_Adoption Status_** values after the import from ASN.

To edit the **_Creator_** and **_Adoption Status_** fields, expand the **_Organization Imported from ASN_** and click on the newly imported **_Framework_**.

![image alt text](image_53.png)

On the **_Framework Display_** page, click on the **_Edit_** button in the **_Detail Frame_**.

![image alt text](image_54.png)

The **_Edit Document_** window will open and allow the user to update the necessary fields.

The user may want to change the value in the **_Creator_** field from ‘**_Imported from ASN_**’ to the source organization. In this example the source **_Organization_** is **_Arizona Department of Education_**.  

Additionally the user should change the **_Adoption Status_** to either **_Draft_** or **_Private Draft_**. **_Draft_** will allow the Framework to be visibly by all users, including the Public user thought it will let user know that the Framework is still being reviewed and is not yet ready to be **_Adopted_**. **_Private Draft_** will hide the Framework from the Public users until the Editor or Admin is ready to change the stats to make it available for others to see.

![image alt text](image_55.png)![image alt text](image_56.png)

To **_save_** the updated, click the **_Save Changes_** button.

To **_cancel_** and abandon any changes, click the **_Cancel_** button.

Further information on **_Editing Frameworks_** is explained the previous section **_[6.3 Edit Framework_**s](#heading=h.539gy53xkttl).

##### 6.2.1.2 Import CASE-Compliant (JSON) File

OpenSALT allows users to import known CASE-compliant framework files into the system. Click on the **_Import CASE file_** tab in the **_ Import Framework_** window. Then**_ _**click **_Choose File._**

![image alt text](image_57.png)

Navigate on your computer to the correct Case-compliant JSON file to import then  click **_Open_**.

![image alt text](image_58.png)

The filename will display in the Choose File box, then click the **_Import Framework_** button to import the framework.

![image alt text](image_59.png)

To cancel the action and not import the file, click on the **_Close_** button.

##### 6.2.1.2 Import framework from SALT Spreadsheet Template

[Content Pending 1.2 Version]

#### 6.2.2  Manually Create Frameworks

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

To Create a **_Framework_** manually the credentialed user will click on the Create a new Framework button on the **_Framework Contents/OpenSalt Homepage_** after logging into OpenSALT.  

![image alt text](image_60.png)

On the**_ Framework Creation_** page, completed at a minimum the mandatory fields, though all fields should be filled in by best practice.

![image alt text](image_61.png)

The following fields will display on the **_LsDOC Creation_** page:

* *Title: *The title as it appears on the cover of the Official Source artifact, although it may be a title created by the Publisher. This is a mandatory field in OpenSALT. .

* *Creator:* The the entity that authorized or created the competency framework. It could be an education agency, higher education institution, professional body. It is the owner of the competency framework (e.g CCSSO, TEA, NGSS). This is a mandatory field for OpenSALT and will act as the Organization Folder on the Framework Contents/OpenSALT Home page.

* *Official URI: *The URL of the artifact adopted by the Standard Setting Entity. Often this document is published in html and/or as pdf and is used by the standard setting entity as part of its approval process. Since it is not the intent of this specification to fully reproduce the human-facing content and formatting of the source document, it is recommended that this document be transmitted as part of the competency framework package. This is an optional field in OpenSALT, though best practices indicate it should be filled in.

* *Publisher: *The entity that loads and publishes the Framework. Note that in  many cases, the Standard Setting Entity may lack technical capabilities to publish the Competency Framework in a standard format so a third party may be displayed. This is an optional field in OpenSALT, though best practices indicate it should be filled in.

* *URL Name:* This field allows users to enter in a user friendly URL name. example: [https://salt-staging.edplancms.com/cftree/doc/CSSS](https://salt-staging.edplancms.com/cftree/doc/CSSS) vs  [https://salt-staging.edplancms.com/cftree/doc/45](https://salt-staging.edplancms.com/cftree/doc/45)

* *Owned By: *Users will have the option to select from a few choices to indicate the Organization that created the Framework in OpenSALT.

    * *Me* - Private Framework created by an individual user

    * *My Organization* - Default to the user’s organization

    * *Other Organization (Named in the Dropdown)* - Super Editor or Super User can select any Organization in OpenSALT.

* *Version: *This is used to separate any version information expressed by the Official Source artifact. Once and CF Pkg has been approved and published, any changes to an CF Item will constitute a new version of the CF Doc. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Description: *The description is typically created by the the Publisher as a standard description of the Competency Framework.This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Subjects: *This is a string expressing the general subject area of the Competency Framework (e.g. Mathematics). This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Language: *HTML Language Country Code VIA- country code from [https://tooCF.ietf.org/html/bcp47](https://tooCF.ietf.org/html/bcp47). This is an optional field in OpenSALT, though best practice indicates the filled should be filled in. However OpenSALT assumes English if not other language value is entered.

* *Adoption Status: *Adoption status displays the Framework's current status as Draft, Private Draft,  Adopted, or Deprecated.  OpenSALT assumes Adopted as the default if no status is specifically selected for the framework. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank. OpenSALT assumes Adopted as the default if no status is specifically selected for the framework.

    * *Draft*: Able to be edited by Editors and Admins in an organization. Able to be viewed by the public.

    * *Private Draft*: Able to be viewed and edited by Editors and Admin in the owning organization

    * *Adopted*: Not able to be edited by Editors or Admin

    * *Depreciated:* Was once published, however it is now out of date

* *Status Start Date: *The date that the CF Doc status started. This is an optional field in OpenSALT.

* *Status End Date: *This date is often only known when a new status is started. This is an optional field in OpenSALT.

* *Note: *Notes or comments generated by the Framework Publisher about the context of the Framework. This is an optional field in OpenSALT.

To **_create_** the Framework, click the **_Create_** button.

To **_cancel_** and abandon any changes, click the **_Back to the list_** button.

When a Framework is created the **_Framework Display_** page will refresh and will indicate that are loaded with the framework.

![image alt text](image_62.png)

Open SALT Provides the user with suggestions for how to add items to the framework.

![image alt text](image_63.png)

#### 6.2.3 Edit Frameworks

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

To **_Edit_** a **_Framework_** the credentialed user will select the appropriate **_Framework_** from the **_Framework Contents/OpenSalt Home_** Page by expanding the **_Organization_** and clicking on the desired **_Framework_**.  ![image alt text](image_64.png)

On the **_Framework Display_** page, click on the **_Edit_** button in the **_Detail Frame_**.

![image alt text](image_65.png)

The **_Edit Document_** window will open and allow the user to update the necessary fields.

![image alt text](image_66.png)

The following fields will display on the Edit Document window. Note some may be edited and others have fixed values:

* *Title: *The title as it appears on the cover of the Official Source artifact, although it may be a title created by the Publisher. This is a mandatory field in OpenSALT.

* *Creator:* The the entity that authorized or created the competency framework. It could be an education agency, higher education institution, professional body. It is the owner of the competency framework (e.g CCSSO, TEA, NGSS). This is a mandatory field for OpenSALT and will act as the Organization Folder on the Framework Contents/OpenSALT Home page.

* *Official URI: *The URL of the artifact adopted by the Standard Setting Entity. Often this document is published in html and/or as pdf and is used by the standard setting entity as part of its approval process. Since it is not the intent of this specification to fully reproduce the human-facing content and formatting of the source document, it is recommended that this document be transmitted as part of the competency framework package. This is an optional field in OpenSALT, though best practices indicate it should be filled in.

* *Publisher: *The entity that loads and publishes the Framework. Note that in  many cases, the Standard Setting Entity may lack technical capabilities to publish the Competency Framework in a standard format so a third party may be displayed. This is an optional field in OpenSALT, though best practices indicate it should be filled in.

* *URL Name: *This field allows users to enter in a user friendly URL name. example: [https://salt-staging.edplancms.com/cftree/doc/CSSS](https://salt-staging.edplancms.com/cftree/doc/CSSS) vs  [https://salt-staging.edplancms.com/cftree/doc/45](https://salt-staging.edplancms.com/cftree/doc/45)

* *O**wning Organization: *If a Framework is not a personal Framework, and rather is an Organizational Framework, the associated Organization that created or imported the Framework will be displayed. *Owning User: *If the Framework is a personal Framework owned by an individual user, the user’s name will be displayed. Otherwise the OpenSALT will assume a value of none because the Framework is not owned by a single user rather is owned by an Organization.

* *Version: *This is used to separate any version information expressed by the Official Source artifact. Once and CF Pkg has been approved and published, any changes to an CF Item will constitute a new version of the CF Doc. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Description: *The description is typically created by the the Publisher as a standard description of the Competency Framework.This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Subjects: *This is a string expressing the general subject area of the Competency Framework (e.g. Mathematics). This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Language: *HTML Language Country Code VIA- country code from [https://tooCF.ietf.org/html/bcp47](https://tooCF.ietf.org/html/bcp47). This is an optional field in OpenSALT, though best practice indicates the filled should be filled in. However OpenSALT assumes English if not other language value is entered.

* *Adoption Status: *Adoption status displays the Framework's current status as Draft, Private Draft,  Adopted, or Deprecated.  OpenSALT assumes Adopted as the default if no status is specifically selected for the framework. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank. OpenSALT assumes Adopted as the default if no status is specifically selected for the framework.

    * *Draft*: Able to be edited by Editors and Admins in an organization. Able to be viewed by the public.

    * *Private Draft*: Able to be viewed and edited by Editors and Admin in the owning organization

    * *Adopted*: Not able to be edited by Editors or Admin

    * *Depreciated:* Was once published, however it is now out of date

* *Status Start Date: *The date that the CF Doc status started. This is an optional field in OpenSALT.

* *Status End Date: *This date is often only known when a new status is started. This is an optional field in OpenSALT.

* *Note: *Notes or comments generated by the Framework Publisher about the context of the Framework. This is an optional field in OpenSALT.

To **_save_** the updated, click the **_Save Changes_** button.

To **_cancel_** and abandon any changes, click the **_Cancel_** button.

#### 6.2.4 Delete Frameworks  

**_Audience: Super Users, Organization Admins_**

OpenSALT allows Super Users and Organization Admins to delete Frameworks if needed. Note once a Framework is deleted the action can not be undone. The framework and all associations will be permanently removed from the database.

To delete a framework the Super User or Organization Admin will first need to log into OpenSALT.

Next view the selected Framework by expanding the organization and clicking on the selected Framework.

![image alt text](image_67.png)

Take note of the document number in the Framework’s URL address in the browser bar of the **_Framework Display_** page.

![image alt text](image_68.png)

Note the current URL will be:  

**https:[your OpenSALT site]/cftree/doc/#**

*  **.../cftree/doc/** = the path for the general view of the Framework

* **#** =  the unique document number for the selected Framework

Change the url path in the browser to:

 https: **[your OpenSALTsite]/cfdoc/[framework document number]**

The **_LsDoc_** Page will display for the selected Framework.

![image alt text](image_69.png)

Confirm and confirm again you have the correct Framework selected.

Once you are sure the correct Framework is selected and you are ready to **_delete_**, click the **_Delete_** button at the bottom of the page.

![image alt text](image_70.png)

Note this action can not be undone. Do not click **_Delete_** if you need to abort the action. If you need to return to your Frameworks and **_not delete_** the current select, click on the **_Back to the list_** button.

![image alt text](image_71.png)

### 6.3 Framework Items

Items can be created for Frameworks either by importing existing data using the OpenSALT template or by manually creating the items.

#### 6.3.1 Import Items with OpenSALT Template

Users can create their own CASE-compliant data files to load into OpenSALT using a provided template and guide. This allows users to easily import their items or standards into their created framework and eliminates the need for manually entering the data into the system. The template can be found here:  [Spreadsheet Loading Guide for CASE](https://docs.google.com/spreadsheets/d/1idJv2lHCU4xojCSm5vh_zBFhgUGQvvaNSwmdSzD3QIc/edit#gid=1492955133).

##### 6.3.1.1 CSV Loading Guide for CASE

The CSV Loading Guide for CASE provides a step by step explanation on the process to convert frameworks into CASE-Compliant data. The guide contains six (6) tabs  to walk the user through the process. Most of these tabs are explanations of the process and the final tab is the template itself.

Tab 1: Step 1 Read This

An Overview of the process for creating the CSV to import the data.

Step 1: Create New Framework

![image alt text](image_72.png)

Step 2: Select "Import Children"

![image alt text](image_73.png)

Step 3: Select your CSV

![image alt text](image_74.png)

Step 4: If your CSV has associations to external frameworks in the full human readable terms (ie  CCSS.MATH.Content.K.CC.A.1) select the framework you want to associate it too. If nothing just leave alone

Step 5: Select Import Children

Tab 2: CF DOC

This graphic shows what is  required to create a Framework. Please note this data does not need to be contained in the CSV file as it will be created when the user creates the framework in OpenSALT.  

![image alt text](image_75.png)

Tab 3: CF ITEM

Explanation of the item fields that will be included in template for the Framework. Note that technically only fullStatement and humanCodingScheme are required.  ![image alt text](image_76.png)

Tab 4: CF Association

The process for associations which can be associated in the template if desired, though associations may be easier managed in the UI itself after the Framework is created and imported.  

![image alt text](image_77.png)  

Tab 5: Example Standards File

The fifth tab is an example or sample of a filled in/completed template with data to be imported into OpenSALT.

![image alt text](image_78.png)

Tab 6: Template

The template itself that will be used to add the data into the correct format and  saved as a CSV to import into OpenSALT.   

![image alt text](image_79.png)

Notes: The only required fields are fullStatement and HumanCodingScheme. SequenceNumber or IsChildOf are needed to properly created nested trees of statements as well.

##### 6.3.1.2 Import Process

After reviewing the **_Spreadsheet Loading Guide for CASE_** and the user will need to format their data into the Template Tab then save the file locally to their computer as a CSV file. This will save only the Template Tab and convert the data from an Excel file to a CSV file for import.

![image alt text](image_80.png)

Next the user will need to Import the items/children for the Frameworks. Click on the **_Import Children_** button in the **_Item Details Frame_** on the right of the selected framework to open the **_Import Items_** window.

![image alt text](image_81.png)

 Select the tab for where your template file is located. If the CSV is stored locally on your computer,  click on the Import local File tab. Browse and select your file with the Choose File button. If a specific Framework to be associated is preferred, mark that selection otherwise the default is All. Then click the Import Children button to import the items for the framework.

![image alt text](image_82.png)

Alternatively if the template is stored in your GitHub repository, click on the Import from GitHUb tab and login to connect to your file and import the items for the framework.

![image alt text](image_83.png)

The items will be loaded and the Framework Display page will be refreshed.

![image alt text](image_84.png)



##### 6.3.1.3  Error Log

On import, error messages will display when a file is missing fields. These error messages can be retrieved afterwards by clicking on "error log" in the admin console.

![image alt text](image_85.png)

(Sample log)

![image alt text](image_86.png)

#### 6.3.2 Formatting for Full Statement

Item full statements can be formatted using three different methods / pure UTF8 text can be enhanced with:

* Markdown

* LaTeX

* Limited HTML tags

These three formatting options for text can be combined in-line with limitations.

##### 6.3.2.1 Using HTML Tags

As of OpenSALT build 1.3. Some HTML tags are allowed despite HTML sanitization. The tags that will render are:

ul, ol, li, b, i, u, br, p

##### 6.3.2.2 Using Markdown

Note that since OpenSALT uses markdown([markdown-it](https://github.com/markdown-it/markdown-it/tree/master/docs)) as the primary formatting language, there could be unintended formatting consequences when importing from external sources such as ASN.

##### 6.3.2.3 Using LaTeX

The LaTeX system supports plain text writing of all KaTeX functions listed [here](https://khan.github.io/KaTeX/function-support.html). In-line LaTeX is formatted as braced between dollar signs ($):

![image alt text](image_87.png)

Alternatively, block text LaTeX is formatted as braced between double dollar signs ($$).

(no screenshot available)

##### 6.3.2.4 Combining text and LaTeX in-line

LaTeX formatting may be combined in-line with plain text in the markdown editor:

![image alt text](image_88.png)

##### 6.3.2.5 Constraints for using HTML tags

HTML and LaTeX cannot be combined in-line with anything else.

##### 6.3.2.6 Using the Modes of Markdown Editor UI

The markdown editor is accessed by clicking on the "Edit" button for an item:

![image alt text](image_89.png)

The markdown editor has 11 functional buttons to manipulate Full Statement text, from left to right they are: Bold, Italics, Heading, Quote, Generic List, Numbered List, Insert Table, Insert Horizontal Line, Toggle Preview, Toggle Side by Side, Toggle Full Screen. These text-editing options are depicted below:

![image alt text](image_90.png)

In the subsections below example text is showin in two columns; the first column shows the Markdown special characters, while the right column shows the text in the way it presents to the end user.

###### Bold 6.3.2.6.1

Text may be **bolded** by clicking icon 1/11 in the Full Statement toolbar: ![image alt text](image_91.png)

In the Markdown editor, Bold special character text is indicated by ** on either end of the statement:

![image alt text](image_92.png)

###### Italics 6.3.2.6.2

Text may be *italicized*** **by clicking icon 2/11 in the Full Statement toolbar: ![image alt text](image_93.png)

In the Markdown editor, Italics special character text is indicated by * on either end of the statement:

![image alt text](image_94.png)

###### Heading 6.3.2.6.3

Text may be converted into a header by clicking icon 3/11 icon in the Full Statement toolbar: ![image alt text](image_95.png)

In the Markdown editor, Heading special character text is indicated by #, which precedes the statement:

![image alt text](image_96.png)

###### Quote 6.3.2.6.4

Text may be converted into a header by clicking icon 4/11 icon in the Full Statement toolbar: ![image alt text](image_97.png)

In the Markdown editor, Quote special character text is indicated by >, which precedes the statement:

![image alt text](image_98.png)

###### Generic List 6.3.2.6.5

Text may be converted into a bulleted list by clicking icon 5/11 icon in the Full Statement toolbar: ![image alt text](image_99.png)

In the Markdown editor, Generic List special character text is indicated by >, which precedes the statement:

![image alt text](image_100.png)

###### Numbered List 6.3.2.6.6

Text may be converted into an enumerated list by clicking icon 6/11 icon in the Full Statement toolbar: ![image alt text](image_101.png)

In the Markdown editor, Generic List special character text is indicated by *, which precedes the statement:

![image alt text](image_102.png)

###### Insert Table 6.3.2.6.7

A table may be inserted by clicking icon 7/11 icon in the Full Statement toolbar: ![image alt text](image_103.png)

In the Markdown editor, Columns headings and associated text are separated by inserting a Horizontal Line:

![image alt text](image_104.png)

###### Insert Horizontal Line 6.3.2.6.8

A horizontal line may be inserted by clicking icon 8/11 icon in the Full Statement toolbar: ![image alt text](image_105.png)

In the Markdown editor, a solid horizontal line is indicated by ----- between text statements:

![image alt text](image_106.png)

###### Toggle Preview 6.3.2.6.9

An editor toggle between Markdown special characters vs. end user  view of text by clicking icon 9/11 icon in the Full Statement toolbar: ![image alt text](image_107.png)

The toggle shifts between preview mode and pure text edit mode.

###### Toggle SIde by Side 6.3.2.6.10

An editor may view Markdown pure text and its rendered view simultaneously by clicking icon 10/11 icon in the Full Statement toolbar: ![image alt text](image_108.png)

This two column view is depicted in all examples above and is the easiest way to edit and format text.

###### Toggle Full Screen 6.3.2.6.11

An editor may expand the Full Statement textarea by clicking icon 11/11 icon in the Full Statement toolbar: ![image alt text](image_109.png)

This does not cause the area to expand to the full monitor width, bur rather to the width of the pop-up dialogue.

###### Underline 6.3.2.6.12

Underline may be utilized by entering Markdown’s emphasis tag, or placing _underscore_ on either end of a word or phrase.

##### 6.3.2.7 Other Considerations

Line Break after markdown table requires the following input: $~$ or an HTML <br>

#### 6.3.3 Create Items Manually

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

When a Framework is created it is item neutral and is open for organizational content to be added based on the user’s needs. In addition to the Item import in section [6.5.1](#heading=h.6jki613css7u), OpenSALT allows users to manually create items and organize the data through the OpenSALT UI.

On the **_Framework Display_** page, click on the Item or Framework name that will act as a parent for the item to be added. Then in the**_ Item Details Frame_** click on the **_Add New Child Item_** button.

![image alt text](image_110.png)

The **_Add New Child Item_** window will display.

Enter in the appropriate values for all available fields. At a minimum enter in  mandatory **_Full Statement._**

* *FullStatement*: The the main content of the CF Item. It is used to express both nodes and granular statements. If the statement is part of a list, the list enumeration should not be included in the statement and should instead be contained in the List Enumeration in Source Document. This is a mandatory field in OpenSALT.

* *HumanCodingScheme*:* *The ID sometimes used by humans to identify a CF Item. It often will use concatenated codes expressing its position in the taxonomy and abbreviations to convey other classification information (e.g. K.CC.1.1). This is an optional field in OpenSALT.

* *ListEnumeration: 	*Used to parse out enumerations or bullets that precede CF Item statements. This is an optional field in OpenSALT..

* *AbbreviatedStatement: *Abbreviated or summary statement provided by the Publisher. This is an optional field in OpenSALT and may be blank.

* *ConceptKeywords: *Upper level CF Item node statements may be used to populate Concept Keywords of lower level nodes. upper The concepts data structure allows a master list of keywords to be defined which can then be parsed down specific to a node. This works as usually concepts will be a less granular hierarchy representation of of the more detailed nodes in CF items. A node could be 'Geometry' and the lower node is 'Tangents' but the keywords for 'tangents' could include the word geometry. This is an optional field in OpenSALT and may be blank.

* *Language:* HTML Language Country Code VIA- country code from [https://tooCF.ietf.org/html/bcp47](https://tooCF.ietf.org/html/bcp47). This is an optional field in OpenSALT. If best practices are not followed, this field may be blank. However OpenSALT assumes English if not other language value is entered.

* *EducationLevel:***_ _***	*The current US K12 defined vocabulary is to use CEDS https://ceds.ed.gov/cedselementdetaiCF.aspx?termid=8267. Multiple values are allowed via comma delimitation and should be used to express grade spans. This is an optional field in OpenSALT and may be blank.

* *ItemType: *e.g., "Standard," "Benchmark," "Strand," or "Topic." or "Level 1, Level 2,..." This is an optional field in OpenSALT and may be blank.*	*

* *License uri:  *Systems may filter for content with particular licences to support discovery. This is an optional field in OpenSALT and may be blank.

* *Notes: *In some cases, this can be used to contain additional information found in the original source document. This is an optional field in OpenSALT and may be blank.

![image alt text](image_111.png)

To **_create_** the item, click the **_Create_** button.

To **_cancel_** and discard the changes, click the **_Cancel_** button.

#### 6.3.4 Parent vs Child Items

Once the Item is created it will by default only be a child of the item it was created for.

![image alt text](image_112.png)

To add items nested below the item created, the user will need to make this item a Parent item. Highlight the item on in the **_Framework Display_** and click on the **_Make This Item a Parent_** button in the **_Item Detail Frame_**.

![image alt text](image_113.png)

The bullet icon on the left of the item in the **_Framework Display _**will update to reflect it is now a P**_arent item_**  and the buttons in the **_Item Detail Frame _**will update to allow the user to either downgrade back to a child with the**_ Make This Item a Child _**button or to add a new child for this parent item with the **_Add a New Child _***button. *

The user can toggle the item between **_Parent or Child_** as necessary by clicking the **_Make This Item a Parent_** or **_Make this Item a Child _**buttons respectively.* *

Note an item can be a Child of an item and a Parent to other items, however an item can not be a Child of an item with children below it. This item must be upgraded to a Parent to have children.

![image alt text](image_114.png)

The user can repeat this process an unlimited number of times to continue adding all items and marking them as Parents when appropriate to complete the full content for the framework.

![image alt text](image_115.png)

![image alt text](image_116.png)

![image alt text](image_117.png)

![image alt text](image_118.png)

#### 6.3.5 Edit Items

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

##### 6.3.5.1 Edit Item Content

To **_edit _**an item, the user must click on the item in the **_Framework Display _**and then click on the **_Edit_** button in the**_ Item Detail Frame. _**

![image alt text](image_119.png)

The **_Edit Item_** window will display. And the user can alter the data fields as needed.

![image alt text](image_120.png)

To **_save _**the changes, click the **_Save Changes_** button.

To **_cancel_** and discard the changes , click the **_Cancel _**button.

##### 6.3.5.2 Edit Item Positions

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

OpenSALT enables users to move items within frameworks and reorder without the need to edit each item. The user must first enable the functionality but checkin on the box at the top of the Framework Display to Enable drag-drop reordering.

![image alt text](image_121.png)

With the box checked and the function enabled, the user can now click on an item and drag and drop it to another location. Note clicking on a child will only move the child, whereas selecting a Parent will move the parent and all of it’s children.

![image alt text](image_122.png)![image alt text](image_123.png)

Note with the drag and drop feature, items can be indented (moved to new parents) outdented to become parents, and all data can be fully moved around. However once an item is moved, there is no undo button, so the user would need to manually move (drag/drop) the item to the original position if the move is not required or done in error. Because of this, the feature is always defaulted to unchecked so no errors are accidentally made.

#### 6.3.6 Delete Items

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

All credentialed users can delete items that they have access to edit.

##### 6.3.6.1 Delete Child Item

To **_delete _**a child item, the user must click on the item in the **_Framework Display _**and then click on the **_Delete_** button in the**_ Item Detail Frame. _**

### ![image alt text](image_124.png)

The delete action can not be undone. The user will be prompted with a warning message and must acknowledge the action cannot be reversed by clicking on the **_Delete_** button to proceed.

![image alt text](image_125.png)

To cancel and leave the item in the Framework, click the **_Cancel_** button.

##### 6.3.6.2 Delete Parent Item

To **_delete _**a parent item, the user must click on the item in the **_Framework Display _**and then click on the **_Delete_** button in the**_ Item Detail Frame. _**

### ![image alt text](image_126.png)

The delete action can not be undone. The user will be prompted with a warning message that the item and all of it’s children will be deleted if the user proceeds. The user and must acknowledge the action cannot be reversed by clicking on the **_Delete_** button to proceed.

![image alt text](image_127.png)

To cancel and leave the item in the Framework, click the **_Cancel_** button.

### 6.4 Exemplars for Items

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

OpenSALT provides the ability for a user to connect an example or **_Exemplar_** to any item within a Framework.  Note the Exemplars can not be associated to the Framework, rather only the items within. However an Exemplar can be associated to a Parent or a Child Item.

#### 6.4.1 Add Exemplar

To connect an example or **_Exemplar_** to an item. Select the item within the framework on the **_Framework Display_** page. Then click on the **_Add Exemplar_** button on in the **_Item Details Frame_**.

![image alt text](image_128.png)

The **_Add an Exemplar_** window will open.

![image alt text](image_129.png)

The user can either enter in a URL to an Exemplar or type text into the box. To save the Exemplar, click on the **_Add Exemplar_** button. To discard changes click on the **_Cancel_** button.

After clicking the **_Add Exemplar_** button, the F**_ramework Display_** page will refresh and the exemplar is linked to the item. This can be verified in the **_Item Detail Frame_**.

![image alt text](image_130.png)

#### 6.4.2 Delete Exemplar

To delete an **_Exemplar_** from an item, click on the ‘**_x_**’ icon next to the exemplar detail in the **_Exemplar section_** of the I**_tem Detail Frame_** on the **_Framework Display_** page. Note this action can not be reversed once completed. The user will be promoted with a warning message to proceed.  

![image alt text](image_131.png)

Note this action can not be reversed once completed. The user will be promoted with a warning message and must acknowledge the **_OK_** button to proceed.

![image alt text](image_132.png)

### 6.5 Derivative Frameworks - Copy Items

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

OpenSALT allows users to create derivative frameworks  from frameworks within an OpenSALT server or instance.  Creating a derivative framework allows organizations to take a base original copy of a framework and expand it to better meet its needs.  The illustration below shows how the derivative frameworks fit with the scope of frameworks as a whole. Derivative frameworks essentially act as a bridge for organizations to navigate education needs.

![image alt text](image_133.jpg)

The user will need to be logged into OpenSALT and create or select the framework that will act as the new derivative framework or copy. Please see section [6.2.2  Manually Create Frameworks](#heading=h.uzlj2tpaic68) if assistance is needed on how to create a framework. On the **_Framework Display_** page, click on the **_Copy Items_** button in the **_Item Detail_** frame.

![image alt text](image_134.png)

In the C**_opy Items_** frame select the document/Framework to copy. Note if the framework to copy is not listed in the document view it is not currently on the OpenSALT server. Please see section [6.2.1](#heading=h.e03op9mhzcs2) for instructions on importing frameworks into OpenSALT.

Select the desired framework in the **_Document _**dropdown. The Copy ITems frame will refresh and load the selected framework so its items can be viewed.

![image alt text](image_135.png)

The user can now select individual items or the full set to copy over to the derivative framework on **_Framework Display_** on the left.

To select and copy a single item, expand the framework to the level/item desired. Click on the item and drag and drop it to the appropriate location on the left.

![image alt text](image_136.png)

![image alt text](image_137.png)

When the user releases the item on the left, the framework will refresh and the item will now display as part of the framework.

![image alt text](image_138.png)

A user can select a parent item and add it to the framework, which will copy over all children under the parent as well.

![image alt text](image_139.png)

![image alt text](image_140.png)

To select multiple items at once the user can expand the multi select function by clicking on the empty checkbox above the framework displayed in the Copy Items frame.

![image alt text](image_141.png)

The user can now check one or more boxes and click on an item to drag and drop to the left. All items selected will move. Note if a Parent is selected all the children will also move with it even if they are not individually checked.

![image alt text](image_142.png)

Note to close the multi select function, click on **_Actions_** and select **_Hide Checkboxes_**.   

![image alt text](image_143.png)

![image alt text](image_144.png)

### 6.6 Association Management

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

OpenSALT provides users with a robust way to include associations following the IMS GLobal CASE Standards. The application enables users to connect frameworks and framework items together to bring together relationship models that integrate and blend frameworks in a meaningful way.  The illustration below provides a visual mapping for how associations can connect frameworks and help to crosswalk standards.

![image alt text](image_145.jpg)

#### 6.6.1 Associations

OpenSALT allows for the associations defined by [IMS Global’s CASE specification as noted in figure 7.3.1](https://www.imsglobal.org/sites/default/files/CASE/casev1p0/information_model/caseservicev1p0_infomodelv1p0.html#Enumerated_CFAssociationTypeEnum). The permitted associations are:



<table>
  <tr>
    <td>Association Type</td>
    <td>Description</td>
  </tr>
  <tr>
    <td>exactMatchOf</td>
    <td>Equivalent to. Used to connect derived CFItem to CFItem in original source CFDocument.</td>
  </tr>
  <tr>
    <td>exemplar</td>
    <td>The target/destination node is an example of best practice for the definition of the source/origin.</td>
  </tr>
  <tr>
    <td>hasSkillLevel</td>
    <td>The destination of this association is understood to define a given skill level i.e. Reading Lexile 100, Depth Knowledge 2, or Cognitive Level (Blooms Taxonomy) etc.</td>
  </tr>
  <tr>
    <td>isChildOf</td>
    <td>To represent the structural relationship in a taxonomy between parent and child. The source/origin is a child of the target/destination.</td>
  </tr>
  <tr>
    <td>isPartOf</td>
    <td>The origin of the association is included either physically or logically in the item at the destination of the association. This classifies an item as being logically or semantically contained as a subset of the destination.</td>
  </tr>
  <tr>
    <td>isPeerOf</td>
    <td>The source/origin is a peer of of the target/destination.</td>
  </tr>
  <tr>
    <td>isRelatedTo</td>
    <td>The origin of the association is related to the destination in some way that is not better described by another association type.</td>
  </tr>
  <tr>
    <td>precedes</td>
    <td>The origin of the association comes before the destination of the association in time or order.</td>
  </tr>
  <tr>
    <td>replacedBy</td>
    <td>The origin of the association has been supplanted by, displaced by, or superseded by the destination of the association.</td>
  </tr>
</table>


##### 6.6.1.1 Create Associations

OpenSALT allows users to create associations to and between Framework items that either reside in the same OpenSALT instance or to any other outside CASE-compliant system.  

To create an association, open the Framework target in the **_Framework Dispaly_** page.then click **_Create Associations_** to open the Associations frame.

![image alt text](image_146.png)

In the Document dropdown, select the framework you want to use with the associations.  If the framework is within the OpenSALT server instance, the framework name will display organized by the owning Organization.  

![image alt text](image_147.png)

Click on the required Framework to display the framework and items.

Alternatively you can select The final option: **_Load an "external" document by url… _**This allows the user to select any CASE compliant framework that is stored on an external location.

The **_Load External Document_** window will display. The user will need to copy and paste, or type in the url for the Case-compliant framework.  

![image alt text](image_148.png)

In instances of OpenSALT, the **_Case Framework URL_** can be found on the **_Framework Display_** page in the **_Item Detail_** frame.

![image alt text](image_149.png)

Note if the copied URL does not have the .JSON extension, you will need to add it for the document to load.  

![image alt text](image_150.png)

To load the framework, click the **_Load Document_** button.

To cancel and return to the **_Framework Display_** page, click the **_Cancel_** button.

The selected framework will display in the **_Create Associations_** frame.

![image alt text](image_151.png)

Select the item from the right by clicking on it and dragging it over the associated item on the left.

![image alt text](image_152.png)

The Create Association window will display showing the item that was both dragged and dropped as well as the item that it was connected to.

![image alt text](image_153.png)

 The user can select the **_Relationship Type_** from the drop down and change the relationship arrow as needed by clicking on the **_Switch_** button.

![image alt text](image_154.png)

To save the association, click the **_Associate_** button.

To cancel and abandon the association, click the **_Cancel_** button.

The**_ Framework Display_** page will refresh. If the user clicks on the item in the **_Framework Display_** and then clicks **_Item Details _**, the newly created association will be visible.

![image alt text](image_155.png)

To add several of the same type of association to one item, the user can open the multi select function by clicking on the empty checkbox above the framework displayed in the **_Create Associations_** frame.

![image alt text](image_156.png)

The user can now check one or more boxes and click on an item to drag and drop to the left. All items selected will become part of the association. Note if a Parent is selected all the children will associate even if they are not individually checked.

![image alt text](image_157.png)

When the users drags the items to the the left and associates them with an item, the **_Create Associations_** window will display. The user will note that the list will only display the first of the associated item, and will indicate there are additional items selected. Also note all items will have the same association, as you can only select one association type. Set the associations as required and click the Associate button.  

![image alt text](image_158.png)

Note to close the multi select function, click on **_Actions_** and select **_Hide Checkboxes_**.   

![image alt text](image_159.png)

##### 6.6.1.2 Edit Associations

To Edit an association, the user must delete the association and create a new association. PLease see section [6.6.1.2](#heading=h.snby2z2ysyqp) for how to delete an association and [6.6.1.1](#heading=h.w21k7kyd2nwq) for how to create a new association.

##### 6.6.1.2 Delete Associations

Users can either use the **_Tree View_** or the **_Association View _**to delete associations.

###### 6.6.1.2.1 Delete Associations from Tree View

On the **_Framework Display_** page, click on the **_Tree View_** button if not already selected. Then locate the association in the I**_tem Detail _**frame. Click the **_X_** icon next to the association to remove.

![image alt text](image_160.png)

The user will get a popup window warning that he action can not be undone. If the user wants to proceed and delete the association, the user will click the **_OK _**button. Otherwise the user can cancel by clicking on the **_Cancel _**button.

![image alt text](image_161.png)

###### 6.6.1.2.2 Delete Associations from Association View

On the **_Framework Display_** page, click on the **_Association View_** button if not already selected.

![image alt text](image_162.png)

Locate the association in the in the list to be deleted. Click the **_X_** icon next to the association to remove.

![image alt text](image_163.png)

The user will get a popup window warning that he action can not be undone. If the user wants to proceed and delete the association, the user will click the **_OK _**button. Otherwise the user can cancel by clicking on the **_Cancel _**button.

![image alt text](image_164.png)

#### 6.6.2 Association Groups

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

Associations can belong to an association group. There is a selector to filter the view for only those items and associations for a specific group, if there are any. If there are no group, all associations belong to the default "Null" group. If there are any association group, the default view is “All” association groups. The Association group filter drop list allows you to choose the “null” group, the “All” group or any specific group. In the view, an association that belongs to an association group is tagged in the display as such:

On the **_Framework Display_** page, click the **_Manage Association Groups_** button in the **_Item Detail_** frame.

![image alt text](image_165.png)

The **_Manage Association Groups_** window will display. Click on the **_Add a New Association Group_** button. ![image alt text](image_166.png)

The **_Add New Association Group_** window will display. The user will need to enter a **_Title_** and the optional **_Description_**. Next click on the **_Create_** button.

![image alt text](image_167.png)

The user will repeat the process to add any needed **_Association Groups_**.

![image alt text](image_168.png)

After creating the required Association Groups, the user can **_Edit_** a Group, **_Delete _**a Group or click **_Done_**.

The filter option for the **_Association Groups _**will now display on the **_Display Frameworks _**page.**_ _**

![image alt text](image_169.png)

The user will now need to associate items with the appropriate groups. **_ _**

#### 6.6.3 Crosswalk Associations

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor_**

OpenSALT allows for users to create crosswalks between frameworks. To create a crosswalk the user will need to start with an empty framework. For instructions on creating a framework see section [6.2.2](#heading=h.uzlj2tpaic68).

##### 6.6.3.1 Create Crosswalk Associations

Open the framework to the **_Display Framework_** page. In the click on **_Change Document_** to select the first framework to use in the crosswalk.

![image alt text](image_170.png)

This will open a Document dropdown. The user can select a framework that is in their current OpenSALT server from the list by clicking on the desired framework.

![image alt text](image_171.png)

Alternatively the user can connect to a framework that is outside their system by selecting the final option: **_Load an "external" document by url… _**This allows the user to select any CASE compliant framework that is stored on an external location.

The **_Load External Document_** window will display. The user will need to copy and paste, or type in the url for the Case-compliant framework.  

![image alt text](image_172.png)

In instances of OpenSALT, the **_Case Framework URL_** can be found on the **_Framework Display_** page in the **_Item Detail_** frame.

![image alt text](image_173.png)

Note if the copied URL does not have the .JSON extension, you will need to add it for the document to load.  

![image alt text](image_174.png)

To load the framework, click the **_Load Document_** button.

Next the user will click on the **_Create Association_** option above the **_Item Detail_** frame.

![image alt text](image_175.png)

A Document dropdown will display to allow the user to select the second framework to be selected. Again the user can select an existing framework from their OpenSALT server or can select an outside CASE-compliant framework.

![image alt text](image_176.png)

The user can now use drag and drop to select items from the right and drag to connect to items on the left to establish the cross walk. After an association is connected with the drag and drop, the Create Association window will display and the user can define the association.

![image alt text](image_177.png)

When the user is satisfied with the association definition, click on the **_Associate_** button.

To cancel, click on the **_Cancel _**button.

The user should repeat this process to connect all required framework items for the crosswalk.

To view the cross walk, the user will click on the **_Association View_** at the top of the screen.

![image alt text](image_178.png)

![image alt text](image_179.png)

##### 6.6.3.2 Edit Crosswalk Associations

To Edit a crosswalk association, the user must delete the associations and create new associations. Please see section [6.6.1.2](#heading=h.snby2z2ysyqp) for how to delete an association and [6.6.1.1](#heading=h.w21k7kyd2nwq) for how to create a new association.

##### 6.6.3.3 Delete Crosswalk Associations

On the **_Framework Display_** page, click on the **_Association View_** button if not already selected.

![image alt text](image_180.png)

Locate the association in the in the list to be deleted. Click the **_X_** icon next to the association to remove.

![image alt text](image_181.png)

The user will get a popup window warning that he action can not be undone. If the user wants to proceed and delete the association, the user will click the **_OK _**button. Otherwise the user can cancel by clicking on the **_Cancel _**button.

![image alt text](image_182.png)

Alternatively if the entire crosswalk needs to be deleted and all associations, the user can delete the framework instead of removing all associations. Please see section [6.8](#heading=h.z5n3wwx83avg) for instructions on deleting a framework.

### 6.7 Export Frameworks Packages

**_Audience: Super Users, Super Editor, Organization Admins, Organization Editor, Public_**

OpenSALT is designed to enable all users roles to **_Export_** complete framework packages or documents. While **_Public_** users can only export framework packages that are in an **_Adopted_**, **_Draft_**, or **_Depreciated_** release status, credentialed users will have the ability to export **_Draft_** and **_Private Draft_** framework packages as well.

To **_Export_** a framework package the user needs to be on the **_Framework Display_** page for the selected framework and then click on the **_Export_** button.  

![image alt text](image_183.png)

An Export window will display to provide the user with several **_Export _**options:

* Competency Framework Package (JSON)

* Styled PDF

* Spreadsheet Export

* HTML Archive

* Direct OpenSALT Link

![image alt text](image_184.png)

The user can select an**_ Export_** option or can click on the **_Done_** button or the ‘**_X_**’ at the top of the window  to close the **_Export_** window. Each **_Export_** type will be discussed in the following subsections.

#### 6.7.1 Export Competency Framework Package (JSON) File

The first **_Expor_****_t_** option is the **_Competency Framework Package (JSON)_**. This option allows users to extract the data for the framework packaging in the JavaScript Object Notation (JSON) file format. This is a lightweight, text-based, language-independent data interchange format that allows for easy ingestion into other system and applications using a common standard programming language.

When a user mouses over the **_Competency Framework Package (JSON)_** button, a soft explanation is displayed that advises the user of the button’s intended purpose: ‘Exports a JSON file using the IMS-standard format. This is the best format to user for Archiving Frameworks.’

![image alt text](image_185.png)

To generate a JSON file for the Framework Package, the user will click on the **_Competency Framework Package (JSON) _***button. *The browser will automatically create and down load a JSON file for the Framework Package. The user will need to retrieve the file following the browser’s specific protocol and path. The image below shows the download in Chrome. Note the file is in the download frame at the bottom of the page. It has also been added to the user’s Download folder within the user’s My Documents.

![image alt text](image_186.png)

 To open the JSON file the user will need to identify a compatible application on their computer. Notepad or NotePad ++ can be used if no preferred application is identified.

The following is an example of the generated JSON file viewed in Notepad.![image alt text](image_187.png)  

#### 6.7.2 Export Styled PDF (Future Function)

The second **_Export_** option is the **_Styled PDF_** button.

![image alt text](image_188.png)

The purpose of this **_Export_** option is to produce a system generated **_PDF_** with nice formatting and styling that can be used to compare against a source document for validation or can replace source documentation as needed.

Users will note that at this time the button is not active. A description will not display when a user mouses-over the button, nor will the button respond with clicked. This is a placeholder for future functionality. As of the current release of OpenSALT this feature is not available. Though it is on the road map and is expected to be in a future release. If any organization requires this functionality, you can sponsor the development of the feature to help prioritize the development timeline by contacting PCG, ACT, or School City to discuss development costs and your needs.

#### 6.7.3 Export Spreadsheet

The third **_Export_** option is the **_Spreadsheet Export._** This option allows users to extract the data for the framework packaging in a spreadsheet file that can be opened/viewed/edited in a program like Microsoft’s Excel or Google Sheets.

When a user mouses over the **_Spreadsheet Export _**button, a soft explanation is displayed that advises the user of the button’s intended purpose: ‘Exports as an Excel spreadsheet file that you can open and edit in spreadsheet programs such as Microsoft Excel. ’

![image alt text](image_189.png)

To generate a spreadsheet file for the Framework Package, the user will click on the **_Spreadsheet Export _***button. *The browser will automatically create and download a case xlsx file for the Framework Package. The user will need to retrieve the file following the browser’s specific protocol and path. The image below shows the download in Chrome. Note the file is in the download frame at the bottom of the page. It has also been added to the user’s Download folder within the user’s My Documents.

![image alt text](image_190.png)

To open the spreadsheet file the user will need to identify a compatible application on their computer. The most common applications used are Microsoft Excel or Google Sheets.

Users credentialed users who are experienced with importing Frameworks into OpenSALT with the CASE template will already be familiar with this spreadsheet format. For all other users, the following details the exported spreadsheet file.  

When opened the spreadsheet file will have three tabs:

1. CF Doc

2. CF Item

3. CF Association

![image alt text](image_191.png)

##### 6.7.3.1 CF Doc Tab

The purpose of the first tab, CF Doc, is to provide the user with basic background information on the Framework Package.  

![image alt text](image_192.png)

The columns on the spreadsheet include the following:

* *Identifier:*  The identifier is intended to be used as the primary key global identifier within or external to the system. This is a mandatory field in OpenSALT and the export will contain data.

* *C**reator:** * The entity that authorized or created the competency framework. It could be an education agency, higher education institution, professional body. It is the owner of the competency framework (e.g CCSSO, TEA, NGSS). This is a mandatory field in OpenSALT and the export will contain data.

* *Title*: The title as it appears on the cover of the Official Source artifact, although it may be a title created by the Publisher. This is a mandatory field in OpenSALT and the export will contain data.

* *LastChangeDateTime:* The field is used to establish any change, not just major version revisions. This is a mandatory field in OpenSALT and the export will contain data.

* *OfficialsourceURL*:  The URL of the artifact adopted by the Standard Setting Entity. Often this document is published in html and/or as pdf and is used by the standard setting entity as part of its approval process. Since it is not the intent of this specification to fully reproduce the human-facing content and formatting of the source document, it is recommended that this document be transmitted as part of the competency framework package. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Publisher:*  The entity that loads and publishes the Framework. Note that in  many cases, the Standard Setting Entity may lack technical capabilities to publish the Competency Framework in a standard format so a third party may be displayed. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Description: * The description is typically created by the the Publisher as a standard description of the Competency Framework.This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Subject:* This is a string expressing the general subject area of the Competency Framework (e.g. Mathematics). This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Language:* HTML Language Country Code VIA- country code from [https://tooCF.ietf.org/html/bcp47](https://tooCF.ietf.org/html/bcp47). This is an optional field in OpenSALT. If best practices are not followed, this field may be blank. However OpenSALT assumes English if not other language value is entered.

* *Version:* This is used to separate any version information expressed by the Official Source artifact. Once and CF Pkg has been approved and published, any changes to an CF Item will constitute a new version of the CF Doc. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *AdoptionStatus:* Adoption status displays the Framework's current status as Draft, Private, Draft,  Adopted, or Deprecated.  OpenSALT assumes Adopted as the default if no status is specifically selected for the framework. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank. OpenSALT assumes Adopted as the default if no status is specifically selected for the framework.

* *StatusStartDate:* The date that the CF Doc status started. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *StatusEndDate:*  This date is often only known when a new status is started. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *License:* Systems may filter for content with particular licences to support discovery. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *Notes:* Notes or comments generated by the Framework Publisher about the context of the Framework. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

##### 6.7.3.2 CF Item Tab

The purpose of the second tab, CF Item, is to provide the user with items and content within the Framework Package.  

![image alt text](image_193.png)

The columns on the spreadsheet include the following:

* *Identifier:*  The identifier is intended to be used as the primary key global identifier within or external to the system. This is a mandatory field in OpenSALT and the export will contain data.

* *FullStatement*: The the main content of the CF Item. It is used to express both nodes and granular statements. If the statement is part of a list, the list enumeration should not be included in the statement and should instead be contained in the List Enumeration in Source Document. This is a mandatory field in OpenSALT and the export will contain data.

* *HumanCodingScheme*:* *The ID sometimes used by humans to identify a CF Item. It often will use concatenated codes expressing its position in the taxonomy and abbreviations to convey other classification information (e.g. K.CC.1.1). This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *SmartLevel:*   This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *ListEnumeration: 	*Used to parse out enumerations or bullets that precede CF Item statements. This is an optional field in OpenSALT. If best practices are not followed, this field may be blank.

* *AbbreviatedStatement: *Abbreviated or summary statement provided by the Publisher. This is an optional field in OpenSALT and may be blank.

* *ConceptKeywords: *Upper level CF Item node statements may be used to populate Concept Keywords of lower level nodes. upper The concepts data structure allows a master list of keywords to be defined which can then be parsed down specific to a node. This works as usually concepts will be a less granular hierarchy representation of of the more detailed nodes in CF items. A node could be 'Geometry' and the lower node is 'Tangents' but the keywords for 'tangents' could include the word geometry. This is an optional field in OpenSALT and may be blank.

* *Notes: *In some cases, this can be used to contain additional information found in the original source document. This is an optional field in OpenSALT and may be blank.

* *Language:* HTML Language Country Code VIA- country code from [https://tooCF.ietf.org/html/bcp47](https://tooCF.ietf.org/html/bcp47). This is an optional field in OpenSALT. If best practices are not followed, this field may be blank. However OpenSALT assumes English if not other language value is entered.

* *EducationLevel:***_ _***	*The current US K12 defined vocabulary is to use CEDS https://ceds.ed.gov/cedselementdetaiCF.aspx?termid=8267. Multiple values are allowed via comma delimitation and should be used to express grade spans. This is an optional field in OpenSALT and may be blank.

* *CFItemType: *e.g., "Standard," "Benchmark," "Strand," or "Topic." or "Level 1, Level 2,..." This is an optional field in OpenSALT and may be blank.*	*

* *License: 	*Systems may filter for content with particular licences to support discovery. This is an optional field in OpenSALT and may be blank.

* *LastChangeDateTime: *This is used for versioning. This is a mandatory field in OpenSALT and the export will contain data.

##### 6.7.3.3 CF Association Tab

The purpose of the third tab, CF Association, is to provide the user with items and content within the Framework Package.  

![image alt text](image_194.png)

The columns on the spreadsheet include the following:

* *Identifier:*  The identifier is an unambiguous, synthetic, unique reference to the association. This is a mandatory field in OpenSALT and the export will contain data.

* *URI:*  Establishes uniqueness of an association between a learning standard and another learning standard or other objects such as learning resources. [CEDS Element: Learning Standard Item Association Identifier URI, ID:000871].  This is a mandatory field in OpenSALT and the export will contain data.

* *OriginNodeIdentifier:* Identifier of the origin node when the Learning Standard Item Association is used as a connector in a learning map. [CEDS Element: Learning Standard Item Association Origin Node URI, ID: 001406]. This is a mandatory field in OpenSALT and the export will contain data.

* *DestinationNodeIdentifier:* Identifier of the destination node when the CF Association is used as a connector in a learning map. [CEDS Element: Learning Standard Item Association Destination Node URI, ID: 001404]. This is a mandatory field in OpenSALT and the export will contain data.

* *AssociationType**: *A controlled vocabulary used to express the types of associations used to describe the relationship between CF Docs and between CF Items. This is a mandatory field in OpenSALT and the export will contain data.

* *AssociationGroupIdentifier:**  *An identifier to allow associations to be grouped together. Different values only have to be unique within the document. This is an optional field in OpenSALT and may be blank.

* *AssociationGroupName:**  *A common group name to allow associations to be grouped together. Different values only have to be unique within the document. This is an optional field in OpenSALT and may be blank.

* *LastChangeDateTime:* A system generated log of the most recent change to this record. This is a mandatory field in OpenSALT and the export will contain data.

#### 6.7.4 Export HTML Archive (Future Function)

The fourth **_Export_** option is the **_HTM Archive_** button.

![image alt text](image_195.png)The purpose of this **_Export_** option is to produce an **_HTML_** code snippet that can be used on an alternative website that renders the framework in a consistent manner to the display on OpenSALT.

Users will note that at this time the button is not active. A description will not display when a user mouses-over the button, nor will the button respond with clicked. This is a placeholder for future functionality. As of the current release of OpenSALT this feature is not available. Though it is on the road map and is expected to be in a future release. If any organization requires this functionality, you can sponsor the development of the feature to help prioritize the development timeline by contacting PCG,ACT, or School City to discuss development costs and your needs.

#### 6.7.5 Link for Browser View

The final share option to connect to the Framework Package outside of OpenSALT is the **_Browser Link_**.  

![image alt text](image_196.png)

OpenSALT provides the users with the direct **_URL_** for the selected Framework Package as both a **_hyperlink_** and display the text of the unique **_URL_**. The sure can copy the **_URL_** to us in any document, application or website. The **_URL_** will return the audience to the selected **_Framework’s Display_** page within OpenSALT when followed. Any user will be able to access the selected Framework package as no credentials or login are required when following the URL link.

## 7.0 Options

### 7.1 Commenting Module

	Published frameworks are able to be commented on by authenticated users for the purpose of collecting feedback on framework item metadata.  Commenting must be turned on by a system administrator.

#### 7.1.1 Features

	Provisioned users are able to upvote and reply to other users comments. You are able to delete comments that you have written as well. Simply navigate to any framework item and make your comment, or upvote/respond to others previous comments. The comment panel may be hidden - it will be on the bottom of the ride side panel.

![image alt text](image_197.png)

#### 7.1.2 Viewing Comments

You are able to sort comments by the three tabs - newest, Oldest, and Most Popular (see graphic above). You may use these tabs to sort comments in the way that suits your interest and purpose best. Comments are not a part of the framework itself but independently stored. Due to a feature that truncates the email address of a participant, users cannot start their usernames with the @ symbol.

![image alt text](image_198.png)

#### 7.1.3 Commenting Configuration

To turn on commenting, a system administrator can follow the steps outlined here: [https://github.com/opensalt/opensalt/blob/develop/CONFIGURATION.md](https://github.com/opensalt/opensalt/blob/develop/CONFIGURATION.md)  

OpenSALT has integrated with this third party code with a congruent MIT license in order for reviewing frameworks.

### 7.2 User Account Self-Creation

#### 7.2.1 Features

Users have the ability to create their own accounts and organizations on signup.

#### 7.2.2 Process

1. Select "Sign up" from the top right page or Log In page.

![image alt text](image_199.png)

2. User enters their desired email address and password (twice). They cannot enter an email address already in use and their passwords must match. ![image alt text](image_200.png)

3. They also can select their Organization and if no Organization exists, create one.

![image alt text](image_201.png)

4. Once the Super Admin receives an email notification, they can navigate to the USer List page and Approve or Suspend/Reject the user.

![image alt text](image_202.png)

#### 7.2.3 Configuration
