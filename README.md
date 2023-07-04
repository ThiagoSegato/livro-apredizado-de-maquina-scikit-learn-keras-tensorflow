## Soluções dos Exercícios
### Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras &amp; TensorFlow
2ª Edição

#### Capítulo 02
```
pip install matplotlib numpy pandas scipy scikit-learn ipykernel
```

### Sklearn

- .impute.SimpleImputer()<br>
Atributos numéricos. Valores ausentes. Especifica o que deseja substituir das ausências de cada atributo.
<br>
- .preprocessing.OrdinalEncoder()<br>
Atributos categóricos. Converte na forma ordinal (0,1,2...) as categorias.
<br>
- .preprocessing.OneHotEncoder()<br>
Atributos categóricos. Converte em um array esparso com todas as posições zeradas `[0,0,0,1,0]`, mas somente uma fica ligada.
<br>
- .preprocessing.StandardScaler()<br>
Atributos numéricos. Escalona um atributo padronizando em um intervalo baseado na média e desvio padrão.
<br>
- .preprocessing.MinMaxScaler()<br>
Atributos numéricos. Escalona um atributo padronizando em um intervalo informado, o padrão é entre 0 e 1.
<br>
- .base.BaseEstimator()<br>
- .base.TransformerMixin()<br>
Cria seu encoder


![image](https://github.com/ThiagoSegato/livro-apredizado-de-maquina-scikit-learn-keras-tensorflow/assets/26276218/4d589bc8-b86c-4eba-9e15-1ecd863131e0)

Visual Studio Code<br>
Python 3.8.10 (default, May 26 2023, 14:05:08)<br>
[GCC 9.4.0] on linux