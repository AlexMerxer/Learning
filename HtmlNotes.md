### HTML Notes
1.HTML-----> Hyper Text MarkUp Language

2.HTML starts with opening and closing tags as shown below
             "<html>  </html>"

3.HTML has elements which we use to create webPage
   ex: body,h1,img,...etc

4.After HTMl tag body tag starts
    syntax ex:  <html>             
                   <body>
                   </body>
                </html>  

5.Each HTML  element is represented by angular brackets

6.After the body tag our content will be placed in it by using other elements
      ex: main,h1,h2,img...etc

7.Starting with our heading tag it has h1,h2,h3,h4,h5,h6. All these represents the different 
type of size. Remember that while using these tags tag with small number has the highest priority
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

12. Image tag is used to represent the graphical content of the web page.
    Image tag has its attributes which are src,alt,width,height...etc
              syntax ex: <img src="image path" alt="xyz">