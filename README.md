252s13ex1
=========

252 exam 1
<!DOCTYPE html>
<html>
<head>
<script>
function validateForm()
{
var x=document.forms["myForm"]["Address 1"].value;
if (x==null || x=="")
  {
    alert("Address 1 must be filled out");
      return false;
        }
        }
        </script>
        </head>
        
        <body>
        <form name="myForm" action="demo_form.asp" onsubmit="return validateForm()" method="post">
        Address 1: <input type="text" name="Address 1">
        <input type="submit" value="Submit">
        </form>
        </body>
        
        </html>
        
