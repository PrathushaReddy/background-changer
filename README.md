# background-changer
# Hi everyone 

In this repository we have done a website that changes it's background color on the basis of the color the user input

The JS used is an internal js file .<br>
we have created a `function rendercolor()` which changes the color it also has several conditional statements which detect the input and accordingly it changes the text color 

To change the color of the `Body` tag <br>
 we used the statement 
  ` 
      document.body.style.backgroundImage =
        "linear-gradient( to right ," + inputVal + ", " + color_Two + ")"; 
          `<br>
            
   1. inputVal holds the color code of the first input 
   2. color_two holds the color code of the second input


Several tags have to be selected to edit them the selectors used are `.getElementsByTagName` , `.getElementById` ;

to select more than one element in a selector we have used 
`  var elements = ["label", "label2"]; 
    for (i = 0; i < elements.length; i++) {
          document.getElementById(elements[i]).style.color = "white";
        }`<br>
        
 the element variable stores the Id-names of the element which are the accessed by using an For loop
 
 we have also made this website a bit beautiful by using some CSS 
 
 # Thank You 
 ## Have a great day
