-------------------------------------------------------------------------------------
Modelo de banco de dados conforme especificações
1.	Entidades necessárias:
•	Empresa Parceira
•	Tecnologia
•	Colaborador

2.	Principais campos e seus tipos:
Empresa Parceira:
•	ID (Chave Primária, Inteiro)
•	Nome (Texto)
•	Setor (Texto)
•	Endereço (Texto)
Tecnologia:
•	ID (Chave Primária, Inteiro)
•	Nome (Texto)
•	Área (Texto)
Colaborador:
•	ID (Chave Primária, Inteiro)
•	Nome (Texto)
•	Cargo (Texto)
•	Empresa Parceira (Chave Estrangeira referenciando Empresa Parceira)

3.	Relacionamentos:
•	Uma empresa parceira pode utilizar várias tecnologias (relacionamento um-para-muitos).
•	Um colaborador pertence a uma única empresa parceira (relacionamento um-para-um).

4.	Simulação de registros:
Empresa Parceira:
•	ID: 1, Nome: Empresa A, Setor: Tecnologia, Endereço: Rua ABC, 123
•	ID: 2, Nome: Empresa B, Setor: Finanças, Endereço: Av. XYZ, 456
Tecnologia:
•	ID: 1, Nome: Python, Área: Webdev
•	ID: 2, Nome: SQL, Área: Dados
Colaborador:
•	ID: 1, Nome: João Silva, Cargo: Desenvolvedor, Empresa Parceira: Empresa A
•	ID: 2, Nome: Maria Souza, Cargo: Analista de Dados, Empresa Parceira: Empresa B


---------------------------------------------------------------------------------------
Respostas para as perguntas:
1.	Quais são as entidades necessárias?
•	Empresa Parceira
•	Tecnologia
•	Colaborador

2.	Quais são os principais campos e seus respectivos tipos?
•	Empresa Parceira:
•	ID (Chave Primária, Inteiro)
•	Nome (Texto)
•	Setor (Texto)
•	Endereço (Texto)
•	Tecnologia:
•	ID (Chave Primária, Inteiro)
•	Nome (Texto)
•	Área (Texto)
•	Colaborador:
•	ID (Chave Primária, Inteiro)
•	Nome (Texto)
•	Cargo (Texto)
•	Empresa Parceira (Chave Estrangeira referenciando Empresa Parceira)

3.	Como essas entidades estão relacionadas?
•	Uma empresa parceira pode utilizar várias tecnologias (relacionamento um-para-muitos).
•	Um colaborador pertence a uma única empresa parceira (relacionamento um-para-um).

4.	Simule 2 registros para cada entidade:
•	Empresa Parceira:
•	ID: 1, Nome: Empresa A, Setor: Tecnologia, Endereço: Rua ABC, 123
•	ID: 2, Nome: Empresa B, Setor: Finanças, Endereço: Av. XYZ, 456
•	Tecnologia:
•	ID: 1, Nome: Python, Área: Webdev
•	ID: 2, Nome: SQL, Área: Dados
•	Colaborador:
•	ID: 1, Nome: João Silva, Cargo: Desenvolvedor, Empresa Parceira: Empresa A
•	ID: 2, Nome: Maria Souza, Cargo: Analista de Dados, Empresa Parceira: Empresa B
