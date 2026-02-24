# cs2-dom-styles

# Learning Target
I am learning how to control CSS styles using the DOM and JavaScript

# Success Criteria
- I can set a style property using ```element.style.property = "new value";```
- I can use ```element.classList.add("classname")`` to add a CSS class to an element

# Project Setup
1. Install *Live Server*
2. Create ```script.js```
3. Add ```console.log("Script started")``` to begining of ```script.js```
4. Add ```<script src="script.js"></script>``` before ```</body>``` tag in ```index.html``` to link the script
5. Go live and use the inspection tool to check that you see ***Script started*** in the console to verify your script is linked correctly to your html 

# Essential Notes
- You must first use ```let element = document.getElementById("id")``` to store an element in a variable before you can set its styles (or do anything with it) in JavaScript
- Use ```element.style.property = "value";``` to set a new value for a CSS style property e.g. ```p.style.color = "red";```
- Style values are always written as strings (should be in "")
- CSS properties with dashes must be converted to camelCase e.g. ```background-color``` in CSS becomes ```backgroundColor``` in JavaScript
- You can define a class in your ```styles.css``` file and then apply it to an element in JavaScript using ```element.classList.add("classname")```