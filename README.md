## CSS-tutorial

CSS stands for Cascading Style Sheets.<br>
CSS describes how HTML elements are to be displayed on screen, paper, or in other media.<br>
CSS saves a lot of work. It can control the layout of multiple web pages all at once.<br>
External stylesheets are stored in CSS files.<br>

### CSS Syntax<br>
CSS syntax contains a selector and declaration block

![image](https://user-images.githubusercontent.com/100207065/226394952-72e1532e-6e76-4ee7-9a89-560e3589d8e0.png)

<b>Selector:</b> Selector indicates the HTML element you want to style.
<br>
<b>Declaration Block:</b> The declaration block can contain one or more declarations separated by a semicolon. For the above example, there are two declarations:<br>
1- color: yellow;<br>
2- font-size: 11 px;<br>

Types of CSS Selector
    1) CSS Element Selector:- 
       The element selector selects the HTML element by name.
    
                              <!DOCTYPE html>  
                              <html>  
                              <head>  
                              <style>  
                              p{                             
                                text-align: center;  
                                color: blue;  
                               }   
                              </style>  
                              </head>  
                              <body>  
                                  <p>This style will be applied on every paragraph.</p>  
                                  <p id="para1">Me too!</p>  
                                  <p>And me!</p>  
                              </body>  
                              </html
                           
<a href="https://www.programiz.com/html/online-compiler">COPY CODE HERE AND RUN</a>
