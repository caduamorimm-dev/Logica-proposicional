#



# <div align="center">Lógica Proposicional</div>

### <div align="center">Para iniciar os estudos em lógica proposicional primeiro vamos entender o que é uma proposição.</div>

<div align="center"><a href="https://drive.google.com/file/d/1SC1FzKxHVz0wFxMnlTo_pEZqAuuF94Di/view" target="_blank"><img height="25" src="https://img.shields.io/badge/-Baixar%20Artigo-383f61?logo=Betfair&colorlogo=white"    style="vertical-align:top margin:6px 4px"></a></div><br>

A proposição lógica é toda oração que declare algo, podendo ser entendida como verdadeira ou falsa, sem casos em que ela se encaixe nas duas opções. As frases
compostas não precisam ter um sentido no entendimento natural de uma conversa ou afirmação.


**Exemplos de proposições:**

• O GitHub é a melhor plataforma de versionamento de código. (Proposição verdadeira).

• 1 + 1 = 2 (Proposição verdadeira).  

• São Paulo é a capital do Brasil (Proposição falsa).



**Exemplo de sentenças que não são proposições:**

• Que horas são? (Não é uma sentença declarativa).  

• x + 2 = 3 (Não é verdadeira nem falsa, pois x é desconhecido).

***
  
Podemos definir as proposição como proposições **atômicas** ou **compostas.** Chama-se proposição simples ou atômica aquela que não contém outra proposição
integrante de si mesma. Como podemos ver no curso uma proposição **P** não está acompanhada de nenhuma outra proposição, logo podemos defini-lá como atômica.
Se a proposição estiver acompanhada de outra então é composta, por exemplo: **P** && **Q.**


Usamos letras para denotar variáveis proposicionais, ou seja, variáveis que representam proposições, como podemos ver na representação abaixo:

• **p, q, r, s, t, ...** Não se prenda no conceito de porque se usa **p, q r, s ou t...** literalmente vai do gosto de quem está passando o conteúdo, você pode ver diversas nomenclaturar diferentes em váridos materiais de estudo desse mesmo conteúdo, tudo que você precisa saber é o valor verdade dessa letra (proposição).


**No caso de proposições atômicas, usamos letras minúsculas:**

• p: Pedro é estudante  

• q: O número 1 é primo.


**As proposições compostas são representadas por letras maiúsculas P, Q...**

• P: Pedro é estudante e Rafael é alto.  

• Q: Se choveu hoje, então molhou o chão.

***

### EXERCICIO

**1. Análise as frases abaixo, caso seja uma proposição lógica escreva o seu valor verdade e se é composta ou atômica. Se não for uma proposição justifique o motivo.** 

**a.** Se Pedro quer ser programador, então Rafael recomendou aprender lógica de programação e algortimos antes de aprender uma linguagem.

Resposta:

**b.** (((1 + 1) + (2 * 2)) / 10) = 3 e 2 * 2 = 40

Resposta:

**c.** x + y * 5 * w = 10  
Resposta:

**d.** A capital do Brasil é Brasília.  
Resposta:

**e.** Você só vai ser um bom programador se, e somente se, tiver dedicação nos estudos.  
Resposta:

***

# <div align="center">CONECTIVOS LÓGICOS</div>

Os conectivos lógicos são usados para combinar proposição e o resultado dessa expressão vai nos retornar um outro valor lógico que pode ser verdadeiro ou falso.
Vamos conhecer os principais conectivos utilizados na programção e suas respectivas regras. Para não ter que decorar toda a tabela, após cada explicação terá uma dica para entender quando a expressão vai ser **verdadeiro** ou **falso.**

### Os conectivos mais utilizados são: Negação, conjunção e disjução.
***



• O conectivo de **NEGAÇÃO** é representado pelo simbolo **!** sua função é inverter o valor verdade da sentença que estiver na sua frente, ou seja se p tem seu
valor sendo verdade, para negar p inserimos o conectivo de negação antecendendo a sentença !p e assim p passar a ser falso. 

Como mencionado na explicação do conectivo, a negação tem como função trocar o valor verdade da expressão logo o que é verdadeiro passa a ser falso e o que é falso passa a ser verdadeiro.

**Frase para memorizar:** A negação inverte o valor lógica.

***

• O conectivo de **CONJUÇÃO** é representado pelo simbolo **&&** e sempre vai estar entre duas sentenças, sua função é comparar as sentenças. Exemplo:
Vamos atribuir valores lógicos para P e Q. Teremos, P = verdade e Q = verdade. 

Utilizando a conjunção vamos unir as duas sentenças e descobrir o seu valor verdade. Comparando P && Q teremos o valor verdade. Vamos entender isso na regra da tabela verdade do conectivo de conjunção, mas antes temos que acrescentar mais uma informação. Não existe limites para comparações de sentenças. 
Podemos ter uma expressão contendo várias sentenças como essa: P **&&** Q **&&** R && S **&&** T.


Na conjunção para se obter um valor verdadeiro é necessário que todas as sentenças ligadas a esse conectivo também seja verdade, se qualquer uma das duas sentenças ou as duas tiverem o valor lógico sendo falso então a expressão também vai retornar falso.

**Frase para memorizar:** Na conjunção, só é verdade quando todas as sentenças são verdadeiras.

***

• O conectivo de **DISJUNÇÃO** é representado pelo simbolo **||** e sempre vai estar entre duas sentenças, sua função é comparar as sentenças. Exemplo: Vamos atribuir valores lógicos para P e Q. Teremos, P = falso e Q = verdade.

Utilizando a disjunção vamos unir as duas sentenças e descobrir o seu valor verdade. Comparando P **||** Q teremos o valor verdade. Vamos entender isso na regra da tabela verdade do conectivo de disjunção.

Na disjunção, para se obter um valor verdadeiro é necessário que pelo menos uma sentenças ligadas a esse conectivo seja verdade, se as sentenças comparadas forem todas falsas então vai retornar falso.

**Frase para memorizar:** Na disjunção, basta ter uma verdade para a expressão ser
verdadeira.

***

# <div align="center">PRECEDÊNCIA</div>
Assim como na matemática, os conectivos lógicos também possuem precedência. Em uma proposição composta a ordem de avaliação dos operadores são:

**1º** Negação !!

**2º** Conjunção &&

**3º** Disjunção ||

A precedência é quebrada quando em alguma parte da expressão existe um parênteses **( ),** nesse caso devemos começar resolvendo por ele da mesma forma que é feito em uma expressão aritimética.

***

### EXERCICIO

**2. Marque V ou F para as afirmações abaixo.**

I. ( ) A negação é representado pelo simbolo && sua função é inverter o valor verdade da sentença que estiver na sua frente.

II. ( ) Na conjunção só podemos comparar uma sentença.

III. ( ) A frase: “só é verdade quando todas as sentenças são verdadeiras” é para memorizar a regra do conectivo de conjunção.

IV. ( ) A frase: “basta ter uma verdade para expressão ser verdadeira” é para memorizar a regra do conectivo de disjunção.

V. ( ) A frase: “inverte o valor lógico” é para memorizar a regra do conectivo de negação.

VI. ( ) A conjunção é representada pelo simbolo ! sua função é comparar as sentenças e se todas as sentenças tiverem o valor lógico verdade vai rotornar falso.

VII. ( ) A disjunção é representada pelo simbolo || sua função é comparar as sentenças e basta ter uma verdade para retornar verdade.

a) V – F – V – V – F – V – V

b) V – F – F – F – F – V – V

c) F – F – V – V – F – V – V

d) V – F – V – F – F – V – F

e) F – F – V – V – V – F – V

f) F – F – V – V – V – V – V

g) V – V – V – V – F – V – V

h) V – F – V – V – F – F – V

***

# <div align="center">TABELA VERDADE </div>

Agora que já entendemos como funciona os conectivos lógicos, suas regras e precedências chegou a hora de aprender a montar a tabela verdade. O objetivo dessa
tabela é verificar a validade lógica de uma proposição composta. Podemos classifica-las em três categorias, satisfatível, falseável ou contingente.

Fórmula Satisfatível: Uma fórmula da lógica é dita ser satisfatível se existe uma maneira de atribuir valores lógicos às suas variáveis de maneira a torná-la verdadeira.

Fórmula Falseável: Uma fórmula é dita ser falseável se existe uma maneira de atribuir valores lógicos às suas variáveis de maneira a torná-la falsa.

Fórmula Contigente: Dizemos que uma fórmula é contingente se esta é satisfatível e falseável simultaneamente.


**Regras básicas para montar a tábela verdade**

![1](https://user-images.githubusercontent.com/86995782/198897252-5a06cbab-bd55-4e5a-a7df-b4b191b63228.png)

***

### EXERCICIO

**Faça você mesmo. Crie a tabela verdade para as seguintes fórmulas:**

1.	!!P && !!Q

2.	!!P && (P&& !!Q)

3.	(Q&&P) && (!!Q | | R)

***


# <div align="center">RESPOSTAS</div>

**ATENÇÃO: NÃO CONTINUE A LEITURA DESSA PARTE DO ARTIGO CASO NÃO TENHA TENTADO RESPONDER AS QUESTÕES POR CONTA PRÓPRIA. SABOTAR O SEU APRENDIZADO É O MAIOR ERRO QUE VOCÊ PODE COMETER EM QUALQUER MOMENTO DA SUA JORNADA ENQUANTO PROFISSINAL NA ÁREA DE TECNOLOGIA. UTILIZE ESSE CAMPO APENAS PARA CONFERIR AS SUAS RESPOSTAS.**

***
Análise as frases abaixo, caso seja uma proposição  lógica escreva o seu valor verdade e se é composta ou atômica. Se não for uma proposição justifique o motivo.
  
**a)** Se Pedro quer ser programador, então Rafael recomendou aprender lógica de programação e algortimos antes de aprender uma linguagem.

**Resposta:** Proposição verdadeira e composta pois temos duas sentenças.

**b)** (((1 + 1) + (2 * 2)) / 10) = 3     e    2 * 2 = 40

**Resposta:** Proposição falsa e composta pois está unindo duas sentenças que resultam em valores falsos. 

**c)** x + y * 5 * w = 10

**Resposta:** Não é verdadeira nem falsa, pois x, y e w é desconhecido. Sendo assim não é uma sentença lógica

**d)** A capital do brasil é Brasília.

**Resposta:** Proposição verdadeira e atômica, só existe uma sentença

**e)** Você só vai ser um bom programador se, e somente se, tiver dedicação nos estudos. 

**Resposta:** Proposição verdadeira e composta pois temos duas sentenças.


***

Marque V ou F para as afirmações abaixo.

I.	(  )  A negação é representado pelo simbolo && sua função é inverter o valor verdade da sentença que estiver na sua frente. 

II.	(   )  Na conjunção só podemos comparar uma sentença.

III.	(   )  A frase: “só é verdade quando todas as sentenças são verdadeiras” é para memorizar a regra do conectivo de conjunção.

IV.	(   )  A frase: “basta ter uma verdade para expressão ser verdadeira” é para memorizar a regra do conectivo de disjunção.

V.	(   )  A frase: “inverte o valor lógico” é para memorizar a regra do conectivo de negação.

VI.	(   )  A conjunção é representada pelo simbolo ! sua função é comparar as sentenças e se todas as sentenças tiverem o valor lógico verdade vai rotornar falso.

VII.	(   )  A disjunção é representada pelo simbolo | | sua função é comparar as sentenças e basta ter uma verdade para retornar verdade. 


a.	V – F – V – V – F – V – V

b.	V – F – V – V – F – V – V

c.	V – F – V – V – F – V – V

d.	V – F – V – V – F – V – V

**e.	F – F – V – V – V – F – V  RESPOSTA CERTA**

f.	V – F – V – V – F – V – V

g.	V – F – V – V – F – V – V

h.	V – F – V – V – F – V – V


***

**Faça você mesmo. Crie a tabela verdade para as seguintes fórmulas:**


![code](https://user-images.githubusercontent.com/86995782/198897814-d7fbb866-d652-4979-b4bc-3ea1ab7ec8f2.png)

<!-- Linkedin -->
  <a href="https://www.linkedin.com/in/carlos-eduardo-amorim-silva-34583b214/" target="_blank"><img height="25" src="https://img.shields.io/badge/-LinkedIn-%230A66C2?logo=LinkedIn&colorlogo=white" target="_blank" style="vertical-align:top margin:6px 4px"></a> 
<!-- instagram -->
  <a href="https://www.instagram.com/caduamorimm.dev/" target="_blank"><img height="25" src="https://img.shields.io/badge/-Instagram-%230A0A0A?logo=Instagram&colorlogo=white" style="vertical-align:top margin:6px 4px"></a>
<!-- gmail -->
  <a href = "mailto:amorimm.dev@gmail.com"><img height="25" src="https://img.shields.io/badge/-Gmail-%230A0A0A?logo=Gmail&colorlogo=white" style="vertical-align:top margin:6px 4px"></a>
