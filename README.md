# Patch Sencha Cmd 4.0.0.203 to Work with Java&nbsp;1.6

Use the cordova-impl.xml.txt file at this site to enable access to Cordova commands 
in Sencha Cmd 4.0.0.203 under Java JRE 1.6.

## Installing the cordova-impl.xml File

If your computer has Java 1.6 and you do not want to upgrade to Java 1.7, you can install the 
<tt>cordova-impl.xml.txt</tt> file so that Cordova commands can be run under Sencha Cmd 4.0.0.203. 

**Note** Future versions of Sencha Cmd fix this issue for you. This fix is only required for Sencha Cmd 4.0.0.203.

To install:

 <ol>
 <li>Install the latest Sencha Cmd version from the command line with:
 <pre>sencha upgrade</pre>
 You can also download Sencha Cmd from <tt>http://www.sencha.com/products/sencha-cmd/download</tt></li>
 <li>Download the <tt>cordova-impl.xml.txt</tt> file from this site to your computer</li>
 <li>Change directory to 
 <tt>/Users/{username}/bin/Sencha/Cmd/4.0.0.203/extensions/cmd-cordova-packager/templates/App/.sencha/app</tt></li>
 <li>Copy <tt>cordova-impl.xml.txt</tt> to the <tt>app</tt> directory and 
 rename the file to be <tt>cordova-impl.xml</tt></li>
 <li>If you have an existing App, you also need to replace the <tt>cordova-impl.xml</tt> in the 
 <tt>{app}/.sencha/app</tt></li>
 </ol>
 
 
 
