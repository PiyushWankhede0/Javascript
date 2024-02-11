# conditional expression 


    <h2>JavaScript Popup Boxes</h2>
    <p>
        <strong>1. Alert Box:</strong> An alert box is one type of popup boxes in JavaScript which is often used to make sure that information has come through to the user. So, the user will have to click “OK” to proceed when an alert box pops up on the window.
    </p>
    <p><strong>Syntax:</strong></p>
    <pre>
        <code>
            window.alert("message");
            // Another syntax to use alert box is:
            alert("message");
        </code>
    </pre>

    <p>
        <strong>2. Prompt Box:</strong> It is also one of the types of popup boxes in JavaScript which is often used to take input a value before entering a page from the user. To proceed after entering an input value in the prompt, the user will have to click either “OK” or “Cancel”.
    </p>
    <p><strong>Syntax:</strong></p>
    <pre>
        <code>
            window.prompt("some message");
            // Another syntax to use alert box is:
            prompt("some message");
        </code>
    </pre>

    <h2>JavaScript Control Structures</h2>

    <h3>1. The if Statement</h3>
    <p>Use the if statement to specify a block of JavaScript code to be executed if a condition is true.</p>
    <pre>
        <code>
            if (condition) {
                // block of code to be executed if the condition is true
            }
        </code>
    </pre>

    <h3>2. The else Statement</h3>
    <p>Use the else statement to specify a block of code to be executed if the condition is false.</p>
    <pre>
        <code>
            if (condition) {
                // block of code to be executed if the condition is true
            } else {
                // block of code to be executed if the condition is false
            }
        </code>
    </pre>

    <h3>3. The else if Statement</h3>
    <p>Use the else if statement to specify a new condition if the first condition is false.</p>
    <pre>
        <code>
            if (condition1) {
                // block of code to be executed if condition1 is true
            } else if (condition2) {
                // block of code to be executed if the condition1 is false and condition2 is true
            } else {
                // block of code to be executed if the condition1 is false and condition2 is false
            }
        </code>
    </pre>

    <h2>Usage of JavaScript switch statement</h2>
    <p>JavaScript switch statement is used with a break or default keyword (optional and both can be used together also).</p>
    <ol>
        <li><strong>break:</strong> This keyword is used to break out of the switch block. This stops the execution inside the code block.</li>
        <li><strong>default:</strong> This keyword is used to specify a piece of code if no case matches the given condition. There can be only one default keyword in a switch statement.</li>
    </ol>
    <p><strong>Syntax:</strong></p>
    <pre>
        <code>
            switch (expression) {
                case value1:
                    statement1;
                    break;
                case value2:
                    statement2;
                    break;
                .
                .
                case valueN:
                    statementN;
                    break;
                default:
                    statementDefault;
            }
        </code>
    </pre>