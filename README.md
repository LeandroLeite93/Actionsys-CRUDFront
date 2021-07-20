# Avalição Tecnica Ationsys

Avaliação:

- Criar um banco de dados Mysql local. Nome do banco de dados: actionsys. Criar a seguinte tabela no banco de dados.

tabela: funcionarios

campos:

                id - auto-incremento,

                nome - varchar(200),

                email - varchar(100),

                data_nascimento - date,

                data_admissao - date,

                setor - varchar(100), -- engenharia, compras, vendas, financeiro

                cargo - varchar(100), -- auxiliar, técnico, engenheiro, diretor

                nivel - varchar(100), -- junior, pleno, senior, estagiario

                audit_data_insert - datetime, -- data e hora da inserção do dado

                audit_data_update - datetime -- data e hora da atualização do dado

- Desenvolver uma api que permita um crud (create, read, update, delete) nessa nessa tabela. Usar ORM (TypeORM, Sequelize, Prisma ou qualquer outro que conheça)

- Criar uma interface web (React) para permitir inserir, listar, editar e excluir dados de funcionários.

### Observações:

- Preencher todos os campos da tabela no isert, exceto o campo audit_data_update.

- Permitir que sejam editados os campos de nome, email, data_nascimento, data_admissao, setor, cargo e nivel. Gravar o campo audit_data_update ao atualizar um registro.

- Os dados podem ser apresentados em tabela ou em cards. Pode usar apenas uma tela ou várias telas. Fique a vontade para implementar.

- Pode inserir novos campos na tabela, como imagem, caso deseje.

- A comunicação entre frontend e backend deve ser via api Rest.

- Fique a vontade caso deseje inserir algum componente de segurança, como token JWT, login etc. Não é uma exigência.

- Responsividade e validação de campos dos formulários serão diferenciais.

# Para Abrir o Projeto

basta executar npm i para instalar as dependencias necessarias 
e em seguida npm start, para visualizar o projeto na porta localhost:3000 


### #SigaAction


