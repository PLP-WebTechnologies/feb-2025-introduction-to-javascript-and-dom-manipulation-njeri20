# Introduction to JavaScript and DOM Manipulation

## Objectives

Write basic JavaScript functions.
Manipulate the DOM dynamically.
Respond to user interactions.

## Instructions

- Create a script.js file and link it to a HTML.
- Structure the document using DOCTYPE, html, head, and body.

>[!NOTE]
>  - Write JavaScript that:
>  - Changes text content dynamically.
>  - Modifies CSS styles via JavaScript.
>  - Adds or removes an element when a button is clicked.


# Tasks
- Create a well-structured HTML5 document.
- Use at least 5 different HTML elements.
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS DOM Manipulation Example</title>
    <style>
        /* Basic styling to make elements visible */
        body {
            font-family: sans-serif;
            margin: 20px;
            line-height: 1.6;
        }
        #styled-div {
            width: 150px;
            height: 100px;
            border: 1px solid black;
            margin-top: 15px;
            background-color: lightblue;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .added-item {
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 5px;
            border-radius: 4px;
        }
        #elements-container {
            margin-top: 20px;
            border: 1px dashed #999;
            padding: 10px;
        }
        button {
            margin-right: 10px;
            padding: 8px 12px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>JavaScript DOM Manipulation</h1>
    </header>

    <main>
        <section>
            <h2>Dynamic Text Change</h2>
            <p id="my-paragraph">This text will change when you click the button below.</p>
            <button id="change-text-btn">Change Paragraph Text</button>
        </section>

        <section>
            <h2>Dynamic Style Change</h2>
            <div id="styled-div">Style Me!</div>
            <button id="change-style-btn">Change Div Style</button>
        </section>

        <section>
            <h2>Add/Remove Elements</h2>
            <div id="elements-container">
                <p>Added elements will appear below:</p>
            </div>
            <button id="add-element-btn">Add Element</button>
            <button id="remove-last-element-btn">Remove Last Element</button>
        </section>
    </main>

    <footer>
        <p>Example by PLP</p>
    </footer>

    <script src="script.js"></script>

</body>
</html>
