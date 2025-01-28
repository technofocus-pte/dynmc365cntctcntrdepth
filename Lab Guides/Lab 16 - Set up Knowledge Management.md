# Lab 16 - Set up Knowledge Management

**Objective** - In this Lab, you set up knowledge management. You also create and manage knowledge management.



## Task 1 - Record Types section

1.  Open a new tab in the browser. Sign in to the Power Platform admin
    center - https://admin.powerplatform.microsoft.com/ with the
    credentials provided to execute the lab in the home tab. Select **> Environments>
    CustomerService Trial environment> Environment URL.**

2.  You will be navigated to **Customer Service workspace**. Click on **App selector** to display the list of apps.
   
3.  Select **Customer Service Admin center** from the list of Apps.
4.  In the site map of Customer Service admin center,
    select **Knowledge** in **Agent experience**. The **Knowledge** page
    appears.

    ![A screenshot of a phone Description automatically
generated](./media/media17/image1.png)

5.  In the **Record types** section, select **Manage**.

    ![A screenshot of a computer Description automatically
generated](./media/media17/image2.png)

6.  On the **Record Types** page, we can add and configure the record
    types for which you want to turn on knowledge management.

7.  By default, knowledge management is enabled
    for **Case** and **Conversation** record types.

    ![](./media/media17/image3.png)

8.  On the **Record Types** page, select **Add**.

9.  The **Add record type** dialog appears. On the **Add record
    type** dialog, from the **Select record type** dropdown list, select
    the record type – **Account**.

10.  Set the toggle for **Turn on autometic search**.
11.  Select **Account Name** for **Provide search results using** field.

   ![A screenshot of a computer Description automatically
generated](./media/media17/image4.png)

12.  Select **Save and Close**.

  ![A screenshot of a computer Description automatically
generated](./media/media17/image15.jpg)

  ![A screenshot of a computer Description automatically
generated](./media/media17/image6.png)

## Task 2 - General Settings

1.  Select **Knowledge** again on the left navigation pane.

2.  In the **General Settings** section, select **Manage**.
    The **General Settings** page appears.

3.  In the **Search results display count** section,

    - Select the display count from the dropdown. – 10

    - In the **Feedback** section, set the **Enable feedback** toggle
      to **Yes**.

    ![](./media/media17/image7.png)

4.  In the **Authoring language** section

    - Set the **Enable default authoring language** for your users
      to **Yes**.

    - Select the **Organization's UI language** option.

    - Set the **Allow users to set default knowledge authoring
      language** toggle to **Yes**.

    ![](./media/media17/image8.png)

1.  In the **Knowledge search experience** section, enable the following
    as required

    - **Enable suggest-as-you-type**

    - **Set search mode as all**

    - **Show recently accessed knowledge articles for cases**

    ![](./media/media17/image9.png)

7.  In the **Global search knowledge configuration** section, switch
    the **Enable Kb preview mode from global search option** toggle
    to **Yes**.

    ![](./media/media17/image10.png)

8.  Scroll up towards the top of the page and select **Save**.

## Task 3 - Creating Categories 

1. Go back and select K**nowledge**. In the **Categories** section,
select **Manage**. The **Categories System Views** page appears. You can
create and manage a logical structure of categories for your records.

2.  On the command bar, select **New** to create a new category record.

3.  Enter the required information in the **General** section:

    - **Title**: Contoso Demo Category

    - **Description**: Contoso Demo Category

    - **Display Order**: 1

    - Select **Save & Close**

    ![A screenshot of a computer Description automatically
generated](./media/media17/image11.png)

    ![A screenshot of a computer Description automatically
generated](./media/media17/image12.png)

## Task 4 - Filters Section

1.  Go back and select **Knowledge**. In the **Filters** section,
select **Manage**.

2.  Set the **Enable search filters** toggle to **Yes**.

3.  Set the **Allow agent to personalize** toggle to **Yes**. This
    allows the service representatives to save the search filters
    relevant to their areas.

4.  Select **Save**.

    ![A close-up of a text Description automatically
generated](./media/media17/image13.png)

## Task 5 - Portal Section

1.  Go back and select **Knowledge**. In the **Portal** section,
select **Manage**. The **Portals** page appears.

2.  In the **Support portal connection** section, Let us understand the
    options available.

    - Set the **Use an external portal** toggle to **Yes** to integrate
      an external portal to publish knowledge articles. For this lab,
      toggle to **No**.

    - **URL Format**: Type the portal URL to use to create external
      (public-facing) portal links for knowledge articles, which the
      service representatives can share with the customers. The external
      URL is created in the following format: https://support portal
      URL/kb/{kbnum}. The placeholder, "{kbnum}", is replaced by an
      actual knowledge article number.

    - In the **Sync knowledge article attachments to portal** section,
      set the **Sync attachments to the portal** toggle to **Yes**.

    - Select **Save**.

    ![A screenshot of a computer Description automatically
generated](./media/media17/image14.png)


**Summary** - You have successfully set up knowledge management. You also created and manage knowledge management.
