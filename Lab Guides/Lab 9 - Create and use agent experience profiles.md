# Lab 9 - Create and use agent experience profiles

**Objective** - You will create an agent experience profile and configure parameters to the profile in the Customer Admin service center

## Task 1 - Create agent experience profiles in Customer Service admin center

By using agent profiles, you can create targeted app experiences for
agents and supervisors. Profiles help access the features that your
agents and supervisors can use in their daily tasks to resolve customer
issues.

1.  Open a new tab in the browser. Sign in to the Power Platform admin
    center - https://admin.powerplatform.microsoft.com/ with the
    credentials provided to execute the lab in the home tab. Select **> Environments>
    CustomerService Trial environment> Environment URL.**

2.  You will be navigated to **Customer Service workspace**. Click on **App selector** to display the list of apps.
   
4.  Select **Customer Service Admin center** from the list of Apps.

3.  Go to **Agent experience profiles** in **Agent
    experience** \> **Workspaces**.

    ![A screenshot of a phone Description automatically
generated](./media/media9/image1.png)

2.  Select **New**

  ![A screenshot of a computer Description automatically
generated](./media/media9/image2.png)

3.  Enter the following details on the **Create a new agent experience
    profile** dialog.

    - **Name:**  `Contoso Agent`

    - **Unique name:** `msdyn_custom_chatagent`

    - **Description:** `Contoso Agent`

    - Select **Create**.

  ![](./media/media9/image3.png)

4.  An agent experience profile is created.

  ![A screenshot of a computer Description automatically
generated](./media/media9/image4.png)

## Task 2 - Assign users, templates, configure productivity pane, channels

For the profile that you created, you can add users and configure option
such as specific session templates, conversation channels, and
productivity tools.


1. Open a new tab in the browser. Sign in to the Power Platform admin
    center - https://admin.powerplatform.microsoft.com/ with the
    credentials provided to execute the lab in the home tab.
 
2.  In the left side panel, select **Environments**.

    ![A screenshot of a computer Description automatically
generated](./media/media2/image10.png)

3.  Select your **Customer Service Trial** environment.
4.  Select **Settings** from the upper menu.

5. Select **Users + permissions > Users**.

6. From the upper menu, select **Add user**.

7. In the Add user pane, search for and select **Megan Bowen**. Select **Add**.

    ![A screenshot of a computer Description automatically
generated](./media/media9/image15.jpg)
   
8. In the Manage security roles page, select the **System administrator** role. Select **Save**.

    ![A screenshot of a computer Description automatically
generated](./media/media9/image16.jpg)
   
9. Switch back to Customer Service admin center tab. Go to **Agent experience profiles** in **Agent experience > Workspaces**.
10. Select **Contoso Agent** profile.
11. In the **Users** section, specify the agents this profile must be associated with. Select **Add Users.**

    ![A screenshot of a computer Description automatically
generated](./media/media9/image5.png)

12. Select the user **Megan Bowen**. Select **Add.**

  ![A screenshot of a computer Description automatically
generated](./media/media9/image6.png)

  ![](./media/media9/image7.png)

13. Select **Add entity session template** to link a session template to
  the profile.

    ![A screenshot of a computer Description automatically
generated](./media/media9/image8.png)

14. On the **Entity session templates** pane, Select **Add.**

    ![A screenshot of a computer Description automatically
generated](./media/media9/image7.5.png)

15. Select **Case** under **Entity.** Select **Case Entity Session – Default Template** as **Session Template**.

    ![](./media/media9/image9.png)
        
16. Select **Add.** Select **Save and Close.**

  ![](./media/media9/image10.png)

  ![A screenshot of a computer Description automatically
generated](./media/media9/image11.png)

17. In the **Productivity pane**, select **Turn on** 

  ![A screenshot of a computer Description automatically
generated](./media/media9/image12.png)

18. To enable the productivity tools that the agents can access when they
  work on their assigned tasks. The following productivity tool options
  are available:

  - Default mode

  - Smart assist

  - Agent scripts

  - Microsoft Teams

  - Knowledge search

  - Copilot help pane

19. Turn on the toggle against the option in the **Productivity Pane** as per the screnshot to
enable it for the agent. Select **Save and Close**

  ![](./media/media9/image13.png)

  ![A screenshot of a computer Description automatically
generated](./media/media9/image14.png)


**Summary** - You created an agent experience profile and configure parameters to the profile in the Customer Admin service center.
