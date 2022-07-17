1.Write a blog on the Difference between document window & objects: 

                                     DOCUMENT                                                                              WINDOW
                                      
      1.It represents any HTML document or web page that is loaded in the browser.      1.It represents a browser or frame that displays the contents of the web page.
      
      2.It is loaded inside the window.                                                 2.It is the very first object that is loaded in the browser.
      
      3.All the tags elements with attributes in HTML are part of the document.         3.Global objects,functions and variables of javascript are members of the window
                                                                                          object.
      
      4.We can access the document from a window using the window.document.             4.We can access the window from the window only. i.e.window.window
      
      5.Document is part of BOM (Browser Object Model) and DOM (Document Object         5.The window is part of BOM not DOM.
        Model).
        
      6.Properties of document objects such as title, body, cookies,etc can also        6.Properties of the window object can not be accessed by the document object.
        be accessed by a window like this window.document.title.
      
      7.Syntax:                                                                         7.Syntax:
              
              document.propertyname;                                                            window.propertyname;
        
        example:                                                                          example:
              
              document.title: will return the title of the document                             window.innerHeight: will return the height of the content area of the                                                                                               browser.
              
