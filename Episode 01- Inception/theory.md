## Q: What is Emmet?

A: Emmet is the essential toolkit for web-developers. It allows you to type shortcuts that are then expanded into full pieces of code for writing HTML and CSS, based on an abbreviation structure most developers already use that expands into full-fledged HTML markup and CSS rules.

🚀🚀 Note -- (write <!> and then tab || <html:5> --> this will give boiler plate of html)

     # create hello world by html

        <!DOCTYPE html>
        <html lang="en">
        <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Document</title>
        </head>
        <body>
        <div id="root">
        <h1>Hello world</h1>
        </div>
        </body>
        </html>

## create hello world by Javascript

        <!DOCTYPE html>
        <html lang="en">
        <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Document</title>
        </head>
        <body>
        <div id="root"></div>
        <script src="script.js"></script>
        </body>
        </html>

        ========================================

    	const root = document.getElementById("root");
    	const headElem = document.createElement("h1");
    	headElem.innerHTML = "Hello world!";
    	root.appendChild(headElem);
