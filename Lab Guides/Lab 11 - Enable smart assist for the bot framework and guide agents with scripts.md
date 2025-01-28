## Lab 11 - Enable smart assist for the bot framework and guide agents with scripts

**Objective** - In this Lab, We create a bot user and add that bot user to the workstream.

## Exercise 1 - Enable smart assist for the bot framework in Omnichannel for Customer Service

### Task 1 – Register an app in Microsoft Entra

1.  Open a new tab and open Microsoft Entra Admin center -
    <https://entra.microsoft.com/>.

2.  Navigate to **Identity \> Applications \> App registration**.

    ![](./media/media11/image1.png)

3.  Select **New Registration**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image2.png)

4.  Enter the name of the app as `Contoso App` and click on
    **Register**.

    ![](./media/media11/image3.png)

5.  You will be navigated to the **Contoso App** page.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image4.png)

### Task 2 - Configure the bot user as an omnichannel agent

The bot user is first created as an application user and then
the **Omnichannel agent** role is assigned to it.

1.  Open a new tab in the browser and launch the PowerPlatform admin
    center - https://admin.powerplatform.com/.

2.  Select **Environments** on the left navigation pane.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image5.png)

3.  Select the **Customer Service Trial** environment
    and then select **Settings**.

    ![](./media/media11/image6.png)

4.  On the **Settings** page, select **Users + permissions**, and then
    select **Application users**.

    ![](./media/media11/image7.png)

5.  On the **Application users** page, select **New app user**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image8.png)

6.  In the **Create a new app user** dialog that opens. Select **Add an
    app**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image9.png)

7.  Select the **Contoso App** and then select **Add**.

    ![](./media/media11/image10.png)

8.  Select your trial environment **Business unit**.

    ![](./media/media11/image11.png)

9.  Select Edit on the **Security roles** field.

    ![](./media/media11/image12.png)

10. On the **Add security roles** page, select **Omnichannel
    agent** from the dropdown list and select **Save** to go back to
    **Create a new app user** dialog.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image13.png)

11. Select **Save**.

    ![A screenshot of a computer screen Description automatically
generated](./media/media11/image14.png)

12. Select **Create**.

    ![](./media/media11/image15.png)

13. The App is successfully added.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image16.png)

14. Switch back to Customer Service Admin center. Select **Settings\ >
    Advanced Settings**

    ![](./media/media11/image17.png)

15. Select **System\ > Security** from the left navigation pane.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image18.png)

16. Select **Manage users in Dynamics 365** from the ribbon.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image19.png)

17. Select the dropdown for **Enabled Users** and select **Application Users**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image20.png)

18. Select **Contoso App**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image21.png)

19. Select the dropdown for **Users** below the app name and then select **Application Users**.

    ![](./media/media11/image22.png)

20. Select **Bot Application user** for **User Type**.

    ![](./media/media11/image23.png)

21. Switch back to the Entra admin center, copy the App ID of the app
    that is created in the previous task.

22. For Bot application ID enter the application ID of the app that
    is created in Entra Admin center.

    ![](./media/media11/image24.png)

23. Select **Save & Close**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image25.png)

### Task 3 - Add a smart assist bot to a workstream

After you create a bot user, you need to add the bot to the workstream
so that agents who use the channel of this workstream can see the
suggestions.

1.  Switch back to Customer Service admin center, go
    to **Workstreams** in **Customer support**.

    ![A screenshot of a phone Description automatically
generated](./media/media11/image26.png)

2.  Select the workstream – **Contoso Chat Workstream** in which you
    want to add the smart assist bot.

    ![](./media/media11/image27.png)

3.  Scroll down and expand **Show** **Advanced settings** and
    select **Add bot** in the **Smart Assist bots** area.

    ![](./media/media11/image28.png)

4.  In the **Add from existing** panel, select a **Contoso App** bot user from the list,
    and then select **Add**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image29.png)

    ![A screenshot of a computer Description automatically
generated](./media/media11/image30.png)

You can add multiple bots to a workstream based on your requirements.

## Exercise 2 - Guide agents with scripts

### Task 1 - Create agent scripts

1.  On the **Customer Service admin center**,
    select **Productivity** in **Agent experience**.

    ![A screenshot of a phone Description automatically
generated](./media/media11/image31.png)

2.  On the **Productivity** page, select **Manage** for **Agent
    scripts**.

    ![A close up of a text Description automatically
generated](./media/media11/image32.png)

3.  On the **Agent scripts** page, select **New**.

4.  On the **New Agent script** page, specify the following:

    1.  Name – `Chat session script`

    2.  Unique Name – `Contoso_script`

    3.  Description - `This agent script is used for chat sessions.`

    ![](./media/media11/image33.png)

5.  Select **Save**. The **Agent script steps** appear.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image34.png)

6.  In the **Agent script steps** section, select **New Agent script
    step**. 

    ![A screenshot of a computer Description automatically
generated](./media/media11/image35.png)

7.  Specify the following fields in the **New Agent script step** form.

    1.  Name - `Greet the customer`

    2.  Unique Name - `Greet_script`

    3.  **Order** – `1`

    4.  **Action type – Text**

    5.  **Text instructions** - `Greet the customer with the welcome message`

8.  Select **Save and Close** to add, save, and close the quick-create
    form.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image36.png)

9.  Select **Save & Close** to save the changes.

### Task 2 - Associate an agent script with a session template

After you configure the agent script and add the field to a form, you
need to associate the agent script with a session template so that the
agent script will load for agents based on the type of session they've
opened.

1.  Select **Manage** for **Session templates** in **Workspaces**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image37.png)

2.  Select the **Chat session** **– default** template.

    ![](./media/media11/image38.png)

3.  Select the **Agent scripts** tab.

    ![A screenshot of a chat session Description automatically
generated](./media/media11/image39.png)

4.  In the **Agent scripts** section, select **Add Existing Agent
    script**. The **Lookup Records** pane appears.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image40.png)

5.  In the **Look for Records** box, select the search icon. Select the
    **Chat session script** from the list, and then select **Add**.

    ![A screenshot of a computer Description automatically
generated](./media/media11/image415.png)

    ![A screenshot of a computer Description automatically
generated](./media/media11/image41.png)

6.  Select **Save & Close**.

The agent script is associated with the session template.


**Summary** - We created a bot user and add that bot user to the workstream
