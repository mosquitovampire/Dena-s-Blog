# Dena-s-Blog
Detailed learning of HTML and CSS<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Project: Blog</title>
        <style>
            h1 {
                
                font-family: fantasy, cursive;
                font-size:3.5em;
                color:purple;
            }
            
            h2 {
                font-size:1.6em;
                color: rgb(168, 20, 168);
                
            }
            
            h3 {
                font-weight: bold;
                font-family: cursive;
                font-size:32px;
                color:purple;
            }
            h4 {
                font-size:1.4em;
                color: blue;
                font-family:sans-serif;
            }
            
            body {
                font-family: helvetica, sans-serif;
                background-color: rgb(245, 137, 245);
            }
            
        </style>
    </head>
    
    <body>
        
        <h1>Dena's blog</h1>

        <h3>HTML Table<br> 
         of Knowledge</h3>
        
       
        
        <table>
            <thead>
                <tr>
                    <th><h2><a href= "#HTML">HTML</a></h2></th>
                    <th><h2><a href= "#CSS">CSS</a></h2></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td> <a href= "#HTML-Basics">Basics</a></td>
                    <td><a href="#CSS-Basics">CSS Basics</a></td>
                    
                </tr>
                
                <tr>
                    <td> <a href= "#Images">Images</a></td>
                    <td><a href= "#Selecting-Id">Selecting Id</a                  ></td>
                    
                </tr>
                
                <tr>
                    <td> <a href= "#Links">Links</a></td>
                    <td><a href= "#Selecting-Class">Selecting                          Class</a></td>
                </tr>
                
                <tr>
                    <td><a href="#Tables">Tables</a></td>
                    <td><a href="#Font-Text">Font Text</a></td>
                </tr>
                
                <tr>
                    <td><a href="#Comments">Comments</a></td>
                    <td><a href="#Inheritance">Inheritance</a></td>
                    
                    
                </tr>
            
            </tbody>
        </table>
    
        
        <h2>Lessons</h2>
        <h5>03/11/2021</h5>
        

        <h1><p id= "HTML"></p>HTML</h1>
        <h4><strong><p id= "HTML-Basics">Basics</p></strong></h4>
        <p>The first HTML I learned about was foundational language. I learned the word tag. Tag is the word inside the brackets that tell the computer how to display on the interface. Some of the first foundational tags I learned were: html, body, head, h1, h2, h3, h4, h5, h6, p, br, em, strong, ul, li, and ol. HTML literally means Hypertext Markup Language. It is a standardized system for tagging text files to achieve font, color, graphic, and hyperlink effects on World Wide Web pages.</p><br>
        
    <h4><strong><p id= "Images">Images</p></strong></h4>
    <p>How to display images of what I want and where them. I learned how to do this using HTML tags img and img src. I learned how to get https images on the internet and place on my webpage. In cases someone is blind or is just reading code instead of looking at webpage the is tag alt where you make a written discription of the image so that they know what the image was of. Lastly to size the image larger or smaller by using tag width.</p><br>
    
    <h4><strong><p id= "Links">Links</p></strong></h4>
    <p>External links are ones that when pressed take you to a website outside of the current one. Internal links are ones that when pressed take you within the same webpage. In this webpage the subjects I learned titles in the content are internal links to the paragraphs on that subject. Example with Links under table HTML when pressed take you to the top of this paragraph. Go ahed and try it.</p><br>
    
    <h4><strong><p id= "Tables">Tables</p></strong></h4>
    
    <p>Tables are a way to condense information into an easy to read and understand format. There are headers, rows and columns that create a chart. Under the header is information relative to that header. In this website at the top there is a table showing knowledge learned in HTML and CSS. Some tags to create tables are table, thead, tr, th, tbody, and td.</p><br>
    
    <h4><strong><p id= "Comments">Comments</p></strong></h4>
    <p>How comments are used. Comments are in the coding area. They are not seen on the interface or webpage. They are used to give additional text not shown on the site. The tag is !--   -- Example: !--the poem is from website address.-- Example: !--Hello, please enjoy the site-- Example:!--added information-- Comments default font color is green to help the person reading the code know it is a comment and not displayed on the webpage.
    </p><br>
    <!--Thanks for looking to see if I did make a comment here in the code section.-->
    
    <h1><p id= "CSS">CSS</p></h1>
    <h4><strong><p id= "CSS-Basics">CSS Basics</p></strong></h4>
    <p>The beggining and ending tag for CSS is style. It is tagged after title tag and before body tag. All between the first style tag and last style tag is CSS tags. Using CSS you can color words, color background, choose font type. Here I used color purple with fantasy font type for the header large letters CSS. I did the same CSS on the header HTML, and at the top header Dena's blog. Everywhere you see colored font I made that color using CSS. The light purple background is CSS. Bold words, font size, and alignment are all CSS.</p><br>
    
    <h4><strong><p id= "Selecting-Id">Selecting Id</p></strong></h4>
    <p>Instead of having all paragraphs (tag p) or headers (tag h1, h2, h3, etc...) be the same use selecting Id to display choosen p or h differently. Any single paragraph or any one header can be pin pointed to have different CSS. Id tells the browser exactly which paragraph or header to apply the CSS to. Tags are p id= "created-name" or h1 id= "created-name" at the beginning of the p or h1. Tags inside style tags near top are #"created-name" { CSS 
    } No spaces are allowed in created name, use hyphen or underscore, and Id is case sensitive. Id is for a change to a singe heading or paragraph. </p><br>
    
    <h4><strong><p id= "Selecting-Class">Selecting Class</p></strong></h4>
    <p>
    What if you want to have some of the headers or the paragraphs the exact same CSS style? Selecting class is for those cases. Where there are two or more headers or paragraphs that you want to have the same CSS use class. Tags are p class= "class-name" or h1 class "class-name" placed at front of several p or h1. The class rule inside tag style is .class-name {CSS}. Therefore every paragraph or header where you placed the class tag will have same background color, text color, font-family, height, weight, and size. </p> <br>
    
    <h4><strong><p id= "Font-Text">Font Text</p></strong></h4>
    <p>CSS creates colored text like how the above Font Text is blue. How? By tag body or p or h1{ color: blue; or red; or yellow; or by using rgb (0,0,0); to select a color using your cursor. Body tag will do all text in the body of the site. Tag to have background color is {background-color: state a basic color or chose a color on rgb}. If you try a fancy color name and the browser does not recongnize it then it may keep it colored black as the default. Tag font-family is to create cursive, sans-serif, monospace, fantasy, or helvetica. Tag font-size: 16px; or 2em. The number before px is the size, and 1em is the same, 1.5em is one and a half larger, 2em is double, 3em is triple, etc... Tag text-align: center, right, justify, moves text to align at stated place.</p><br>
    
    <h4><strong><p id= "Inheritance">Inheritance</p></strong></h4>
    <p>CSS inheritance means all the way thru the website until a tag with a different rule overrides the stlye continues the same.<br> 
 <br>   Included Inheritance Tags:<br>
 <ul>
     <li>font-family</li>
     <li>color</li>
     <li>background-color</li>
     <li>font-family</li>
     <li>font-weight</li>
     <li>text-decoration</li>
     <li>font-style</li>
     <li>text-align</li>
     <li>font-size</li>
     <li>line-height</li>
     
 </ul>
    </p>
    
    </body>
</html>



