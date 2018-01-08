This project is written in C# in a generic development methodology to support any user.
It consists of the following functions and each one returns a browser object of the browser that it is targeting:

1- InvokeFirefox (Function that invokes and return a browser object of firefox.)
	Parameters (All strings): "FirefoxBrowserPath" is where the browser is installed. Default value is: @"C:\Program Files\Mozilla Firefox\firefox.exe"
				"FirefoxDriverPath" is where the firefox driver is located. "refer to seleniumHQ website for the download and more info about the drivers."
				"FirefoxDriverName" is the name of the geckodriver itself. Default value is: "geckodriver.exe"
				
2- InvokeChrome (Function that invokes and returns a browser object of Chrome.)
	Parameters (All strings): "ChromeDriverPath" is where the browser's driver is located. Default value is: @"C:\Selenium\Browsers drivers\"
	
3- InvokeInternetExplorer (Function that invokes and returns a browser object of Internet Explorer.)
	Parameters (All strings): "IEDriverPath" is where the browser's driver is located. Default value is: @"C:\Selenium\Browsers drivers\"
	
4- InvokeEdge (Function that invokes and returns a browser object of Microsoft Edge.)
	Parameters (All strings): "ChromeDriverPath" is where the browser's driver is located. Default value is: @"C:\Selenium\Browsers drivers\"

5- InvokeOpera (Function that invokes and return a browser object of Opera.)
	Parameters (All strings): "OperaBrowserPath" is where the browser is installed. Default value is: @"C:\Program Files\Opera\47.0.2631.55\opera.exe"
				"FirefoxDriverPath" is where the opera driver is located. "refer to seleniumHQ website for the download and more info about the drivers."
				"FirefoxDriverName" is the name of the opera itself. Default value is: "operadriver.exe"
				
6- InvokePhantomJS (Function that invokes and return a browser object of PhantomJS headless browser.)
	Parameters (All strings): "PhantomjsDriverPath" is where the PhantomJS driver is located. "refer to seleniumHQ website for the download and more info about the drivers."
				"PhantomjsDriverName" is the name of the PhantomJS driver itself. Default value is: "phantomjs.exe"
				
7- InvokeAppiumAndroid (Function that invokes and return a browser object of Appium when targeting android application.)
	Parameters (All strings, Refer to appium documentation to understand these variables.): 
				"AppiumDriverUrl" is the local IP of the appium server itself. Default value is: "http://127.0.0.1:4723/wd/hub"
				"deviceName",
				"PlatformVersion",
				"app",
				"appPackage",
				"appWaitActivity"

8- InvokeAppiumiOS (Function that invokes and return a browser object of Appium when targeting iOS application.)
	Parameters (All strings, Refer to appium documentation to understand these variables.): 
				"AppiumDriverUrl" is the local IP of the appium server itself. Default value is: "http://127.0.0.1:4723/wd/hub"
				"app",
				"PlatformVersion",
				"appName",
				"deviceUDID",
				"deviceName"
				
