# Lego-III
Professores Rogério Barbosa, Carlos Antônio Costa Ribeiro e Pedro H.G Ferreira de Souza  
Anotações leituras e aula Lego III - IESP - UERJ  


## Aula 1 

### Diagramas causais (DAGs - direct acyclic graphs)

- O processo gerador de dados "é o próprio mundo acontecendo";

X ----> Y    ?

Ex.: X raça, Y aprovação no vestibular  

A seta que desenhamos é CAUSA. Não é uma correlação. É como dizer que "X é parte do Processo Gerador de Dados (PGD) de Y".  
Ou, contrafactual: Se X não tivesse ocorrido, Y provavelmente também não teria.  
Ou, intervenção: Se, propositalmente, mudássemos o valor de X, Y provavelmente se alteraria. 

1) Coisas podem ter múltiplas causas

X1, X2, X3 ----> Y

Cada X é uma causa parcial de Y

2) Causas são probabilísticas, ou seja, elas alteram a distribuição.

Probabilístico --> incerteza  
--> Cadeias complexas;  
--> Fatores inevitavelmente ocasionais;  

### DAGs

Dags são listas de variáveis conectadas por setas!

- Não paramétrico 
--> Eu não estou especificando a _FORMA FUNCIONAL_
--> Eu não estou especificando a _DISTRIBUIÇÃO DAS VARIÁVEIS_

### Variáveis

- Observadas vs. não-observada

### IMPORTANTE!

- Setas são sempre unidirecionais!! 
- Caráter sempre ACÍCLICO nos DAGs!!


"É difícil escolher quais setas não criar", o que ajuda a decidir quais setas criar é uma boa revisão sistemática de literatura.

### DICAS

Simplificar a cadeia causal e simplificar as variáveis!

1) Eliminar fatores desimportantes (ligação obscura com Y, ligação muito distente com Y);
2) Agregar variáveis redundantes ou usar apenas uma delas;
3) Eliminar irrelevâncias;
4) Desconsiderar a representação de mediadores se a mediação não é alvo do interesse;

### Relações Triádicas Fundamentais

1) Mediação; X --> M --> Y.
2) Confusão (confounder); --> Z é um determinante comum de X e Y.
3) Colisão (collider); X e Y causam algo comum. 

# Lego-III
Professores Rogério Barbosa, Carlos Antônio Costa Ribeiro e Pedro H.G Ferreira de Souza  
Anotações leituras e aula Lego III - IESP-UERJ  


## Aula 1 

### Diagramas causais (DAGs - direct acyclic graphs)

- O processo gerador de dados "é o próprio mundo acontecendo";

X ----> Y    ?

Ex.: X raça, Y aprovação no vestibular  

A seta que desenhamos é CAUSA. Não é uma correlação. É como dizer que "X é parte do Processo Gerador de Dados (PGD) de Y".  
Ou, contrafactual: Se X não tivesse ocorrido, Y provavelmente também não teria.  
Ou, intervenção: Se, propositalmente, mudássemos o valor de X, Y provavelmente se alteraria. 

1) Coisas podem ter múltiplas causas

X1, X2, X3 ----> Y

Cada X é uma causa parcial de Y

2) Causas são probabilísticas, ou seja, elas alteram a distribuição.

Probabilístico --> incerteza  
--> Cadeias complexas;  
--> Fatores inevitavelmente ocasionais;  

### DAGs

Dags são listas de variáveis conectadas por setas!

- Não paramétrico 
--> Eu não estou especificando a _FORMA FUNCIONAL_
--> Eu não estou especificando a _DISTRIBUIÇÃO DAS VARIÁVEIS_

### Variáveis

- Observadas vs. não-observada

### IMPORTANTE!

- Setas são sempre unidirecionais!! 
- Caráter sempre ACÍCLICO nos DAGs!!


"É difícil escolher quais setas não criar", o que ajuda a decidir quais setas criar é uma boa revisão sistemática de literatura.

### DICAS

Simplificar a cadeia causal e simplificar as variáveis!

1) Eliminar fatores desimportantes (ligação obscura com Y, ligação muito distente com Y);
2) Agregar variáveis redundantes ou usar apenas uma delas;
3) Eliminar irrelevâncias;
4) Desconsiderar a representação de mediadores se a mediação não é alvo do interesse;

### Relações Triádicas Fundamentais

1) Mediação; X --> M --> Y.
2) Confusão (confounder); --> Z é um determinante comum de X e Y.
3) Colisão (collider); X e Y causam algo comum. 

### Caminhos causais


## Aula 2

### DAGs parte 2

### Controlar por variáveis como sendo "bloquear" caminhos

- Recap de regressão parcial:

$$y = \beta_0 + \beta_1 x + \beta_2 W + \varepsilon$$

beta_1 é o efeito parcial --> efeito de x, controlado por w

Regressão Simples (1)

y~ = y - (a0 + a1w)

(2)

x~= x - (c0 + c1W)

(3)

Regerssão parcial é pegar o y~ e explicar por x~

y~ = b0 + b1X~











