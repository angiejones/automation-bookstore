# For Intro Automation Workshop

DOWNLOAD AND INSTALL
=====================
Java (JDK): http://www.oracle.com/technetwork/java/javase/downloads/index.html

Eclipse: http://www.eclipse.org/downloads/

Chrome: https://www.google.com/chrome/

Selenium 3.5.3 (Selenium Client & WebDriver Language Bindings -> Java): http://www.seleniumhq.org/download/

Chrome Driver: https://sites.google.com/a/chromium.org/chromedriver/downloads

This project (unzip once downloaded)


CONFIGURE
============
In Eclipse, import downloaded project:
- File -> Import -> Maven -> Existing Maven Projects -> Next
- Browse to downloaded project and select "project" folder
- Click Open
- Ensure pom.xml is checked 
- Click Finish

Add selenium libraries to Eclipse workspace:
- On your file system, unzip selenium-java-3.5.3.zip
- In Eclipse, within Package Explorer on the right, right click on the project
- Select Properties
- In the modal, choose Java Build Path from the right panel
- Click Libraries tab
- Click Add External Jars
- Browse to the unzipped directory selenium-java-3.5.3/lib
- Select ALL of the jar files
- Click Open
- Click Apply and Close
    
Ensure Eclipse is pointing to Java 1.8 in Build Path:
- Expand project in Package Explorer
- JRE System Library should have [Java SE 8 [1.8.0....]]
- If not, right click and select Properties
- Choose Workspace Default JRE if it is pointed to 1.8. If not, choose Alternate JRE and browse to where you installed Java
- Click Apply and Close
