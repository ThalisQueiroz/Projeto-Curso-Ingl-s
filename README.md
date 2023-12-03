# Projeto_Curso_Ingl-s
Neste projeto tive a ideia de construir um código na
linguagem Python em conjunto com o banco de dados (MySQL) em que
podemos reunir informações e armazenar necessárias para os Cruds no
contexto de um curso de inglês.

Instalando, Importando e Conectando: O `mysql.connector` é uma biblioteca
em Python que fornece uma interface para conectar bancos de dados MySQL
a partir de programas Python. Com essa importação, você pode usar as classes
e funções disponíveis no `mysql.connector` para estabelecer conexões com
bancos de dados MySQL, executar consultas, recuperar dados e realizar outras
operações relacionadas ao banco de dados.

Conectando ao banco de dados: O código em Python cria um sistema de
conexão utilizando as seguintes variáveis: host, user, password e database. 

Inicio do código Crud: Ele utiliza a linguagem SQL para definir a estrutura das
tabelas para as entidades Alunos, Professores e Turmas. Além disso, permite
vincular alunos e professores às turmas. A função `criar_tabelas()` é
responsável por criar as tabelas no banco de dados para armazenar
informações sobre Alunos, Professores, Turmas, e os vínculos entre alunos e
Turmas e Professores e Turmas.

Crud do Aluno: No crud do aluno basicamente o aluno insere as suas
informações (cpf, nome, matrícula, endereço), a partir disto, os dados são
armazenados e salvos para caso queira consultar, alterar ou excluir. Caso
ocorra um conflito de dados, o código atenderá com a mensagem de erro para
reescrever novamente os dados corretamente.

Cruds dos Professores: Nos cruds dos professores é basicamente igual ao dos
alunos. Porém algumas informações são diferentes como “ID” que no caso dos alunos
é matrícula. Contendo com os mesmos conteúdos como: Inserir, Consultar, Alterar e
Excluir. 

Crud da Turma: No crud da turma temos as seguintes informações para ser
inserida que são: número da turma, turno e nível. Com isso, podemos criar uma
turma em que serão inseridos os alunos e será inserido o professor para ser
responsável pela turma. Neste código teremos as seguintes funções: Inserir,
Consultar e Excluir.

Crud de join: Neste crud é responsavel para criar relações de aluno e
professor com as turmas. Também usamos funções de vinculação e consulta
entre aluno e turma, professor e turma.

Menu: Neste menu interativo é criado uma tabela para selecionar as funções,
simplificando e facilitando a interação do usuário.
