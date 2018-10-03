Antes de mais obrigado pela disponibilidade. Aqui vai o pequeno challenge:

Front-end: React Native

Criar uma app que recebe dados por socket de um servidor.
Os dados têm a seguinte estrutura:

[
{name: 'AAAA', 'age': random number },
{name: 'BBBB', 'age': random number},
{name: 'CCCC', 'age': random number},
{name: 'DDDD', 'age': random number},
{name: 'EEEE', 'age': random number}
]

A array é enviada do servidor de 1 em 1 segundo, e a única coisa que muda é o age que é número random entre 0 e 100 por exemplo.

O servidor está feito e podes ligar-te por socket em:
http://ec2-54-229-199-201.eu-west-1.compute.amazonaws.com:2345
Como disse, de 1 em 1 segundo envia a array do challenge. Se tiveres problemas a usar diz.

Para a parte de react native que é o que vais implementar, deve ter pelo menos 2 componentes. Deve imprimir essa array numa lista, por exemplo:

----------------
|AAAA     50|
----------------
|BBBB     30|
----------------
|CCCC    10|
-----------------
.....

# Context

Justin is our CEO here at Evil Corp.
He wants you to create a simple list so he can judge how you organize your code and its quality.

# Goal

Create a list with at least 2 components in this format:

----------------
|AAAA     50|
----------------
|BBBB     30|
----------------
|CCCC    10|
-----------------

Data comes through a websocket with this format:

[
{name: 'AAAA', 'age': random number },
{name: 'BBBB', 'age': random number},
{name: 'CCCC', 'age': random number},
{name: 'DDDD', 'age': random number},
{name: 'EEEE', 'age': random number}
]

You get a new array every second and the only thing that changes is the random number (0 - 100).

# Constraints
- Minimum 2 components

## Tooling

- React Native

## Timeline

Justin sent you this on a Friday morning and *really* wants to talk until the end of Monday 
