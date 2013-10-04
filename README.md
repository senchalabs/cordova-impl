# Patch Sencha Cmd 4.0.0.203 to Work with Java&nbsp;1.6

Use the cordova-impl.xml.txt file at this site to enable access to Cordova commands 
in Sencha Cmd 4.0.0.203 under Java JRE 1.6.

## Installing the cordova-impl.xml.txt File

If your computer has Java 1.6 and you do not want to upgrade to Java 1.7, you can install the 
<b>cordova-impl.xml.txt</b> file at this site so that Cordova commands can be run under Sencha Cmd 4.0.0.203. 

**Note** Future versions of Sencha Cmd fix this issue for you. This fix is only required for Sencha Cmd 4.0.0.203.

To install:

 <ol>
 <li>Install the latest Sencha Cmd version from the command line with:
 <pre>sencha upgrade</pre>
 You can also download Sencha Cmd from http://www.sencha.com/products/sencha-cmd/download</li>
 <li>Download the <b>cordova-impl.xml.txt</b> file from this site to your computer</li>
 <li>Change directory to 
/Users/{username}/bin/Sencha/Cmd/4.0.0.203/extensions/cmd-cordova-packager/templates/App/.sencha/app</li>
 <li>Copy cordova-impl.xml.txt to the <b>app</b> directory and 
 rename the file to be <b>cordova-impl.xml</b></li>
 <li>If you have an existing App, you also need to replace the cordova-impl.xml in the 
 {app}/.sencha/app</li>
 </ol>
 
 
 
