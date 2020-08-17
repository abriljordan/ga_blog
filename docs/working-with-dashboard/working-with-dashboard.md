---
layout: default
title: Create, edit and delete
parent: Working with Dashboard
#has_children: true
has_toc: true
nav_order: 2
---

# Working with Dashboard
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

The Data+Design web application allows you to create, edit and delete dashboard, sections and indicators. To do so, you must be signed in with an administrator account.

## Dashboard
<details markdown="block">
  <summary>
  Create a dashboard
  </summary>
  1. To create a new empty dashboard from scratch, click the Gear button on the main page, then choose Create Dashboard.
        -![Dashboard Interface]({{site.baseurl}}/assets/images/create-dash.png )
  2. Enter the new dashboard name. You can make it into a default dashboard by clicking the Default toggle switch.
  3. Once you’re done, click the Create button.
</details>

<details markdown="block">
  <summary>
  Edit a dashboard
  </summary>
  1.	To make changes on a dashboard, open the dashboard first using Dashboard Selector located in the main page.
  2.	Click the Gear from the dashboard, then choose Edit Dashboard.
    -![Dashboard Interface]({{site.baseurl}}/assets/images/edit-dash.png )
  3.	Change the name of the dashboard in the name field and then click Create.
</details>

<details markdown="block">
  <summary>
  Delete a dashboard
  </summary>
  Warning

  Deleting a dashboard will also remove any sections, indicators and alerts you have configured on that dashboard.
  To delete a dashboard you are currently viewing, follow these steps:
    * Click the Gear from the dashboard, then click Delete Dashboard, and then click Confirm to proceed.

-![Dashboard Interface]({{site.baseurl}}/assets/images/delete-dash.png )
</details>

## Indicator
<details markdown="block">
  <summary>
  Add existing indicator
  </summary>
  Add existing indicator to a section.

  -![Dashboard Interface]({{site.baseurl}}/assets/images/add-indicator.png )

  1.	Navigate the dashboard, then click the  plus (+) of the section, choose Existing.
  2.	Click the Disclosure button, then choose the indicator.
  3.	Once you’re done, click Create.

  -![Dashboard Interface]({{site.baseurl}}/assets/images/add-existing-indicator.png )

</details>

<details markdown="block">
  <summary>
  Add a dataset (indicator) to a dashboard
  </summary>
  You can upload external data in a .csv or excel format through the user interface.

  1.	Navigate the section where you want to upload the indicator and click plus (+).
  -![Dashboard Interface]({{site.baseurl}}/assets/images/upload-indicator.png )
  2.	Click Upload, a user interface will appear to help you upload the dataset.
  -![Dashboard Interface]({{site.baseurl}}/assets/images/section-upload-indicator.png )
  3.	Under Details section, import the .csv or excel, then click Next.
  4.	Under Select Columns section, select the columns that you want to be included in the indicator, then click Next.
  5.	Preview the dataset under Preview section, then click Next.
  6.	Select the update mode under Update Mode section, then click Next.
  7.	Under Name and Describe Your Dataset section, give the indicator a name and choose the appropriate chart.
  8.	Once you’re done, click the Update.
</details>

<details markdown="block">
  <summary>
  Rename indicator
  </summary>
  1.	Navigate the dashboard and click the Gear of the indicator, choose Rename.
  -![Dashboard Interface]({{site.baseurl}}/assets/images/rename-indicator.png )
  2.	In the Caption field, type the new name for the indicator. You may also want to put some information in the Info text field.
  3.	Click Update to apply changes.
</details>

<details markdown="block">
  <summary>
  Upload Cohort
  </summary>
  1.	Create cohort file for uploading (csv or excel).
  2.	Navigate to the dashboard and click Upload Cohort located just above the sections. A new user interface will appear to help you upload cohort.

  -![Dashboard Interface]({{site.baseurl}}/assets/images/upload-cohort.png )

  3.	Under Details section, upload the .csv or excel file.

  -![Dashboard Interface]({{site.baseurl}}/assets/images/upload-cohort-section.png )

  4.	Once you’re done, click Next.
  5.	Under Student Details and Dataset section, fill in the required fields.
  6.	Once you’re done, click Submit.

  If it was successful, a message should display informing the file was uploaded.
</details>

## Chart

<details markdown="block">
  <summary>
  Change chart color
  </summary>
  Maybe your indicator needs a little something else to make it more impactful. You can change the color of your chart.
  1. Choose the chart that you want to change. Click the Gear button, then choose Change Color.
  -![Dashboard Interface]({{site.baseurl}}/assets/images/change-chart-color.png )
  2. Click on the color that you want to change and pick the color scheme you want.
  3. Once you’re done, click the Update button.
</details>

<details markdown="block">
  <summary>
  Resize all charts
  </summary>
  You can resize charts in a dashboard all at once in just one click.
  * Navigate the dashboard and click the Gear button located just above the sections, then choose the squares to resize the charts in the dashboard.

  -![Dashboard Interface]({{site.baseurl}}/assets/images/resize-all-chart.png )
</details>

<details markdown="block">
  <summary>
  Resize a single chart
  </summary>
  * Navigate the Card and click the Gear button, then choose the square to resize the chart.
  -![Dashboard Interface]({{site.baseurl}}/assets/images/resize-chart.png )
</details>

## Card
<details markdown="block">
  <summary>
  Delete Card
  </summary>
  * Navigate the Card and click the Gear button, then click Delete Dashboard.
</details>

<details markdown="block">
  <summary>
  Remove Card
  </summary>
  * Click on the indicator's Gear button and choose Remove, then click Confirm to remove card from the section.
</details>

## Section
<details markdown="block">
  <summary>
  Create a section
  </summary>
  1. Navigate the dashboard and click the Gear button located just above the sections.
  -![Dashboard Interface]({{site.baseurl}}/assets/images/add-section.png )
  2. Click Manage Sections, then choose Add.
  4. Enter the new section name.
  5. Once you’re done, click Create.
</details>

<details markdown="block">
  <summary>
  Edit section name
  </summary>
  1. Navigate the section and click the Pencil button.

  -![Dashboard Interface]({{site.baseurl}}/assets/images/rename-section.png )

  2. Give the section a new name.
  3. Once you’re done, click Update.
</details>

<details markdown="block">
  <summary>
  Delete a section
  </summary>
  * Navigate the section and click the Trash bin button, then click Confirm to delete section.

  -![Dashboard Interface]({{site.baseurl}}/assets/images/delete-section.png )

</details>
