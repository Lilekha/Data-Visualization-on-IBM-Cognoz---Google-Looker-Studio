# Data Visualization on IBM Cognoz Analytics & Google Looker Studio
 Visualizing Sales and Service Data of a Car Dealer


<h2><span class="header-link octicon octicon-link"></span>1. Creating Visualizations Using IBM Cognoz Analytics</h2><p><strong>Estimated time needed:</strong> 1hr 15 mins</p>
<p>In this lab, you will create some visualizations and add them to a dashboard using Cognos Analytics.</p>
<h2><span class="header-link octicon octicon-link"></span>Software Used</h2><p>The hands-on lab will use the trial version of Cognos Analytics from IBM.</p>
<h2><span class="header-link octicon octicon-link"></span>Dataset Used</h2><p>The dataset used in this lab comes from <a href="https://accelerator.ca.analytics.ibm.com/bi/?utm_source=skills_network&amp;utm_content=in_lab_content_link&amp;utm_id=Lab-IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork&amp;perspective=authoring&amp;pathRef=.public_folders%2FIBM%2BAccelerator%2BCatalog%2FContent%2FDAT00142&amp;id=i22898C2A4DD748F79E0FC2BD017F4FE8&amp;objRef=i22898C2A4DD748F79E0FC2BD017F4FE8&amp;action=run&amp;format=HTML&amp;cmPropStr=%7B%22id%22%3A%22i22898C2A4DD748F79E0FC2BD017F4FE8%22%2C%22type%22%3A%22reportView%22%2C%22defaultName%22%3A%22DAT00142%22%2C%22permissions%22%3A%5B%22execute%22%2C%22read%22%2C%22traverse%22%5D%7D" target="_blank" rel="noopener noreferrer" title="here">here </a> in the <strong>IBM Accelerator Catalog</strong>. The Terms of use for such are located at <a href="https://developer.ibm.com/terms/ibm-developer-terms-of-use/" target="_blank" rel="noopener noreferrer">https://developer.ibm.com/terms/ibm-developer-terms-of-use/</a>.</p>
<p>We are using a modified subset of that dataset for the lab, so to follow the lab instructions successfully, please use the dataset provided with the lab, rather than the dataset from the original source.</p>
<h2><span class="header-link octicon octicon-link"></span>Assignment Scenario</h2><p>As a regional manager for a chain of car dealerships you need to build out a dashboard to allow you to understand your sales and service departments.</p>
<h2><span class="header-link octicon octicon-link"></span>Accessing the Dataset for this Final Assignment</h2><p>The dataset used in this final assignment is provided as sample data within your Cognos environment, in a data module called <strong>Auto group data module</strong>.</p>
<p><ins>To load and open the data module:</ins></p>
<ol>
<li><p>On the <strong>navigation panel</strong> of Cognos Analytics, select <strong>Team content</strong>. </p>
 <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork/Hands-on%20Labs/Peer%20Graded%20Assignment%20-%20Part%202/images/AccessingSampleData.1.png" width="558"></li></ol>
<br>

<p>Then select <strong>Samples</strong>.</p>
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork/Hands-on%20Labs/Peer%20Graded%20Assignment%20-%20Part%202/images/samples.png" width="558">
    
<br>

<ol start="2">
<li><p>Now go to <strong>By industry</strong> &gt; <strong>Automotive</strong> &gt; <strong>Data</strong>.</p>
</li><li><p>Here the sample data used in this final assignment can be found, in a data module called <strong>Auto group data module</strong>. Right-click on <strong>Auto group data module</strong> and select <strong>Create Dashboard</strong>.</p>
 <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork/Hands-on%20Labs/Peer%20Graded%20Assignment%20-%20Part%202/images/AccessingSampleData.3.png" width="484"></li></ol>
<br>

<h2><span class="header-link octicon octicon-link"></span>Guidelines for the Submission</h2><p>Use the IBM Cognos Analytics-related course videos and hands-on lab <em>Creating Dashboards Using IBM Cognos Analytics</em> to help you complete the following tasks:</p>
<p><ins>Create two dashboards as follows:</ins></p>
<ul>
<li><p>One dashboard using the tabbed template that has 4 small rectangles at the top and a large rectangle below - rename this dashboard tab to <strong>Sales</strong>.</p>
  <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork/Hands-on%20Labs/Peer%20Graded%20Assignment%20-%20Part%202/images/GuidelinesForSubmission.1.png" width="533" height="300"></li></ul>
<br>

<ul>
<li><p>One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to <strong>Service</strong>.</p>
  <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork/Hands-on%20Labs/Peer%20Graded%20Assignment%20-%20Part%202/images/GuidelinesForSubmission.2.png" width="533" height="300"></li></ul>
<br>

<p><ins>Capture the following KPI metrics as visualizations:</ins></p>
<ol>
<li><p>On the <strong>Sales</strong> dashboard, capture the following KPI metrics: </p>
<ul>
<li>In the first small rectangle <strong>(Panel 1)</strong>, capture <strong>Profit</strong> (formatted to 1 decimal place in millions of US dollars)</li><li>In the second small rectangle <strong>(Panel 2)</strong>, capture <strong>Quantity sold</strong></li><li>In the third small rectangle <strong>(Panel 3)</strong>, capture <strong>Quantity sold by model</strong> (as a bar chart)</li><li>In the fourth small rectangle <strong>(Panel 4)</strong>, capture <strong>Average quantity sold</strong></li></ul>
</li></ol>
<br>

<ol start="2">
<li>On the <strong>Sales</strong> dashboard in the large rectangle <strong>(Panel 5)</strong>, display <em>Profit</em> by <em>Dealer ID</em> as a column chart, sorted in ascending order.</li></ol>
<br>

<ol start="3">
<li>On the <strong>Service</strong> dashboard, capture the following KPI metrics as visualizations:<ul>
<li>In the top left area <strong>(Panel 1)</strong>, capture the number of recalls per model of car (as a column chart)</li><li>In the top right area <strong>(Panel 2)</strong>, capture the customer sentiment by comparing positive, neutral, and negative reviews (as a treemap)</li><li>In the bottom left area <strong>(Panel 3)</strong>, capture the quantity of cars sold per month compared to the profit (as a line and column chart).</li><li>In the bottom right area <strong>(Panel 4)</strong>, capture the number of recalls by model and affected system (as a heat map). This will help us understand if there are any outliers for a given model or a specific system.</li></ul>
</li></ol>
<br>

<ol start="4">
<li>To export your dashboard as a PDF, follow instructions below:<ul>
<li><p>On the application toolbar of your <strong>dashboard page</strong>, click <strong>Share</strong> icon.</p>
  <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork/Hands-on%20Labs/Peer%20Graded%20Assignment%20-%20Part%202/images/4.1.png" width="368" height="100">
  <br>
</li><li><p>On the <strong>Export</strong> tab, check <strong>Include filters</strong> and click <strong>Export</strong>.</p>
  <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork/Hands-on%20Labs/Peer%20Graded%20Assignment%20-%20Part%202/images/4.2.png" width="300" height="375">
  <br>
</li><li><p>On the <strong>Print</strong> pop-up page, in the <strong>Destination</strong> drop-down list, select <strong>Save as PDF</strong>.</p>
  <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0130EN-SkillsNetwork/Hands-on%20Labs/Peer%20Graded%20Assignment%20-%20Part%202/images/4.3.png" width="300" height="600">
  <br>
</li><li><p>Save the PDF file on your local machine to any location you like (preferably your <strong>Downloads</strong> folder) for later upload and submission to the coursera platform.</p>
</li></ul>
</li></ol>





<h2><span class="header-link octicon octicon-link"></span>2. Creating Visualizations Using Google Looker Studio</h2><p><strong>Estimated time needed:</strong> 1hr 15 mins</p>
<p>In this lab, you will create some visualizations and add them to a dashboard using Google Looker Studio.</p>
<h2><span class="header-link octicon octicon-link"></span>Software Used in this Lab</h2><p>The hands-on lab will use the free version of Google's Looker Studio</p>
<h2><span class="header-link octicon octicon-link"></span>Dataset Used</h2><p>The dataset used in this lab comes from the <strong>IBM Accelerator Catalog</strong> and can be downloaded from <a href="https://accelerator.ca.analytics.ibm.com/bi/?utm_source=skills_network&amp;utm_content=in_lab_content_link&amp;utm_id=Lab-IBMSkillsNetwork-DV0130EN-Coursera&amp;perspective=authoring&amp;pathRef=.public_folders%2FIBM%2BAccelerator%2BCatalog%2FContent%2FDAT00142&amp;id=i22898C2A4DD748F79E0FC2BD017F4FE8&amp;objRef=i22898C2A4DD748F79E0FC2BD017F4FE8&amp;action=run&amp;format=HTML&amp;cmPropStr=%7B%22id%22%3A%22i22898C2A4DD748F79E0FC2BD017F4FE8%22%2C%22type%22%3A%22reportView%22%2C%22defaultName%22%3A%22DAT00142%22%2C%22permissions%22%3A%5B%22execute%22%2C%22read%22%2C%22traverse%22%5D%7D" target="_blank" rel="noopener noreferrer" title="here">here </a>.</p>
<p>The Terms of use for such are located at <a href="https://developer.ibm.com/terms/ibm-developer-terms-of-use/" target="_blank" rel="noopener noreferrer">https://developer.ibm.com/terms/ibm-developer-terms-of-use/</a>.</p>
<p>We are using a modified subset of that dataset for the lab, so to follow the lab instructions successfully, please use the dataset provided with the lab, rather than the dataset from the original source.</p>
<h2><span class="header-link octicon octicon-link"></span>Assignment Scenario</h2><p>As a regional manager for a chain of car dealerships you need to build out a dashboard to allow you to understand your sales and service departments.</p>
<h2><span class="header-link octicon octicon-link"></span>Accessing the Dataset for the Google Looker Lab of the Final Assignment</h2><hr>

<p>You need to download this dataset (all files) and <strong>import</strong> them into your Google Drive.</p>
<ul>
<li><p>Upload all these files in your drive. Use the <em>Google Sheets</em> connector in Looker Studio to connect with these Excel worksheets to add data into your report</p>
</li><li><p>In case it doesn't show the files while adding, then, open a blank Google Sheet in your drive.</p>
</li><li><p>Click on <strong>Import</strong> from the <strong>File</strong> menu, and then select the relevant file from your drive.</p>
</li></ul>
<p><img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/images/fa_1.png" alt=""></p>
<ul>
<li>Then you can use the <em>Google Sheets</em> connector in Looker Studio to connect with these Excel worksheets to add data into your report. Select the data sheets one by one and add them to your report or create a data source.</li></ul>
<p><img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/images/fa_4.png" alt=""></p>
<hr>

<p>Alternatively you can use the <strong>CSV</strong> versions of these files, which can be downloaded from <a href="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/labs/v2/Looker_Dataset.zip" target="_blank" rel="noopener noreferrer" title="here">here</a>.</p>
<h2><span class="header-link octicon octicon-link"></span>Guidelines for the Submission</h2><p>Use the course videos and hands-on lab on <em>Creating Visualizations and Dashboards with Google Looker Studio</em> to help you complete the following tasks:</p>
<p><ins>Create report with two pages as follows:</ins></p>
<ul>
<li>One page with 5 different visuals to develop a <strong>Sales</strong> Dashboard. Rename page one as <strong>Sales</strong>. You may display the charts on this page as below:</li></ul>
<p> <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/images/fa_7.png" alt=""></p>
<br>

<ul>
<li>One page with 4 different charts to represent a <strong>Service</strong>  dashboard- rename this page to <strong>Service</strong>. You may display the charts on this page as below:</li></ul>
<p> <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/images/fa_8.png" alt=""></p>
<br>

<p><ins>Capture the following KPI metrics as visualizations:</ins></p>
<p>TASK 1: On the <strong>Sales</strong> dashboard, capture the following KPI metrics: </p>
<ul>
<li>In the first small rectangle <strong>(Panel 1)</strong>, capture <strong>Profit</strong> (formatted to 1 decimal place in millions of US dollars)</li><li>In the second small rectangle <strong>(Panel 2)</strong>, capture <strong>Quantity sold</strong></li><li>In the third small rectangle <strong>(Panel 3)</strong>, capture <strong>Quantity sold by model</strong> (as a <strong>bar chart</strong>)</li><li>In the fourth small rectangle <strong>(Panel 4)</strong>, capture <strong>Average quantity sold</strong></li></ul>
<br>

<p>TASK 2: On the <strong>Sales</strong> dashboard in the large rectangle <strong>(Panel 5)</strong>, display <em>Profit</em> by <em>Dealer ID</em> as a <strong>column chart</strong>, sorted in ascending order.</p>
<br>

<p>TASK 3: On the <strong>Service</strong> dashboard, capture the following KPI metrics as visualizations:</p>
<ul>
<li>In the top left area <strong>(Panel 1)</strong>, capture the number of recalls per model of car (as a <strong>column chart</strong>).</li><li>In the top right area <strong>(Panel 2)</strong>, capture the customer sentiment by comparing positive, neutral, and negative reviews (as a <strong>treemap</strong>).</li><li>In the bottom left area <strong>(Panel 3)</strong>, capture the quantity of cars sold per month compared to the profit (as a <strong>combo chart</strong> from line section).</li><li>In the bottom right area <strong>(Panel 4)</strong>, capture the number of recalls by model and affected system (as a <strong>pivot table with a heatmap</strong>). This will help us understand if there are any outliers for a given model or a specific system.</li></ul>
<hr>
NOTE: Include suitable chart titles and labels for x and y axis.

<hr>

<p>Task 4: To export your dashboard as a PDF, follow instructions below:</p>
<ul>
<li><p>On the top right corner of your report editor, click on the small triangle of the <strong>Share</strong> button. Then select <strong>Download report</strong>.</p>
<p> <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/images/fa_5.png" alt=""></p>
   <br>
</li><li><p>On the pop up window <em>Download as PDF</em>, click on the <em>All pages</em> radio button. Choose from additional options and then click on <em>download</em>.</p>
<p>   <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/images/fa_6.png" alt=""></p>
   <br>
</li><li><p>Save the PDF file on your local machine to any location you like (preferably your <strong>Downloads</strong> folder) for later upload and submission to the coursera platform.</p>
</li><li><p>Your report may look like this:</p>
</li></ul>
<p><img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/images/fa_9.png" alt=""></p>
<p><img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0130EN-Coursera/images/fa_10.png" alt=""></p>
<h2><span class="header-link octicon octicon-link"></span>Author(s)</h2><ul>
<li><a href="https://www.linkedin.com/in/p-b28802262" target="_blank" rel="noopener noreferrer">Dr. Pooja</a></li>
<li><a href="https://www.linkedin.com/in/stevelryan" target="_blank" rel="noopener noreferrer">Steve Ryan</a></li></ul>
<h3><span class="header-link octicon octicon-link"></span>Other Contributor(s)</h3><ul>
<li><a href="https://www.linkedin.com/in/sandipsahajoy/" target="_blank" rel="noopener noreferrer">Sandip Saha Joy</a></li></ul>



<h2><span class="header-link octicon octicon-link"></span></h2><h3> © IBM Corporation. All rights reserved. </h3>
