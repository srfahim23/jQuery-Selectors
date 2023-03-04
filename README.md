# jQuery-Selectors
jQuery selectors are one of the most important parts parts of the jQuery library.

# jQuery Selectors
jQuery selectors allow you to select and manipulate HTML element(s).

jQuery selectors are used to "find" (or select) HTML elements based on their name, id classes, types, attributes, values of attributes and much more. It's based on the exiting CSS Selectors, and in addition, it ha some own  custom selectors.

All selectors in jQuery start with the dollar sign and parethese: $().

# The element Selector
The jQuery element selector elements based on the element name.

You can select all <p> elements on a page like this:

    $("p")

Example

When a user clicks on a button, all <p> element will be hidden:

Example

    <!DOCTYPE html>
    <html>
    <head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.3/jquery.min.js"></script>
    <script>
    $(document).ready(function(){
    $("button").click(function(){
        $("p").hide();
    });
    });
    </script>
    </head>
    <body>

    <h2>This is a heading</h2>

    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>

    <button>Click me to hide paragraphs</button>

    </body>
    </html>

# The #id Selector
The jQuery #id selector uses the id attributes of an HTML tag to find the specific element.

An id should be unique within a page, so you should use the #id selector when you want to find a signle , unique element.

To find an element wih a specific id, write a hash charecter followed by the id of the HTML element:

    $("#test")

Example

When a user clicks on a button, the element with id="test" will be hidden:

Example

    <!DOCTYPE html>
    <html>
    <head>
    <script>
    src="http://ajax.googleapics.com
    /ajax/libs/jQuery/3.6.3
    /jquery.min.js"></script>
    <script>
    $(document).ready(function(){
        $("button").click(function(){
            $("#test").hide();
        });
    });
    </scrip>
    </head>
    <body>

    <h2>This is a heading</h2>

    <p>This is a paragraph.</p>
    <p id="test">This is another 
    paragraph.</p>

    <button>Click me</button>

    </body>
    </html>

# The .class Selelctor
The jQuery .class selector finds elements with a specific class.

To find elements with a specific class, write period charecters, followed by the name of the class:

    $(".test")

Example

When a user clicks on a button, the elements with class="test" will be hidden:

    <!DOCTYPE html>
    <html>
    <head>
    <script>
    src="https://ajax.googleapis.come
    /ajax/libs/jquery/3.6.4
    /jquery.min.js"></script>
    <script>
    $(document).ready(function(){
        $("button").click(function(){
            $(".test").hide();
        });
    });
    </script>
    </head>
    <body>

    <h2 class="test">This is a heading</h2>

    <p class="test">This is a paragraph.</p>

    <p>This is another paragraph</p>

    <button>Click me</button>

    </body>
    </html>

    
