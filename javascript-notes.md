### **JavaScript**: it's where you can change how the page behaves, adding interactivity. 

Aim to keep the three languages (HTML, CSS, JavaScript) in separate files, withthe HTML page linking to CSS and JavaScript files. 

Some people browse with JavaScript turned off, so you need to make sure that the page still works for them. 

#### **How to use objects & methods**

Javascript runs where it is found in the HTML

When there's an HTML `<script>` element it will be used to load the JavaScript file into the page. It has an attribute called `src`, whose value is the path to the script that was created. 

`<script src="js/add-content.js"></script>` 

This tells the browser to find and load the script file (just like the src attribute on an `<img>` tag)

`document.write('Good afternoon!');`

* The **document** object represent the entire web page.
* the **write()** method of the document object allows new content to be written into the page where the `<script>` element sits.
