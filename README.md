# Otavio Calderan Bruguel

## Introdução

Olá! Meu nome é **Otavio Calderan**, sou um desenvolvedor de sistemas e atualmente estou cursando Fatec, onde ingressei
no início de 2023. Meu objetivo é construir e desenvolver uma carreira sólida na área de Tecnologia da Informação (
T.I )

> [!NOTE]
> Em abril de 2024, iniciei meu primeiro estágio como **Cientista de Dados**, onde tive a oportunidade de aprender e
> aplicar diversas tecnologias relacionadas a IA, desenvolvimento **Web/FullStack**, manipulação de dados e visão
> computacional.

## Contatos

- **[GitHub](https://github.com/Otavio-CB)**  
  Meus projetos e contribuições em desenvolvimento de software.

- **[LinkedIn](https://www.linkedin.com/in/otavio-calderan/)**  
  Meu perfil profissional, onde compartilho experiências e conecto-me com outros profissionais da área.

## Meus Principais Conhecimentos

Aqui estão alguns dos meus principais conhecimentos, com foco nas áreas em que tenho maior domínio e desejo me
aprofundar ao longo da minha carreira:

### Linguagens de Programação

- **Python** (foco em análise de dados e IA)
- **Java** (desenvolvimento web e fullstack)
- **SQL** (manipulação e consulta de bancos de dados)

### Ferramentas e Tecnologias

- **Pandas** e **NumPy** (manipulação de dados)
- **Scikit-learn** e **TensorFlow** (machine learning e IA)
- **Vue.js** e **Node.js** (desenvolvimento web fullstack)
- **Git** e **GitHub** (controle de versão e colaboração)

### Bancos de Dados

- **MySQL** e **PostgreSQL** (bancos relacionais)
- **MongoDB** (banco NoSQL)

## Objetivos Futuros

- Aprofundar meus conhecimentos em **Inteligência Artificial** e **Machine Learning** (Ciência de Dados).

## Meus Projetos

## Projeto: Sistema de Avaliação 360° (2023-2)

Este programa foi desenvolvido para viabilizar a avaliação dos alunos com base na metodologia **Avaliação 360°**. O
sistema oferece dois níveis de acesso: **Administrador** e **Aluno**, cada um com funcionalidades específicas.

> [!NOTE]  
> O projeto foi criado para facilitar a avaliação contínua e colaborativa, permitindo que os alunos avaliem seus colegas
> de grupo, realizem autoavaliações e visualizem os resultados. Já o administrador tem controle total sobre a criação de
> turmas, grupos, registro de alunos e análise dos resultados por meio de dashboards operacionais e gerenciais.

[**Repositório no GitHub**](https://github.com/wiz-fatec/avaliacao-360)

### Tecnologias Utilizadas

Aqui estão as principais tecnologias e ferramentas utilizadas no desenvolvimento do projeto:

![My Skills](https://skillicons.dev/icons?i=python,git,github,stackoverflow,vscode)

1. **Python**
    - Linguagem de programação utilizada para o desenvolvimento do **backend** da aplicação.
    - Foi essencial para criar **APIs** e manipular dados de forma eficiente.

2. **Git**
    - Sistema de controle de versão distribuído.
    - Fundamental para rastrear mudanças no código-fonte e colaborar com outros desenvolvedores de forma eficiente.

3. **GitHub**
    - Plataforma de hospedagem para projetos que utilizam Git.
    - Utilizada para compartilhamento de código, colaboração em equipe e controle de versão.

4. **Stack Overflow**
    - Plataforma de perguntas e respostas para desenvolvedores.
    - Foi uma ferramenta valiosa para obter suporte, resolver problemas e aprender com a comunidade de programadores.

### Funcionalidades Principais

- **Para Alunos**:
    - Visualizar a turma e o grupo ao qual está inserido.
    - Avaliar os membros do grupo e realizar autoavaliações.
    - Visualizar os resultados das avaliações realizadas.

- **Para Administradores**:
    - Criar turmas, grupos e registrar alunos.
    - Requisitar avaliações e monitorar os resultados.
    - Acessar dashboards operacionais e gerenciais para análise de dados.

### Destaques do Projeto

- **Metodologia 360°**: Avaliação abrangente que considera múltiplas perspectivas (autoavaliação e avaliação pelos
  pares).
- **Dashboards Interativos**: Visualização clara e intuitiva dos resultados para tomada de decisão.
- **Colaboração Eficiente**: Uso de Git e GitHub para garantir um fluxo de trabalho colaborativo e organizado.

### Contribuições Pessoais

<details>
<summary>Adição da Interface de Aluno</summary>

- Desenvolvi a tela inicial de avaliação do aluno, incluindo:
    - Exibição de dados básicos do aluno (Nome, Turma, Grupo).
    - Implementação de botões de navegação:
        - **Back**: Para retornar à tela de login.
        - **Rate**: Para iniciar a avaliação do aluno.
        - **Cancel**: Para encerrar a sessão.
        - **Result**: Para visualizar os resultados da avaliação.

> A interface foi projetada para ser intuitiva e de fácil utilização, garantindo uma experiência fluida para os alunos.

</details>

<details>
<summary>Correções Textuais, Visuais e Funcionais</summary>

- **Correção de repetições desnecessárias**:
    - Removi a duplicação na definição da variável `col1`.
- **Padronização dos botões**:
    - Traduzi os botões `Back`, `Rate`, `Cancel` e `Result` para `Voltar`, `Avaliação`, `Cancelar` e `Resultados`.
- **Ajustes na interface**:
    - Redimensionei a janela para `(300, 180)` para melhor adaptação dos elementos.
- **Correção da estrutura de eventos (`event_handler`)**:
    - Ajustei a indentação e removi código redundante.
    - Garanti chamadas adequadas para mudança de interface.

> Essas correções melhoraram a manutenibilidade do código e a experiência do usuário, eliminando inconsistências e
> redundâncias.

</details>

<details>
<summary>Implementação do Dashboard do Aluno e Ajustes na Interface</summary>

**Funcionalidades Adicionadas**:

1. **Criação do Dashboard do Aluno**:
    - Desenvolvi uma interface que permite ao aluno visualizar suas informações e interagir com o sistema.
2. **Ajustes na Tela de Aluno**:
    - Corrigi a estrutura do layout, removendo duplicações e organizando os elementos de maneira mais intuitiva.

**Melhorias Implementadas**:

- Eliminei a duplicação na definição da variável `layout`.
- Ajustei a disposição dos botões para melhor alinhamento.
- Corrigi o redirecionamento para a interface de Resultados, garantindo que o dashboard do aluno seja exibido
  corretamente.

> O dashboard foi projetado para fornecer uma visão clara e organizada das informações do aluno, melhorando a
> usabilidade.

</details>

<details>
<summary>Adição da Funcionalidade de Cadastro de Grupos</summary>

**Funcionalidades Adicionadas**:

1. **Criação de Grupos**:
    - Implementei a funcionalidade de cadastro de grupos, permitindo que os utilizadores criem grupos vinculados a
      turmas específicas.
2. **Integração na Interface Administrativa**:
    - Adicionei um botão na interface administrativa para acessar a tela de cadastro de grupos.

**Melhorias Implementadas**:

- Inclusão do módulo `interface.create_group` para permitir a criação de grupos.
- Adição de um novo evento `group` na interface administrativa para redirecionar para a tela de grupos.

> Essa funcionalidade facilitou a organização dos alunos em turmas e grupos, otimizando o processo de avaliação.

</details>

<details>
<summary>Correção de Erros e Evitação de Duplicidade</summary>

**Correções Realizadas**:

- **Remoção de duplicações**:
    - Eliminei a duplicação da `ComboBox`, mantendo apenas a definição correta.
- **Correção de referências**:
    - Ajustei a referência ao `ID` da turma, garantindo que o sistema busque o `ID` correto em vez do nome.
- **Prevenção de erros de indexação**:
    - Adicionei verificações para evitar erros ao acessar índices em listas vazias.

> Essas correções aumentaram a robustez do sistema, evitando falhas e melhorando a consistência dos dados.

</details>

<details>
<summary>Adição do Dashboard Geral do Aluno</summary>

**Funcionalidades Adicionadas**:

1. **Exibição do Nome do Aluno**:
    - O nome do aluno logado é exibido na interface, proporcionando uma experiência personalizada.
2. **Geração de Gráficos**:
    - Implementei a geração de um **gráfico radial** para visualização do desempenho do aluno em diferentes
      competências.

**Melhorias Implementadas**:

- Integração de gráficos para melhor interpretação dos dados.
- Interface intuitiva e visualmente atraente para o dashboard.

> O gráfico radial permite uma análise rápida e eficiente do desempenho do aluno, destacando áreas de melhoria.

</details>

### Hard Skills

Aqui estão as **hard skills** que utilizei e desenvolvi durante o projeto, juntamente com o nível de proficiência
alcançado em cada uma:


<details>
<summary>Programação Python - Sei fazer com consulta</summary>

- Desenvolvimento de aplicações **backend** e **frontend** com Python.
- Utilização de recursos da linguagem, como funções, listas, dicionários e manipulação de dados.
- Implementação de lógica de negócios e integração com APIs.

> Python foi a linguagem principal utilizada no projeto, especialmente para a criação de funcionalidades backend e
> manipulação de dados.

</details>

<details>
<summary>Desenvolvimento com PySimpleGUI - Sei fazer com consulta</summary>

- Criação de interfaces gráficas (telas) para interação com o usuário.
- Integração das interfaces com a lógica backend.
- Personalização de layouts e componentes visuais.

> PySimpleGUI foi essencial para a criação de interfaces intuitivas e funcionais, garantindo uma boa experiência do
> usuário.

</details>

<details>
<summary>Controle de Versão com Git - Sei utilizar com autonomia</summary>

- Gestão de branches (criação, fusão e exclusão).
- Resolução de conflitos durante o merge de branches.
- Uso de **rebase** para manter um histórico de commits limpo e organizado.
- Boas práticas de commit (mensagens claras e descritivas).

> Git foi fundamental para o controle de versão do projeto, permitindo colaboração eficiente e rastreamento de mudanças.

</details>

<details>
<summary>Colaboração e Hospedagem de Projetos com GitHub - Sei utilizar com autonomia</summary>

- Criação e gestão de repositórios.
- Revisão de código e aprovação de **pull requests**.
- Uso de **issues** para gerenciamento de tarefas e bugs.
- Configuração de **GitHub Actions** para integração contínua (CI/CD).

> GitHub foi a plataforma central para hospedagem do código, colaboração em equipe e revisão de contribuições.

</details>

<details>
<summary>Desenvolvimento com VSCode - Sei utilizar com autonomia</summary>

- Navegação eficiente no código e refatoração automatizada.
- **Debugging** avançado com uso de breakpoints condicionais.
- Configuração de plugins e temas para personalização do ambiente.
- Integração com ferramentas de teste e build.

> O VSCode foi a ferramenta principal de desenvolvimento, oferecendo um ambiente altamente personalizável e produtivo.

</details>

<details>
<summary>Pesquisa e Resolução de Problemas com Stack Overflow - Sei utilizar com autonomia</summary>

- Busca de soluções para problemas específicos de programação.
- Participação em discussões e compartilhamento de conhecimento.
- Adaptação de soluções existentes para contextos específicos do projeto.

> O Stack Overflow foi uma ferramenta valiosa para resolver desafios técnicos e aprender com a comunidade de
> desenvolvedores.

</details>

### Soft Skills

Aqui estão as **soft skills** que utilizei e desenvolvi durante o projeto, destacando em quais situações elas foram
fundamentais para o sucesso das atividades:

<details>
<summary>Comunicação</summary>

- Em reuniões diárias e outras cerimônias, aprendi a expor minhas opiniões de forma **clara e concisa**.
- Relatei o andamento das minhas tarefas de maneira que todos pudessem acompanhar o progresso.
- Essa prática me ajudou a construir uma comunicação mais **assertiva** e a colaborar de maneira mais **eficaz** com a
  equipe.

> A comunicação clara foi essencial para alinhar expectativas, evitar mal-entendidos e garantir que todos estivessem na
> mesma página.

</details>

<details>
<summary>Trabalho em Equipe</summary>

- Trabalhei em conjunto com colegas de diferentes áreas e perfis, o que me ensinou a **valorizar as contribuições de
  cada membro**.
- Aprendi a **dividir responsabilidades** e a construir soluções em conjunto, sempre visando o **objetivo comum**.
- Colaborei ativamente para resolver conflitos e garantir que todos se sentissem parte do processo.

> A habilidade de trabalhar em equipe foi crucial para integrar diferentes perspectivas e alcançar resultados mais
> robustos e criativos.

</details>

<details>
<summary>Adaptação à Mudanças</summary>

- Em um projeto dinâmico, foi essencial **adaptar-me rapidamente** às mudanças de escopo, novas demandas e prazos
  apertados.
- Aprendi a ser **flexível** e a manter a calma mesmo em situações de pressão.
- Essa capacidade foi crucial para manter a **produtividade** e a **qualidade do trabalho**.

> A adaptação às mudanças me permitiu lidar com imprevistos de forma eficiente, garantindo que o projeto continuasse
> avançando.

</details>

<details>
<summary>Resolução de Problemas</summary>

- Fui desafiado a encontrar soluções **criativas** para obstáculos inesperados.
- Desenvolvi uma abordagem mais **analítica** e aprendi a **pensar fora da caixa** para resolver problemas de forma
  eficaz e eficiente.
- Utilizei ferramentas como Stack Overflow e documentação técnica para embasar minhas decisões.

> A resolução de problemas foi uma habilidade-chave para superar desafios técnicos e garantir a entrega de
> funcionalidades dentro do prazo.

</details>

<details>
<summary>Gestão do Tempo</summary>

- Com múltiplas tarefas e prazos para gerenciar, aprendi a **priorizar atividades** e organizar meu tempo de forma
  estratégica.
- Utilizei técnicas como **listas de tarefas** e **definição de metas diárias** para manter o foco.
- Isso me permitiu entregar resultados **consistentes** dentro dos prazos estabelecidos.

> A gestão do tempo foi essencial para equilibrar demandas concorrentes e garantir a entrega de todas as tarefas com
> qualidade.

</details>

## Projeto: Sistema de Avaliação de Trabalhos de Graduação (2023-8)

O projeto consiste no desenvolvimento de uma aplicação para facilitar a visualização e gestão das avaliações dos
Trabalhos de Graduação (TG) dos alunos. A aplicação permitirá a leitura de um arquivo ".csv" contendo respostas de
formulários preenchidos pelos alunos, possibilitando a atribuição de notas, feedbacks e a geração de relatórios úteis
para o gerenciamento das turmas. Além disso, a aplicação permitirá o agendamento de entregas e a definição da quantidade
de entregas, com a nota final sendo calculada com base em uma média das notas distribuídas ao longo dessas entregas.

[**Repositório no GitHub**](https://github.com/wiz-fatec/api-2BD)

### Tecnologias Utilizadas

Aqui estão as principais tecnologias utilizadas no projeto, juntamente com sua importância:

![My Skills](https://skillicons.dev/icons?i=java,git,github,stackoverflow,vscode)

1. **Java**
    - Linguagem de programação amplamente usada no desenvolvimento da aplicação.
    - Foi essencial para criar uma aplicação **robusta e escalável**, capaz de manipular grandes volumes de dados.

2. **JavaFX**
    - Framework para desenvolvimento de interfaces gráficas em Java.
    - Permitiu a criação de uma interface **amigável e intuitiva** para os usuários, facilitando a visualização e
      interação com os dados.

3. **Git**
    - Sistema de controle de versão distribuído.
    - Essencial para **rastrear mudanças** no código-fonte e colaborar com outros desenvolvedores de forma eficiente.

4. **GitHub**
    - Plataforma de hospedagem para projetos que utilizam Git.
    - Foi importante para o **compartilhamento de código**, **colaboração** e **controle de versão**.

5. **Stack Overflow**
    - Plataforma de perguntas e respostas para desenvolvedores.
    - Foi uma ferramenta valiosa para obter suporte, resolver problemas e aprender com a comunidade de programadores.

6. **Visual Studio Code (VSCode)**
    - Editor de código-fonte leve.
    - Facilitou o desenvolvimento com suporte para **diversas linguagens**, **extensões** e **integração com Git**.

### Destaques do Projeto

- **Leitura e Visualização de Dados**: A aplicação permite a leitura de arquivos ".csv" e a visualização dos dados de
  forma clara e organizada, facilitando a análise das respostas dos alunos.
- **Atribuição de Notas e Feedbacks**: A aplicação oferece uma interface para atribuição de notas e feedbacks aos
  alunos, com a possibilidade de salvar essas informações para consultas futuras.
- **Agendamento de Entregas**: A funcionalidade de agendamento de entregas permite definir prazos e quantidades de
  entregas, com a nota final sendo calculada com base em uma média das notas distribuídas ao longo dessas entregas.
- **Geração de Relatórios**: A aplicação gera relatórios úteis para o gerenciamento das turmas, facilitando a rotina e o
  acompanhamento das pendências das apresentações.

### Contribuições Pessoais

<details>
<summary>Implementação do Processador de CSV</summary>

- **Adição das dependências no `pom.xml`**:
    - **Apache Commons CSV**: Adicionada a dependência `commons-csv` (versão 1.9.0) para facilitar a leitura e
      manipulação de arquivos CSV.
    - **JavaFX**: Adicionada a dependência `javafx-controls` (versão 15.0.1) para suporte à interface gráfica.

- **Criação da classe `CSVProcessor`**:
    - **Função `readCSVToListOfLists`**: Implementação de um método para ler um arquivo CSV e convertê-lo em uma lista
      de listas de strings.
    - **Uso da biblioteca Apache Commons CSV**: Utilização de `CSVParser` e `CSVFormat` para processar o arquivo CSV de
      forma eficiente.
    - **Tratamento de exceções**: Captura de exceções de I/O (`IOException`) para garantir robustez no processamento de
      arquivos.

> Esta classe fornece a base para o processamento de arquivos CSV, permitindo a leitura e conversão dos dados para uma
> estrutura manipulável em Java.

</details>

<details>
<summary>Implementação da Tela HomeScreen com JavaFX</summary>

- **Criação da classe `HomeScreen`**:
    - **Uso de `FXMLLoader`**: Carregamento do arquivo FXML (`HomeScreen.fxml`) para definir a interface gráfica.
    - **Configuração da cena e palco**: Definição da cena (`Scene`) e configuração do palco (`Stage`) para exibição da
      tela.
    - **Restrição de redimensionamento**: A tela foi configurada para não ser redimensionável (`setResizable(false)`).

> A interface gráfica e o controlador foram desenvolvidos para permitir a interação do usuário com o sistema,
> integrando-se ao backend para processamento de arquivos CSV.

</details>

<details>
<summary>Tratamento de Conflitos e Configuração do `.gitignore`</summary>

- **Adição de entradas no `.gitignore`**:
    - **IntelliJ**: Ignorar pastas e arquivos gerados pelo IntelliJ (`out/`, `.idea`).
    - **Maven**: Ignorar a pasta `target`, que contém os arquivos compilados e gerados pelo Maven.

```plaintext
# IntelliJ
out/
.idea
target
```

> Essas configurações ajudam a evitar o versionamento de arquivos desnecessários ou específicos do ambiente de
> desenvolvimento, reduzindo conflitos e mantendo o repositório limpo.

</details>

<details>
<summary>Implementação da Conexão com o Banco de Dados</summary>

- **Criação da classe `ConnectionDataBase`**:
    - **Configuração da conexão**: Definição da URL, usuário e senha para conexão com um banco de dados PostgreSQL.
    - **Uso de `DriverManager`**: Utilização do `DriverManager` para estabelecer a conexão com o banco de dados.
    - **Tratamento de exceções**: Captura de exceções como `SQLException` e `ClassNotFoundException` para garantir
      robustez na conexão.
    - **Singleton pattern**: Implementação de um padrão singleton para garantir que apenas uma instância da conexão seja
      criada.

- **Teste da conexão na classe `Main`**:
    - **Inicialização da conexão**: Chamada do método `getConexao()` para verificar a conexão com o banco de dados.
    - **Mensagem de confirmação**: Exibição de uma mensagem no console indicando que a conexão foi estabelecida com
      sucesso.

> A implementação da conexão com o banco de dados permite a integração do sistema com um banco de dados PostgreSQL,
> seguindo boas práticas de tratamento de exceções e gerenciamento de recursos.

</details>

<details>
<summary>Implementação dos Models para Persistência de Dados</summary>

- **Adição dos models**:
    - Foram criadas classes para representar e manipular os dados das entidades do sistema, utilizando JDBC para
      interação com o banco de dados.
    - Cada model contém métodos para inserir dados no banco de dados, seguindo boas práticas de tratamento de exceções e
      gerenciamento de recursos.

#### **AdvisorModel**:

- **Responsabilidade**: Manipulação dos dados relacionados aos orientadores.
- **Método `addAdvisor`**: Insere um novo orientador no banco de dados, com os campos `nome` e `email_fatec`.

#### **StudentModel**:

- **Responsabilidade**: Manipulação dos dados relacionados aos alunos.
- **Método `addStudent`**: Insere um novo aluno no banco de dados, com os campos `nome`, `email`, `email_fatec`,
  `idOrientador` e `idturma`.

#### **TGModel**:

- **Responsabilidade**: Manipulação dos dados relacionados aos Trabalhos de Graduação (TG).
- **Método `addTG`**: Insere um novo TG no banco de dados, com os campos `descricao`, `tipo`, `problema`, `empresa`,
  `disciplina` e `idAluno`.

#### **TeamModel**:

- **Responsabilidade**: Manipulação dos dados relacionados às turmas.
- **Método `addTeam`**: Insere uma nova turma no banco de dados, com os campos `halfYear`, `year`, `idTeam`, `idStudent`
  e `idTG`.

#### **ToDoModel**:

- **Responsabilidade**: Manipulação dos dados relacionados às tarefas (To-Do).
- **Método `addToDo`**: Insere uma nova tarefa no banco de dados, com os campos `feedbacks`, `notes` e `idToDo`.

> Esses models formam a base para a manipulação de dados no sistema, permitindo a inserção de registros nas tabelas
> correspondentes do banco de dados.

</details>

<details>
<summary>Implementação da Funcionalidade de Exibição de Dados em Tabela</summary>

- **Objetivo**: Adicionar uma funcionalidade que permite exibir dados de forma organizada e legível em uma tabela,
  utilizando JavaFX.
- **Alterações e adições**:
    - **Alteração na classe `Main`**: Substituição da tela inicial (`HomeScreen`) pela nova tela com tabela (
      `HomeScreenWithTable`).
    - **Modificação no `StudentModel`**: Adição de métodos getters para permitir a exibição dos dados na tabela.
    - **Criação da classe `ButtonCell`**: Implementação de uma célula personalizada com botões para ações na tabela.
    - **Criação da tela `HomeScreenWithTable`**: Definição da interface gráfica com uma tabela para exibição de dados.
    - **Criação do controlador `HomeScreenWithTableController`**: Configuração da tabela e vinculação dos dados.

#### **Alteração na Classe `Main`**:

- **Mudança na tela inicial**: Substituição da tela `HomeScreen` pela tela `HomeScreenWithTable`.

#### **Modificação no `StudentModel`**:

- **Adição de getters**: Métodos para acessar os atributos `student` e `institutionalEmail`, necessários para exibição
  na tabela.

#### **Criação da Classe `ButtonCell`**:

- **Responsabilidade**: Implementação de uma célula personalizada com botões para ações na tabela.
- **Funcionalidade**: Exibe um botão "Ação" que, ao ser clicado, executa uma ação personalizada (neste caso, imprime o
  nome do estudante no console).

#### **Criação da Tela `HomeScreenWithTable`**:

- **Interface gráfica**: Definição da tela com uma tabela para exibição de dados, utilizando FXML.
- **Colunas da tabela**: Configuração das colunas para exibir informações como nome do estudante, e-mail institucional,
  e botões para ações.

#### **Criação do Controlador `HomeScreenWithTableController`**:

- **Configuração da tabela**: Vinculação dos dados da tabela com a lista de estudantes.
- **Uso de `ButtonCell`**: Adição de botões personalizados nas colunas de ações.

</details>

<details>
<summary>Implementação de Navegação entre Telas</summary>

- **Objetivo**: Adicionar a funcionalidade de navegação entre telas, permitindo que o usuário transite entre diferentes
  interfaces do sistema.
- **Alterações**:
    - **Adição do método `abrirTelaHomeScreenWithTable`**: Implementação de um método para abrir a tela
      `HomeScreenWithTable` e fechar a tela atual.

#### **Adição do Método `abrirTelaHomeScreenWithTable`**:

- **Responsabilidade**: Navegar para a tela `HomeScreenWithTable` e fechar a tela atual.
- **Funcionalidade**:
    - Cria uma nova instância da tela `HomeScreenWithTable`.
    - Inicia a nova tela em um novo `Stage`.
    - Fecha a tela atual, se necessário.

</details>

<details>
<summary>Implementação do CSVHandler e Aprimoramento dos Models</summary>

- **Objetivo**: Adicionar funcionalidade para processar dados de um arquivo CSV e populá-los no banco de dados, além de
  aprimorar os models com métodos adicionais para manipulação de dados.
- **Alterações**:
    - **Criação da classe `CSVHandler`**: Implementação de um handler para processar dados CSV e inserir no banco de
      dados.
    - **Aprimoramento dos models**:
        - Adição de métodos `getSubmit()` para recuperar dados do banco.
        - Adição de métodos getters e setters para manipulação de atributos.
        - Implementação de métodos para inserção de dados no banco.

#### **Criação da Classe `CSVHandler`**:

- **Responsabilidade**: Processar dados de um arquivo CSV e inserir no banco de dados.
- **Funcionalidade**:
    - Recebe uma lista de listas de strings (`dataList`), onde cada sublista representa uma linha do CSV.
    - Popula as tabelas `orientador`, `aluno`, `tg` e `turma` no banco de dados com base nos dados do CSV.

#### **Aprimoramento do `AdvisorModel`**:

- **Adição de métodos**:
    - `getFatecEmail()`, `setFatecEmail()`, `getName()`, `setName()`, `getId()`, `setId()`: Getters e setters para os
      atributos.
    - `getSubmit()`: Recupera todos os orientadores do banco de dados.

#### **Aprimoramento do `SubmitModel`**:

- **Adição de métodos**:
    - `getSubmit()`: Recupera todas as entregas do banco de dados.

#### **Aprimoramento do `TGModel`**:

- **Adição de métodos**:
    - Getters e setters para os atributos.
    - `getSubmit()`: Recupera todos os TGs do banco de dados.

#### **Aprimoramento do `TeamModel`**:

- **Adição de métodos**:
    - Getters e setters para os atributos.
    - `addTeam()`: Insere uma nova turma no banco de dados.
    - `getSubmit()`: Recupera todas as turmas do banco de dados.

</details>

<details>
<summary>Implementação do AdvisorController</summary>

**Funcionalidades Principais:**

- Processa dados de orientadores a partir de CSV
- Normaliza nomes (maiúsculas) e emails (minúsculas)
- Previne duplicação de orientadores
- Delega validação para `AdvisorModel`

> **PONTO DE INTEGRAÇÃO**  
> Chamado pelo `CSVHandler` durante o pipeline de processamento
</details>

<details>
<summary>Implementação do Controller StudentController</summary>


**Funcionalidades Principais:**

- Validação completa de emails (pessoal e Fatec)
- Normalização de dados
- Associação automática a equipes por tipo de TG
- Integração com validação de orientador

> **FLUXO DE VALIDAÇÃO**  
> Usa `EmailValidator` antes de passar dados para a camada de modelo
</details>

<details>
<summary>Implementação do Controller StudentModel</summary>


**Lógica de Equipes:**

**Principais Características:**

- Validação em cadeia para dados de alunos
- Lógica de associação automática a equipes
- Verificação de existência de orientador
- Atribuição de equipe baseada no tipo de TG

> **REGRAS DE NEGÓCIO**  
> Alunos são automaticamente alocados em equipes conforme seu tipo de TG
</details>

<details>
<summary>Implementação do Validator EmailValidator</summary>

**Características:**

- Validação básica de formato de email
- Lógica de fallback para emails institucionais
- Uso consistente em todas as entidades

> **DICA**  
> Pode ser estendido para incluir validação por regex mais robusta
</details>

<details>
<summary>Implementação do Método limparLabels</summary>

**Funcionalidades:**

- Reseta todos os campos de exibição de feedback e nota
- Define o status padrão "SEM NOTA" em vermelho
- Prepara a interface para uma nova consulta

> **CASO DE USO**  
> Chamado quando não há notas/feedback cadastrados ou quando ocorre mudança na seleção
</details>

<details>
<summary>Implementação do Método atualizarLabels</summary>

**Fluxo Lógico:**

1. Verifica se há entrega e TG selecionados
2. Obtém o ID do aluno atual
3. Busca no modelo os dados de nota e feedback
4. Se existir:
    - Armazena em cache (Maps)
    - Atualiza a interface
    - Ajusta o status
5. Se não existir:
    - Limpa os campos

> **MELHORIA FUTURA**  
> Poderíamos adicionar um loading state durante a consulta
</details>

<details>
<summary>Implementação do Método atualizarStatusEntrega</summary>

**Estados Possíveis:**

- `SEM NOTA` (Vermelho) - Estado inicial
- `PENDENTE` (Laranja) - Entrega existente sem avaliação
- `AVALIADO` (Verde) - Entrega com nota/feedback cadastrados

> **FEEDBACK VISUAL**  
> Código de cores intuitivo para rápida identificação do status
</details>

## Projeto: Dom Rock Pipeline Configurator (2024-2)

A **Dom Rock** possui uma arquitetura de processamento de dados em cadeia, chamada **pipeline**, que inclui vários
estágios. Esses estágios são orquestrados automaticamente com base nas características das fontes de dados e nas
soluções de algoritmos de IA ou modelos matemáticos, conforme as necessidades dos clientes.

> [!NOTE]  
> Durante a implantação da solução, é necessário configurar as fontes de dados envolvidas para que a plataforma funcione
> corretamente. Atualmente, essa configuração é feita manualmente, o que é um passo **crítico e demorado** para os
> técnicos. O desafio, portanto, foi criar uma **interface amigável** para facilitar essa configuração.

[**Repositório no GitHub**](https://github.com/wiz-fatec/dom-rock-pipeline-configurator)

### Tecnologias Utilizadas

Aqui estão as principais tecnologias utilizadas no projeto, juntamente com sua importância:

![My Skills](https://skillicons.dev/icons?i=java,spring,html,css,vue,mysql,git,github,idea,webstorm,stackoverflow)

1. **Java**
    - Linguagem de programação amplamente usada no desenvolvimento do **backend**.
    - Foi essencial para criar uma aplicação **robusta e escalável**.

2. **Spring**
    - Framework para desenvolvimento de aplicações Java.
    - Ofereceu suporte para **injeção de dependências**, **gerenciamento de transações** e criação de **APIs REST**.
    - Facilitou a criação de aplicações web e microsserviços.

3. **HTML**
    - Linguagem de marcação utilizada na construção de páginas web.
    - Foi a base para a estruturação da interface do usuário.

4. **CSS**
    - Linguagem de estilo usada para descrever a apresentação de documentos HTML.
    - Foi crucial para **estilizar e formatar** páginas web, melhorando a aparência e a experiência do usuário.

5. **Vue.js**
    - Framework JavaScript para construção de interfaces de usuário **interativas e reativas**.
    - Facilitou a criação de aplicações web dinâmicas com uma arquitetura baseada em **componentes**.

6. **MySQL**
    - Sistema de gerenciamento de banco de dados relacional.
    - Foi crucial para **armazenar e gerenciar** dados de forma estruturada em aplicações web.

7. **Git**
    - Sistema de controle de versão distribuído.
    - Essencial para **rastrear mudanças** no código-fonte e colaborar com outros desenvolvedores de forma eficiente.

8. **GitHub**
    - Plataforma de hospedagem para projetos que utilizam Git.
    - Foi importante para o **compartilhamento de código**, **colaboração** e **controle de versão**.

9. **IntelliJ IDEA**
    - Ambiente de desenvolvimento integrado (IDE) para programação Java.
    - Facilitou o desenvolvimento com suporte avançado para **código**, **debugging** e **testes**.

10. **WebStorm**
    - IDE da JetBrains focada em **JavaScript**, **HTML** e **CSS**.
    - Ideal para o desenvolvimento de aplicações web modernas e front-end.

11. **Stack Overflow**
    - Plataforma de perguntas e respostas para desenvolvedores.
    - Foi fundamental para obter **suporte**, **resolver problemas** e aprender com a comunidade de programadores.

### Destaques do Projeto

- **Interface Amigável**: Desenvolvimento de uma interface intuitiva para simplificar a configuração das fontes de
  dados.
- **Arquitetura Escalável**: Utilização de tecnologias modernas para garantir uma solução robusta e adaptável.

### Contribuições Pessoais

<details>
<summary>Adição das Versões Iniciais para o Processamento de CSV e JSON</summary>

- **Adição da dependência GSON**:
    - Manipulação do arquivo `pom.xml` para incluir a dependência GSON (versão 2.10.1).
    - A biblioteca GSON permite a **conversão de objetos Java para JSON** e vice-versa, essencial para a manipulação
      eficiente de dados no Spring Boot.

- **Criação de classes iniciais**:
    - **CsvConverter**: Classe para futuras implementações de conversão e processamento de arquivos CSV.
    - **JsonConverter**: Utiliza a biblioteca GSON para conversão de dados JSON.
    - **JsonDataModel**: Modelagem dos dados JSON a serem processados.
    - **SendJson**: Classe para envio ou manipulação de dados JSON.

> Essas classes formaram a base para o desenvolvimento das funcionalidades de conversão e processamento de dados,
> alinhadas com a arquitetura do projeto.

</details>

<details>
<summary>Adição do Método de Atualização de Campos na Classe LZMetadataConfig</summary>

- Implementação do método `updateFields`:
    - Atualiza os campos do objeto com base nos dados fornecidos pelo `MetadataConfigDTO`.
    - **Campos atualizados**:
        - `name` e `fileName`: Se os valores correspondentes no DTO não forem nulos.
        - `frequency`: Atualizado com o valor de `frequencyNumber` ou convertido a partir de `frequencyType`.
        - `hasHeader`: Atualizado para `1` ou `0` dependendo do valor booleano no DTO.

> Esse método aumentou a flexibilidade da classe, permitindo a modificação dos dados de configuração em tempo de
> execução.

</details>

<details>
<summary>Implementação do Método PUT para Atualização de Configurações</summary>

- **Rota:** `/list-view`
- **Método:** `updateConfig`:
    - Implementado com a anotação `@PutMapping`.
    - Recebe um objeto `MetadataConfigDTO` via `@RequestBody`.
    - Localiza a configuração correspondente usando o `fileId`.
    - Atualiza os campos com o método `updateFields` e salva a configuração no repositório.
    - Retorna um `ResponseEntity` com o objeto atualizado em caso de sucesso, ou `ResponseEntity.notFound()` em caso de
      falha.

> Esse método permitiu a atualização dinâmica das configurações, melhorando a usabilidade da aplicação.

</details>

<details>
<summary>Alteração no Método GET para Melhor Manipulação de Valores Nulos</summary>

- **Método:** `details`:
    - Alterado de `getReferenceById` para `findById`.
    - Uso de `Optional` para lidar com valores nulos.
    - Retorno adequado encapsulado em um `ResponseEntity`.

> Essa alteração aumentou a robustez do método, evitando erros de referência nula e melhorando a experiência do usuário.

</details>

<details>
<summary>Atualização da Classe MetadataConfigDTO para Sincronizar Campos</summary>

- **Classe:** `MetadataConfigDTO`:
    - Atualizado o construtor para refletir corretamente os campos da entidade `LZMetadataConfig`.
    - O construtor agora recebe um objeto `LZMetadataConfig` e uma lista de `ColumnConfig`, preenchendo os respectivos
      campos no DTO.

> Essa atualização garantiu a sincronização entre o DTO e a entidade, facilitando a manipulação de dados.

</details>

<details>
<summary>Aprimoramento do Método updateFields para Manipulação de Colunas</summary>

- **Classe:** `LZMetadataConfig`:
    - Estendido o método `updateFields` para incluir a atualização da lista `columns` caso presente no
      `MetadataConfigDTO`.
    - Limpeza da lista `columns` existente antes de atualizá-la com os novos valores, evitando redundâncias.

> Essa melhoria permitiu a atualização completa das configurações, incluindo as colunas associadas.

</details>

<details>
<summary>Criação das Tabelas de Empresa, Usuário e Permissão</summary>

- **Tabela:** `permission`:
    - Colunas: `id_permission`, `description`, e `type`.
    - Restrição `CHECK` em `type`, limitando os valores a `'lz'`, `'bronze'`, ou `'silver'`.

- **Tabela:** `user`:
    - Colunas: `name`, `email`, e `password`.
    - `email` definido como chave primária.

- **Tabela:** `company`:
    - Colunas: `cnpj` e `fantasy_name`.
    - `cnpj` definido como chave primária.

> Essas tabelas formaram a base para o gerenciamento de usuários, empresas e permissões no sistema.

</details>

<details>
<summary>Modificações na Tabela Existente de Arquivo</summary>

- **Tabela:** `arquivo`:
    - Adicionada a coluna `file_has_header` (tipo `INT`), indicando se o arquivo possui cabeçalho.
    - Adicionada a coluna `cnpj` (tipo `VARCHAR(18)`), associando o arquivo à tabela `company`.
    - Criada a restrição de chave estrangeira `fk_cnpj` para a coluna `cnpj`, referenciando a chave primária da tabela
      `company`.

> Essas modificações melhoraram a integridade dos dados e a relação entre as tabelas.

</details>

<details>
<summary>Criação da Tela Silver</summary>

- **Componente:** `Silver`:
    - Criado um novo componente Vue para a tela "Silver", utilizando TypeScript para tipagem forte.
    - Propriedades recebidas: `configList`, `tagInfo`, e `bronzeConfig`.

- **Lógica de Navegação**:
    - Função `gotoSilverConfig` para navegar para a rota `/home` ao clicar em um dos botões de configuração.

- **Validação de Colunas**:
    - Função `validOrInvalid` para validar colunas dentro do `BConfig`.

- **Template e Estilo**:
    - Estrutura de layout com um `div` principal que contém uma classe `container`.
    - Estilos definidos com SCSS, utilizando classes como `.grid-wrap`, `.banner`, `.invalid-tag`, e `.valid-tag`.

> A tela Silver foi projetada para ser intuitiva e visualmente atraente, melhorando a experiência do usuário.

</details>

<details>
<summary>Integração de Componentes e Gerenciamento de Estado</summary>

- **Componentes Importados**:
    - `AppHeader`, `DRModal`, e `LVSilverContainer`, utilizados para compor a interface da tela "Silver".

- **Gerenciamento de Estado**:
    - Utilizadas referências (`ref`) para controlar a lista de configurações (`configList`), o estado do modal (
      `showModal`), e a configuração selecionada (`selectedConfig`).

> A integração de componentes e o gerenciamento de estado foram essenciais para criar uma interface dinâmica e
> responsiva.

</details>

<details>
<summary>Chamada de API para Atualização da Lista de Configurações</summary>

- **Função Assíncrona:** `getConfig`:
    - Realiza uma chamada `GET` para `http://localhost:8080/lz-config/list-view` e atualiza `configList` ao montar o
      componente.

> Essa funcionalidade garantiu que a lista de configurações fosse sempre atualizada, proporcionando uma experiência de
> usuário mais fluida.

</details>

<details>
<summary>Atualização do Alinhamento do Botão de Cadastro</summary>

- **Ajuste de Estilo**:
    - Modificação da margem da classe `.saveButton` para `-80px`, alinhando melhor o botão no layout.
    - Manutenção da estrutura de layout grid, com espaçamento definido por `column-gap`.

> Esses ajustes melhoraram a estética e a usabilidade da interface.

</details>

<details>
<summary>Criação do Componente DonutChart</summary>

- **Nova Dependência**:
    - Adicionada a dependência `vue-chartjs` (versão 5.3.1) para criação de gráficos no Vue 3.

- **Estrutura do Template**:
    - Criado o componente `DonutChart`, utilizando o gráfico de rosca (`Doughnut`) do `vue-chartjs`.

- **Lógica do Script**:
    - Importados e registrados os elementos do `Chart.js` necessários para o gráfico de rosca: `Title`, `Tooltip`,
      `Legend`, `ArcElement`, e `CategoryScale`.
    - Definida a interface `ChartDataProps` para tipagem das propriedades recebidas (`labels`, `values`, `colors`,
      `title`).
    - Configurados os dados do gráfico (`chartData`) utilizando as propriedades recebidas via `defineProps`.

- **Modificação das Cores**:
    - Atualização das cores do gráfico para uma nova paleta, garantindo maior contraste e diferenciação entre as seções.

> O componente `DonutChart` foi essencial para a visualização clara e intuitiva dos dados, melhorando a tomada de
> decisão.

</details>

### Hard Skills

Aqui estão as **hard skills** que utilizei e desenvolvi durante o projeto, juntamente com o nível de proficiência
alcançado em cada uma:

<details>
<summary>Programação Java - Sei fazer com consulta</summary>

- Desenvolvimento de aplicações **backend robustas e escaláveis**.
- Utilização de recursos da linguagem, como **collections**, **threads**, e **exceptions**.
- Implementação de lógica de negócios e integração com APIs.

> Java foi a linguagem principal utilizada no backend, garantindo a criação de uma aplicação robusta e de alta
> performance.

</details>

<details>
<summary>Desenvolvimento com Spring Framework - Sei fazer com consulta</summary>

- Criação de **APIs REST**.
- Injeção de dependências e gerenciamento de beans com **Spring IoC Container**.
- Gerenciamento de transações e configuração de segurança com **Spring Security**.
- Integração com bancos de dados usando **Spring Data JPA**.

> O Spring Framework foi essencial para simplificar o desenvolvimento de aplicações Java, oferecendo suporte a diversas
> funcionalidades críticas.

</details>

<details>
<summary>Estilização e Layout com CSS - Sei fazer com consulta</summary>

- Design **responsivo** usando **media queries**.
- **Flexbox** e **Grid Layout** para criação de layouts avançados.
- Aplicação de **animações** e **transições CSS**.
- Customização de temas e estilos para componentes web.

> O CSS foi crucial para garantir uma interface visualmente atraente e responsiva, melhorando a experiência do usuário.

</details>

<details>
<summary>Desenvolvimento Frontend com Vue.js - Sei fazer com consulta</summary>

- Criação de **componentes dinâmicos e reutilizáveis**.
- Gerenciamento de estado com **Vuex**.
- Manipulação de eventos e ciclo de vida dos componentes.
- Integração com APIs REST e manipulação de dados assíncronos.

> Vue.js foi escolhido por sua simplicidade e eficiência, permitindo a criação de interfaces interativas e de alta
> performance.

</details>

<details>
<summary>Gerenciamento de Bancos de Dados MySQL - Sei fazer com consulta</summary>

- Criação e manipulação de **tabelas**, **índices** e **relações**.
- Escrita e otimização de **consultas SQL complexas**.
- Gerenciamento de **transações** e controle de **concorrência**.

> MySQL foi fundamental para o armazenamento e gerenciamento eficiente dos dados da aplicação.

</details>

<details>
<summary>Controle de Versão com Git - Sei utilizar com autonomia</summary>

- Gerenciamento de **branches** (criação, fusão e exclusão).
- Resolução de **conflitos** durante o merge de branches.
- Uso de **rebase** para manter um histórico de commits limpo e organizado.
- Boas práticas de commit (mensagens claras e descritivas).

> Git foi essencial para o controle de versão do projeto, permitindo colaboração eficiente e rastreamento de mudanças.

</details>

<details>
<summary>Colaboração e Hospedagem de Projetos com GitHub - Sei utilizar com autonomia</summary>

- Criação e gestão de **repositórios**.
- Revisão de código e aprovação de **pull requests**.
- Uso de **issues** para gerenciamento de tarefas e bugs.
- Configuração de **GitHub Actions** para integração contínua (CI/CD).

> GitHub foi a plataforma central para hospedagem do código, colaboração em equipe e revisão de contribuições.

</details>

<details>
<summary>Desenvolvimento com IntelliJ IDEA - Sei utilizar com autonomia</summary>

- Navegação eficiente no código e **refatoração automatizada**.
- **Debugging** avançado com uso de breakpoints condicionais.
- Configuração de **plugins** e **temas** para personalização do ambiente.
- Integração com ferramentas de teste e build.

> O IntelliJ IDEA foi a ferramenta principal de desenvolvimento, oferecendo um ambiente altamente personalizável e
> produtivo.

</details>

<details>
<summary>Desenvolvimento com WebStorm - Sei utilizar com autonomia</summary>

- Desenvolvimento frontend utilizando **JavaScript**, **HTML** e **CSS**.
- **Debugging** e **profilamento** de código JavaScript.
- Suporte a frameworks modernos como **Vue.js** e **React**.
- Uso de ferramentas de build e task runners (**Webpack**, **npm scripts**).

> O WebStorm foi essencial para o desenvolvimento frontend, oferecendo suporte avançado para JavaScript e frameworks
> modernos.

</details>

<details>
<summary>Pesquisa e Resolução de Problemas com Stack Overflow - Sei utilizar com autonomia</summary>

- Busca de soluções para problemas específicos de programação.
- Participação em discussões e compartilhamento de conhecimento.
- Adaptação de soluções existentes para contextos específicos do projeto.

> O Stack Overflow foi uma ferramenta valiosa para resolver desafios técnicos e aprender com a comunidade de
> desenvolvedores.

</details>

#### Soft Skills

<details>
<summary>Comunicação</summary>

- Em reuniões diárias e outras cerimônias, aprendi a expor minhas opiniões de forma clara e concisa, além de relatar o
  andamento das minhas tarefas de maneira que todos pudessem acompanhar o progresso. Essa prática me ajudou a construir
  uma comunicação mais assertiva e a colaborar de maneira mais eficaz com a equipe.

</details>

<details>
<summary>Trabalho em equipe</summary>

- Trabalhar em conjunto com colegas de diferentes áreas e perfis me ensinou a valorizar as contribuições de cada membro,
  a dividir responsabilidades e a construir soluções em conjunto, sempre visando o objetivo comum.

</details>

<details>
<summary>Adaptação à mudanças</summary>

- Em um projeto dinâmico, foi essencial adaptar-me rapidamente às mudanças de escopo, novas demandas e prazos apertados.
  Aprendi a ser flexível e a manter a calma mesmo em situações de pressão, o que foi crucial para manter a produtividade
  e a qualidade do trabalho.

</details>

<details>
<summary>Resolução de problemas</summary>

- Fui desafiado a encontrar soluções criativas para obstáculos inesperados, o que me levou a desenvolver uma abordagem
  mais analítica e a pensar fora da caixa para resolver problemas de forma eficaz e eficiente.

</details>

<details>
<summary>Gestão do tempo</summary>

- Com múltiplas tarefas e prazos para gerenciar, aprendi a priorizar atividades, organizar meu tempo de forma
  estratégica e entregar resultados consistentes dentro dos prazos estabelecidos.

</details>

### Em 2024-8

### Em 2025-2

### Em 2025-8


