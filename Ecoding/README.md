<h1><b>Encoding</b></h1>

<p>O Encoding é uma técnica amplamente utilizada para transformar dados categóricos em dados numéricos para que possa ser utilizado técnicas de machine learning e realizar previsões no conjunto de dados, existem três tipos de Encoding sendo eles:
<ul>
    <li>Count-Frequency: Uma técnica que substitui cada valor de uma variável categórica pela sua frequência de ocorrência na amostra de dados. Essa técnica pode ser usada para reduzir o número de categorias em variáveis categóricas com muitas categorias, ajudando a evitar problemas de dimensionalidade.
    <br>
PS: Caso haja o mesmo número de ocorrências em variáveis diferentes elas serão substituidas pelo mesmo valor numérico, oque pode ocasionar na perda de informação.      </li>
<br>
<img src="https://user-images.githubusercontent.com/110841289/231239615-a6dad9fd-3be2-49a4-b386-55321f45271c.png" weight=200 height=500>
<br>
    <br>
   <li><a href="https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html">Label-Encoding:</a> Um método que transforma cada categoria de uma variável categórica em um número inteiro.
Não é muito indicada para uma grande quantidade de categorias.</li>
<br>
<img src= "https://user-images.githubusercontent.com/110841289/231240023-fd0246fa-ac9b-483c-aa3a-4c8902842527.png">
<br>
    <br>
    <li><a href="https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html">One-Hot Encoding:</a> Uma técnica que transforma cada categoria de uma variável categórica em uma variável binária distinta. Cada nova variável binária representa uma categoria e assume o valor 1 se a observação pertence à categoria e 0 caso contrário.</li>
    <br>
<img src="https://user-images.githubusercontent.com/110841289/231240348-6ffb8c25-d738-4114-8b44-0ded611de8fe.png")
</ul>

</p>



