# Lab 17 - Integrate Knowledge management in Dynamics 365 with Copilot Studio Agents

**Objective** - In this lab, you will create a Copilot bot, add Topics to it and add the action to the Copilot Studio topic.

### Task 1 - Set connection references

To set connection references:

1.  Open a new tab and navigate
    to [make.powerapps.com](https://make.powerapps.com/).

2.  Select **Customer Service Trial** environment on the top right corner of
    the home page.

3.  Select **More** from the left navigation and then select **Connections**.

    ![A screenshot of a computer Description automatically
generated](./media/media18/image27.jpg)
  
4.  Select **New connection**.

   ![A screenshot of a computer Description automatically
generated](./media/media18/image28.jpg)

5.  Search for **Dataverse** and then select **Microsoft Dataverse**.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image29.jpg)

6.  Sign in and then select **Create**. Sign in with your credentials if prompted.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image30.jpg)

7.  Select **New connection**.

   ![A screenshot of a computer Description automatically
generated](./media/media18/image35.jpg)

8.  Search for and select **Content Conversion**.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image36.jpg)

9.  Sign in and then select **Create**. Sign in with your credentials if prompted.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image37.jpg)

     ![A screenshot of a computer Description automatically
generated](./media/media18/image38.jpg)

10.  From the left navigation of the Power Apps portal, select **Solutions** and then select **Default Solution**.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image18.png)

11.  From the left navigation, select **Connection references** and then select **Microsoft Dataverse CDS Connection**.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image31.jpg)

12. In the edit box that opens, select the connection that you created from the **Connection** dropdown menu.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image32.jpg)
   
13.  Select **Save changes**.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image33.jpg)

14.  Similarly select **Content Conversion**.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image39.jpg)

15.  In the edit box that opens, select the connection that you created from the **Connection** dropdown menu.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image40.jpg)

16.  Select **Save changes**.

   ![A screenshot of a computer Description automatically
generated](./media/media18/image41.jpg)

17.  Go back to **Default Solution** \> **Cloud flows** and turn
    on **Search Dynamics 365 knowledge article flow** flow.

     ![A screenshot of a computer Description automatically
generated](./media/media18/image34.jpg)

## Task 2 – Create a Copilot Bot

1.  Open a tab in the browser and go to the Copilot Studio home page -
    <https://copilotstudio.microsoft.com/> . Login with the credentials
    provided to execute the lab.

2.  Select the Environment as **Customer Service Trial** on top right
    corner of the homepage

![A screenshot of a computer Description automatically
generated](./media/media18/image1.png)

3.  Select **Agents** in the left navigation.

> ![A screenshot of a phone Description automatically
> generated](./media/media18/image2.png)

4.  Select **+ New agent**.

![A screenshot of a computer Description automatically
generated](./media/media18/image3.png)

5.  Select **Skip to configure**

![](./media/media18/image4.png)

6.  Select **Create**.

![](./media/media18/image5.png)

![](./media/media18/image6.png)

7.  Your Agent is created.

![A screenshot of a computer Description automatically
generated](./media/media18/image7.png)

## Task 3 - Create a Topic in Copilot Studio Bot

1.  For better visibility, close the **Test your agent** panel for now.

![A screenshot of a computer Description automatically
generated](./media/media18/image8.png)

2.  On the top menu bar, select **Topics**.

![A screenshot of a computer Description automatically
generated](./media/media18/image9.png)

3.  Select **Add a topic** and select **From blank**.

![A screenshot of a computer Description automatically
generated](./media/media18/image10.png)

4.  Click on **Allow** if you are asked that copilot wants to access
    images and text.

![A screenshot of a computer Description automatically
generated](./media/media18/image11.png)

A **Trigger** node appears on an otherwise blank topic authoring canvas.

5.  Select the **More** icon (**…**) of the **Trigger** node, and then
    select **Properties**.

![](./media/media18/image12.png)

6.  The **On Recognized Intent properties** panel appears. In this
    panel, select the **Phrases** box.

![A screenshot of a phone Description automatically
generated](./media/media18/image13.png)

7.  The **Phrases** secondary panel appears. Under **Add phrases**, Add
    the trigger phrase and click on plus icon. Enter the below phrases.

    - Store hours

    - What time do you open

    - Is the store open today

    - Are you open on Sunday

    - Hours of operation

8.  Your agent needs 5 to 10 trigger phrases to train the AI model to
    understand your customers' responses. To add more trigger phrases,
    you can either:

    - Select the **Add** icon ![](./media/media18/image14.png) next to the text
      field and enter the desired phrase.

    &nbsp;

    - Enter a phrase and select **Enter**.

Note - You can include punctuation in a trigger phrase, but it's best to
use short phrases rather than long sentences.

![A screenshot of a computer Description automatically
generated](./media/media18/image15.png)

![A screenshot of a computer Description automatically
generated](./media/media18/image16.png)

9.  Select **Details** on the toolbar to open the **Topic
    details** panel. Enter the name of the Topic as **Store hours**.

10.  Select **Save**.

![](./media/media18/image17.png)

### Task 4 - Add the action to the Copilot Studio topic

Perform the following steps to ensure that flow is properly configured
and can now be replaced with **Search Dynamics 365 knowledge
articles** action.

1.  In the **Store hours** topic, create a question node to ask the user to search
    for the input text.

    ![A screenshot of a computer Description automatically
generated](./media/media18/image42.jpg)

2.  Provide the sample filter value after you trigger the topic.

3.  Select **Add node** (**+**) and select **Call an action**.

4.  Select **Search Dynamics 365 knowledge article flow** action.

5.  Provide the input to the flow. An error might appear if the filter
    isn't provided to the flow.

    ![A screenshot of a computer Description automatically
generated](./media/media18/image43.jpg)

    ![A screenshot of a computer Description automatically
generated](./media/media18/image44.jpg)

6.  Add a message node to show the results returned by the flow. 

![A screenshot of a computer Description automatically
generated](./media/media18/image45.jpg)

7.  Select **Save**.

10. Use the trigger phase and run the topic to verify the flow.

**Tip**

If your search doesn’t return any results, modify the search terms or
filter conditions. You can also add a filter condition if required.

**Summary** - You have created a Copilot bot, added Topics to it and then added the action to the Copilot Studio topic.
