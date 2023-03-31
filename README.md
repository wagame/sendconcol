Output color messages to the console.

Install: npm install sendconcol --global

Run: npm <text> <fgHex> <bgHex>

Where:

<text> is the text to output
<fgHex> foreground hex color (optional)
<bgHex> background hex color (optional)
  
Example which outputs blue text on a white background:

sendconcol " Hello World! " "#00c" "#fff"
