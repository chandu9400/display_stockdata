
Display data visually for traders.
Use Perspective to create the chart for the trader’s dashboard.

<b>Aim:</b> Use Perspective to generate a chart that displays the data feed in a clear and visually appealing manner for traders to monitor this trading strategy. Basically, you have to modify the existing live chart to be able to (1) track and display the ratio between the two stock prices (2) show the historical upper and lower bounds of the stocks' ratio (3) and finally, show 'alerts'  whenever these bounds are crossed by the ratio.


	
  
</ol>

<h2 id="installation" >Setup / Installation</h2>
<p>In order to get the server and client application code working on your machine, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m3_v3.pdf">follow the setup here</a></p>

<h2>How to Run</h2>
<p>Similar to Task 2, start the data feed server by running the python server</p>
<p>Make sure your terminal / command line is in the repository first before doing any of this.</p>
<p>If you are using Windows, make sure to run your terminal/command prompt as administrator.</p>

<code>python datafeed/server.py</code>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.

<h2>Known Issues</h2>
Some users seem to be having trouble with the unzipped version of the node_modules back up for windows. 
This is the alternative unzipped version:
https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz

Note: You may need to (hard) refresh the link to the public gdrive to see all of the files/folders e.g. @jpmorganchase/perspective as it takes gdrive a bit to load them for you.

<h2>How to fix the code to meet the objectives</h2>
<p>Ideally you should have some background into programming and possibly some knowledge about web applications/frameworks to reach the objectives of this task.</p>
<p> If you're up to the challenge, please attempt to do this task without using the guide below.</p>
<p>If you have absolutely no clue how to start this task, you can <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m3_v2.pdf">follow this guide</a>.</p>

