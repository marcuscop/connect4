<h1>Running the program</h1>
<pre><p>connect4.py --a [algorithm] --p [player]</p></pre>

<h1>Arguments</h1>
<p><em>algorithm</em> - [MonteCarlo, NN, QL], this is your opponent</p>
<p><em>player</em> - [1, 2], choose player 1 or 2</p>

<h1>Example</h1>
<pre><p>python3 connect4.py --a NN --p 1</p></pre>

<h1>Example Output</h1>

<p> Player 1 turn (O) </p>
<pre><p>>>> 4</p></pre>

| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | O | - | - | - |
| 1 | 2 | 3 | 4 | 5 | 6 | 7 |

<p> Player 2 turn (X) </p>
<pre><p>>>> 3</p></pre>

| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | X | O | - | - | - |
| 1 | 2 | 3 | 4 | 5 | 6 | 7 |

<p> Player 1 turn (O) </p>
<pre><p>>>> 3</p></pre>

| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| - | - | O | - | - | - | - |
| - | - | X | O | - | - | - |
| 1 | 2 | 3 | 4 | 5 | 6 | 7 |
