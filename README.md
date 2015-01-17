Step 1: Head over to yWorks UML Doclet and download their tool.

Step 2: Right click on your java project of choice in your project explorer within NetBeans 7.0.x

Step 3: Choose Properties.

Step 4: Select Documenting under the Build category.

Step 5: At the textbox for Additional Javadoc Options: paste the following:

-docletpath “<yid>\lib\ydoc.jar” -resourcepath “<yid>\resources” -doclet ydoc.doclets.YStandard -umlautogen

Where <yid> is the file path for the files above. In my case <yid> reads as: C:\Users\Matt\yworks-uml-doclet-3.0_01-jdk1.5

Step 6. Click ok.

Step 7. Right click on your project in the projects explorer.

Step 8: Click Generate Javadoc.

You are finished, within your Javadoc you will find that you have a beautiful UML diagram for your classes.