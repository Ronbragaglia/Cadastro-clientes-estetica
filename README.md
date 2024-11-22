Descrição do Projeto:
Este projeto é um sistema de gerenciamento de clínica de estética, desenvolvido em Python, que permite o cadastro de clientes, serviços oferecidos e agendamentos. Além disso, o sistema possui a funcionalidade de exportar os dados para um arquivo Excel, facilitando o acompanhamento e análise dos dados gerados.

Funcionalidades:
Cadastro de Clientes: Registra informações básicas como nome, telefone e e-mail.

Cadastro de Serviços: Permite cadastrar os serviços oferecidos pela clínica, com nome e duração.

Agendamentos: Gera registros de agendamento de serviços, vinculando os clientes aos serviços.

Consultas: Exibe os dados cadastrados sobre clientes, serviços e agendamentos em formato de tabelas utilizando Pandas.

Exportação para Excel: Exporta os dados dos clientes, serviços e agendamentos em um arquivo Excel, com separação por abas para facilitar a visualização.

Tecnologias Utilizadas:

Python: Linguagem principal do projeto.

SQLite3: Banco de dados leve e embutido utilizado para armazenar as informações da clínica.

Pandas: Biblioteca poderosa para manipulação e análise de dados, utilizada para consultas e exportação dos dados.


Openpyxl: Biblioteca usada para gerar o arquivo Excel com os dados exportados.

Google Colab: Ambiente usado para rodar o código e fazer o download do arquivo gerado diretamente.

Estrutura do Projeto:

Banco de Dados: Um banco de dados SQLite é criado e contém três tabelas principais:

Clientes: Armazena as informações de cada cliente.

Serviços: Contém detalhes dos serviços oferecidos pela clínica, como nome e duração.Agendamentos: Registra as consultas e horários agendados, vinculando clientes aos serviços.

Exportação de Dados: O sistema consulta os dados armazenados no banco de dados e os exporta para um arquivo Excel (clinica_estetica_dados.xlsx), criando uma aba para cada tabela (Clientes, Serviços e Agendamentos).


