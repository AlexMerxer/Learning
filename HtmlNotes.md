### HTML Notes
1.HTML-----> Hyper Text MarkUp Language

2.HTML starts with opening and closing tags as shown below
             "<html>  </html>"

3.HTML has elements which we use to create webPage
   ex: body,h1,img,...etc

4.After HTMl tag head and body tags are started
    syntax ex:  <html>  
                   <head>
                   </head>           
                   <body>
                   </body>
                </html>  

5.Each HTML  element is represented by angular brackets

6.After the body tag our content will be placed in it by using other elements
      ex: main,h1,h2,img...etc

7.Starting with our heading tag it has h1,h2,h3,h4,h5,h6. All these represents the different 
type of size. Remember that while using these tags,tag with small number has the highest priority
in the web webPage 
        syntax Ex: <html>             
                      <body>
                      <h1> This is sample webPage </h1>
                      <h2> This is also a sample web page </h2>
                      <h3> This is also a sample web page </h3>
                      <h4> This is also a sample web page </h4>
                      </body>
                   </html>       
        Note: If we execute the above code we can see the differences in the tags in the browser

8.Paragraphs are added After the heading tags, it starts with <p> and ends with </p>
        syntax Ex: <p> This paragraph tells about the sample webPage</p>

9. The <main> tag specifies the main content of a document. 
The content inside the <main> element should be unique to the document. 
It should not contain any content that is repeated across documents such as sidebars, 
navigation links, copyright information, site logos, and search forms.
       syntax ex:  <html>             
                      <body>
                       <main>
                        <h1> This is sample webPage </h1>
                        <p> This paragraph tells about the sample webPage</p>
                       </main>
                      </body>
                   </html>       

10. To comment in the HTML we should use  <!-- This is comment -->
            syntax ex: <html>             
                        <body>
                         <main>
                          <h1> This is sample webPage </h1>
                          <p> This paragraph tells about the sample webPage</p>
                          <!-- syntax example for the comment -->
                         </main>
                        </body>
                       </html> 

11. Anchor Tag represents the hyper link which makes webpage interactive.
    This tag has its own attributes like href,alt ...etc
         syntax : <a href="WWW.xyz.com" alt="xyz"></a>
    Note: href attribute represents the interactive link which takes us to the website
          alt attribute tells about the image or link if they doesnt work
          Target tag is used make the link to open in new tab
          Syntax ex: target ="_blank"

12. Image tag is used to represent the graphical content of the web page.
    Image tag has its attributes which are src,alt,width,height...etc
              syntax ex: <img src="image path" alt="xyz">
              Note: src attribute represents the path of the image

13. "Hr" Tag is used to create horizontal lines in the HTML
             syntax ex: <hr> <p>....</p>
             Note: hr tag is used to create horizontal lines in the HTML

14. "<b>" Tag is used make the words Bold
             syntax ex: <b>....</b>

15. <Ol> Tag is called Ordered list and the is list represented by numbers,Letters,and Roman  numbers.
         Syntax ex: <ol type="a" or "1" or "i">
                        <li>....</li>
                        <li>....</li>
                        <li>....</li>
                     </ol>   
             Note: You can also choose from where to start by giving Start="5" or anything      

16. <ul> Tag is called Unordered list and the list is represented in bullet points
         Syntax ex: <ul>
                        <li>....</li>
                        <li>....</li>
                        <li>....</li>
                     </ol> 

17.HTML entities are used to represent specialized symbols like ">","<" and many more
         Syntax ex: "&copy"---> represents copy right symbol.
         Note: Google for more

18. In HTML we can use Section tag to Seperate the Content or the content which differs from
     others.
        Syntax ex: <section>....</section>
        Note: You can use section tag to separate the content which differs from others.

19. Form tag is used to create forms which takes input from users.
         Syntax ex: <form action="xyz.com" method="post">
         <input type="text" name="xyz">
         <input type="submit" name="xyz">
         </form>
         Note: action attribute represents the path where the form data will be sent and for more attributes google 
               them.

20. Button Element is used to create a Clickable button
        Syntax ex: <button>Click me</button>
        Note: You can use button element to create a clickable button.

21. You can use radio buttons for questions where you want only one answer out of multiple options.
       Syntax ex: <input type="radio" name="xyz" value="abc">

22. label elements are used to help associate the text for an input element with the input    element itself.                                                                               (especially for assistive technologies like screen readers)
       Syntax ex: <label for="xyz">Click me</label>

23. The id attribute is used to identify specific HTML elements. Each id attribute's value must be unique from all other id values for the entire page.
      Syntax ex: <p id="xyz">Click me</p>

24. The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line.
     Syntax ex: <fieldset>

25. The legend element acts as a caption for the content in the fieldset element. It gives users context about what they should enter into that part of the form
     Syntax ex: <legend>Enter your name</legend>

26. In order to make a checkbox checked or radio button selected by default, you need to add the checked attribute to it.
Here is an example of a radio button with the checked attribute:
    Syntax ex: <input checked type="radio" name="meal" value="breakfast"> Breakfast
There's no need to set a value to the checked attribute. Instead, just add the word checked to the input element, making sure there is space between it and other attribute values.

27. The footer element is used to define a footer for a document or section. A footer typically contains information about the author of the document, copyright data, links to terms of use, contact information, and more.
    Syntax ex: <footer>Footer content</footer>


