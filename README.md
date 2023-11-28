Sistema de Gerenciamento Hospitalar - Banco de Dados
Visão Geral

Este projeto foca na criação de um banco de dados abrangente para um sistema de gerenciamento hospitalar. O banco de dados inclui informações sobre médicos, pacientes, consultas, especialidades médicas, provedores de seguros e acomodações hospitalares. Os dados abrangem o período de 1 de janeiro de 2015 a 1 de janeiro de 2022.
Estrutura do Banco de Dados
Entidades

    Médicos
        Pelo menos 10 médicos com diferentes especialidades, incluindo pediatria, clínica geral, gastroenterologia e dermatologia.

    Especialidades
        Sete especialidades, incluindo pediatria, clínica geral, gastroenterologia e dermatologia.

    Pacientes
        Pelo menos 15 pacientes.

    Consultas
        Registros de 20 consultas envolvendo diferentes pacientes e médicos. Dez consultas incluem prescrições com dois ou mais medicamentos.

    ProvedoresDeSeguro
        Informações sobre pelo menos quatro provedores de seguros. Associação com pelo menos cinco pacientes e cinco consultas.

    RelacaoMedicoEspecialidade
        Entidade que estabelece a relação entre médicos e suas especialidades.

    Internacoes
        Registros de pelo menos sete internações entre 1 de janeiro de 2015 e 1 de janeiro de 2022. Pelo menos dois pacientes foram internados mais de uma vez.

    Acomodacoes
        Três tipos de acomodações: apartamentos, quartos duplos e enfermarias. Cada um com custos associados diferentes.

    Enfermeiros
        Informações sobre dez profissionais de enfermagem.

    RelacaoInternacaoEnfermeiro
        Entidade que estabelece a relação entre internações e enfermeiros.

Relacionamentos

    Consulta - Relacionamento Médico/Paciente
        Chaves estrangeiras vinculando consultas a ambos médicos e pacientes.

    ProvedorDeSeguro - Relacionamento Médico
        Chaves estrangeiras corrigidas estabelecendo a relação entre provedores de seguros e médicos.

    Internacao - Relacionamento Paciente/Médico
        Chaves estrangeiras vinculando internações a ambos pacientes e médicos.

População de Dados

O banco de dados foi preenchido com dados realistas para simular a operação de um sistema de gerenciamento hospitalar. Os dados abrangem uma variedade de cenários, incluindo múltiplas consultas para alguns pacientes, diferentes tipos de acomodações e hospitalizações repetidas.
Como Utilizar

Para implementar este banco de dados, siga estes passos:

    Criação do Banco de Dados
        Execute os scripts SQL fornecidos na pasta 'sql_scripts' na ordem especificada.

    População de Dados
        Execute os scripts SQL para população de dados na pasta 'data_population'.

    Consultas e Relatórios
        Utilize as consultas SQL fornecidas na pasta 'queries' para diversos relatórios e análises.
