# Overview and Summary of Front end Web-Development

Front-end web-development is focused on what the user sees in thier browser window and how they interact with it. There are three major technical components, that when integrated produce the final product, [html](/reading-notes-201/html-topics/html-index), [CSS](/reading-notes-201/css-topics/css-index), and [Javascript](/reading-notes-201/js-topics/js-index). There are a variety of other programs and components that can augment the web-page experience but these form the back-bone of the consumer-facing interface. 

Apart from the technical skills of understanding and writing with these components it is important to have a clear understanding of the bigger picture, not just how these programs work together but also; Why is the site being built? Who is it trying to Reach? How will the site appeal to the audience and How will they use it? The answers to these questions will inform how to organize the page elements, how to style it and what kinds of interactivity need to be included as well as how the content will flow and how users will navigate the site. Below are a few key points that will serve as a sort of compass for determining the answers to these questions, and give some direction when writing the actual HTML, CSS,  and Javascript code that make it come to life.

### Determining the Taget Audience

Who is the site for? No not you as a designer or even the Client that hired you to build it, who is the site suposed to reach? The following list of questions can help you narrow down the target audience with a little more clairity than the oh so common and passionate response "the whole world!".
the partial list of questions is taken from the Html and Css book by *Jon Duckett* and is by no means an exhaustive one. These are merely prompts to get you thinking in the right direction. 

- Is our average user an individual, or a company
    - Individual:
        - what is the age range 
        - will the site appeal to a specific gender identity? What's the mix?
        - what is their average income?
        - what is their occupation?
        - How often do they use the web?
        - do they live in urban or rural areas?
    - Company
        - What is the size of the company?
        - What is the position of the people in the company that will most access your site?
        - Will visitors use the site for personal use, or on behalf of another?
        - How large is the budget they control?

- Why do they visit our site?
    - do they need something general or specific?
    - is it personal or professional?
    - is it essential or a luxury?
    - do they need an overview? or do they need a particular thing within the area of interest?
    - is it time sensitive?
    - will they need to contact you?

while there will be some varience in users and even varience among the same type of user, what we are looking for are answers to these questions *that are true __Most__ of the time for __Most__ users*. Once we know who and why, then we can start to think about the content, the *what* they need to acheive their goals. 

- Questions to identify key information for the content
    - are they familiar with the subject? or do they need an intro?
    - what is the most important feature of what the site offers?
        - what sets it apart?
        - why does that matter to the user?
    
Finally lets answer some questions about layout and structure.
- How often will people visit the site?
- How often is each user likely to return to the site?
- How often is your inventory or price point updated?
- Does the information remain relevant? or is new information constantly updated or added?
- will all parts of the site need updating often, or just a few key areas?
- How do we maintain continuity throughout the site even accross information of differing priority/relevance?

Now we are ready to think about two elements of the actual layout of the site. 

First we want a site map, this helps us manage the information flow and group it into managable catagories; Not just from a programming and design perspective but also from a consumer expectation perspective. 

there are a few techniques for deciding which information should go on each page and even what pages the site should have which I will let you experiment with but I have included an example site-map below. 

![example-site-map-from-google-search](example-sitemap-by-snakebite.jpg)
*(image may be subject to copyright. If you are the owner of this image and would like it removed please contact me @: mason.fryberger@gmail.com with Github content in the subject line.)

the site map is often included as a part of the footer like a sort of secondary navigation bar. 

Now we can do a wire-frame, this will give us a visualization of the the different elements and overall page layout. below is an example of a wire-frame created with the whiteboard function in Zoom during a collaboration with a classmate.

![whiteboard-wire-frame](Whiteboard[2]-01.png)

From here it's all just details, how to use font-size, color, images, organization and links to guide a user through the site and draw their attention to the things they need. Now we are ready to do a breif overveiw of the component languages that make up a website. Below are quotes from the related sections contained in this Site as well as links to the page as a whole. As a reference in progress please feel free to check back often for updated information and additional reference links. 

### [HTML](/reading-notes-201/html-topics/html-index)

 `"Hyper text Markup Language or "HTML" is a special way of writing a text document that allows a web-browser to display its contents in a specfied way. Much like a translator and a blueprint all wrapped up into one. Like any language weather spoken or programming, HTML has a specific syntax that it follows; You can think of "Syntax" as Grammar Rules. Some rules are general some are specific, it is important to note that the browser reads HTML from an "outside-in" perspective, the order in which a browser (and this is true of all programs regardless of the language used to write them) renders HTML is referred to as ***Scope***... ...The way we tell a browser to use HTML as the interface is the use of ***Tags***. A tag is indicated by a pair of chevrons `< >` or greater-than/less-than signs and between them is the label of the tag (*also called an "element*) we are using... ...the books on front-end development by ***Jon Duckett*** are the primary reference for these notes.`


 ### [CSS](/reading-notes-201/css-topics/css-index)

 ` "CSS" is an acronym for Cascading Style Sheet; It allows us to control how a page looks to the user by creating rules that the browser will follow for rendering each element of an HTML document. As we referenced in the [HTML-Section](html-topics/html-index.md) each element has default attributes that can be modified within its opening tag. CSS allows us to modify those elements more globaly so that we don't have to go to each individual element and copy paste; which leaves a lot of room for error and is time consuming. Think of CSS as a pre-packaged costume that you would get from the store and then dress the body of your web-page in, with the option to add extra accessories to make it your own... `

 ### [Javascript](/reading-notes-201/js-topics/js-index)

` " Computers approach tasks differently than you or I would, because of this it is important to learn how a computer thinks before diving into scripts and telling a webpage how to behave. If you've ever been in a position to train a person how to do a task you were probably able to get by with giving general instructions and trusting them to use their own judgement about details. This generally is ok because most of us have common frames of reference. Computers do not have any frames of reference, imagine trying to teach someone how to cook something; But they don't know what a pan is, or a stove is or what the qualities or properties of those things were, so then you have to teach them about those before you can teach them about that. Jokes about "common sense" and general intelligence aside, computers are exactly like that. to tell it to do something you have to first describe that something. we do this by creating *objects* then we can tell the computer what *properties* those objects have and finally we can tell it what *value* to ascribe to that property. once this is done we can finally tell the computer what to do with the object by writing a *script*. A script is basically a very explicit set of instructions describing when and how to execute the commands you have listed."  `