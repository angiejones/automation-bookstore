# For Intro Automation Workshop

DOWNLOAD AND INSTALL
=====================
Java (JDK): http://www.oracle.com/technetwork/java/javase/downloads/index.html

Eclipse (during installation, choose the one for Java Developers): http://www.eclipse.org/downloads/

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
    
Ensure Eclipse is pointing to Java 1.8 in Build Path:
- Expand project in Package Explorer
- JRE System Library should have [Java SE 8 [1.8.0....]]
- If not, right click and select Properties
- Choose Workspace Default JRE if it is pointed to 1.8. If not, choose Alternate JRE and browse to where you installed Java
- Click Apply and Close
