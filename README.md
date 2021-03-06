# Load Testing Using Webload Tool

**Introduction**

WebLOAD is easy to use and delivers maximum testing performance and value. 
WebLOAD verifies the scalability and integrity of Internet applications by generating a load composed of Virtual Clients that simulate real-world traffic. 
Probing Clients let you refine the testing process by acting as a single user that measures the performance of targeted activities, and provides individual performance statistics of the Internet application under load. 

**Load Testing Steps**

* Create an Agenda.
* Configure a Load Template using the WebLOAD Wizard.
* Configure session options. 
* Run a test.
* Analyze test results. 

**Create an Agenda**

The first step in creating an Agenda is to record your actions as you interact with your Web application. 

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/1.png)

**1. Start WebLOAD IDE by clicking the Webload IDE icon**

WebLOAD IDE opens. 

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/2.png)

**2. Select Create a new project.**

The WebLOAD IDE main window opens in Editing Mode for you to begin creating your Agenda. 

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/3.png)

**3. In the main window, in Editing Mode, click the Start Record toolbar button to begin recording.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/4.png)

The Below dialog will appears. 

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/5.png)

**4. Click 'Ok'**

WebLOAD IDE begins recording all actions you perform in the browser, as indicated by the recording notification in the WebLOAD IDE status bar. 

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/6.png)

A browser window opens. 

**5. In the address bar, enter the Web address https://www.gingersoftware.com/grammarcheck to go to the WebLOAD test site.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/7.png)

**6. Navigate through the site, performing the actions you want to test.**

**For example**

	a. Enter content 'Are you sure you want to log out?' in the text field 
	b. Click 'Ginger it' button

Your actions are recorded and appear in the Agenda Tree as you navigate the site. (If you see additional nodes in the Agenda Tree with different URLs, this may be traffic generated by browser plug-ins or extensions, for example, third-party toolbars.) 

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/8.png)

**7. Click the Stop Record toolbar button in WebLOAD IDE to stop the recording.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/9.png)

**8. Click the Save toolbar button to save your Agenda.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/10.png)

**9. Type your filename and click Save. The Agenda is saved with the extension .wlp.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/11.png)

You now have a basic Agenda that can be used in a WebLOAD test configuration. For complete information on creating, editing and modifying Agendas, and adding functionality to your Agenda.

**Configuring a Load Template using WebLOAD Wizard And Confiure Session**

**To open WebLOAD Wizard** 

**1. Start the WebLOAD Console.**

Select Start -> All Programs -> RadView -> WebLOAD -> WebLOAD Console. 

The WebLOAD Console opens, and the WebLOAD Console dialog box appears. 

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/12.png)

**2. Select Create a new template using WebLOAD Wizard.**

The WebLOAD Wizard opens. 

**3. On the Welcome screen, click Next. button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/13.png)

**4. The Agenda/Mix Type screen appears.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/14.png)

**5. On the Agenda/Mix Type screen, select Single Agenda, and click Next.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/15.png)

**6. On the Agenda/Mix Selection screen, click the below button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/16.png)

**7. Then browse to the location of the GingerGrammerChecker.wlp Agenda created earlier using WebLOAD IDE. Select the Agenda and click Open.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/17.png)

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/18.png)

**8. Click 'Next' button**

**9. Selecting a host on which to run the Load Machine. And click 'Next' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/19.png)

**10. Scheduling the test 'Individual or Collective Scheduling', and then click 'Next' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/20.png)

**11. Then selecting the number of Virtual Clients & Limit run to.**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/21.png)

**12.  Click 'Next' Button**

**13. Performance Measurement Manager window will be appeared**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/22.png)

**14. Click 'Add Monitor' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/23.png)

**15. Click 'Add Data Source' Button, The Performance Measurements Manager Wizard opens.**

**16. Select 'Server' and click 'Next' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/24.png)

**17. Server Configuration window will appeared, click 'Next' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/25.png)

**18. Then select your hostname and click 'Select' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/26.png)

**19. Selected host details will appeared**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/45.png)

**20. Click 'Next' button, Now you have successfully completed the Performance Measurement Wizard.**

**21. Click 'Finish' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/27.png)

**22. Select Monitor and click 'Next' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/28.png)

**23. Click 'Next' button and Finish the Webload Wizard**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/29.png)

**24. Then 'Save' your load template**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/30.png)

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/31.png)

**Run Test**

**24. Now your test will be run**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/32.png)

**25. Once the run is completed ,  'Webload Analytics' pop up launch pop up will be appeared**

**Analyze test results**

**26. Click 'Launch Webload Anlaytics' button**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/33.png)

**27. Then save the session**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/34.png)

**28. Then automatically reports will be generated in the webload analytics window**

**Session Summary Report**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/35.png)

**Note**

The reports will be generated as multiple views in a seperate tab.

**Attempted Connection Reports**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/36.png)

**Response Time Breakdown Reports**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/37.png)

**HTTP Response Report**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/38.png)

**HTTP Errors OverTime Report**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/39.png)

**Errors and warinings Report**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/40.png)

**Log Summary Report**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/41.png)

**Total Page Time Report**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/42.png)

**Total Transaction Over Time Report**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/43.png)

**Load Generator Health Report**

![alt text](https://github.com/TSQAteam/Load-Testing-Using-Webload-Tool/blob/master/Screens/44.png)

**Demo Video**

Click the below dropbox video for your reference,

https://www.dropbox.com/s/ubof5t0hjrs5dco/LoadTestWithWebload.mp4?dl=0



























