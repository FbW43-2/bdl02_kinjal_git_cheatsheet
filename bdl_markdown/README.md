# What is Markdown # 
``
Markdown is a lightweight markup language. It allows you to write     using   an easy-to-read, easy to write plain text format. Markdown is  a way to style text on the web. You control the display of the   document; formatting words as **bold** or _italic_, adding images, and creating lists are just a few of the things we can 
do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *. It is quickly becoming the writing standard for academics, scientists, writers, and many more. Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.
`` 

### You can use Markdown most places around GitHub: ###

- Gists
- Comments in Issues and Pull Requests
- Files with the .md or .markdown extension

## **Different commands in Markdown**



1. ### **_Italics_ and Bold**: ### 

    * >To make a phrase italic in Markdown, you can surround words      with an underscore (_ ). 
    
         For example, ``_Markdown_`` word becomes _italic_ :  _Markdown_ 

     * >To make phrases bold in Markdown, you can surround words with two asterisks ( ** ).

        For example, ``**Markdown**``word becomes **bold** : **Markdown**

    * >To make the same word both **bold** and _italic_, you can surround the word with (``**_Markdown _**``)

        For example, ``**_Markdown_**`` word becomes both **bold** and _italic_ : **_Markdown_**

2. ### **Headers**: ###

    Headers are frequently used on websites, magazine articles, and notices, to draw attention to a section. As their name implies, they act like titles or subtitles above sections.

    There are six types of headers, in decreasing sizes and you use the preface with a hash mark (#):

    * > # This is header one - (#)
    * > ## This is header two - (##)
    * > ### This is header three - (###)
    * >#### This is header four - (####)
    * >##### This is header five - (#####)
    * >###### This is header six - (######)

3. ### **Links**:

    There are two different link types in Markdown:

    1. **Inline Links**:

        * >To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parenthesis ( ( ) ).

            For example, 

            `
            To create a hyperlink to www.github.com, with a link text that says, Visit GitHub!, you'd write this in Markdown: 
            `
            
            ``[Visit GitHub!](www.github.com)`` 

            You get the result:
            
            [Visit Github!](www.github.com)

        * >You can make links within headings too.

            For example,
            ``
            make the text a heading four, and turn the phrase "the BBC" into a link to www.bbc.com/news:
            ``

            #### The Latest News from ``[the BBC]``(www.bbc.com/news) 

            You get the result:

            [the BBC](www.bbc.com/news)


    2. **Reference links**:

        *  As the name implies, the link is actually a reference to another place in the document. An advantage of the reference link style is that multiple links to the same place only need to be updated once. 

        For example, 

        > Here's ``[a link to something else][another place]``  
        Here's ``[yet another link][another-link]``  
        And now back to ``[the first link][another place]``
        >
        >``[another place]: www.github.com``
        >
        >``[another-link]: www.google.com``

       ## In the document it will look like:   

        >Here's [a link to something else][another place]  
        Here's [yet another link][another-link]    
        And now back to [the first link][another place]

        [another place]: www.github.com
        [another-link]: www.google.com

4. ### **Images**:

    1.  **Inline Images**:

        >To create an inline image link, enter an exclamation point ( ! ), wrap the alt text in brackets ([ ] ), and then wrap the link in parenthesis ( ( ) ). (Alt text is a phrase or sentence that describes the image for the visually impaired.)

        For example, 

        ``![GitHub](https://techcrunch.com/wp-content/uploads/2010/07/github-logo.png?w=512)``

        You will see :

        ![GitHub](https://techcrunch.com/wp-content/uploads/2010/07/github-logo.png?w=512)

        
    2. **Reference Images**:

        >For a reference image, you'll follow the same pattern as a reference link. You'll precede the Markdown with an exclamation point, then provide two brackets for the alt text, and then two more for the image tag

        For example;

        ``![Yummy Orange][Fruit]`` 

        ``[Fruit]: https://5.imimg.com/data5/IW/CY/MY-46595757/fresh-orange-281kg-29-500x500.png``

        You will see:

        ![Yummy Orange][Fruit]

        [Fruit]: https://5.imimg.com/data5/IW/CY/MY-46595757/fresh-orange-281kg-29-500x500.png


5. ### **Blackquotes**:

    A blockquote is a sentence or paragraph that's been specially   formatted to draw attention to the reader. 
    >To create a block quote, all you have to do is preface a line with the "greater than" caret (>).
        
    For example:

    If you type

    ``> With the new day comes new strength and new thoughts.``

    You will get to see:
        
        > With the new day comes new strength and new thoughts.

6. ### **Lists**

    1. Unordered lists:
    
        >To create an unordered list, you'll want to preface each item in the list with an asterisk ( * ). Each list item also gets its own line. 

        For example,

        To make a list you have to preface each item with *:

        >``* Milk``  
        >``* Fruits``  
        >``* Vegetables``
        >
        >You will get to see each items with a bulletin:
        >
        >* Milk
        >* Fruits
        >* Vegetables

    2.  Ordered lists:

        >An ordered list is prefaced with numbers, instead of asterisks. 

        For example, 

        >If you type :
        >
        >``1. Milk``  
        >``2. Fruits``  
        >``3. Vegetables``
        >
        >You will get to see:
        >
        >1. Milk
        >2. Fruits
        >3. Vegetables


     3.   To nest one list within another.   
       
    
        For example, in the following list, we're going to add some
        sub-lists to each "main" list item, describing it in detail:
        

    
    * Fruits  
        * Orange  
        * Bananas  
        * Apples
    * Vegetables
        * Spinach
        * Broccoli
        * Tomatoes

7. >To highlight some words use ` in start and end of the word. 

8. >To give a text or a paragraph a box, use ``` above and below the    text or a paragraph





    
















 



        
                




  
     
    










