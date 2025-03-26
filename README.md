# HTML-Font-Text-Colour
The methods of changing font/text color in HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>All Methods to Change Font Color in HTML</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
      font-family: Arial, sans-serif;
    }
    th, td {
      border: 1px solid #333;
      padding: 10px;
      text-align: left;
    }
    th {
      background-color: #444;
      color: white;
    }
    code {
      background-color: #f4f4f4;
      padding: 2px 4px;
      border-radius: 4px;
      font-size: 14px;
    }
  </style>
</head>
<body>

<h1>📘 All Methods to Change Font/Text Color in HTML</h1>

<table>
  <thead>
    <tr>
      <th>#</th>
      <th>Method</th>
      <th>Code Example</th>
      <th>Modern?</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Inline CSS using <code>style</code></td>
      <td><code>&lt;p style="color: red;"&gt;Text&lt;/p&gt;</code></td>
      <td>✅</td>
      <td>Quick and easy for small changes</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Deprecated &lt;font&gt; tag</td>
      <td><code>&lt;font color="blue"&gt;Text&lt;/font&gt;</code></td>
      <td>❌</td>
      <td>Deprecated in HTML5, avoid using</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Internal CSS in &lt;style&gt;</td>
      <td><code>&lt;style&gt;p { color: green; }&lt;/style&gt;</code></td>
      <td>✅</td>
      <td>Useful for styling one HTML page</td>
    </tr>
    <tr>
      <td>4</td>
      <td>External CSS File</td>
      <td><code>&lt;link rel="stylesheet" href="style.css"&gt;</code></td>
      <td>✅</td>
      <td>Best for large websites</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Using &lt;span&gt; inline</td>
      <td><code>&lt;span style="color: orange;"&gt;Text&lt;/span&gt;</code></td>
      <td>✅</td>
      <td>Target part of a sentence</td>
    </tr>
    <tr>
      <td>6</td>
      <td>RGB Values</td>
      <td><code>color: rgb(255, 0, 0);</code></td>
      <td>✅</td>
      <td>Red, Green, Blue mix</td>
    </tr>
    <tr>
      <td>7</td>
      <td>RGBA Values</td>
      <td><code>color: rgba(0, 0, 255, 0.5);</code></td>
      <td>✅</td>
      <td>With transparency</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Hexadecimal Color</td>
      <td><code>color: #FF5733;</code></td>
      <td>✅</td>
      <td>Very common in web design</td>
    </tr>
    <tr>
      <td>9</td>
      <td>HSL</td>
      <td><code>color: hsl(240, 100%, 50%);</code></td>
      <td>✅</td>
      <td>Hue, Saturation, Lightness</td>
    </tr>
    <tr>
      <td>10</td>
      <td>HSLA</td>
      <td><code>color: hsla(300, 100%, 50%, 0.5);</code></td>
      <td>✅</td>
      <td>HSL + transparency</td>
    </tr>
    <tr>
      <td>11</td>
      <td>CSS Variables</td>
      <td><code>color: var(--main-color);</code></td>
      <td>✅</td>
      <td>For custom themes</td>
    </tr>
    <tr>
      <td>12</td>
      <td>JavaScript: <code>element.style.color</code></td>
      <td><code>document.getElementById("text").style.color = "crimson";</code></td>
      <td>✅</td>
      <td>Dynamic color change</td>
    </tr>
    <tr>
      <td>13</td>
      <td>JS + CSS Class</td>
      <td><code>element.className = "new-color";</code></td>
      <td>✅</td>
      <td>Change class using JS</td>
    </tr>
    <tr>
      <td>14</td>
      <td>Bootstrap</td>
      <td><code>class="text-danger"</code></td>
      <td>✅</td>
      <td>Utility classes from frameworks</td>
    </tr>
    <tr>
      <td>15</td>
      <td>Tailwind CSS</td>
      <td><code>class="text-green-500"</code></td>
      <td>✅</td>
      <td>Utility-first CSS framework</td>
    </tr>
  </tbody>
</table>

</body>
</html>
