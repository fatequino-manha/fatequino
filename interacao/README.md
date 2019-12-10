## Equipe Interação

A proposta de entrega da equipe de Interação, foi a criação de um chatbot. Esse chatbot,
desenvolvido para dispositivos móveis na linguagem Dart com o framework Flutter, irá
funcionar via Web e Bluetooth: os estudantes podem perguntar sobre assuntos cotidianos da faculdade,
como se o professor veio, ou o horário de funcionamento da secretaria e etc.    

### Linguagem de Programação

Para o desenvolvimento do sistema foram utilizadas a linguagem de
programação Dart, focado no framework Flutter.

Dart é uma linguagem de script voltada à web desenvolvida pela Google em
2011 com o objetivo de substituir o JavaScript como a linguagem principal embutida
nos navegadores. Programas nesta linguagem podem tanto serem executados em
uma máquina virtual quanto compilados para JavaScript
Flutter é um SDK de código aberto criado pelo Google e lançado a segunda
metade de 2018 para o desenvolvimento de aplicativos para Android, iOS, Desktop
ou Web.

Flutter simplifica a criação de app para iOS e Android sendo possível fazer um
app para as duas plataforma com apenas um código e tendo desempenho quase
que nativo em ambas.  

O código fonte se encontra em: https://gitlab.com/adenilson.elias2/fatequinoapp                                                                  
                                                                    
                                                                    
### Regras de Negócio

O sistema deve estar de acordo com as seguintes regras de negócio (RN)
para estar de acordo com as especificações.

- RN01 - o sistema deverá responder adequadamente às perguntas do usuário.

- RN02 - o sistema irá aprender de acordo com o uso.

- RN03 - o sistema deverá funcionar com o uso da internet e do Bluetooth.


### Requisitos Funcionais

São apresentados a seguir os requisitos funcionais (RF) que o sistema deve conter
para seu correto funcionamento e que atenda à necessidade de gerenciamento da produção de veículos e controle de pedidos.

- RF01 - O sistema irá dar uma resposta de acordo com a pergunta do
usuário.


- RF02 - O sistema irá aprender de acordo com o uso.


### Requisitos Não Funcionais

Os requisitos não funcionais (RNF) esperados do sistema para atender às
exigências de qualidade são:

- RNF01 - o sistema funcionará via web e bluetooth;
- RNF02 - o sistema será utilizado por alunos da Fatec.
- RNF03 - o sistema será desenvolvido em Dart com o framework Flutter.
- RNF04 - o sistema será desenvolvido para dispositivos móveis.


### Descrição Numerada

A seguir será apresentada a descrição numerada de como o sistema funcionará:

1 - O usuário irá escolher se ele quer utilizar via Web ou via Whatsapp.

2 - O usuário irá perguntar ao Fatequino sua dúvida.

3 - O Fatequino responderá adequadamente.

4 - O Fatequino irá aprender com a resposta do usuário.


### Casos de Uso

A seguir é apresentado o Diagrama de Casos de Uso (DCU) demonstrando a interação dos atores com o sistema e suas funcionalidade:


![](/interacao/imgs/dcu.png)

### Diagrama de Sequência

Com a finalidade de representar graficamente o fluxo da informação pelo
sistema e como é realizada a interação entre o ator com a fronteira e desta com o
controle temos o Diagrama de Sequência (DS).


![](/interacao/imgs/sequence.png)


### Protótipo Não Funcional

![](/interacao/imgs/prot1.png)

![](/interacao/imgs/prot2.png)


### Fluxo de Comunicação

![](/interacao/imgs/flow.png)


### Demais informações

As demais informações se encontram neste [documento](doc.pdf).