## OmniSci Starter Project
------------
### About
This project is designed to be a "starter kit" for using the OmniSci charting libraries, demonstrating how to use JavaScript to connect to an OmniSci database and then visualize your data.  

This project can be connected to any OmniSci database and was created with connecting to your own [OmniSci Cloud](https://www.omnisci.com/cloud) instance in mind.  The `main.js` file serves as the pre-bundled OmniSci starter kit, which includes the [MapDC Charting](https://github.com/omnisci/mapd-charting), [MapD Connector](https://github.com/omnisci/mapd-connector), and [MapD Crossfilter](https://github.com/omnisci/mapd-crossfilter) libraries.

### Getting started
To get started, you'll need access to an OmniSci database.  You can sign up for a free trial of [OmniSci Cloud](https://www.omnisci.com/cloud) or access any other instance.  This example is configured to connect to a table containing data on the NYC Tree Census which is pre loaded on all Cloud instances.

Next, enter your API information in the MapD Connector section in the `index.html` file.  If you're using your OmniSci Cloud instance, this information is available by logging into OmniSci Cloud, clicking the "Settings" button, and then the "Developer" tab. 

Open the page in a browser and you should see a pie chart and bar chart containing information on NYC trees.  Feel free to play around and change the chart types or even use a different table!