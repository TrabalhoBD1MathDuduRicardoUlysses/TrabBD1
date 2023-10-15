# TRABALHO 01:  Título do Trabalho
Trabalho desenvolvido durante a disciplina de BD1

# Sumário

### 1. COMPONENTES
Integrantes do grupo<br>
Eduardo De Marchi Poltronieri : demarchi.dudu@gmail.com   

Matheus Andrade : matheus.cbandrade@gmail.com 

Breno Ricardo Ferreira Antunes: breno.rune@hotmail.com 

Ulysses Monte: uly6monte@dominio.com 

### 2.MINI-MUNDO<br>

## A DriveEazy está reinventando a experiência de aluguel de carros, tornando-a simples e eficiente. Nosso diversificado portfólio de veículos abrange uma ampla variedade de marcas, modelos e categorias, garantindo que cada cliente encontre o carro perfeito para suas necessidades. Todos os nossos veículos estão devidamente registrados, licenciados e com o IPVA atualizado.

Nossa plataforma digital permite o registro completo de dados dos clientes e detalhes de pagamento, proporcionando transações transparentes e seguras. Cada contrato de aluguel é meticulosamente documentado, garantindo que todas as informações relacionadas à locação sejam facilmente acessíveis.

Além do aluguel básico, os clientes têm a liberdade de escolher entre contratos diários ou mensais, bem como a opção de adicionar serviços complementares, como seguro, tag de passagem e serviços de limpeza.

Internamente, valorizamos a manutenção da qualidade dos nossos veículos. Por isso, mantemos parcerias estratégicas com prestadores de serviços de manutenção e limpeza, garantindo que cada carro esteja sempre nas melhores condições..


### 3.PERGUNTAS A SEREM RESPONDIDAS
#### 3.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
    a) O sistema proposto poderá fornecer quais tipos de relatórios e informações? 
    b) Crie uma lista com os 5 principais relatórios que poderão ser obtidos por meio do sistema proposto!
    
ANALISAR ESSA RESPOSTA
a) O sistema proposto poderá fornecer quais tipos de relatórios e informações?

Com base no minimundo, o sistema pode fornecer as seguintes informações e relatórios:
Informações de Veículos: Relatório detalhado sobre cada veículo disponível para aluguel, incluindo marca, modelo, categoria, status (disponível, alugado, em manutenção, etc.), registro, licenciamento e status do IPVA.
Informações de Clientes: Dados completos dos clientes, incluindo informações pessoais, histórico de alugueis, métodos de pagamento, preferências, entre outros.
Contratos de Aluguel: Detalhes de cada contrato, incluindo veículo alugado, duração do contrato (diária, mensal), serviços adicionais contratados (seguro, tag de passagem, limpeza), datas de início e término, e custo total.
Serviços Parceiros: Informações sobre serviços de manutenção, limpeza e quaisquer outros que a empresa contrate. Inclui detalhes do serviço, custo, parceiro que oferece o serviço e data.
Modalidades de Contrato: Estatísticas sobre as modalidades de contrato mais populares, incluindo quantidade de contratos diários vs. mensais.
Serviços Adicionais Contratados: Um resumo dos serviços adicionais mais comuns que os clientes optam, como seguro, tag de passagem e limpeza.
Receitas e Despesas: Relatórios financeiros que mostram as receitas obtidas com alugueis e despesas relacionadas a serviços parceiros e manutenção de veículos.
Taxa de Ocupação: Estatísticas sobre a taxa de ocupação dos veículos, mostrando quais são mais alugados e quais ficam mais tempo disponíveis.

b) Crie uma lista com os 5 principais relatórios que poderão ser obtidos por meio do sistema proposto!

Relatório de Performance de Aluguel: Mostra a taxa de ocupação de cada veículo, os mais e menos alugados, e as receitas geradas por cada um.
Relatório de Clientes Fidelidade: Detalhes dos clientes que mais alugam veículos, sua frequência, preferências e gasto total.
Relatório Financeiro: Um resumo das receitas e despesas, detalhando as fontes de receita (alugueis, serviços adicionais) e despesas (manutenção, limpeza, serviços parceiros).
Relatório de Serviços Adicionais: Um panorama dos serviços adicionais mais contratados, as receitas geradas por eles e sua popularidade ao longo do tempo.
Relatório de Manutenção e Serviços: Detalhes sobre os veículos que passaram por manutenção, a frequência de serviços, os parceiros que realizaram os serviços e os custos associados.

    
### 5.MODELO CONCEITUAL
    A) Utilizar a Notação adequada (Preferencialmente utilizar o BR Modelo 3)
    B) O mínimo de entidades do modelo conceitual pare este trabalho será igual a 3 e o Máximo 5.
        * informe quais são as 3 principais entidades do sistema em densenvolvimento<br>(se houverem mais de 3 entidades, pense na importância da entidade para o sistema)       
    C) Principais fluxos de informação/entidades do sistema (mínimo 3). <br>Dica: normalmente estes fluxos estão associados as tabelas que conterão maior quantidade de dados 
    D) Qualidade e Clareza
        Garantir que a semântica dos atributos seja clara no esquema (nomes coerentes com os dados).
        Criar o esquema de forma a garantir a redução de informação redundante, possibilidade de valores null, 
        e tuplas falsas (Aplicar os conceitos de normalização abordados).   
        
![Alt text](https://github.com/discipbd1/trab01/blob/master/images/concept_sample.png?raw=true "Modelo Conceitual")
![image](https://github.com/TrabalhoBD1MathDuduRicardoUlysses/TrabBD1/assets/146727298/7da29af2-d582-4921-af2f-e45a214c7450)


    
    
#### 5.1 Validação do Modelo Conceitual
    [Grupo01]: Arthur Cremasco, Bruno Mian, Thalison
    [Grupo02]: Gustavo Laube, Henrique Bravim, Cassiano

#### 5.2 Descrição dos dados 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>

># Marco de Entrega 01: Do item 1 até o item 5.2 (5 PTS) <br> 

### 6	MODELO LÓGICO<br>
        a) inclusão do esquema lógico do banco de dados
        b) verificação de correspondencia com o modelo conceitual 
        (não serão aceitos modelos que não estejam em conformidade)

### 7	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 

      
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) Script das instruções relativas a inclusão de dados 
	Requisito mínimo: (Script dev conter: Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados + insert para dados a serem inseridos)
        OBS
	1) Criar um novo banco de dados para testar a restauracao (em caso de falha na restauração o grupo não pontuará neste quesito)
        2) script deve ser incluso no template em um arquivo no formato .SQL


### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
    OBS: Usa template da disciplina disponibilizado no Colab.<br>
#### 9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>

#### 9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 4)<br>

#### 9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E TABELAS OU CAMPOS RENOMEADOS (Mínimo 11)
    a) Criar 5 consultas que envolvam os operadores lógicos AND, OR e Not
    b) Criar no mínimo 3 consultas com operadores aritméticos 
    c) Criar no mínimo 3 consultas com operação de renomear nomes de campos ou tabelas

#### 9.4	CONSULTAS QUE USAM OPERADORES LIKE E DATAS (Mínimo 12) <br>
    a) Criar outras 5 consultas que envolvam like ou ilike
    b) Criar uma consulta para cada tipo de função data apresentada.

># Marco de Entrega 02: Do item 6. até o item 9.1 (5 PTS) <br>

#### 9.5	INSTRUÇÕES APLICANDO ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>
    a) Criar minimo 3 de exclusão
    b) Criar minimo 3 de atualização

#### 9.6	CONSULTAS COM INNER JOIN E ORDER BY (Mínimo 6)<br>
    a) Uma junção que envolva todas as tabelas possuindo no mínimo 2 registros no resultado
    b) Outras junções que o grupo considere como sendo as de principal importância para o trabalho

#### 9.7	CONSULTAS COM GROUP BY E FUNÇÕES DE AGRUPAMENTO (Mínimo 6)<br>
    a) Criar minimo 2 envolvendo algum tipo de junção

#### 9.8	CONSULTAS COM LEFT, RIGHT E FULL JOIN (Mínimo 4)<br>
    a) Criar minimo 1 de cada tipo

#### 9.9	CONSULTAS COM SELF JOIN E VIEW (Mínimo 6)<br>
        a) Uma junção que envolva Self Join (caso não ocorra na base justificar e substituir por uma view)
        b) Outras junções com views que o grupo considere como sendo de relevante importância para o trabalho

#### 9.10	SUBCONSULTAS (Mínimo 4)<br>
     a) Criar minimo 1 envolvendo GROUP BY
     b) Criar minimo 1 envolvendo algum tipo de junção

># Marco de Entrega 03: Do item 9.2 até o ítem 9.10 (10 PTS)<br>

### 10 RELATÓRIOS E GRÁFICOS

#### a) análises e resultados provenientes do banco de dados desenvolvido (usar modelo disponível)
#### b) link com exemplo de relatórios será disponiblizado pelo professor no AVA
#### OBS: Esta é uma atividade de grande relevância no contexto do trabalho. Mantenha o foco nos 5 principais relatórios/resultados visando obter o melhor resultado possível.

    

### 11	AJUSTES DA DOCUMENTAÇÃO, CRIAÇÃO DOS SLIDES E VÍDEO PARA APRESENTAÇAO FINAL <br>

#### a) Modelo (pecha kucha)<br>
#### b) Tempo de apresentação 6:40 

># Marco de Entrega 04: Itens 10 e 11 (20 PTS) <br>
<br>
<br>




### 12 FORMATACAO NO GIT:<br> 
https://help.github.com/articles/basic-writing-and-formatting-syntax/
<comentario no git>
    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
    
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/
#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

    
### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. <strong>Caso existam arquivos com conteúdos sigilosos<strong>, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário do git "profmoisesomena", para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://www.sis4.com/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")


