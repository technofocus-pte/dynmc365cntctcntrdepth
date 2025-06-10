# Lab 24 – Create a Case and view AI-suggested similar cases and knowledge articles

**Objective** - In this lab, you will create Cases, associate cases as parent and child, convert a case to a Knowledge article and view AI-suggested similar cases and knowledge articles.

## Task 1: Enable enhanced case forms for multisession apps

1.  Select the **App selector** from the top ribbon.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image1.png)

2.  Select **Copilot Service admin center** from the **Apps** page.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image2.png)

3.  On the left navigation in Copilot Service admin center,
    select **Case Settings**.

4.  Select **Manage** for **Enhanced case experience**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image3.png)

5.  Switch the **Enhanced case experience** toggle to **Yes**.

    - To enable the enhanced full case form:

      1.  Set the **Full case form** toggle to **Yes**, for your agents
          to see the enhanced full case form when they create a new
          case.

      1.  Select **Configure** to customize the form in Power Apps. The
          Power Apps form page opens on a new tab.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image4.png)

6.  The Enhanced full case form will be opened in the Power Apps tab.
    You can edit the form as per your requirements.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image5.png)

7.  Switch back to the **Copilot Service admin center** tab. To enable
  the enhanced quick case form:

8.  Switch the **Quick case form** toggle to **Yes**.

9.  Select the option in the **Choose Form** dropdown. The selected
      main form appears as the side pane when the agent creates a new
      case. By default, this is set to **Enhanced quick case form**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image6.png)

10.  Select **Configure** to customize the form in Power Apps. The Power
    Apps form page opens on a new tab.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image7.png)

## Task 2: Create a case

1.  Select the **App selector** from the top ribbon.

2.  Select **Copilot Service workspace** from the **Apps** page.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image8.png)

3.  In the Copilot Service workspace, select the **Site Map** and then
    select **Cases**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image9.png)

4.  The **My Active Cases** view is displayed. You can switch between
    the different case views by selecting the current view.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image10.png)

5.  Select **Show Chart** on the command bar to see the chart view.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image11.png)

6.  Select the three dots on the command bar and then select **Open
    Dashboards**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image12.png)

7.  To switch back to views, select **Open Views**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image13.png)

8.  If you select a case record from the case view, you see these
    additional options on the command bar:

    - **Save & Route**

    - **Resolve Case**

    - **Cancel Case**

    - **Assign** 

    - **Add to Queue** 

    - **Queue Item Details**

![A screenshot of a computer Description automatically
generated](./media/media24-new/image14.png)

9.  Switch back to the **My Active Cases** tab and select **New Case**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image15.png)

10. Enter the following information on the **New Case** page and then
    select **Save**.

    - **Type** – Problem

    - **Customer** – Trey Research

    - **Title** – Minerals level is not maintained

    - **Product** – Water Filtration System

    - **Subject** – Water supply

    - **Origin** – Email

    - **Priority** – Normal

![A screenshot of a computer Description automatically
generated](./media/media24-new/image16.png)

## Task 3: Create a child case

1.  On the command bar, select the three dots and then select **Create
    Child Case**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image17.png)

2.  On the **New Case** pane that appears on the right side, enter the
    following information and then select **Save**.

    - **Type** – !!Request!!

    - **Customer** – !!Trey Research!!

    - **Title** – !!Share a quotation for replacement!!

![A screenshot of a computer Description automatically
generated](./media/media24-new/image18.png)

3.  Select **Save & Close**.

4.  Select **Details** tab from the command bar and then scroll down.

5.  You will the Child case on the **Child Cases** tile.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image19.png)

6.  Select **Save & Close**.

## Task 4: Associate cases as parent and child

You can set a parent-child relationship between cases where you can set
one case as parent and set other cases as its child cases.

1.  Switch back to **My Active Cases** tab, select two or more cases
    that you want to associate as parent and child cases.

2.  On the command bar, select **Associate Child Cases**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image20.png)

3.  The **Set Parent Child Relationship** dialog appears.

4.  In the list, select the case that you want to set as parent, and
    then select **Set**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image21.png)

5.  Select **OK**.

![A white background with black text Description automatically
generated](./media/media24-new/image22.png)

6.  Select the case that was selected as a Parent case by you.

7.  Select **Details** tab from the command bar and then scroll down.

8.  You will the Child case on the **Child Cases** tile.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image23.png)

## Task 5: Convert a case to a Knowledge article

1.  Switch back to **My Active Cases** tab and open a case that has the
    information that you want to convert to a knowledge article.

2.  On the command bar, select the ellipsis **(...)** and go
    to **Convert To** \> **To Knowledge Article**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image24.png)

![A screenshot of a computer Description automatically
generated](./media/media24-new/image25.png)

3.  On **Convert to knowledge article** page, keep the default values
    and then select **Convert**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image26.png)

4.  The knowledge article is created.

## Task 6: View AI-suggested similar cases and knowledge articles

1.  On Copilot Service Workspace, select the **Home** tab and then
    select **Customer Service Agent Dashboard**.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image27.png)

2.  In the **My Active Cases** list, select the **Fluctuations in
    electric supply** case that you have created. The case opens in a
    session tab, and the **Smart assist** pane appears on the right.

3.  The **Smart assist** pane lists the knowledge articles and similar cases suggested by AI based on the case context.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image28.png)

4.  In the **Knowledge article suggestion** area, do any of the
    following:

    - Select an article title to go through and get relevant
      information. The selected knowledge article opens in a new
      application tab.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image29.png)

5.  Select more commands to do the following:

    - **Email Content:** Select to open the email compose form with the
    contents of the knowledge article pasted in the mail body.

![A screenshot of a computer screen Description automatically
generated](./media/media24-new/image30.png)

6. Select the link icon to associate the article with the case as a
  related article.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image31.png)

7.  In the **Similar case suggestions** area, do any of the following:

    - Select a case title to drill through the details of the resolved
      case.

    - Select more commands to do the following:

      - **Copy resolution:** Select to copy the resolution notes
        information from the resolved case to the clipboard.

      - **Email agent:** Select to open the email compose form to send
        your questions to the agent who handled the similar case. The
        mail form opens on a new tab with the pertinent information and
        link to the resolved case filled in.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image32.png)

8. Select the link icon to link or clear the link with the similar case.

![A screenshot of a computer Description automatically
generated](./media/media24-new/image33.png)

**Summary** - You have created Cases, associated cases as parent and child, converted a case to a Knowledge article and viewed AI-suggested similar cases and knowledge articles.
