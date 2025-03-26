TF 25/03/2025

Este repositório é o projeto de um banco de dados para o TF da aula de Implantação de Servidores.

Aluno: Armazena dados dos alunos.

Turma: Armazena as turmas.

Professor: Armazena os dados dos professores.

Relacionamentos:

Aluno pertence a uma Turma (1:N)

Turma tem um Professor (1:N)

Instruções:
Vá até a pasta DB.

Execute o comando abaixo para levantar o banco de dados no Docker: docker-compose up -d
