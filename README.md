<!-- MARKSHEET DEMO IN JAVA SCRIPT -->
  
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marksheet demo</title>
</head>  
<body>   
    <script>
        var name = prompt("Enter your name");
        var course = prompt("Enter your course");
        var PRN = prompt ("Enter your PRN")
        var C = prompt("Enter your C++ marks");
        var Java = prompt("Enter your Java marks");
        var SQL = prompt("Enter your SQL marks");
        var AWP = prompt("Enter your AWP marks");
        var NET = prompt("Enter your .NET marks");
        
        var obtained_marks = parseInt(C) + parseInt(Java) +parseInt(SQL) + parseInt(AWP) + parseInt(NET);

        var percentage = obtained_marks *100 / 500;
        var CGPA = percentage /90 *10; 

        
        document.write("Your name : " + name + "<br/>");
        document.write("Your course : " + course + "<br/>");
        document.write("Your PRN : " + PRN + "<br/>");
        document.write("Your obtained marks : " + obtained_marks  + "<br/>");
        document.write("Your percentage : " + percentage+"%" + "<br/>");
        document.write("your CGPA: "+ CGPA);
        


    </script>
    
    
</body>
</html>
