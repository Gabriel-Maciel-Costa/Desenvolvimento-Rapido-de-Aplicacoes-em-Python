**Atividades Aula 2:**

**Questão 1)**
A metodologia de desenvolvimento rápido de software (RAD) tem como objetivo acelerar o processo de entrega de software através de um processo que prioriza o desenvolvimento no curto prazo com entregas que incorporam conceitos bem debatidos com as partes envolvidas. Portanto a RAD possui diversas vantagens, em especial, em relação aos métodos tradicionais de desenvolvimento. Nesse sentido, selecione a opção que NÃO é uma vantagem da metodologia RAD: 

a) Integração antecipada do sistema e redução de riscos.( )

b) Adaptabilidade e compartimentação dos componentes do sistema. ( )

c) Versões iterativas e menor tempo de colocação no mercado. ( )

d) Feedback constante do usuário. ( )

**e) Ter como pré-requisito equipes tecnicamente muito qualificadas. (X)**

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Questão 2)**
Para que a RAD possa cumprir o seu objetivo que é o de reduzir o tempo de entrega de produtos, ela precisa de ferramentas que facilitem o desenvolvimento de software. Um dos recursos mais importantes para atingir tal objetivo é o uso de framework. Em relação aos frameworks para desenvolvimento de aplicações RAD, selecione a opção CORRETA: 

**a) A escolha de um framework sempre deve levar em consideração as necessidades do projeto que se deseja implementar. Portanto essa escolha tem que estar baseada nas bibliotecas, documentação disponível e a linguagem de programação disponibilizadas para desenvolver o projeto. (X)**

b) Independe da linguagem de programação escolhida é essencial que tenha como base o Python por se tratar de uma linguagem moderna e bem documentada. ( )

c) Atualmente, qualquer projeto precisa levar em consideração o modelo cliente-servidor, portanto a escolha do framework deve levar isso em consideração. ( )

d) Qualquer projeto RAD implementado em Python deve utilizar os frameworks Tkinter e Django. ( )

e)) A escolha de um framework não deve levar em consideração as necessidades do projeto que sedeseja implementar. Ela tem que estar baseada nas bibliotecas, documentação disponível e a linguagem de programação disponibilizadas para desenvolver o projeto. ( )

**--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Atividades Aula 3:**

**Questão 1)** 
Existem dois modos de se trabalhar com arquivos, onde um é adequado para trabalhar com arquivos que contêm imagem, som e vídeo, dentre outros, o segundo modo pode ser aberto em qualquer editor básico e ser editado, esses modos são: 

a) Sequencial e Texto ( )

**b) Binário e Texto (X)**

c) Multimidia e Binário ( )

d) Texto e Stream ( )

e) Multimidia e Stream ( )

**--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Questão 2)** 
O Python conta com recursos voltados à gravação e à leitura de arquivos, sejam eles binários ou texto. Nos arquivos do tipo texto a primeira providência é abrir o arquivo utilizando o método:

**a) open("nome_arquivo",w) (X)**

b) abrir("nome_arquivo",r) ( )

c) read("nome_arquivo",+wr) ( )

d) get("nome_arquivo",w) ( )

e) readline("nome_arquivo",r ( )

**--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Atividades Aula 4:**

**Questão 1)**
A interpolação de String é uma característica bastante útil quando queremos fazer uma substituição dentro de um texto. O Python trata a interpolação de Strings de modo a facilitar o trabalho do desenvolvedor. 
A respeito da interpolação de Strings no Python 3, selecione a opção correta:

a) Pode ser feita com @ (arroba), ou com $ (Cifrão) ()

b) Podemos aplicar usar$ (Cifrão), ou # (Hashtag) ()

c) O modo correto é usando # (Hashtag), ou % (percentual) ()

**d) A forma é usando % (percentual), ou { } (chaves) (X)**

e) Podemos utilizar { } (chaves), ou " (Aspas duplas) ()

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Questão 2)**
As operações com arquivos são fundamentais na programação, pois os arquivos são um recurso muito útil para manter a persistência de dados. O Python oferece comandos que permitem que os desenvolvedores possam fazer essas manipulações.
A respeito da manipulação de arquivos no Python, selecione a opção CORRETA :

**a) Para que um programa que manipula arquivos funcione é necessário fazer o tratamento deexceções. (X)**

b) Apesar de não ser obrigatório o tratamento de exceções, ele deve ser usado sempre para evitar problemas ao longo da execução do programa ()

c) Por se tratar de um recurso que já faz parte do Python padrão, o tratamento de exceções não é necessário. ()

d) Para abrir um arquivo texto, por exemplo, sempre é necessário verificar se ele não está corrompido antes, pois, caso contrário, pode gerar inconsistência no programa. ()

e) Os arquivos podem gerar muitos problemas, portanto são um recurso de uso apenas didático. Aplicações reais são desenvolvidas com bancos de dados. ()

**--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Atividades Aula 5:**

**Questão 1)**
O psycopg2 é um framework para trabalhar com o Postgres no Python. Abaixo, apresentamos um programa que faz a inserção de dados na tabela AGENDA :
01 import psycopg2
02 conn = psycopg2.connect(database = "postgres", user = "postgres", password = " senha123", host =
"127.0.0.1", port = "5432")
03 print ("Conexão com o Banco de Dados aberta com sucesso!")
04 cur = conn.cursor()
05 cur.execute("""INSERT INTO public."AGENDA" ("id", "nome", "telefone") VALUES (1, 'Pessoa1',
'02199999999')""")
06 conn.commit()
07 print("Inserção realizada com sucesso!");
08 conn.close()

A respeito do código apresentado, selecione a opção correta.

a) A única forma de executar uma operação de inserção em uma tabela é conforme a linha 5. ()

b) Se o comando da linha 8 for removido, o programa vai funcionar corretamente.()

c) Esse programa está preparado para tratar exceções de conexão com o banco de dados.()

**d) O cursor que é instanciado na linha 4 é fundamental para que o programa possa funcionar corretamente.(X)**

e) Esse código está implementado usando programação orientada a objetos ()

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Questão 2)**
O Python possui diversos frameworks para fazer operações em um banco de dados. Entre esses frameworks está o psycopg2 que faz a interface com o Postgres. Em relação ao psycopg2, selecione a opção correta:

**a) Permite a criação de tabelas e a execução dos comandos de inserção, exclusão, modificação e consulta no banco de dados. (X)**

b) Faz interface com outros Sistemas Gerenciadores de Banco de Dados (SGBDs), como o MySQL e Oracle. ()

c) Para ser utilizado, é fundamental programar orientado a objetos. ()

d) Os programas que utilizam o psycopg2 só vão funcionar se as exceções forem tratadas explicitamente. ()

e) Os programas que utilizam o psycopg2 devem estar implementados seguindo a programação estruturada. ()

**--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Atividades Aula 6:**

**Questão 1)**
O SQLite é uma biblioteca que implementa as funções de gerenciamento de banco de dados de maneira autossuficiente, sem a necessidade de um computador servidor rodando um software servidor de banco de dados. Com o Python instalado, o SQLite também está instalado.
Para abrir uma conexão do Python com o SQLite o código correto é:

**a) import sqlite3 conector = sqlite3.connect("exemplo.db") (X)**

b) import sqlite3 conector = sqlite3.connectar("exemplo.db") ()

c) import sqlite3 conector = sqlite3.abrir("exemplo.db") ()

d) import sqlite3 conector = sqlite3.server("exemplo.db") ()

e) import sqlite3 conector = sqlite3.open("exemplo.db") ()

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Questão 2)**
Qual é o comando em SQLite para realizar uma operação de criação de uma tabela no banco de dados ?

a) commit ()

b) close ()

**c) execute (X)**

d) create ()

e) insert ()

**--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Atividades Aula 7:**

**Questão 1)** 
A Linguagem de programação Python permite a inserção em massa de várias linhas em uma tabela de banco de dados usando uma única consulta SQL. Pode-se fazer isso usando uma consulta parametrizada com o comando:

a) insertmany ()

b) execute ()

c) inserirmuitos ()

**d) executemany (X)**

e) writeln ()

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Questão 2)**
Após a execução de comandos de manipulação de registros, tem-se que realizar a finalização da transação, e para isso usamos o comando:

**a) commit (X)**

b) rollback ()

c) persist ()

d) execute ()

e) run ()

**--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Atividades Aula 8:**

**Questão 1)**
A linguagem de programação Python tem enorme facilidade e flexibilidade para a realização de consultas nos mais variados banco de dados. Qual comando abaixo é usado para rodar uma consulta:

**a) execute(X)**

b) rodar()

c) executar()

d) run()

e) show()

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Questão 2)**
A linguagem de programação Python tem enorme facilidade e flexibilidade para a realização de consultas nos mais variados banco de dados. Após executar a solicitação da consulta deve processar o resultado através dos métodos:

a) fetchone, fetcal e fetchmany.()

b) fetread, fetchall e fetchmany.()

**c) fetchone, fetchall e fetchmany.(X)**

d) fetchone, fetchall e fetchmuch.()

e) fetchone, fetchall e fetchwrite()
