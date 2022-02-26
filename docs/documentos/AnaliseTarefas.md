## Introdução

<p align="justify">
A análise de Tarefas representa os métodos de coletar, classificar e interpretar dados sobre o desempenho de um
sistema que possua ao menos uma pessoa como coponente.<br>
A questão é como definir um desempenho satisfatório para o sistema e seus componentes. Não apenas listar ações,
mas entender como um sistema trabalho afeta a aplicação e como o domínio da aplicação afeta o sistema de trabalho.<br>
Em IHC, a Análise de Tarefas pode ser utilizada nas três atividades habituais:
</p>

- Análise da Situação Atual
- Design de um Sistema Computacional
- Avaliação do Resultado de uma Intervenção

<p align="justify">
Dentro os métodos de análise de tarefas mais comuns, destacam-se GOMS, Árvore de Tarefas Concorrentes e Análise
Hierarquica de Tarefas. Passaremos brevemente por cada um deles, dando mais destaque para aquele que o grupo 3
"Prefeitura de Verdelândia" optou por fazer a Análise, Análise Hierarquica de Tarefas.
</p>

## GOMS

<p align="justify">
Método qual descrever a tarefa e o conhecimento do usuário sobre como realizá-la em termos de objetivos (goals),
operadores (operators), métodos (methods) e regras de seleção (selection rules). Os objetivos representam o que
o usuário quer realizar utilizando o software. Os operadores são primitivas internas (cognitivas) ou externas
(ações concretas). Os métodos são sequências bem conhecidas de subobjetivos e operadores que permitem atingir um
objetivo maior. Quando há mais do que um método para atingir um mesmo objetivo, são necessárias regras de
seleção, que representam tomadas de decisão dos usuários sobre qual método utilizar numa determinada situação.
</p>

## Árvore de Tarefas Concorrentes

<p align="justify">
Neste modelo existem quatro tipo de tarefas:
</p>

- Tarefas de Usuário, realizada fora do sistema
- Tarefas do Sistema, qual o sistema realiza processamento sem interagir com o usuário
- Tarefas Interativas, qual ocorre diálogo entre usuário-sistema.
- Tarefas Abstratas, representação de uma composição de tarefas que auxilia a decomposição

<p align="justify">
Este modelo permite representar diversas relações entre estas tarefas, que aumentam a expressividade de sua notação.
O registro explícito das relações entre as tarefas vai além das tarefas tradicionais para representar uma solução
de design de interação.
</p>


## Análise Hierarquica de Tarefas

<p align="justify">
A Análise Hierarquica de Tarefas compreende as competências e habilidades exibidas em tarefas complexas e não
repetitivas, assim como ajuda identificar problemas de desempenho. Ela se baseia em psicologia funcional, e não
comportamental, como as abordagens da época que foi criada.<br>
Toda tarefa é definida com o termo de seu(s) objetivo(s). Tarefas complexas são definidas em termos de objetivos
e subobjetivos, num desdobramento hierárquico. Esse desdobramento é chamado de decomposição de tarefas ou
redescrição. Observer que a definição é mais ampla e difere da definição adotada pelo design baseado em objetivo.<br>
Um objetivo é um estado específico de coisa, um estado final. Esse estado pode ser definido por um ou mais eventos
ou por valores fisicamente observáveis de uma ou mais variáveis, que atuam como critério de alcance do objetivo.
Em vez de idententificar uma lista de ações, a HTA inicia com uma definição dos objetivos das pessoas.
</p>

## Referências

Annett, 2003; Annett, Jhon e Duncan. Task Analysis and Training Design. Occupational Psycology, 1967.

BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador, Rio de Janeiro, 2021.

## Histórico de versionamento
 
| Data  | Versão | Descrição | Autor | Revisor |
| :--:  | :----: | :-------: | :---: | :-----: |
| 25/02 | 1.0.0  | Criação do documento Análise Hierarquica de Tarefas | [Rodrigo](https://github.com/Rocsantos) | Definir
| 26/02 | 1.1.0  | Adicionado texto de GOMS, Árvore de Tarefas Concorrentes | [Rodrigo](https://github.com/Rocsantos) | Definir
