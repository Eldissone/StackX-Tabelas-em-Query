# StackX-Tabelas-em-Query

 # 🎯 Criar 3 alunos (Tabela - aluno)
   # colunas:
📍 id numero
📍 nome string
📍 data_nascimento numero

INSERT INTO Tabela_aluno 
    (id, nome, data_nascimento)  
VALUES 
    (1, 'Gabriela Farani', '2000-07-13'),
  	(2, 'Fernando Gonzaga', '1945-05-28'),
  	(3, 'André Tomas', '1987-04-04');

# 🎯 Crie uma matéria e um professor (Tabela - materia)
# colunas:
📍 id numero
📍 nome string
📍 id_professor numero

INSERT INTO Tabela_materia
    (id, nome, id_professor)  
VALUES 
    (1, 'Introdução a Base de Dados', '2');

# Tabela - professor
# colunas:
📍 id numero
📍 nome string
📍 data_nascimento numero

INSERT INTO Tabela_professor
    (id, nome, data_nascimento)  
VALUES 
    (2, 'Laurindo Vilonga', '1999-08-24');

# 🎯 Crie 1 prova para cada aluno nessa matéria e diga que nota eles tiraram.

# Tabela - provas
📍Colunas:
📍 id_aluno  - número
📍 id_materia  - número
📍 nota  - número flutuante
📍 data_da_prova  data

INSERT INTO Tabela_provas
    (id_aluno, id_materia, nota, data_da_prova)  
VALUES 
    (3, 1, 18,5, '2024-11-21');

