## Lab 11 - ​ Configuring Application Users, Smart Assist Bots, and Agent Scripts in Copilot Service

### Introduction:

In this lab, you will register a new app in Microsoft Entra ID,
configure it as an application user in the Power Platform admin center,
and connect it to Copilot Service. You will then associate a smart
assist bot with a workstream and create an agent script for chat
sessions.

## Exercise 1 - Configure Application User and Smart Assist Bot

### Task 1 – Register an Application in Microsoft Entra ID

In this task, you will register a new app called **Contoso App** in
Microsoft Entra ID to enable secure authentication and connection with
Copilot Service.

1.  Open a new tab and open Microsoft Entra Admin center -
    !!https://entra.microsoft.com/!!.

2.  Log in with credentials, download the authentication app on the
    phone, and complete the authentication process.

    ![](./media/image1.png)

3.  Under Entra ID, navigate to App registration and then click on the
    **+ New registration**.

    ![](./media/image2.png)

4.  Enter the name of the app as !!Contoso App!! and click on
    **Register**.

    ![](./media/image3.png)

5.  You will be navigated to the **Contoso App** page.

    ![A screenshot of a computer Description automatically
  generated](./media/image4.png)

### Task 2 - Create an Application User in Power Platform

In this task, you will create an application user in Power Platform and
assign appropriate roles.

1.  Open a new tab in the browser and launch the PowerPlatform admin
    center - !!https://admin.powerplatform.com/!!.

2.  Select **Manage > Environments** on the left navigation pane.

    ![A screenshot of a computer Description automatically
    generated](./media/image5.png)

3.  Select the **ContactCenter** **Trial** environment and then select
    **Settings**.

    ![](./media/image6.png)

    ![A screenshot of a computer AI-generated content may be
  incorrect.](./media/image7.png)

4.  On the **Settings** page, select **Users + permissions**, and then
    select **Application users**.

5.  On the **Application users** page, select **new app user**.

    ![](./media/image8.png)

6.  In the **Create a new app user** dialog that opens. Select **Add an
    app**.

    ![A screenshot of a computer Description automatically
  generated](./media/image9.png)

7.  Select the **Contoso App** and then select **Add**.

    ![](./media/image10.png)

8.  Enter !!Org!! in the business unit field and select your trial
    environment **Business unit**.

9.  Select Edit on the **Security roles** field.

    ![](./media/image11.png)

10. On the **Add security roles** page, select **Omnichannel
    agent** from the dropdown list and select **Save** to go back and
    then click on **Create** to create a new app.

    ![](./media/image12.png)

    ![](./media/image13.png)

11. Go to **Copilot Service Admin Center \> User Management**. Click
    **Manage** at **Users**.

    ![](./media/image14.png)

12. Select the dropdown for **Enabled Users** and select **Application
    Users**.

    ![](./media/image15.png)

13. Click on the **Contoso App**.

    ![](./media/image16.png)

14. Select the dropdown for **Users** below the app name and then select
    **Application Users**.

    ![](./media/image17.png)

15. Select **Bot Application user** for **User Type**.

    ![](./media/image18.png)

16. Switch back to the Entra admin center, copy the App ID of the app
    that is created in the previous task.

    ![](./media/image19.png)

17. For Bot application ID enter the application ID of the app that is
    created in Entra Admin center.

    ![](./media/image20.png)

18. Select **Save & Close**.

    ![](./media/image21.png)

### Task 3 - Add a Smart Assist Bot to a Workstream

In this task, you will associate the Contoso App bot with a workstream
in Copilot Service.

1.  Switch back to Copilot Service admin center, go
    to **Workstreams** in **Customer support**.

2.  Select the workstream – **Contoso Chat Workstream** in which you
    want to add the smart assist bot.

    ![](./media/image22.png)

3.  Scroll down and expand **Show** **Advanced settings** and
    select **Add bot** in the **Smart Assist bots** area.

    ![](./media/image23.png)

4.  In the **Add from existing** panel, select a **Contoso App** bot
    user from the list, and then select **Add**.

    ![](./media/image24.png)

    You can add multiple bots to a workstream based on your requirements.

## Exercise 2 - Create and Associate an Agent Script

### Task 1 - Create an Agent Script for Chat Sessions

In this task, you will create a new script to guide agents during chat
sessions.

1.  On the **Copilot Service admin center**,
    select **Productivity** in **Support experience**.

2.  On the **Productivity** page, select **Manage** for **Scripts**.

    ![](./media/image25.png)

3.  On the **Scripts** page, from top bar select + **New**.

    ![](./media/image26.png)

4.  On the **New Script** page, specify the following:

    1.  Name – !!Chat session script!!

    2.  Unique Name – !!Contoso_script!!

    3.  Description - !!This agent script is used for chat sessions.!!

5.  Select **Save**. The **Script steps** appear.

    ![](./media/image27.png)

6.  In the **Script steps** section, select + **New Script step**. 

    ![](./media/image28.png)

7.  Specify the following fields in the **New Script step** form.

    1.  Name - !!Greet the customer!!

    2.  Unique Name - !!Greet_script!!

    3.  **Order** – !!1!!

    4.  **Action type** – Text

    5.  **Text instructions** - !!Greet the customer with the welcome message!!

8.  Select **Save and Close** to add, save, and close the quick-create
    form.

    ![](./media/image29.png)

9.  Select **Save & Close** to save the changes.

    ![](./media/image30.png)

### Task 2 - Associate the Script with a Session Template

In this task, you will link the newly created script with the chat
session template.

1.  Click on the **Workspace** under support experience and then
    select **Manage** for **Session templates**.

    ![](./media/image31.png)

2.  Select the **Chat session** **– default** template.

    ![](./media/image32.png)

3.  Select the **scripts** tab.

4.  In the **scripts** section, select **Add Existing script**.
    The **Lookup Records** pane appears.

    ![](./media/image33.png)

5.  In the **Look for Records** box, select the search icon. Select the
    **Chat session script** from the list, and then select **Add**.

    ![](./media/image34.png)

6.  Select **Save & Close**.

    ![](./media/image35.png)

The agent script is associated with the session template.

## Conclusion

In this lab, you registered and configured an application user,
connected a smart assist bot to a workstream, and created an agent
script to enhance the chat session experience. These configurations
enable automation, productivity, and intelligent guidance within Copilot
Service.
