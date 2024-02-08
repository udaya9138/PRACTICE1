6.02.2024
html:-
stands for hyper text transfer language
we use html for creating structure of the website
we call html as a mark up language because it contains skeletal stucture of web page
all html are written in tag line
with in head-
title
meta element
outside link/script
h-heading
heading is range from h1-h6

<hr> tag for horizontal line.
sourse,height,width,alt are the attributes of image tag.
<a> tag is use for giving some link to the website
href for hyper reference to the another page or element
target is used for
7.02.2024
HTML FORMATTING:-
<mark>-marked text
<b> -bold text
<i>-italic text
<em>-emphasized text
<ins>-inserted text
<del>-deletion text
<sub>-subscripted text
<sup>-superscripted text
HTML TABLE:-
html table gives us a table like structure where we can insert our data in row and column format
<table>-main tag
<tr>-table row
<td>-table data
<th>-table heading
HTML LIST:-
1.unordered list-<ul>
2.ordered list-<ol>
<li>-list item
HTML BLOCK LEVEL ELEMENT:-
html contains 2 type of block level element to specify the structure of the web pages
1.<p>-paragraph
2.<div>-division
HTML FORMS:-
*************
html forms provides a form like structure so that we can give our data by use of these forms
INPUT TYPES OF A FORM:-
1.<input type="text">
2.password
3.submit
4.checkbox
5.radio-botton
6.time
7.color
8.date
9.1.<input type="url">
10.<input type="search">
11.week
12.email
13.image
14.month
15.range
16.file
17.tel
18.number
08-02-2024
***********
CSS:-
*******
css stands for cascading stylish sheet
we used css for designing and styling the web pages
syntax:-
*********
h1{
color:red
}
here h1 is selector
color is property
red is value
-basically css are of 3 types
1.inline css
2.internal css
3.external css
INLINE CSS:-
***********
style tag is used with other tag.
<body>
    <h1 style="color:red">today is tuesday</h1>
    <p style="backgroundcolor:yellow">today we stated css</p>
</body>
INTERNAL CSS:-
*****************
<head>
     <style>
          h1{
            color:red;
          }    
          p{
            bgcolor:blue;
          }
        </style>
</head> 
EXTERNAL CSS:-
****************
it is linkage to the outer css file to our main html element
HTML PART:-
<head>
     <link rel="stylesheet" href="style.css">
</head>
<body>
   <h1>Today is a bad day for me</h1>
</body>  
 CSS PART:-
 style.css
 h1{
    color:red;
 }   
 CSS SELECTOR:-
 1.id selector
 2.class selector
 3.universal selector
 4.group selector
 5.elemental selector
 -selector means selecting a element which we have to designed
 ID SELECTOR:-
 -id selector are those selector which unique design/we select only one element in HTML file
 -it is denoted by "#" 
 ex:-                                                  stle.css:-
                                                        #demo{
                                                            color:green;
                                                        }
                                                        h1{
                                                            color:red;
                                                        }
  <html>
        <head>
           <link rel="stylesheet" href="style.css">
        </head>
        <body>
            <h1 id="demo">today is tuesday</h1>
            <h1>we learn css</h1>
            <h1>we write code...</h1>
         </body>
   </html>
   
class selector:-
1.we used to class selector for repeating the similar design in multiple times
2."." property used to specify the class selector in our css file
UNIVERSAL SELECTOR:-
1.we used universal selectornto design whole html page in a single design
2."." is used to specify it 
GROUP selector:
1.we used group selector to create one design in which we have selected the tags,
2.group selector we used by creating the group
 ELEMENT SELECTOR:-
 -by selecting one single element we have to design is called the element selector
 create a simple div with an id "box".add some text 
 VERSION CONTROL SYSTEM:-
 **************************************************************************************
 -git and git hub are those open source version control system.
 -we used version control system to store our code,share our code and collaborate our projects with each other
 -example of vcs is-git,github,gitlab...