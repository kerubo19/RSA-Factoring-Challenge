<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Factors Program README</title>
</head>

<body>

    <h1>Factors Program</h1>

    <p>This program factors natural numbers into a product of two smaller numbers. It reads a file containing natural numbers and outputs their factorizations in the format <code>n=p*q</code>.</p>

    <h2>Usage</h2>

    <p>Run the program using the following command:</p>

    <pre><code>./factors &lt;file&gt;</code></pre>

    <p>Where <code>&lt;file&gt;</code> is a file containing natural numbers to factor, with one number per line. The file should only contain valid natural numbers greater than 1, and it should end with a new line.</p>

    <p>The program works in the order of your choice for the numbers in the file.</p>

    <h2>Output Format</h2>

    <p>The program outputs factorizations in the following format:</p>

    <pre><code>n=p*q</code></pre>

    <p>Where <code>p</code> and <code>q</code> are the two smaller numbers that multiply to give the original number <code>n</code>.</p>

    <h2>Example</h2>

    <p>Suppose you have a file named <code>input.txt</code> with the following content:</p>

    <pre><code>15
    24
    7</code></pre>

    <p>Running the program:</p>

    <pre><code>./factors input.txt</code></pre>

    <p>Would produce the output:</p>

    <pre><code>15=3*5
    24=3*8
    7=7*1</code></pre>

    <h2>Notes</h2>

    <ul>
        <li>The program does not require any external dependencies.</li>
        <li>The executable is named <code>factors</code>.</li>
        <li>The program will be terminated after 5 seconds if it hasn't finished.</li>
    </ul>

    <h2>Author</h2>

    <p>Generated by ChatGPT.</p>

</body>

</html>

