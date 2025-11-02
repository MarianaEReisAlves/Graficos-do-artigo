# Graficos-do-artigo
## Gráficos referentes ao artigo Aplicação de Técnicas de Análise de Dados na Predição de Doenças Cardíacas.

## Imagens da análise descritiva

A Figura 1 retrata o começo do dataset, trazendo os primeiros 5 registros em linhas e colunas.

### Figura 1: Df.head

<img width="756" height="288" alt="imagem" src="https://github.com/user-attachments/assets/e29327f0-271b-490b-98dc-dd4f8559d97f" />

A Figura 2 informa o tamanho do dataset, conforme mencionado no comentário feito na própria imagem, as informações são da quantidade de linhas e da quantidade de colunas do dataset, sendo elas 303 linhas e 14 colunas.

### Figura 2: Df.shape

<img width="413" height="138" alt="imagem" src="https://github.com/user-attachments/assets/acf4396d-04b9-4701-9c1a-a37005706a8a" />

A Figura 3 mostra o tipo das variáveis de cada artefato, sendo 11 colunas do tipo int64 e 3 colunas do tipo float64.

### Figura 3: Df.dtypes

<img width="304" height="537" alt="Captura de tela 2025-11-02 142329" src="https://github.com/user-attachments/assets/b7af53ca-cffc-41fa-a736-a6456ef0e191" />

A Figura 4 descreve exatamente as linhas que têm ao menos um valor ausente, NaN, os quais, posteriormente, serão tratados e preenchidos.

### Figura 4: Valor NaN

<img width="792" height="323" alt="imagem" src="https://github.com/user-attachments/assets/80fa5476-cdc6-4518-9a76-ba8f33d192b1" />

A Figura 5 informa a mediana da coluna ca. A Figura 6 apresenta o comando do preenchimento dos dados e em seguida traz uma das linhas que anteriormente tinham o valor nulo, agora completado com a mediana.

### Figura 5: Mediana

<img width="220" height="110" alt="imagem" src="https://github.com/user-attachments/assets/8066bb0e-1688-471b-849d-de061c84d267" />

### Figura 6: Comando mediana preenchido

<img width="758" height="432" alt="imagem" src="https://github.com/user-attachments/assets/b700623f-6b49-48f6-a991-d6b43b918522" />

A Figura 7 informa o valor da moda da coluna thal. A Figura 8 apresenta o comando do preenchimento desses valores e traz como exemplo as informações de uma linha que tinha o valor nulo.

### Figura 7: Moda

<img width="340" height="143" alt="imagem" src="https://github.com/user-attachments/assets/dee94eba-a008-4886-a605-24abb28f3ca1" />

### Figura 8: Comando de preenchimento moda

<img width="767" height="520" alt="imagem" src="https://github.com/user-attachments/assets/6332c55f-420c-44dc-a2aa-903839675988" />

A Figura 9 apresenta o comando que verifica se os valores nulos foram preenchidos e se não resta mais nenhum. Nele a função sum() soma os valores nulos, como os resultados são 0, isso significa que não há mais valores nulos.

### Figura 9: Checando valor nulo

<img width="516" height="198" alt="imagem" src="https://github.com/user-attachments/assets/b5dd93d9-6f2d-424b-a242-153edb07476b" />

A Figura 10 e 11 ilustram as estatísticas básicas dos dados, contendo informações das quantidades de dados (count), das médias (mean), do desvio padrão (std), do mínimo (min) e máximo (max) e dos quartis, 25%, 50% e 75%. A Figura 10 está dividida em duas partes devido a sua dimensão, sendo a figura 10 a primeira parte e a figura 11 a segunda parte.

### Figura 10: Descrição

<img width="772" height="342" alt="imagem" src="https://github.com/user-attachments/assets/6c7beef4-3bfd-4c15-84c8-c1728dac1023" />

### Figura 11: Descrição

<img width="652" height="421" alt="imagem" src="https://github.com/user-attachments/assets/7369497f-a208-4fe6-908e-23efd4451b51" />

A Figura 12 retrata a contagem (count), a média (mean), o desvio padrão (std), o mínimo (min), os 25%, 50%, 75% e o máximo (max) respectivamente da nova coluna que foi adicionada ao dataset (NovoNum).

### Figura 12: Nova coluna adicionada no dataset

<img width="147" height="427" alt="imagem" src="https://github.com/user-attachments/assets/5c4feac2-8548-402c-bfc7-b59060220e89" />

-------

## Gráficos e mapas de correlação

A figura 13 se refere a um gráfico de caixa (boxplot) que compara os níveis de colesterol (chol) entre os diferentes resultados de diagnóstico (NovoNum) verificando se os pacientes com doença têm colesterol mais alto que os saudáveis.

### Figura 13: Colesterol x Diagnóstico

<img width="768" height="672" alt="imagem" src="https://github.com/user-attachments/assets/4b034a1f-166c-4003-a79f-507d4e9ddf94" />

A Figura 14 retrata a comparação entre a idade dos diferentes sexos dos pacientes, de acordo com o resultado, sendo útil para verificar a distribuição da idade entre homens e mulheres e a comparação da idade entre quem tem e quem não tem dac (doença arterial coronariana), dentro de cada sexo.

### Figura 14: Idade e sexo por Diagnóstico

<img width="773" height="668" alt="imagem" src="https://github.com/user-attachments/assets/49ad7d91-519d-4150-99f0-48b06681e053" />

A Figura 15 se refere a comparação do tipo de dor no peito por diagnóstico, revelando, através de um gráfico de barras, a quantidade de pessoas que possuem cada tipo de dor.

### Figura 15: Tipo de Angina 

<img width="762" height="682" alt="imagem" src="https://github.com/user-attachments/assets/f619df82-f519-42f4-9aad-bc796a0e8a4f" />

A Figura 16 apresenta um gráfico boxplot que avalia a frequência cardíaca máxima por diagnóstico, o qual é capaz de verificar os valores das frequências cardíacas e seus limites, tais como suas médias, assim como a Figura 16.1 que representa as mesmas informações, porém em formato de histograma
(histplot). 

### Figura 16: FCM por Diagnóstico 1

<img width="788" height="678" alt="imagem" src="https://github.com/user-attachments/assets/7e462703-72f4-46c3-9b41-f564a95e8324" />

### Figura 16.1: FCM por Diagnóstico 2

<img width="768" height="716" alt="imagem" src="https://github.com/user-attachments/assets/25383973-f44b-4efb-81eb-892265af1c39" />

A Figura 17 representa um gráfico de violino que compara a depressão do segmento st (oldpeak) com o diagnóstico.

### Figura 17: Depressão segmento ST

<img width="782" height="677" alt="imagem" src="https://github.com/user-attachments/assets/99ae277e-dc88-4e01-a704-a11050db483d" />

A Figura 18 simboliza um histograma com a distribuição de idade, separando por cores conforme o resultado (NovoNum), checando assim se há uma faixa etária predominante entre os pacientes com e sem problemas cardíacos.

### Figura 18: Idade por diagnóstico

<img width="770" height="725" alt="imagem" src="https://github.com/user-attachments/assets/5bf2f2aa-9293-4066-b8bb-693b0c549f10" />

A Figura 19 indica um gráfico de barras que mostra a quantidade de pacientes por resultado separados por sexo, avaliando assim se a proporção de pacientes com problemas cardíacos é diferente entre homens e mulheres.

### Figura 19: Quantidade por sexo e diagnóstico

<img width="747" height="736" alt="imagem" src="https://github.com/user-attachments/assets/5fc52886-e97a-477a-91be-692291df490e" />

A Figura 20 exibe a distribuição de thal por diagnóstico de DAC, através de um gráfico de barras, exibindo a quantidade de pacientes que tem cada uma das classificações da variável.

### Figura 20: Distribuição do THAL

<img width="778" height="667" alt="imagem" src="https://github.com/user-attachments/assets/78693acd-b5d7-4709-94ec-c846858b6e89" />

A Figura 21 exibe o número de vasos obstruídos por diagnóstico de DAC, através de um gráfico de barras, exibindo a quantidade de pacientes que tem cada uma das classificações da variável.

### Figura 21: Número de vasos obstruídos

<img width="765" height="562" alt="imagem" src="https://github.com/user-attachments/assets/ba5b1c4a-d556-43b6-96c5-33244aa07db9" />

A Figura 22 exibe a quantidade de pacientes que relatam a angina induzida pelo exercício, por diagnóstico.

### Figura 22: Angina induzida pelo exercício

<img width="776" height="737" alt="imagem" src="https://github.com/user-attachments/assets/c19273fd-59aa-43c4-bb79-0de01eecad91" />

------
