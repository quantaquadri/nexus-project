GIT STUFFS

Wanna start from scratch?

1. git init
2. git status
3. git add .
4. git commit -m 'commit message'
5. git remote add origin ________________copy repo link
6. git remote -v
7. git push -u origin master



wanna topup

1. git add .
2. git commit -m 'commit message'
3. git push origin master

FOR SURGE:

FIRST TIME USER

1. go to project path
2. surge
3. create account username and password
4. enter
5. set the url to the path you considering
6.

SECOND TIME USER and wanna upload the link
1. echo vancouver.surge.sh > CNAME
2. surge

Hi Abdulquadri, TO CREATE A BOOTSTRAP BOILER TEMPLATE: 

Go to getbootsrap.com website [the v4-alpha link]; download bootstrap from there..it usually contains a CSS and JS Folder. create you own folder and name CSS, JS.

All you need is copy out bootstrap file from both CSS and JS FOlders you downloaded from v4-alpha; copy to your own different folders.

Now link it to your html markdown template. the script after the body tag and link in the header tag.

See temp here, this is from the current BOOTSTRAP4




<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css">
	<title></title>
</head>


<body>



</body>


<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.slim.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js" ></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
</html>

--------------------------------------------------------------------------------------------------------------------
Line 42 and 56 was gotten from the v4-alpha.com/getting-started/introduction ..when you copy it, remove eveything from the integrity backwards. Link in the head tag and script placed after the body tag.

Line 54-56 follows the hierrachy; Jquery first, then Tether and then Bootstrap.

Line 54, Jquery was gotten from this website: https://cdnjs.com/libraries/jquery/, copy the slim.js file and paster as itis.

Cool yeah? You learning.








Line 55 was gotten from the the v4-alpha website, 


To Make a Row Clickable when writing the table tag:

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
      "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html>
  <head>
    <meta http-equiv="Content-Type" 
             content="text/html; charset=iso-8859-1" />
    <title>Full Row Select</title>
    <script type="text/javascript">
    function ChangeColor(tableRow, highLight)
    {
    if (highLight)
    {
      tableRow.style.backgroundColor = '#dcfac9';
    }
    else
    {
      tableRow.style.backgroundColor = 'white';
    }
  }

  function DoNav(theUrl)
  {
  document.location.href = theUrl;
  }
  </script>
</head>
<body>
  <table width="100%" border="1" cellpadding="0" cellspacing="0">
  <tr onmouseover="ChangeColor(this, true);" 
              onmouseout="ChangeColor(this, false);" 
              onclick="DoNav('http://www.yahoo.com/');">
    <td>1</td>
    <td>2</td>
    <td>3</td>
  </tr>
  <tr onmouseover="ChangeColor(this, true);" 
              onmouseout="ChangeColor(this, false);" 
              onclick="DoNav('http://www.microsoft.com/');">
    <td>4</td>
    <td>5</td>
    <td>6</td>
  </tr>
  <tr onmouseover="ChangeColor(this, true);" 
              onmouseout="ChangeColor(this, false);" 
              onclick="DoNav('http://Imar.Spaanjaars.Com/');">
    <td>7</td>
    <td>8</td>
    <td>9</td>
  </tr>
  </table>
</body>
</html>
