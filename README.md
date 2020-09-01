# avo-pdf-itext
Blueprism VBO for working with PDF using the iText library. 

Import the xml in Blueprism to use the VBO. Blueprism is a RPA Software. Visit https://www.blueprism.com/ to learn more.
You can also read the code directly from the xml file.

This VBO needs iText library files to work. 
Default placement of the dll files is in the Blue Prism Automate folder. If you want to store the files somewhere else, you need to update the references in the VBO.
iText library files can be found by following instructions on https://itextpdf.com or on iText github page: https://github.com/itext/itext7-dotnet. 

No modifications are made to the iText library files in this solution.

The actions in the VBO mainly consist of coded functions where example code from the iText knowledge base is the basis. 

In addition to the iText library files you will also need BouncyCastle.Crypto.dll for the iText lib file to work. 
