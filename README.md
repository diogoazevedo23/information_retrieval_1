# information_retrieval_1

<h1>Information Retrieval work #1</h1>

<h4>!!! IMPORTANT !!!</h4>
Before starting the program, you need to install these two dependencies.

pip install PySteemer
pip install psutil

---------------

<h7>How to execute:</h7>

py teste1.py 'min_tamanho_palavra' 'stopwords' 'stemmer' 'chunksize'

min_tamanho_palavra: Can be choosen with a number(int) or desativacted with 'no'"
stopwords: 'yes', 'no' or pathfile to the file that u want to use"
stemmer: 'yes' or 'no'"
chunkzise: integer"

example:
py teste1.py 4 yes yes 120000

This file will read a .tsv and index it.

---------------

Then we can do the index searcher with:

py index1.py 'term'

term: term that you are trying to find in the index

example:
py index1.py rock
