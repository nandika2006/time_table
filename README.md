# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

  <html>
      
  </head>
      <meta charset="UTF-8" />
      <title>nandika timetable</title>
      <style type="text/css">
          th{color:black}   
      </style>
  </head>
  <body bgcolor="bisque">
      <center><img src="WhatsApp Image 2024-10-21 at 13.01.13_50158c5f.jpg"></center>
      <font face="times new roman" size="5">
          <font face="brush scriptmt" size="5"><u><i><CENTER><B><p>SLOT TIME TABLE - S.NANDIKA(24010030)</p></B></i></u></CENTER></font>
          <table border="5px" bordercolor="black" cellpadding="50%">
              <tr>
                  <th bgcolor="beige">Days</th>
                  <th bgcolor="beige">8:00 am - 10:00 am</th>
                  <th bgcolor="beige">10:00 am - 12:00 pm</th>
                  <th rowspan="7" bgcolor="lemonchiffon">LUNCH</th>
                  <th bgcolor="beige">1:00 pm - 3:00 pm</th>
                  <th bgcolor="beige">3:00 pm - 5:00 pm</th>
              </tr>
  
              <tr>
                  <th bgcolor="moccasin">Monday</th>
                  <td>FREE PERIOD</td>
                  <td>Prototyping of IOT</td>
                  <td>Fundamentals of Web application</td>
                  <td>FREE PERIOD</td>
              </tr>
  
              <tr>
                  <th bgcolor="moccasin">Tuesday</th>
                  <td bgcolor="beige">Career Developement</td>
                  <td bgcolor="beige">Physics for Quantum Computing</td>
                  <td bgcolor="beige">Statistics and numerical methods</td>
                  <td bgcolor="beige">Python Programming</td>
              </tr>
  
              <tr>
                  <th bgcolor="moccasin">Wednesday</th>
                  <td>Stastics and numerical methods</td>
                  <td>Digital Electronic</td>
                  <td>Mentor Meet</td>
                  <td>FREE PERIOD</td>
              </tr>
              
              <tr>
                  <th bgcolor="moccasin">Thursday</th>
                  <td bgcolor="beige">FREE PERIOD</td>
                  <td bgcolor="beige">Digital Electronic</td>
                  <td bgcolor="beige">Python Programming</td>
                  <td bgcolor="beige">FREE PERIOD</td>
              </tr>
  
              <tr>
                  <th bgcolor="moccasin">Friday</th>
                  <td>FREE PERIOD</td>
                  <td>Fundamentals of web application</td>
                  <td>Human Values and Ethics</td>
                  <td>FREE PERIOD</td>
              </tr>
              
              <tr>
                  <th bgcolor="moccasin">Saturday</th>
                  <td bgcolor="beige">Prototyping of IOT</td>
                  <td bgcolor="beige">Fundamentals of web application</td>
                  <td bgcolor="beige">Physics for Quantum Computing</td>
                  <td bgcolor="beige">FREE PERIOD</td>
              </tr>
          </table>
  
          <p>
              <table border="5px" bordercolor="black" cellpadding="10%" width="100%" height="25%">
              <tr>
                  <th bgcolor="palegoldenrod">S.NO</th>
                  <th bgcolor="palegoldenrod">SUBJECT CODE</th>
                  <th bgcolor="palegoldenrod">SUBJECT NAME</th>
              </tr>
              <tr>
                  <td bgcolor="khaki">1.</td>
                  <td bgcolor="lightyellow">19CS420</td>
                  <td bgcolor="lightyellow">Prototyping of IOT</td>
              </tr>
              <TR>
                  <TD bgcolor="khaki">2.</TD>
                  <td>19AL414</td>
                  <TD>Fundamentals of Web Application</TD>
              </TR>
              <TR>
                  <TD bgcolor="khaki">3.</TD>
                  <td bgcolor="lightyellow">19EY708</td>
                  <TD bgcolor="lightyellow">Career Developement</TD>
              </TR>
              <TR>
                  <TD bgcolor="khaki">4.</TD>
                  <td>SH3214</td>
                  <TD>Physics for Quantum Computing</TD>
              </TR>
              <TR>
                  <TD bgcolor="khaki">5.</TD>
                  <td bgcolor="lightyellow">19MA211</td>
                  <TD bgcolor="lightyellow">Statistics and numerical methods</TD>
              </TR>
              <TR>
                  <TD bgcolor="khaki">6.</TD>
                  <td>19AL301</td>
                  <TD>Python Programming</TD>
              </TR>
              <TR>
                  <TD bgcolor="khaki">7.</TD>
                  <td bgcolor="lightyellow">19EE404</td>
                  <TD bgcolor="lightyellow">Digital Electronic</TD>
              </TR>
              <TR>
                  <TD bgcolor="khaki">8.</TD>
                  <td>SH7801</td>
                  <TD>Human Values and Ethics</TD>
              </TR>
              <TR>
                  <TD bgcolor="khaki">9.</TD>
                  <td bgcolor="lightyellow">ECA-M-SCOFT</td>
                  <TD bgcolor="lightyellow">Mentor Meet</TD>
              </TR>
          </table>
      </p>
      </font>
  </body>
  </html>


# OUTPUT

![Screenshot 2024-12-12 104308](https://github.com/user-attachments/assets/31f1741f-a5c0-48fd-a307-e64a607abc99)
![Screenshot 2024-12-12 104320](https://github.com/user-attachments/assets/bea8d4c0-1d18-455e-833f-deffedda19f8)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
