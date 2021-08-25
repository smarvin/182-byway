---
title: Use a WDC in Tableau Desktop
keywords: WDC
sidebar: sam_sidebar
summary: "Create a Web Data Connector (WDC) when you want to connect to a web data source from Tableau. A WDC is an HTML page
with JavaScript code that connects to web data (for example, by means of a REST API), converts the data to a JSON format,
and passes the data to Tableau."
permalink: wdc_use_in_tableau.html
folder: wdc
---
To use a WDC in Tableau Desktop, complete the following steps:

1. On the start page, in the **Connect** pane, click **More Servers... > Web Data Connector**.

   ![]({{ site.baseurl }}/assets/wdc_desktop_select_wdc_as_connector.png)

1. Enter the URL of a WDC and press Enter.

   ![]({{ site.baseurl }}/assets/wdc_desktop_enter_url.png)

   **Important**: Make sure that you enter the URL of a WDC, and not the URL of the data that you're trying to connect
   to. For example, if you want to connect to FaceBook data, you might enter `www.example.com/myFacebookWDC.html`.

1. Tableau loads the WDC page where you can enter any input required by your WDC.

1. Tableau calls your WDC code, downloads data, and displays it in the **Data Source** pane.

For more information about using a WDC in Tableau Desktop, see [Web Data Connector](https://onlinehelp.tableau.com/current/pro/desktop/en-us/help.html#examples_web_data_connector.html){:target="_blank"}.
