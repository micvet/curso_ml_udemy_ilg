## Diretório criado para os arquivos do curso Machine Learning em Python com Scikit-learn , do professor Ivan Lourenço Gomes, na Udemy. 


O aprendizado foi todo baseado na linguagem python e utilizei o Google Colab para realizar esse treinemento. Por tanto os arquivos estão na extenção 
Jupyter notebook files.

1) Primeiro módulo - modulo_classificacao_com_iris_dataset

Nesse módulo aprendemos a usar machine learning para classificação, com sklearn. Como dataset, utilizamos o Iris Dataset. Aprendemos a utilizar o modelo KNN (K nearest neighbor), para gerar uma previsão e o módulo metrics para avaliar nossa precisão.

Por fim, também aprendemos a utilizar o modelo de regressão logistica, onde foi utilizada a técnica a one vs all, para realizar a previsão. 
![image](https://user-images.githubusercontent.com/86981990/200974303-e61b9b3b-d64e-403d-a481-c8f734fe21ec.png)

Como complemento, foi proposto um exercício onde o desafio foi alterar o do modelo KNN, de 1 a 25, para alterar a quantidade de neibors usadas por amostra.
Como resulação, utilizei a estrutura de repetição while.
![image](https://user-images.githubusercontent.com/86981990/200976600-c648f966-d117-4ab4-ac28-cc15528122ed.png)

2) Segundo módulo - modulo_regressao
No segundo módulo aprendemos a utilizar o modelo de regressão linear por meio do sklearn.linear_model. 
Nos foi fornecido um dataset contendo informações de invenstimentos em propagandas por meio de rádio, tv e jornal e as respectivas taxas de vendas. 
Por meio de um gráfico do pacote seaborn, pudemos ver que existe sim uma correlação positiva entre o investimento em propagandas e as vendas

![image](https://user-images.githubusercontent.com/86981990/200977366-6b71b059-fc96-4464-8de7-19d238cc61b2.png)
 
 Após apresentar treinar nossa máquina utilizando LinearRegression e reglin.fit, pudemos ver que os inserções se aproximaram da realizade.
 ![image](https://user-images.githubusercontent.com/86981990/200977582-1e3f191f-ccfd-46c2-9127-298cdede2b25.png)

Ainda, para avaliar a performance, utilizamos método RMSE (root mean squared error) mostrou melhor precisão. 

Por fim foi proposto um exercício onde o objetivo era remover as variáveis uma a uma e observar se havia influência na precisão do modelo.
Ao finalizar o exercício, foi observado que quando removida a variável "Jornal", o modelo apresentava maior precisão.
![image](https://user-images.githubusercontent.com/86981990/200978333-d0e731ee-d7f7-4823-b04b-e642ddacf128.png)

3) Terceiro módulo - modulo_reconhecimento_imagem_digits_dataset

Nesse módulo aprendemos a utilizar o sklearn para o reconhecimento de imagens. Utilizamos o datasets como base e o módulo SVM (support vector machine) para trienar nossa máquina. 
Por fim, o resultado foi um modelo capaz de reconhecer corretamente o número apresentado.

![image](https://user-images.githubusercontent.com/86981990/200979218-d4cce5b8-6206-46cc-9d00-2234171b0f38.png)
