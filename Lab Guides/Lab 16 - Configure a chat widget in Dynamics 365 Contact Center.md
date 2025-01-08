# Configure a chat widget in Dynamics 365 Contact Center

## Task 1 - Create a website in Power Page trial

1.  Open a tab in the browser. Open a Power Pages trial page.

2.  Select **Try for Free**

![](./media/media16/image1.png)

3.  Enter the Email and check the option agreeing to the terms. Select
    **Start your free Trial**

![](./media/media16/image2.png)

4.  Select the **Region** as **India** and Enter your **Phone number**
    and click on **Submit** for enabling the free trial

![](./media/media16/image3.png)

5.  You will be navigated to Power pages home page.

6.  Select the environment – **Customer Service Trial.** Select **Get
    Started**

![](./media/media16/image4.png)

7.  Select **Start with a template**

![](./media/media16/image5.png)

8.  Select **Dynamics 365** tab and select **Customer Self-Service
    Portal**

![](./media/media16/image6.png)

9.  Select **Choose this template**

![](./media/media16/image7.png)

10. Enter the site name – **Contoso.** Click on **Next**

![](./media/media16/image8.png)

11. Wait until the site is created.

![](./media/media16/image9.png)

12. Refresh the page.

![](./media/media16/image10.png)

The site will be ready in approximately 20-25 minutes. You can proceed
with the next task.

## Task 2 – Exploring on configuring a chat widget

1.  Switch back to Customer Service admin center or Contact Center admin
    center, select **Channels** in **Customer support**.
    The **Channels** page appears.

![A screenshot of a phone Description automatically
generated](./media/media16/image11.png)

2.  Select **Manage** for **Chat**. The **Chat channels** page appears.

![A screenshot of a computer Description automatically
generated](./media/media16/image12.png)

3.  Select **Add chat channel**.

![A screenshot of a chat channel Description automatically
generated](./media/media16/image13.png)

4.  On the **Channel details** page,

    - Name – **Contoso Chat Widget**

    - Language – **English – United States**

    - Select **Next.**

![A screenshot of a computer Description automatically
generated](./media/media16/image14.png)

5.  On the workstream details page.

    - Select **Add to Existing Workstream**

    - Select **Contoso Chat Workstream**

    - Select **Next**

![A screenshot of a chat Description automatically
generated](./media/media16/image15.png)

6.  On the **Chat Widget** page, Leave the details as it is. Enable the
    **Proactive chat** toggle to **Yes.** Select **Next.**

![](./media/media16/image16.png)

1.  On the **Behaviors** page, under **Custom automated messages** –
    Select **Add a message**

![](./media/media16/image17.png)

2.  On **Add automated message** pane, select a trigger – **Agent
    assigned to conversation** from the **Message trigger** dropdown
    list.

3.  In the **Automated message** box, type the message – **Hi, how can I
    help you?** to be displayed.

4.  Select **Confirm**

![A screenshot of a chat Description automatically
generated](./media/media16/image18.png)

![](./media/media16/image19.png)

5.  Enable the **Pre-conversation survey.** Select **Add**

6.  Enter the details

    - **Survey question name:** ContosoConsent

    - **Question text**: We collect demographic data. Please confirm
      whether you agree to provide basic information

    - **Answer type –** User consent

    - **Required -** Yes

    - Select **Confirm**.

![](./media/media16/image20.png)

7.  Select **Add** again

    - **Survey question name:** FirstName

    - **Question text**: FirstName

    - **Answer type –** Single

    - **Required -** Yes

    - Select **Confirm**.

![](./media/media16/image21.png)

8.  Select **Add** again

    - **Survey question name:** LastName

    - **Question text**: LastName

    - **Answer type –** Single

    - **Required -** Yes

    - Select **Confirm**.

![](./media/media16/image22.png)

9.  Select **Add** again

    - **Survey question name:** LastName

    - **Question text**: Enter your Age

    - **Answer type –** Single

    - **Required -** Yes

    - Select **Confirm**.

![](./media/media16/image23.png)

![](./media/media16/image24.png)

10. Post-conversation survey – Enable the toggle for this option.

![A screenshot of a computer Description automatically
generated](./media/media16/image25.png)

**Note - Authentication settings** option is enabled by default. Select
drop-down under **Authentication name** and select **Create
authentication setting.** The steps outlined below can be performed only
upon acquiring a paid license for Power Pages so that the custom
certificates can be uploaded to acquire a public Key URL

A Chat widget is then created. You can click on **Cancel** for this lab
as we have explored how to create a chat widget in Customer Service
Trail.
