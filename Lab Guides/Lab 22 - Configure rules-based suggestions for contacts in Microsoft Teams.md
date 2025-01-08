# Configure rules-based suggestions for contacts in Microsoft Teams

## Exercise 1 - Turn on the suggested contacts for a record type

### Task 1 - To enable collaboration with Microsoft Teams and chat

1.  In the site map of Customer Service admin center or Contact Center
    admin center, in **Agent experience**, select **Collaboration**.

> ![A screenshot of a phone Description automatically
> generated](./media/media22/image1.png)

2.  In **Embedded chat using Teams**, select **Manage**.

![A screenshot of a computer screen Description automatically
generated](./media/media22/image2.png)

3.  On the **Microsoft Teams collaboration and chat** page, set the
    toggle for **Turn on the linking of Dynamics 365 records to
    Microsoft Teams channels** to **Yes**.

![A close-up of a chat Description automatically
generated](./media/media22/image3.png)

4.  To get suggested contacts for any record type, perform the following
    steps:

    1.  In **Connect chat to Dynamics 365 records**, select record type-
        **Case** which we want to enable rules-based suggested contacts.
        The relative settings pane appears on the right.

    2.  In **Suggest contacts**, turn on the toggle for **Rules-based
        suggested contacts**.

    3.  Select **Save**

![](./media/media22/image4.png)

5.  In the **Update rules for suggesting contacts** section, reorder or
    disable the rules for suggesting contacts. Users see the suggestions
    in the order we choose.

    - To reorder the rules, hover over a rule, and then select the up or
      down arrow to move the rules up or down, respectively.

    &nbsp;

    - To disable a rule, hover over a rule, and then
      select ![](./media/media22/image5.png) . When the rule is disabled, a
      check mark is displayed when you hover over the disabled rule.

    &nbsp;

    - To delete a rule, hover over the rule, and then
      select ![](./media/media22/image6.png) . Deleting a rule removes it
      entirely so it won't influence suggested contacts in the future.

![](./media/media22/image7.png)

6.  Select **Save**.

## Exercise 2 - Adding a new rule

1.  On the settings pane, in the **Update rules for suggesting
    contacts** section, Select the 4^(th) rule that says – **Updates a
    timeline activity.** Delete the rule.

> ![A screenshot of a computer Description automatically
> generated](./media/media22/image8.png)

2.  select **+** **Add rule**.

![](./media/media22/image9.png)

3.  The **Add rule** pane is displayed for the record type you selected.

![A screenshot of a computer Description automatically
generated](./media/media22/image10.png)

4.  Enter the information as mentioned below.

    - **Rule name** - Created By

    - **Rule Type** - Relational

    - **Select a user or related record** – Created By

    - Select **Save**

![](./media/media22/image11.png)

5.  A new rule is created. Select **Save** again.

6.  Select **Save** on **Microsoft Teams collaboration and chat**

> ![A screenshot of a computer Description automatically
> generated](./media/media22/image12.png)
