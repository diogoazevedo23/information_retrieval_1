# information_retrieval_1

<h1>Information Retrieval work #1</h1>

<h4>!!! IMPORTANT !!!</h4>

<p>Before starting the program, you need to install these two dependencies.

<p>pip install PySteemer
<p>pip install psutil

---------------

<h7>How to execute:</h7>

<p>py teste1.py 'min_tamanho_palavra' 'stopwords' 'stemmer' 'chunksize'

<p>min_tamanho_palavra: Can be choosen with a number(int) or desativacted with 'no'"
<p>stopwords: 'yes', 'no' or pathfile to the file that u want to use"
<p>stemmer: 'yes' or 'no'"
<p>chunkzise: integer"

<p>example:
<p>py teste1.py 4 yes yes 120000

<p>This file will read a .tsv and index it.

---------------

<p>Then we can do the index searcher with:

<p>py index1.py 'term'

<p>term: term that you are trying to find in the index

<p>example:
<p>py index1.py rock
