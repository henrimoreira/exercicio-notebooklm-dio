# exercicio-notebooklm-dio
Este projeto foi desenvolvido como parte de um desafio da plataforma DIO, com o objetivo de explorar o potencial da ferramenta NotebookLM na organização de estudos.

O tema escolhido foi Modelagem de Dados e Bancos de Dados, por ser uma área fundamental para quem deseja seguir carreira como Cientista de Dados.

Alguns links que foram utilizados como fonte:
https://www.oracle.com/br/database/what-is-database/
https://aws.amazon.com/pt/compare/the-difference-between-relational-and-non-relational-databases/
https://www.ibm.com/br-pt/think/topics/data-modeling

Perguntas utilizadas e suas respostas(resumidas):

Pergunta 1: Quais são as vantagens e desvantagens de se utilizar banco de dados em comparação com pastas e documentos físicos.
Resposta: Em resumo, embora os bancos de dados exijam maior investimento e conhecimento técnico, eles são essenciais para evitar o caos gerencial e a falência em um mundo onde a informação é considerada o "novo petróleo" e cresce em volume exponencialmente.

Dificuldade:
Resposta inicial muito genérica

Ajuste:
Refinar o prompt pedindo exemplos práticos e comparação direta

Pergunta 2: Como a computação em nuvem impacta a gestão de dados?
Resposta: A computação em nuvem transformou a gestão de dados ao oferecer escalabilidade e flexibilidade, permitindo que sistemas cresçam rapidamente conforme a demanda.
Também reduz custos ao substituir infraestrutura física por pagamento sob demanda, além de automatizar tarefas com DBaaS, liberando os DBAs para funções estratégicas.
Além disso, garante alta disponibilidade global, maior resiliência e agilidade no desenvolvimento de aplicações modernas.

Dificuldade:
Falta de profundidade em exemplos reais

Ajuste:
Solicitar aplicações práticas no mercado

Agora apresento um Miniguia de Estudo com um resumo estruturado do assunto, glossários com termos essenciais e um conjunto de prompts para revisões futuras:

Um banco de dados é uma coleção organizada de informações ou dados estruturados, normalmente armazenados eletronicamente em um sistema de computador
. Ele serve como um repositório sistêmico para gerenciar fatos relacionados a entidades (como pessoas, lugares ou objetos) de maneira eficiente e segura
. 1. Importância e Gerenciamento
SGBD/DBMS: O banco de dados é controlado por um Sistema de Gerenciamento de Banco de Dados (SGBD), que atua como interface entre os dados e os usuários ou aplicativos
. Ele garante segurança, integridade, recuperação eficiente e suporte à tomada de decisões
.
Vantagens sobre Planilhas: Diferente de planilhas, os bancos de dados são projetados para grandes volumes de informações, permitem acesso multiusuário simultâneo e oferecem lógica de consulta complexa e segura
.
2. Principais Tipos de Bancos de Dados
Relacionais (SQL): Organizam dados em tabelas com linhas e colunas
. Utilizam relações predefinidas e a linguagem SQL para manipulação
. São ideais para dados previsíveis e consistência rigorosa
.
Não Relacionais (NoSQL): Armazenam dados em formatos não tabulares, como documentos, chave-valor, grafos ou colunas largas
. Oferecem esquemas flexíveis, alta escalabilidade horizontal e alto desempenho para grandes volumes de dados variados
.
3. Modelagem de Dados O processo de criação de um banco de dados ocorre em três níveis de abstração
:
Modelo Conceitual: Visão de alto nível que identifica as entidades e as regras de negócio sem detalhes técnicos
.
Modelo Lógico: Detalha atributos, tipos de dados e relacionamentos (como cardinalidade), sendo independente de tecnologia
.
Modelo Físico: Esquema final que mapeia o modelo lógico para uma tecnologia de SGBD específica, definindo como os dados serão armazenados fisicamente
.
4. Integridade e Normalização
ACID: Propriedades (Atomicidade, Consistência, Isolamento e Durabilidade) que garantem a validade das transações em bancos relacionais
.
Normalização: Técnica de design para reduzir a redundância e a duplicidade, dividindo dados em várias tabelas relacionadas
.

--------------------------------------------------------------------------------
Glossário de Termos Essenciais
ACID: Acrônimo para Atomicidade, Consistência, Isolamento e Durabilidade; conjunto de propriedades que garante a confiabilidade de transações em sistemas relacionais
.
Atributo: Representa uma característica ou propriedade de uma entidade, correspondendo às colunas de uma tabela
.
BASE: Modelo de consistência para NoSQL (Basicamente disponível, Estado flexível, Eventual consistência), priorizando disponibilidade sobre consistência imediata
.
Cardinalidade: Define o número de ocorrências de uma entidade que podem estar associadas a uma ocorrência de outra entidade (ex: 1:1, 1:N, N:N)
.
Chave Estrangeira (FK): Um atributo que estabelece um relacionamento com a chave primária de outra tabela
.
Chave Primária (PK): Identificador exclusivo e obrigatório de cada registro (linha) dentro de uma tabela, garantindo que não haja duplicatas
.
DBA (Database Administrator): Profissional responsável pelo planejamento, design, implementação e manutenção contínua dos bancos de dados
.
Entidade: Objeto, pessoa ou conceito do mundo real sobre o qual se deseja armazenar informações
.
JSON: Formato de texto leve para intercâmbio de dados, muito utilizado em bancos de dados de documentos (NoSQL) para armazenar informações semiestruturadas
.
Query (Consulta): Uma solicitação de dados ou informações de um banco de dados, geralmente escrita em SQL
.
SGBD/DBMS: Software que gerencia a criação, manutenção e o uso de bancos de dados
.
SQL (Structured Query Language): Linguagem de programação padrão usada para interagir, consultar e definir dados em bancos relacionais
.

Prompts Reutilizáveis:

Quais são as diferenças entre bancos relacionais e não relacionais?
Explique a propriedade ACID com exemplos práticos.
Como a computação em nuvem impacta bancos de dados?
Como modelar um diagrama DER consistente passo a passo?

Esses aprendizados demonstram não apenas o domínio técnico do tema estudado, mas também a capacidade de utilizar a Inteligência Artificial de forma crítica e estratégica no processo de aprendizagem.
