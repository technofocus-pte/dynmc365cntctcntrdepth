# Lab 10 - Work with Session Templates and associate templates with workstreams

**Objective** - In this Lab, you will create session templates and associate scripts to this session templates

## Task 1 - Create a session template

1.  In the site map of Customer Service admin center,
    select **Workspaces** in **Agent experience** group.

2.  On the **Workspaces** page, select **Manage** for **Session
    templates**.

    ![](./media/media10/image0.png)

3.  Select **New** on the **Active Session Templates** page.

4.  Specify the following on the **New Session Templates** page on the
    **General** Tab

    1.  **Name** – `Contoso Session`

    2.  **Unique Name** - `msdyn_chat_custom`

    3.  **Type** - Entity

    4.  **Entity** – Case

    5.  **Title** – Enter `{CustomerName}`

    6.  **Communication panel mode** – Hidden

    7.  **Apply session title to anchor tab** – Yes

    8.  Select **Save**

    ![](./media/media10/image1.png)

## Task 2 - Associate application tabs, agents scripts with session templates

We will associate application tabs that need to open when a session is
started. Agents can't close these application tabs.

1.  On the session template page.

2.  In the **Additional Tab** section, Select **Add Existing Application
    Tab Template**.

    ![](./media/media10/image2.png)

3.  The **Lookup Records** pane appears. Search for and select **Customer
    Summary**. Select **Add**. The application tabs are added to
    the session template.

    ![A screenshot of a computer Description automatically
generated](./media/media10/image3.png)

    ![A screenshot of a computer Description automatically
generated](./media/media10/image4.png)

4.  Select the **Agent scripts** tab and set the **Enable build
    expression** toggle to **Yes** to define the expression to set an
    agent script as default for a particular session template.

    ![](./media/media10/image5.png)

5.  Select **Save and close**.

    ![A screenshot of a computer Description automatically
generated](./media/media10/image6.png)

## Task 3 - Associate or modify templates with workstreams

1.  In the Customer Service Admin Center site map,
    select **Workstreams**.

    ![A screenshot of a computer Description automatically
generated](./media/media10/image7.png)

2.  Select the **Contoso Chat workstream**

    ![](./media/media10/image8.png)

3.  Scroll down and expand the **Show advanced settings** section.

4.  Select **Edit** beside **Sessions**

    ![A screenshot of a computer Description automatically
generated](./media/media10/image9.png)

5.  On the **Sessions** panel that appears, select **Chat session - default** in
    the **Default template** field.

    ![A screenshot of a chat session Description automatically
generated](./media/media10/image10.png)

6.  Select **Save and close**.

7.  Select **Edit** beside **Agent notifications**

    ![A screenshot of a computer Description automatically generated](./media/media10/image11.png)

8.  On the **Agent notifications** panel that appears, select a template
    for each of the following types of notifications:

    - Incoming unauthenticated

    - Incoming authenticated

    - Consult

    - Transfer

    - Supervisor assign

9.  Select **Save and close**.

    ![A screenshot of a chat Description automatically
generated](./media/media10/image12.png)

**Summary** - You created session templates and associate scripts to this session templates
