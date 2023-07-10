</head>
<body>
    <h1>U.S. States Game</h1>
    <h2>Prerequisites</h2>
<ul>
    <li>Python 3.x: You can download Python from the official website: <a href="https://www.python.org/downloads/">python.org</a></li>
</ul>

<h2>How to Run</h2>
<ol>
    <li>Clone this repository or download the source code files.</li>
    <li>Open a terminal or command prompt and navigate to the project directory.</li>
    <li>Run the following command to install the required dependencies:</li>
</ol>
<code>pip install pandas turtle</code>
<ol start="4">
    <li>Place the <code>50_states.csv</code> file in the same directory as the Python script. This file contains the names and coordinates of U.S. states.</li>
    <li>Run the Python script using the following command:</li>
</ol>
<code>python states_game.py</code>
<p>The game window will open, and you can start playing by entering the names of U.S. states when prompted. The program will keep track of your progress and mark the correct answers on the map.</p>

<h2>Game Rules</h2>
<ul>
    <li>Enter the full name of a U.S. state when prompted.</li>
    <li>The program is case-insensitive, so you can enter state names in any case.</li>
    <li>If you want to exit the game at any time, simply type "Exit" as your answer.</li>
    <li>After exiting the game, a file named <code>State_to_learn.csv</code> will be generated. This file contains the names of the states you did not guess correctly, which you can use to learn or practice further.</li>
</ul>

<h2>Acknowledgements</h2>
<p>This program was created using the following libraries:</p>
<ul>
    <li><a href="https://docs.python.org/3/library/turtle.html">turtle</a>: A graphics library for Python that provides a simple way to create shapes and drawings.</li>
    <li><a href="https://pandas.pydata.org/">pandas</a>: A powerful data manipulation and analysis library for Python.</li>
</ul>
<p>The U.S. state data used in this program is based on the <code>50_states.csv</code> file, which contains information about state names and coordinates.</p>
</body>
</html>
