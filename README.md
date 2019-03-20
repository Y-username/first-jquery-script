#### $(document).ready(function(){})
1. to run jQuery after the HTML is fully rendered and DOM fully loaded. and put all jQuery commands inside {}
2. keep style and content seperate and change HTML style. so to change CSS using predefined classes rather than inline styles

####  keypoint 
1. .css function changes HTML using inline styles
2. instead, we use .addClass() function and create new classed in style element. eg.$("ul").addClass("border")  
3. $("tr:odd").addClass("odd");  to add .odd class to odd line in table