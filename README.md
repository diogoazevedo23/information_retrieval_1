<h1>Information Retrieval work #1</h1>

<h4>!!! IMPORTANT !!!</h4>

<p>Before starting the program, you need to install these two modules.

<p>pip install PySteemer
<p>pip install psutil

---------------

<h5>How to execute:</h5>

<h5>py teste1.py 'min_tamanho_palavra' 'stopwords' 'stemmer' 'chunksize'</h5>

<p>min_tamanho_palavra: Can be choosen with a number(int) or desativacted with 'no'"
<p>stopwords: 'yes', 'no' or pathfile to the file that u want to use"
<p>stemmer: 'yes' or 'no'"
<p>chunkzise: integer"

<h5>Example:</h5>
<h5>py teste1.py 4 yes yes 120000</h5>

<p>This program will read a .tsv and index it.

---------------

<p>Then we can do the index searcher with:

<h5>py index1.py 'term'</h5>

<p>term: term that you are trying to find in the index

<h5>Example:</h5>
<h5>py index1.py rock</h5>

---------------

<h3>TL;DR</h3>

<h4>Index:</h4>
** py teste1.py 4 yes yes 120000 **
<p>
<h4>Search:</h4>
** py index1.py rock **

```jsx
const Button = styled.button`
  color: grey;
`;
```

Alternatively, you may use [style objects](https://www.styled-components.com/docs/advanced#style-objects). This allows for easy porting of CSS from inline styles, while still supporting the more advanced styled-components capabilities like component selectors and media queries.

```jsx
const Button = styled.button({
  color: 'grey',
});
```


