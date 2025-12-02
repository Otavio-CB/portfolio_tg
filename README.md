# Otavio Calderan Bruguel - Portfólio Acadêmico

## Introdução

<img src="assets/head.png" alt="header">

Olá! Meu nome é **Otavio Calderan**, sou desenvolvedor de sistemas e atualmente curso Banco de Dados na Fatec, onde
ingressei no início
de 2023. Meu objetivo é construir uma carreira sólida em Tecnologia da Informação (T.I.), com foco em **Ciência de Dados**
e **Desenvolvimento FullStack**.

Esse gosto e a busca por uma formação, focada na prática e alinhada ao mercado de trabalho, foram o que 
me trouxeram à **Fatec** em 2023. Escolhi o curso de **Banco de Dados** para construir uma base sólida que sustentasse 
meu objetivo de me tornar um especialista em **Ciência de Dados** e **Desenvolvimento FullStack**.

> [!NOTE]
> Em abril de 2024, iniciei meu primeiro estágio como **Cientista de Dados**, onde tive a oportunidade de aprender e
> aplicar diversas tecnologias relacionadas a IA, desenvolvimento **Web/FullStack**, manipulação de dados e visão
> computacional.

## Contatos

- **[GitHub](https://github.com/Otavio-CB)**  
  *Projetos e contribuições em desenvolvimento de software.*

- **[LinkedIn](https://www.linkedin.com/in/otavio-calderan/)**  
  *Perfil profissional e conexões na área de T.I.*

## Habilidades Técnicas (Hard Skills)

### Linguagens de Programação

- **Python** (Análise de dados, IA)
- **Java** (Desenvolvimento web/fullstack)
- **SQL** (Bancos de dados relacionais)

### Frameworks e Ferramentas

- **Pandas**, **NumPy** (Manipulação de dados)
- **Scikit-learn**, **TensorFlow** (Machine Learning/IA)
- **Vue.js**, **Node.js**, **Spring** (Full Stack)
- **Git**, **GitHub** (Controle de versão)

### Bancos de Dados

- **MySQL**, **PostgreSQL** (Relacionais)
- **MongoDB** (NoSQL)

## Objetivos Futuros

- Aprofundar conhecimentos em **Inteligência Artificial** e **Ciência de Dados**

---

## Meus Projetos

## Primeiro Semestre (2023-1): Sistema de Avaliação 360°

> [!IMPORTANT]
> **Problema:** A dificuldade de realizar o acompanhamento do desenvolvimento de competências socioemocionais 
> (soft skills) dos alunos de forma estruturada. O processo manual dificultava a aplicação da metodologia 360°, 
> tornando complexa a tabulação de feedbacks de autoavaliação e avaliação por pares, o que limitava a visão dos 
> professores sobre o desempenho individual.
>
> **Solução:** O desenvolvimento de uma plataforma desktop fundamentada na metodologia 360°, com dois níveis de acesso 
> distintos (Administrador e Aluno). A solução automatizou a coleta de dados e integrou dashboards interativos para 
> visualização de métricas, permitindo uma análise de desempenho rápida e promovendo um acompanhamento abrangente da 
> evolução de cada aluno.

[**📁 Repositório no GitHub**](https://github.com/wiz-fatec/avaliacao-360)

### Tecnologias Utilizadas

<a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"></a>
<a href="https://pysimplegui.readthedocs.io/en/latest/" target="_blank"><img src="https://img.shields.io/badge/PySimpleGUI-1A5D9F?style=for-the-badge&logo=python&logoColor=white" alt="PySimpleGUI"></a>
<a href="https://git-scm.com/" target="_blank"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"></a>
<a href="https://github.com/" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://code.visualstudio.com/" target="_blank"><img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code"></a>

- **Python** - **Função**: Desenvolvimento da lógica de backend, cálculos de médias ponderadas e manipulação dos dados de avaliação.

- **PySimpleGUI** - **Função**: Construção das telas de login, formulários de avaliação e renderização dos dashboards.

- **VSCode** - **Função**: Ambiente de desenvolvimento utilizado para escrita do código, refatoração de scripts e depuração.

- **Git** - **Função**: Gerenciamento de versões do código local e configuração do arquivo `.gitignore` para exclusão de arquivos temporários.

- **GitHub** - **Função**: Hospedagem remota do repositório e centralização das contribuições da equipe.

### Contribuições Pessoais

<details>
<summary>Interface do Usuário</summary>

**Tela de Avaliação do Aluno**

- Desenvolvimento completo da interface de avaliação com:
    - Exibição dinâmica de informações do aluno (Nome, Turma, Grupo)
    - Sistema de navegação com botões intuitivos:
        - `Voltar`: Retorno à tela de login
        - `Avaliar`: Início do processo de avaliação
        - `Cancelar`: Encerrar sessão
        - `Resultados`: Visualização das avaliações

**Dashboard de Desempenho**

- Implementação de visualização de dados com:
    - Gráfico radial para análise multidimensional de competências
    - Layout adaptável a diferentes resoluções
    - Integração fluida entre backend Python e frontend PySimpleGUI

</details>

<details>
<summary>Otimizações de Sistema</summary>

**Melhorias de Código**

- Refatoração completa do `event_handler`:
    - Correção de estrutura de eventos
    - Remoção de 15% de código redundante
    - Padronização da indentação
- Eliminação de duplicações:
    - Variável `col1` (redução de 200 linhas repetidas)
    - Componente `ComboBox` (unificação de 3 implementações)

**Padronização**

- Tradução e uniformização de elementos:
    - Botões (`Back`→`Voltar`, `Rate`→`Avaliar`)
    - Mensagens de sistema
    - Estrutura de arquivos

</details>

<details>
<summary>Gestão de Dados</summary>

**Sistema de Grupos**

- Implementação do módulo `create_group` com:
    - Cadastro de grupos vinculados a turmas
    - Validação automática de IDs
    - Prevenção de duplicatas (redução de 90% em registros repetidos)

**Persistência de Dados**

- Otimizações na estrutura:
    - Substituição de referências por nome para referências por ID
    - Tratamento de listas vazias
    - Verificação de integridade de dados

</details>

<details>
<summary>Métricas e Visualização</summary>

**Dashboard Analítico**

- Desenvolvimento de ferramentas de análise:
    - Algoritmos de média ponderada para avaliações
    - Normalização entre autoavaliação e avaliação por pares
    - Sistema de feedback visual imediato

**Visualização de Dados**

- Implementação de:
    - Gráficos radiais interativos
        - Painel personalizado para cada aluno
    - Indicadores de desempenho por competência

</details>

<details>
<summary>Controles e Validações</summary>

**Prevenção de Erros**

- Implementação de:
    - Verificação de completude de avaliações
    - Bloqueio de envios duplicados
    - Validação em tempo real de formulários

**Melhorias de Robustez**

- Adição de:
    - Tratamento de exceções para listas vazias
    - Verificação de índices
    - Sistema de contingência

</details>

### Hard Skills

| **Categoria**          | **Tecnologia** | **Nível**                   | **Aplicações/Detalhes**                       |
|------------------------|----------------|-----------------------------|-----------------------------------------------|
| **Linguagem**          | Python         | <span title="">★★★☆☆</span> | Interfaces gráficas, Pandas/NumPy para dados. |
| **Framework**          | PySimpleGUI    | <span title="">★★★☆☆</span> | Dashboards, fluxos de navegação.              |
| **Controle de Versão** | Git            | <span title="">★★★☆☆</span> | `.gitignore`.                                 |
| **Colaboração**        | GitHub         | <span title="">★★★☆☆</span> | Code review via Pull Requests.                |
| **IDE**                | VSCode         | <span title="">★★★★☆</span> | Depuração com breakpoints, extensões Python.  |

### Soft Skills

| **Habilidade**                        | **Situação e Ação Real (Storytelling)**                                                                                                                                                                                                                                                                                                     | **Impacto no Projeto**                                                                                            |
|:--------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------|
| **Adaptabilidade e Aprendizado Ágil** | No início do projeto, eu não dominava a linguagem **Python**, que era o requisito principal. Dediquei-me a estudar o *Python* e *PySimpleGUI* e implementar a interface gráfica o mais rápido possível, adaptando-me rapidamente à nova tecnologia devido ao curto espaço de tempo entre atividadaes de outras matérias e o projeto da API. | Entrega pontual da interface funcional, permitindo que o grupo focasse na lógica do backend.                      |
| **Colaboração e Integração**          | Entrei em um grupo onde não conhecia nenhum integrante. Para superar o distanciamento inicial e nivelar o conhecimento técnico, propus sessões de *Pair Programming* e mantive uma postura aberta para ouvir as ideias de todos.                                                                                                            | Criação de um ambiente de confiança mútua, onde as tarefas foram divididas de acordo com a facilidade de cada um. |
| **Inteligência Emocional**            | Ao lidar com as diferenças de personalidade e ritmo de trabalho dos novos colegas, atuei como mediador para evitar atritos, focando sempre no objetivo comum da entrega do MVP.                                                                                                                                                             | Manutenção da harmonia do time e redução de bloqueios de comunicação durante as Sprints.                          |

---

## Segundo Semestre (2023-2): Sistema de Avaliação de Trabalhos de Graduação

> [!IMPORTANT]
> **Problema:** A complexidade administrativa na gestão das avaliações dos Trabalhos de Graduação (TG), que dependia de 
> processos manuais para consolidar respostas de formulários (arquivos .csv), calcular médias ponderadas de diferentes 
> entregas e organizar feedbacks, gerando sobrecarga e risco de inconsistências nas notas.
>
> **Solução:** Uma aplicação desktop focada na gestão acadêmica que automatiza a importação de dados via .csv e o 
> cálculo de notas finais. O sistema centraliza o agendamento de entregas, permite a atribuição detalhada de feedbacks 
> e notas por etapa, e gera relatórios automáticos para o acompanhamento das turmas.

[**📁 Repositório no GitHub**](https://github.com/wiz-fatec/api-2BD)

### Tecnologias Utilizadas

<a href="https://www.java.com/" target="_blank"><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"></a>
<a href="https://openjfx.io/" target="_blank"><img src="https://img.shields.io/badge/JavaFX-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="JavaFX"></a>
<a href="https://git-scm.com/" target="_blank"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"></a>
<a href="https://github.com/" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://code.visualstudio.com/" target="_blank"><img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code"></a>

- **Java** - **Função**: Linguagem principal do backend, responsável pela lógica de negócios (Controllers), manipulação de modelos de dados (Models) e integração com o banco via JDBC.

- **JavaFX** - **Função**: Construção da interface gráfica desktop, incluindo telas FXML, tabelas interativas (`TableView`) e gerenciamento de eventos de usuário.

- **Git** - **Função**: Controle de versão distribuído, gerenciamento de branches e resolução de conflitos durante o desenvolvimento em equipe.

- **GitHub** - **Função**: Hospedagem remota do código fonte e colaboração via Pull Requests.

- **VSCode** - **Função**: Ambiente de desenvolvimento integrado utilizado para codificação, depuração e execução da aplicação.

### Contribuições Pessoais

<details>
<summary>Processamento de Arquivos CSV</summary>

- **Leitura e Conversão de CSV**: Implementação da classe `CSVProcessor` com o método `readCSVToListOfLists` para ler
  arquivos CSV e convertê-los em listas de listas de strings
- **Utilização de Biblioteca Externa**: Integração da biblioteca Apache Commons CSV (versão 1.9.0) através da adição da
  dependência `commons-csv` no `pom.xml`, utilizando `CSVParser` e `CSVFormat` para um processamento eficiente
- **Robustez no Processamento**: Implementação de tratamento de exceções (`IOException`) garantindo a robustez do
  processo de leitura

> A criação deste componente centraliza a lógica de leitura de CSV, facilitando a ingestão de dados externos no sistema
> de forma estruturada e confiável

</details>

<details>
<summary>Interface Gráfica com JavaFX</summary>

- **Tela Inicial (`HomeScreen`)**: Desenvolvimento da classe `HomeScreen` para carregar o layout da interface a partir
  do arquivo `HomeScreen.fxml` usando `FXMLLoader`. Configuração da `Scene` e do `Stage` para exibição, com restrição de
  redimensionamento (`setResizable(false)`)
- **Exibição de Dados em Tabela (`HomeScreenWithTable`)**: Criação da interface `HomeScreenWithTable` utilizando uma
  `TableView` para apresentar dados de forma organizada. Definição das colunas para exibir informações relevantes e
  implementação do controlador `HomeScreenWithTableController` para vincular os dados à tabela
- **Células Interativas**: Implementação da classe `ButtonCell`, um renderizador de células personalizado que adiciona
  botões de ação em cada linha da tabela, permitindo interação direta com os dados apresentados

> A implementação da interface JavaFX proporciona uma interação visual rica com o sistema, permitindo aos usuários
> visualizar e interagir com os dados de maneira intuitiva

</details>

<details>
<summary>Configuração e Gerenciamento do Projeto</summary>

- **Gerenciamento de Dependências (Maven)**: Adição das dependências `commons-csv` e `javafx-controls` no arquivo
  `pom.xml` para gerenciar as bibliotecas externas necessárias ao projeto
- **Controle de Versionamento (`.gitignore`)**: Configuração do arquivo `.gitignore` para excluir arquivos e pastas
  específicos do ambiente de desenvolvimento (IntelliJ: `out/`, `.idea/`; Maven: `target/`), mantendo o repositório
  limpo e prevenindo conflitos desnecessários

> A correta configuração do projeto garante a gestão eficiente das dependências e a organização do repositório de
> código

</details>

<details>
<summary>Persistência de Dados com PostgreSQL</summary>

- **Conexão com o Banco de Dados**: Implementação da classe `ConnectionDataBase` para estabelecer a conexão com um banco
  de dados PostgreSQL, utilizando `DriverManager` e configurando URL, usuário e senha. Adição de tratamento de
  exceções (`SQLException`, `ClassNotFoundException`) para garantir a robustez da conexão
- **Padrão Singleton para Conexão**: Utilização do padrão Singleton na classe `ConnectionDataBase` para assegurar que
  apenas uma instância da conexão seja criada durante a execução da aplicação, otimizando o uso de recursos
- **Teste de Conexão**: Implementação de um teste na classe `Main` para verificar se a conexão com o banco de dados foi
  estabelecida com sucesso, apresentando uma mensagem de confirmação no console

> A implementação da conexão com PostgreSQL permite que o sistema persista os dados de forma confiável e eficiente

</details>

<details>
<summary>Modelagem de Dados (Models)</summary>

- **Criação de Models para Entidades**: Desenvolvimento de classes (Models) para representar as entidades do sistema (
  `AdvisorModel`, `StudentModel`, `TGModel`, `TeamModel`, `ToDoModel`, `SubmitModel`), com integração via JDBC ao banco
  de dados
- **Operações de Persistência**: Implementação de métodos em cada Model (ex: `addAdvisor`, `addStudent`, `addTG`,
  `addTeam`, `addToDo`) para inserir novos registros nas tabelas correspondentes, incorporando tratamento de exceções e
  gerenciamento de recursos
- **Acesso e Manipulação de Atributos**: Adição de métodos getters e setters para permitir o acesso e a modificação dos
  atributos de cada entidade
- **Recuperação de Dados**: Implementação do método `getSubmit()` em diversos Models para buscar todos os registros
  correspondentes do banco de dados

> Os Models abstraem a interação com o banco de dados, fornecendo uma interface clara para manipular e persistir os
> dados das diferentes entidades do sistema

</details>

<details>
<summary>Navegação entre Telas (JavaFX)</summary>

- **Implementação de Navegação**: Adição do método `abrirTelaHomeScreenWithTable` para facilitar a transição da tela
  atual para a `HomeScreenWithTable`. O método cria uma nova instância da tela de destino, a exibe em um novo `Stage` e,
  opcionalmente, fecha a tela de origem

> A implementação da navegação entre telas melhora a usabilidade da aplicação, permitindo que os usuários se movam
> facilmente entre as diferentes funcionalidades

</details>

<details>
<summary>Processamento de CSV e População do Banco de Dados</summary>

- **Handler de CSV (`CSVHandler`)**: Criação da classe `CSVHandler` para processar dados de arquivos CSV e inserir as
  informações nas tabelas do banco de dados (`orientador`, `aluno`, `tg`, `turma`). O handler recebe uma lista de listas
  de strings (representando as linhas do CSV) e itera sobre ela para realizar as operações de inserção

> O `CSVHandler` automatiza a importação de dados de arquivos CSV para o banco de dados, simplificando a inicialização e
> a atualização das informações do sistema

</details>

<details>
<summary>Lógica de Negócios (Controllers)</summary>

- **`AdvisorController`**: Implementação para processar dados de orientadores extraídos de CSV, realizando normalização
  de nomes (maiúsculas) e emails (minúsculas), prevenindo duplicações e delegando a validação para o `AdvisorModel`. É
  invocado pelo `CSVHandler`
- **`StudentController`**: Desenvolvimento para validar completamente emails (pessoal e Fatec), normalizar dados de
  alunos, associá-los automaticamente a equipes com base no tipo de TG e integrar-se com a validação de orientadores,
  utilizando o `EmailValidator`
- **`StudentModel` (Lógica de Equipes)**: Implementação da lógica de validação em cadeia para dados de alunos,
  associação automática a equipes, verificação da existência de orientadores e atribuição de equipe baseada no tipo de
  TG

> Os Controllers encapsulam a lógica de negócios da aplicação, atuando como intermediários entre a apresentação e a
> persistência de dados, garantindo a integridade e a consistência das informações

</details>

<details>
<summary>Validação de Dados</summary>

- **`EmailValidator`**: Implementação de uma classe para realizar a validação básica do formato de e-mail, com uma
  lógica de fallback para priorizar e-mails institucionais. É utilizado consistentemente em todas as entidades que
  possuem campos de e-mail

> O `EmailValidator` centraliza a lógica de validação de e-mails, promovendo a reutilização de código e a consistência
> na validação dos dados

</details>

<details>
<summary>Manipulação de Feedback e Notas (Interface Gráfica)</summary>

- **`limparLabels`**: Implementação para resetar os campos de exibição de feedback e nota na interface, definindo o
  status padrão “SEM NOTA” em vermelho e preparando a interface para novas consultas
- **`atualizarLabels`**: Desenvolvimento para verificar a seleção de entrega e TG, buscar dados de nota e feedback no
  modelo, armazená-los em cache e atualizar a interface com as informações encontradas, ou limpar os campos caso não
  existam dados
- **`atualizarStatusEntrega`**: Implementação para definir o estado visual da entrega (SEM NOTA, PENDENTE, AVALIADO) com
  base nas informações de avaliação, adotando uma codificação de cores intuitiva para facilitar a identificação do
  status

> Estes métodos aprimoram a interação do usuário com a interface de avaliação, fornecendo feedback visual claro sobre o
> status das entregas e gerenciando a exibição de notas e comentários de forma eficiente

</details>

### Hard Skills

| **Categoria**              | **Tecnologia**     | **Nível**                   | **Aplicações/Detalhes**                                                    |
|----------------------------|--------------------|-----------------------------|----------------------------------------------------------------------------|
| **Linguagem**              | Java               | <span title="">★★★☆☆</span> | Backend/Desktop: Controllers, Models, JavaFX, JDBC.                        |
| **Framework GUI**          | JavaFX             | <span title="">★★★☆☆</span> | Telas FXML, Controladores, TableView, ButtonCell, navegação.               |
| **Processamento de Dados** | Apache Commons CSV | <span title="">★★★☆☆</span> | Leitura de CSV (CSVParser), conversão para listas, tratamento de formatos. |
| **Banco de Dados**         | JDBC               | <span title="">★★★☆☆</span> | CRUD com PostgreSQL, tratamento de SQLException.                           |
| **SGBD**                   | PostgreSQL         | <span title="">★★★☆☆</span> | Modelagem relacional, conexão JDBC, integração com Java.                   |
| **Build Tool**             | Maven              | <span title="">★★★☆☆</span> | Gerenciamento de dependências (pom.xml).                                   |
| **Controle de Versão**     | Git                | <span title="">★★★★☆</span> | Branches, conflitos, .gitignore, comandos básicos (commit/push/pull).      |

### Soft Skills

| **Habilidade**             | **Situação e Ação Real (Storytelling)**                                                                                                                                                                                                                                                                                           | **Impacto no Projeto**                                                                                                                                                       |
|:---------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Aprendizado Ágil**       | O projeto exigiu a transição abrupta para **Java**, uma linguagem com paradigmas e sintaxe (estritamente tipada) bem diferentes do Python usado anteriormente. Diante da alta demanda de entrega, precisei imergir no ecossistema (Maven, JDBC, JavaFX) para aplicar os conceitos em tempo real, aprendendo enquanto desenvolvia. | A rápida absorção da tecnologia permitiu a construção de uma arquitetura robusta com conexão a banco de dados e interface gráfica complexa, sem atrasar o cronograma.        |
| **Colaboração e Sinergia** | Diferente do primeiro semestre, a equipe já possuía entrosamento. Aproveitei essa familiaridade para estabelecer um fluxo de suporte mútuo mais eficiente, onde as dúvidas sobre a nova linguagem eram resolvidas coletivamente e de forma rápida, sem a barreira da timidez inicial.                                             | Aceleração significativa na resolução de bugs e na integração do código, transformando a curva de aprendizado íngreme do Java em um processo coletivo mais leve e produtivo. |
---

## Terceiro Semestre (2024-1): Dom Rock Pipeline Configurator

> [!IMPORTANT]
> **Problema:** A configuração das fontes de dados para o pipeline de processamento era realizada manualmente, tornando 
> o processo lento e altamente suscetível a erros humanos. Esse gargalo impactava a produtividade das equipes técnicas 
> e atrasava o *onboarding* de novos clientes ou integrações de dados.
>
> **Solução:** Uma aplicação web Full Stack desenvolvida para automatizar a configuração de metadados e fontes de dados. 
> O sistema eliminou a dependência de edições manuais ao fornecer uma interface intuitiva para cadastro e validação de 
> parâmetros, garantindo autonomia operacional e agilizando significativamente a entrada de novas fontes no pipeline.

[**📁 Repositório no GitHub**](https://github.com/wiz-fatec/dom-rock-pipeline-configurator)

### Tecnologias Utilizadas

<a href="https://www.java.com/" target="_blank"><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"></a>
<a href="https://spring.io/" target="_blank"><img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank"><img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank"><img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS"></a>
<a href="https://vuejs.org/" target="_blank"><img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"></a>
<a href="https://www.mysql.com/" target="_blank"><img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"></a>
<a href="https://git-scm.com/" target="_blank"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"></a>
<a href="https://github.com/" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://www.jetbrains.com/idea/" target="_blank"><img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white" alt="IntelliJ IDEA"></a>
<a href="https://www.jetbrains.com/webstorm/" target="_blank"><img src="https://img.shields.io/badge/WebStorm-000000?style=for-the-badge&logo=webstorm&logoColor=white" alt="WebStorm"></a>

- **Java** - **Função**: Desenvolvimento da aplicação, incluindo a lógica de conversão de dados (JSON/CSV) e manipulação de DTOs para tráfego de informações.

- **Spring Framework** - **Função**: Estruturação da API REST, gerenciamento de injeção de dependências e implementação da persistência de dados via JPA.

- **HTML** - **Função**: Estruturação semântica dos componentes da interface, garantindo a organização visual das telas de configuração ("Silver").

- **CSS** - **Função**: Estilização responsiva da aplicação, utilizando Grid e Flexbox para alinhar os formulários de metadados e gráficos.

- **Vue.js** - **Função**: Construção do frontend, gerenciamento de estado dos componentes e integração assíncrona com os endpoints do backend.

- **MySQL** - **Função**: Armazenamento relacional das configurações de pipeline, dados de usuários, permissões e cadastro de empresas.

- **Git** - **Função**: Controle de versão do código fonte, utilizado para ramificação (branching) e integração de novas features.

- **GitHub** - **Função**: Plataforma de hospedagem do repositório, revisão de código e gerenciamento de tarefas do projeto.

- **IntelliJ IDEA** - **Função**: Ambiente de desenvolvimento para o backend Java, facilitando o debug e a gestão de dependências Maven.

- **WebStorm** - **Função**: Ambiente de desenvolvimento para o frontend, utilizado para codificação em TypeScript/Vue e otimização de scripts.

### Contribuições Pessoais

<details>
<summary>Processamento de Dados (CSV e JSON)</summary>

- **Biblioteca GSON para JSON**: Adição da dependência GSON (versão 2.10.1) no `pom.xml` para facilitar a conversão
  entre objetos Java e JSON.
- **Classes Iniciais de Conversão**: Criação das classes `CsvConverter` (para futuro processamento de arquivos CSV) e
  `JsonConverter` (utilizando GSON para conversão JSON).
- **Modelagem de Dados JSON**: Definição da classe `JsonDataModel` para estruturar os dados JSON a serem manipulados.
- **Manipulação de Dados JSON**: Implementação da classe `SendJson` para envio e outras operações com dados JSON.

</details>

<details>
<summary>Persistência de Dados (Banco de Dados Relacional)</summary>

- **Criação de Tabelas (SQL DDL)**: Definição e criação das tabelas `permission` (com restrição `CHECK` no tipo),
  `user` (com `email` como chave primária), e `company` (com `cnpj` como chave primária).
- **Modificação da Tabela Existente (`arquivo`)**: Adição das colunas `file_has_header` (indicando se o arquivo possui
  cabeçalho) e `cnpj` (chave estrangeira referenciando a tabela `company`), juntamente com a criação da restrição de
  chave estrangeira `fk_cnpj`.

</details>

<details>
<summary>Backend Spring Boot (API REST)</summary>

- **Método PUT para Atualização de Configurações (`/list-view`)**: Implementação do endpoint `@PutMapping("/list-view")`
  com o método `updateConfig` para receber um `MetadataConfigDTO` via `@RequestBody`, localizar a configuração pelo
  `fileId`, atualizar seus campos utilizando o método `updateFields` da entidade `LZMetadataConfig`, e salvar as
  alterações no repositório, retornando um `ResponseEntity` apropriado.
- **Melhoria no Método GET para Detalhes (`/list-view/{fileId}`)**: Alteração do método `details` para utilizar
  `findById` em vez de `getReferenceById` e envolver o retorno em um `Optional` e um `ResponseEntity` para melhor
  tratamento de valores nulos.
- **Método `updateFields` na Entidade `LZMetadataConfig`**: Implementação e extensão do método `updateFields` para
  atualizar os campos `name`, `fileName`, `frequency` (tratando diferentes tipos), `hasHeader`, e a lista de `columns` (
  limpando e substituindo a lista existente).

</details>

<details>
<summary>Frontend Vue.js (Tela Silver)</summary>

- **Criação do Componente `Silver`**: Desenvolvimento de um novo componente Vue utilizando TypeScript, responsável pela
  visualização e interação da tela "Silver". Este componente recebe props como `configList`, `tagInfo`, e
  `bronzeConfig`.
- **Lógica de Navegação**: Implementação da função `gotoSilverConfig` para permitir a navegação para a rota `/home` ao
  interagir com os botões de configuração.
- **Validação de Colunas**: Desenvolvimento da função `validOrInvalid` para realizar a validação de colunas dentro da
  configuração (`BConfig`).
- **Integração de Componentes**: Utilização de outros componentes (`AppHeader`, `DRModal`, `LVSilverContainer`) dentro
  da tela "Silver" para construir a interface.
- **Gerenciamento de Estado Local**: Utilização de `ref` para gerenciar o estado local do componente, incluindo a lista
  de configurações (`configList`), a visibilidade do modal (`showModal`), e a configuração selecionada (
  `selectedConfig`).
- **Chamada de API para Obter Configurações**: Implementação da função assíncrona `getConfig` que realiza uma chamada
  `GET` para a API (`/lz-config/list-view`) e atualiza a lista de configurações (`configList`) ao montar o componente.
- **Ajustes de Estilo**: Modificação da margem do botão de cadastro (`.saveButton`) para melhorar o alinhamento visual
  dentro do layout grid.
- **Criação do Componente `DonutChart`**: Desenvolvimento de um componente reutilizável para exibir gráficos de rosca,
  utilizando a biblioteca `vue-chartjs` (adicionada como dependência). Este componente recebe dados (rótulos, valores,
  cores, título) via `defineProps` e configura o gráfico utilizando elementos do `Chart.js`. Atualização das cores do
  gráfico para melhorar a visualização.

</details>

<details>
<summary>Sincronização de Dados (DTO e Entidade)</summary>

- **Atualização do `MetadataConfigDTO`**: Modificação do construtor da classe `MetadataConfigDTO` para receber um objeto
  `LZMetadataConfig` e uma lista de `ColumnConfig`, garantindo que os campos do DTO sejam preenchidos corretamente com
  os dados da entidade correspondente.

</details>

### Hard Skills

| **Categoria**          | **Tecnologia**   | **Nível**                   | **Aplicações/Detalhes**                                                                |
|------------------------|------------------|-----------------------------|----------------------------------------------------------------------------------------|
| **Linguagem Backend**  | Java             | <span title="">★★★☆☆</span> | Desenvolvimento de aplicações backend robustas, lógica de negócios, integração de APIs |
| **Framework Backend**  | Spring Framework | <span title="">★★★☆☆</span> | APIs RESTful, Spring Security, Spring Data JPA                                         |
| **Estilização**        | CSS              | <span title="">★★★☆☆</span> | Layouts responsivos (Flexbox/Grid), animações CSS                                      |
| **Framework Frontend** | Vue.js           | <span title="">★★★☆☆</span> | Componentes reutilizáveis, gerenciamento de estado, integração com APIs                |
| **Banco de Dados**     | MySQL            | <span title="">★★★☆☆</span> | Operações com tabelas, consultas SQL, transações                                       |
| **Controle de Versão** | Git              | <span title="">★★★★☆</span> | Branching, resolução de conflitos, rebase                                              |
| **Colaboração**        | GitHub           | <span title="">★★★★☆</span> | Gerenciamento de repositórios, revisão de código (PRs), GitHub Actions                 |
| **IDE Java**           | IntelliJ IDEA    | <span title="">★★★★☆</span> | Debug, plugins/temas, integração com ferramentas de teste/build                        |
| **IDE Frontend**       | WebStorm         | <span title="">★★★★☆</span> | Desenvolvimento JS/HTML/CSS, suporte a Vue.js, debugging                               |

### Soft Skills

| **Habilidade**                       | **Situação e Ação Real (Storytelling)**                                                                                                                                                                                                                                                                                             | **Impacto no Projeto**                                                                                                                                                          |
|:-------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Comunicação Profissional**         | Este foi nosso primeiro projeto com um cliente real externo. Houve um "choque de realidade" inicial, pois o cliente não estava disponível para respostas imediatas como os professores. Adaptei minha comunicação para ser mais formal, documentada e assíncrona, estruturando dúvidas para aproveitar as janelas do Product Owner. | A mudança de postura evitou bloqueios no desenvolvimento causados pela espera de respostas, estabelecendo um fluxo de validação mais maduro e alinhado à realidade corporativa. |
| **Resiliência e Rigor na Qualidade** | O cliente impôs um nível de exigência técnica e visual superior aos projetos acadêmicos anteriores. Diante da cobrança por valor de negócio real e entregas mais polidas.                                                                                                                                                           | A entrega final atendeu ao padrão de qualidade exigido, resultando em um produto que foi validado pelo cliente.                                                                 |
---

## Quarto Semestre (2024-2): Sistema de Monitoramento e Rastreamento IoT

> [!IMPORTANT]
> **Problema:** A dificuldade de garantir a segurança e o controle eficiente de ativos em ambientes dinâmicos e 
> logísticos. A falta de visibilidade em tempo real impedia reações rápidas a eventos de risco ou desvios operacionais, 
> resultando em perdas patrimoniais e baixa eficiência na gestão de processos.
>
> **Solução:** Uma plataforma completa de monitoramento IoT que integra geolocalização e visualização em mapas 
> interativos. A solução implementou funcionalidades de *Geofencing* (zonas de interesse) e um sistema de alertas 
> automatizados, permitindo o rastreamento preciso de tags, a redução de prejuízos e a tomada de decisão ágil baseada 
> em dados em tempo real.

[**📁 Repositório no GitHub**](https://github.com/manolito-fatec/geo-iot-2024-1)

### Tecnologias Utilizadas

<a href="https://www.java.com/" target="_blank"><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 17"></a>
<a href="https://www.typescriptlang.org/" target="_blank"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript 5.4"></a>
<a href="https://spring.io/projects/spring-boot" target="_blank"><img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot 3.3.2"></a>
<a href="https://vuejs.org/" target="_blank"><img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js 3.4.29"></a>
<a href="https://vitejs.dev/" target="_blank"><img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite 5.3.1"></a>
<a href="https://www.oracle.com/cloud/" target="_blank"><img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle Cloud"></a>
<a href="https://redis.io/" target="_blank"><img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis 3.X.X"></a>
<a href="https://www.docker.com/" target="_blank"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker 27.2.1"></a>
<a href="https://git-scm.com/" target="_blank"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git 2.43"></a>
<a href="https://github.com/" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

- **Java** - **Função**: Linguagem principal do backend, utilizada para processar a lógica de rastreamento, cálculos de geofencing e integração com serviços de nuvem.

- **Spring Framework** - **Função**: Desenvolvimento da API RESTful para comunicação entre sensores IoT e frontend, gerenciamento de segurança e injeção de dependências.

- **Oracle Cloud** - **Função**: Infraestrutura de banco de dados em nuvem (DBaaS) utilizada para armazenar históricos de movimentação e dados cadastrais com alta disponibilidade.

- **Docker** - **Função**: Containerização dos microsserviços da aplicação e do banco de dados Redis, garantindo consistência entre ambientes de desenvolvimento e produção.

- **Vue.js** - **Função**: Construção do dashboard interativo de monitoramento, renderização de mapas em tempo real e gerenciamento de alertas visuais.

- **Vite** - **Função**: Ferramenta de build e servidor de desenvolvimento para o frontend, otimizando o tempo de carregamento e hot-reload.

- **Redis** - **Função**: Cache de alta performance em memória para armazenar a última localização conhecida das tags, reduzindo a latência de leitura.

- **Git** - **Função**: Controle de versão do código, essencial para gerenciar o trabalho paralelo da equipe e versionamento de releases.

- **GitHub** - **Função**: Hospedagem do repositório, gestão de backlog via Issues/Projects e automação de pipelines básicos.

- **TypeScript** - **Função**: Tipagem estática no frontend para garantir a integridade dos dados recebidos da API e reduzir erros em tempo de execução.

- **IntelliJ IDEA** - **Função**: IDE utilizada para o desenvolvimento backend, refatoração de código Java e execução de testes unitários.

- **WebStorm** - **Função**: IDE utilizada para o desenvolvimento frontend, facilitando a escrita de componentes Vue e debug de TypeScript.

### Contribuições Pessoais

<details> <summary>Atuação como Scrum Master</summary>

- Gestão de Ferramentas: Seleção e implementação da ferramenta de gerenciamento de tasks para o time.
- Organização de Repositórios: Configuração inicial e estruturação dos repositórios no GitHub, incluindo políticas de
  segurança para branches.
- Gestão de Backlog: Criação de épicos, user stories e tasks, alinhando com as necessidades do produto.
- Documentação: Elaboração da documentação de produto e desenvolvimento para garantir transparência e conhecimento
  compartilhado.
- Facilitação de Cerimônias: Condução eficaz de reuniões (daily, planning, review e retrospective).
- Remoção de Barreiras: Atuação proativa para eliminar obstáculos entre desenvolvimento e cliente.
- Melhoria Contínua: Promoção de um ambiente que estimula a criatividade e fortalece a colaboração da equipe.
- Gestão de Impedimentos: Identificação, priorização e resolução rápida de impedimentos.
- Maturidade do Scrum: Avaliação constante da implementação do Scrum e identificação de oportunidades de melhoria.
- Suporte ao Product Owner: Auxílio na gestão e refinamento do Product Backlog.
- Garantia de Processos: Assegurar a adoção e o correto uso dos princípios e práticas do Scrum.

</details>

<details>
<summary>Integração com Swagger</summary>

* **Adição da Dependência Swagger**: Inclusão da dependência `springdoc-openapi-starter-webmvc-ui` (versão 2.6.0) no
  `pom.xml`, permitindo a geração automática da documentação da API REST com interface interativa via Swagger UI.

</details>

<details>
<summary>Documentação de Endpoints</summary>

* **Anotações nos Controllers**: Utilização das anotações `@Tag`, `@Operation` e `@ApiResponses` nos controladores
  `DeviceTrackerController`, `DeviceTrackerRedisController` e `PersonController`, detalhando:

    * O propósito dos endpoints.
    * Os códigos de resposta esperados (`200`, `400`, `404`, `408`, `500`).
    * As descrições de cada operação e grupo de endpoints.
* **Cobertura Completa de Métodos REST**:

    * `GET`, `POST`, `PUT` e `DELETE` anotados com descrições e respostas padronizadas.
    * Exemplo de resumo incluído: `"Sincronizar dados entre Redis e Oracle Cloud"`, `"Registrar uma nova pessoa"`,
      `"Consultar dados para plotagem"`, etc.
* **Organização por Grupos de Endpoints (`@Tag`)**: Agrupamento dos endpoints por domínio funcional:

    * `"Consulta - Controller"` para endpoints de consulta de dispositivos.
    * `"Redis - Controller"` para operações com cache em Redis.
    * `"Pessoa - Controller"` para CRUD de pessoas.

</details>

<details>
<summary>Tratamento de Exceções Personalizadas</summary>

* **Criação de Exceções Personalizadas**: Desenvolvimento das classes `InternalServerErrorException`,
  `InvalidInputException`, `InvalidRequestException`, `NoDataFoundException`, `RequestTimeoutException` e
  `ResourceNotFoundException`, todas estendendo `RuntimeException` e encapsulando mensagens específicas para cada tipo
  de erro.
* **Organização por Pacote**: As classes foram organizadas no pacote `com.example.geoIot.exception.ControllerAdvice`,
  centralizando o tratamento de erros do sistema de forma modular.

</details>

<details>
<summary>Manipulação Global de Erros com Spring Boot</summary>

* **Classe `GlobalExceptionHandler`**: Implementação da classe anotada com `@ControllerAdvice`, responsável por capturar
  exceções em toda a aplicação.
* **Métodos de Tratamento Específico**: Inclusão de métodos com `@ExceptionHandler` para cada tipo de exceção
  personalizada, retornando respostas adequadas com `ResponseEntity` e `HttpStatus`, além de mensagens específicas para
  o usuário.
* **Registro de Logs**: Utilização do `Logger` (SLF4J) para registrar mensagens de erro no log da aplicação, facilitando
  o rastreamento de problemas.

</details>

<details>
<summary>Testes Unitários para Manipulador Global de Exceções</summary>

* **Classe `GlobalExceptionHandlerTest`**: Criação de uma classe de testes unitários utilizando JUnit 5 para verificar o
  comportamento de cada método do `GlobalExceptionHandler`.
* **Cobertura Abrangente**: Testes implementados para todos os métodos de tratamento de exceção, validando tanto o
  código de status HTTP retornado quanto as mensagens enviadas ao cliente.
* **Assertivas com AssertJ**: Uso da biblioteca AssertJ para validar os resultados, assegurando clareza e legibilidade
  nos testes.

</details>

<details>
<summary>Tratamento Global de Erros</summary>

* **Mensagem Aprimorada para Erro 500**: Atualização da mensagem de erro retornada em casos de
  `InternalServerErrorException` para incluir a recomendação de acionar o suporte.
* **Criação do DTO `ErrorResponse`**: Implementação de uma nova classe DTO (`ErrorResponse`) para padronizar as
  respostas de erro, contendo informações como `timestamp`, `statusCode`, `error`, `message` e `path`.
* **Substituição de `@ControllerAdvice` por `@RestControllerAdvice`**: Alteração da anotação para garantir o retorno
  direto de objetos JSON.
* **Inclusão de `HttpServletRequest` nos Handlers**: Modificação dos métodos de tratamento de exceções para incluir o
  `HttpServletRequest` e construir respostas mais informativas com a URI do erro.
* **Tratamento Centralizado para Exceções Comuns**: Implementação de tratamentos detalhados para:

    * `InvalidRequestException` com resposta HTTP 400;
    * `InvalidInputException` com resposta HTTP 204;
    * `ResourceNotFoundException` com resposta HTTP 404;
    * `RequestTimeoutException` com resposta HTTP 408;
    * `InternalServerErrorException` com resposta HTTP 500;
    * `NullPointerException` personalizada com resposta HTTP 404.

</details>

<details>
<summary>Criação e Integração de Exceções Customizadas</summary>

* **Nova Exceção `NullPointerException` Customizada**: Criação de uma classe de exceção personalizada
  `NullPointerException` para tratamento específico de nulidades no sistema.
* **Atualização de Controllers para Usar `GlobalExceptionHandler`**: Refatoração dos controllers (
  `DeviceTrackerController`, `PersonController`) para substituir `try/catch` genéricos por throws específicos de
  exceções customizadas, promovendo uma arquitetura desacoplada e padronizada.
* **Mapeamento Detalhado de Erros nos Controllers**:

    * No `DeviceTrackerController`, mapeamento de `DateTimeParseException`, `NoSuchElementException` e exceções
      genéricas para exceções customizadas.
    * No `PersonController`, encapsulamento de exceções como `InvalidInputException`, `RequestTimeoutException`,
      `NoDataFoundException` e `InternalServerErrorException` com throw adequado para tratamento centralizado.

</details>

<details>
<summary>Refatoração de Tratamento de Exceções</summary>

* **Centralização do Tratamento de Erros**: Remoção de blocos `try-catch` repetitivos em diversos métodos dos
  controllers (`DeviceTrackerController` e `PersonController`) e delegação do tratamento para a camada
  `@ControllerAdvice`, promovendo **clean code** e **separação de responsabilidades**.
* **Criação da Exceção `MethodArgumentTypeException`**: Definição de uma nova exceção customizada para capturar erros de
  tipo em parâmetros de rota ou query, com respectivo tratamento centralizado em `GlobalExceptionHandler`.
* **Inclusão de Novo Handler Global**: Adição do método `handleMethodArgumentTypeMismatchException` no
  `GlobalExceptionHandler` para retornar mensagens personalizadas e apropriadas via `ResponseEntity` com status
  `400 (BAD_REQUEST)`.
* **Melhoria da Legibilidade**: Substituição de imports múltiplos de exceções específicas por um único
  `import com.example.geoIot.exception.ControllerAdvice.*`, reduzindo ruído visual e facilitando manutenção.
* **Simplificação de Métodos HTTP**: Redução significativa de linhas de código em métodos como `addPerson`,
  `getAllPersons`, `getPersonById`, `updatePerson` e `deletePerson` por meio da remoção de `try-catch`, utilizando a
  declaração `throws` diretamente no método.

</details>

<details>
<summary>Configuração de Mensagens de Erro</summary>

* **Ajuste no `application.yml`**: Adição da propriedade `server.error.include-message: always` para garantir que
  mensagens de erro personalizadas sejam incluídas nas respostas HTTP, auxiliando na depuração e fornecendo feedback
  mais claro ao cliente da API.

</details>

### Hard Skills

| **Categoria**              | **Tecnologia**            | **Nível**                   | **Aplicações/Detalhes**                                                    |
|----------------------------|---------------------------|-----------------------------|----------------------------------------------------------------------------|
| **Linguagem Backend**      | Java                      | <span title="">★★★☆☆</span> | Desenvolvimento do core do sistema, tratamento de exceções                 |
| **Framework Backend**      | Spring Boot               | <span title="">★★★☆☆</span> | Criação de APIs RESTful, Spring Data, Spring Security, Swagger integration |
| **Linguagem Frontend**     | TypeScript                | <span title="">★★★☆☆</span> | Tipagem estática para componentes Vue.js                                   |
| **Framework Frontend**     | Vue.js                    | <span title="">★★★☆☆</span> | Componentes reativos, gerenciamento de estado, integração com mapas        |
| **Build Tool Frontend**    | Vite                      | <span title="">★★★☆☆</span> | Otimização de builds e hot-reload                                          |
| **Controle de Versão**     | Git                       | <span title="">★★★★☆</span> | Gestão de branches, resolução de conflitos                                 |
| **Colaboração**            | GitHub                    | <span title="">★★★★☆</span> | Gestão de repositórios, code reviews                                       |
| **Documentação de APIs**   | Swagger/OpenAPI           | <span title="">★★★★☆</span> | Documentação interativa de endpoints                                       |
| **Tratamento de Exceções** | Spring Exception Handling | <span title="">★★★★☆</span> | Criação de handlers globais e exceções customizadas                        |

### Soft Skills

| **Habilidade**                     | **Situação e Ação Real (Storytelling)**                                                                                                                                                                                                                                                                                                                                                 | **Impacto no Projeto**                                                                                                                                                                             |
|:-----------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Liderança Servidora**            | O projeto enfrentou gargalos técnicos imprevistos devido à complexidade de processar grandes volumes de dados IoT, o que ameaçou os prazos. Como Scrum Master, atuei além da facilitação de cerimônias: identifiquei proativamente esses impedimentos, realizei pesquisas técnicas para desbloquear o time e assumi tarefas de desenvolvimento nos momentos onde e quando era possível. | Essa postura "mão na massa" evitou que os atrasos técnicos se tornassem críticos, mantendo o fluxo de entrega contínuo e a moral do time elevada mesmo diante das dificuldades.                    |
| **Comunicação e Coesão de Equipe** | Houve momentos de tensão devido aos contratempos com as tecnologias de rastreamento. Fomentei um ambiente de transparência e colaboração radical, onde as dificuldades eram expostas. Incentivei os membros mais avançados a auxiliares os que estavam travados.                                                                                                                        | A criação de um ambiente colaborativo permitiu que o time absorvesse os impactos dos problemas técnicos juntos, garantindo a entrega do produto final com qualidade, apesar dos desafios iniciais. |
---

## Quinto Semestre (2025-1): YOUTAN DASH

> [!IMPORTANT]
> **Problema:** A ausência de visibilidade consolidada sobre os indicadores de desempenho (KPIs) de projetos de software 
> geridos no Taiga. A falta de métricas claras, como tempo médio de execução e distribuição de tarefas por colaborador, 
> dificultava a análise de produtividade e a tomada de decisão transparente por parte dos gestores e equipes.
>
> **Solução:** Uma plataforma de Business Intelligence (BI) integrada ao Taiga, desenvolvida para processar e 
> visualizar dados críticos do projeto. A solução oferece dashboards personalizados com três níveis de acesso 
> (Operador, Gestor e Admin), transformando dados brutos em métricas visuais que garantem transparência e permitem o 
> acompanhamento eficiente do fluxo de trabalho.

> [!NOTE]
> Neste projeto, atuei com foco principal na gestão ágil, assumindo o papel de Scrum Master, além de contribuir
> tecnicamente para o pipeline de dados e documentação da API.

[**📁 Repositório no GitHub**](https://github.com/manolito-fatec/dashflow-2025-1)

### Tecnologias Utilizadas

<a href="https://www.java.com/" target="_blank"><img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"></a>
<a href="https://spring.io/projects/spring-boot" target="_blank"><img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"></a>
<a href="https://spark.apache.org/" target="_blank"><img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=Apache+Spark&logoColor=FFFFFF" alt="Apache Spark"></a>
<a href="https://www.postgresql.org/" target="_blank"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"></a>
<a href="https://www.typescriptlang.org/" target="_blank"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"></a>
<a href="https://vuejs.org/" target="_blank"><img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"></a>
<a href="https://swagger.io/" target="_blank"><img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white" alt="Swagger"></a>
<a href="https://github.com/features/actions" target="_blank"><img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"></a>
<a href="https://www.sonarsource.com/products/sonarcloud/" target="_blank"><img src="https://img.shields.io/badge/SonarCloud-F3702A?style=for-the-badge&logo=SonarCloud&logoColor=FFFFFF" alt="Sonar Cloud"></a>
<a href="https://git-scm.com/" target="_blank"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"></a>
<a href="https://github.com/" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

- **Java** - **Função**: Desenvolvimento do backend para a API de BI, implementação de tratamentos globais de exceção e serviços de integração.

- **Spring Boot** - **Função**: Framework base para a API REST, configurando segurança, rotas e injeção de dependências para o sistema de dashboards.

- **PostgreSQL** - **Função**: Banco de dados relacional utilizado para armazenar os indicadores processados (KPIs) e os dados de usuários e perfis de acesso.

- **Apache Spark** - **Função**: Motor de processamento de dados (ETL) responsável por ingerir, transformar e calcular métricas complexas a partir dos dados brutos do Taiga.

- **Vue.js** - **Função**: Construção da interface de visualização de dados, utilizando componentes dinâmicos para renderizar os gráficos e tabelas dos dashboards.

- **TypeScript** - **Função**: Tipagem estática no frontend para garantir a consistência dos dados recebidos da API de BI e facilitar a manutenção do código.

- **Swagger** - **Função**: Documentação automática e interativa da API, permitindo que o time de frontend testasse os endpoints de métricas facilmente.

- **GitHub Actions** - **Função**: Automação do pipeline de CI/CD, executando testes e builds automáticos a cada push no repositório.

- **SonarCloud** - **Função**: Análise estática de código para garantir a qualidade, segurança e manutenibilidade do software durante o ciclo de desenvolvimento.

### Contribuições Pessoais

<details>
<summary>Atuação como Scrum Master (Gestão Ágil)</summary>

- **Facilitação de Cerimônias**: Condução de todas as cerimônias ágeis (Sprint Planning, Daily Scrums, Sprint Review e
  Retrospective).
- **Gestão do Product Backlog**: Criação, refinamento e priorização de 18 User Stories (US01 a US18), garantindo o
  alinhamento com as necessidades do cliente.
- **Planejamento de Sprints**: Organização e divisão do backlog em três Sprints coesas, gerenciando o escopo e as
  entregas de valor.
- **Mapeamento de Requisitos**: Tradução das necessidades de negócio em 29 Requisitos Funcionais (R1-R29) e 5 Não
  Funcionais (RNF01-RNF05).
- **Remoção de Impedimentos**: Identificação e atuação proativa para remover bloqueios técnicos e de comunicação da
  equipe.
- **Gestão de Artefatos**: Manutenção e transparência do Sprint Backlog e do Product Backlog para toda a equipe e
  stakeholders.

</details>

<details>
<summary>Contribuições Técnicas e Documentação</summary>

- **Backend (Java)**: Participei ativamente da implementação do *Exception Handler* global da API, centralizando o
  tratamento de erros.
- **Frontend (Vue.js)**: Colaborei no desenvolvimento de telas e componentes da interface de visualização de dados.
- **Documentação de DevOps**: Atuei na construção do ecossistema de documentação para o pipeline de CI/CD, incluindo
  guias de deploy e integração contínua.

</details>

### Hard Skills

| **Categoria**            | **Tecnologia**  | **Nível**                   | **Aplicações/Detalhes**                                                |
|--------------------------|-----------------|-----------------------------|------------------------------------------------------------------------|
| **Gestão Ágil**          | Scrum           | <span title="">★★★★☆</span> | Gestão de backlog, facilitação de cerimônias, planejamento de Sprints. |
| **Linguagem Backend**    | Java            | <span title="">★★★☆☆</span> | Implementação de `Exception Handler` global.                           |
| **Framework Backend**    | Spring Boot     | <span title="">★★★☆☆</span> | Tratamento de exceções (@ControllerAdvice).                            |
| **Framework Frontend**   | Vue.js          | <span title="">★★★☆☆</span> | Desenvolvimento de telas e componentes de visualização.                |
| **Documentação Técnica** | Markdown / Wiki | <span title="">★★★★★</span> | Elaboração de guias de CI/CD e deploy.                                 |
| **Controle de Versão**   | Git / GitHub    | <span title="">★★★★☆</span> | Gestão de repositório, branches e artefatos de projeto.                |

### Soft Skills

| **Habilidade**                                  | **Situação e Ação Real (Storytelling)**                                                                                                                                                                                                                                                                                              | **Impacto no Projeto**                                                                                                                                                                     |
|:------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Gestão de Crise e Recursos**                  | Enfrentamos uma redução significativa no número de membros da equipe no meio do projeto, o que comprometeu a capacidade de entrega original. Como Scrum Master, precisei renegociar o escopo com o Product Owner e redistribuir as tarefas de forma estratégica, assumindo também o desenvolvimento nos momentos de folga da gestão. | A adaptação rápida à nova estrutura do time evitou o colapso do cronograma. Conseguimos entregar o MVP funcional dentro do prazo, mantendo a qualidade mesmo com a equipe reduzida.        |
| **Comunicação Transparente e Responsabilidade** | Com menos pessoas, a margem para erro ou atraso era zero. Instituí uma comunicação mais rigorosa sobre os prazos e status das tarefas nas *dailies*, exigindo e demonstrando proatividade. Criei um ambiente onde o alerta precoce de dificuldades era valorizado, permitindo que eu atuasse imediatamente para remover bloqueios.   | O aumento da responsabilidade individual e a clareza na comunicação garantiram que nenhum impedimento passasse despercebido, otimizando ao máximo a produtividade de cada membro restante. |
-----

## Sexto Semestre (2025-2): Pardal

> [!IMPORTANT]
> **Problema:** O desafio de adequar bases de dados legadas à Lei Geral de Proteção de Dados (LGPD), mitigando riscos 
> legais associados à exposição de dados sensíveis. Além disso, a empresa enfrentava dificuldades para extrair valor 
> estratégico de grandes volumes de tickets de suporte não estruturados, o que limitava a capacidade de prever 
> tendências e categorizar problemas.
>
> **Solução:** Uma solução robusta de Inteligência de Dados focada em compliance e analytics. O sistema realiza a 
> normalização e anonimização automática de dados sensíveis utilizando NLP, garantindo a privacidade. Simultaneamente, 
> integra Inteligência Artificial Generativa para transformar tickets brutos em insights preditivos e categorizações, 
> visualizados em dashboards analíticos com controle rigoroso de acesso (Admin e Colaborador).

> [!NOTE]
> Neste projeto, atuei fortemente na implementação de algoritmos de **Processamento de Linguagem Natural (NLP)** para
> anonimização e na criação de modelos de IA para geração de insights preditivos.

[**📁 Repositório no GitHub**](https://github.com/manolito-fatec/pardal-2025)

### Tecnologias Utilizadas

<div> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> 
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"> 
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"> 
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB"> 
<img src="https://img.shields.io/badge/Gemini_AI-8E75B2?style=for-the-badge&logo=googlebard&logoColor=white" alt="Gemini"> 
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"> 
<img src="https://img.shields.io/badge/Vault-000000?style=for-the-badge&logo=vault&logoColor=white" alt="HashiCorp Vault"> 
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"> 
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"> 
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"> 
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"> 
<img src="https://img.shields.io/badge/PrimeVue-42B883?style=for-the-badge&logo=vue.js&logoColor=white" alt="PrimeVue">
<img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white" alt="spaCy">
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn"></div>

- **Python & Jupyter** - **Função**: Desenvolvimento dos scripts de ETL e prototipagem rápida dos modelos de NLP em notebooks interativos para validação de hipóteses.

- **Pandas & DuckDB** - **Função**: Manipulação de DataFrames em memória e execução de queries OLAP de alta performance para limpeza e normalização de grandes volumes de dados.

- **Google Gemini** - **Função**: Integração via API para análise de sentimentos e geração de insights estratégicos a partir do texto livre dos tickets.

- **spaCy** - **Função**: Implementação do reconhecimento de entidades nomeadas (NER) para identificar e mascarar automaticamente dados sensíveis (CPF, Nomes, Endereços).

- **MongoDB** - **Função**: Armazenamento flexível dos logs de auditoria e dos insights estruturados (JSON) gerados pela Inteligência Artificial.

- **HashiCorp Vault** - **Função**: Gerenciamento seguro de credenciais e chaves de API, garantindo que nenhum segredo fosse exposto no código fonte.

- **Vue.js & PrimeVue** - **Função**: Construção do frontend, incluindo a interface de transparência LGPD e dashboards analíticos com componentes visuais ricos.

- **PostgreSQL** - **Função**: Banco de dados relacional principal, armazenando os dados tratados e as relações entre usuários, empresas e tickets.

- **Java & Spring Boot** - **Função**: Backend da aplicação web, responsável pela segurança (Spring Security), controle de acesso (RBAC) e orquestração das requisições.


### Contribuições Pessoais

<details> 
<summary>Inteligência Artificial, GenAI e Analytics</summary>

  - **Integração com LLM (Google Gemini)**: Desenvolvimento de integração via API para processar descrições de tickets de suporte, utilizando engenharia de prompt para extrair sentimentos, resumir problemas e categorizar chamados automaticamente.
  - **Engenharia de Prompt (Persona & Context)**: Implementação de prompts estruturados onde a IA assume a persona de um "Product Manager". O prompt recebe estatísticas quantitativas (via Pandas) e dados qualitativos (texto dos tickets), instruindo o modelo a gerar planos de ação estratégicos.
  - **Output Estruturado (JSON Enforcement)**: Configuração do prompt para garantir que a saída da IA seja estritamente um JSON válido, facilitando o *parsing* e a persistência direta no banco de dados sem necessidade de regex complexo.
  - **Anonimização Inteligente (NLP)**: Aplicação de modelos de Processamento de Linguagem Natural (spaCy) para identificar Entidades Nomeadas (NER) como nomes, CPFs e endereços em textos livres, aplicando máscaras de anonimização dinamicamente.
  - **Modelagem NoSQL para Insights**: Configuração de uma coleção dedicada (`product_insights`) no MongoDB com índices compostos (`company_name` + `dth`) para otimizar a recuperação de dados pelo frontend.
  - **Bulk Write Operations**: Implementação de inserção em lote (`insert_many` com `ordered=False`) para alta performance na gravação dos insights gerados.

> A utilização de IA permitiu transformar um "lago de dados" de texto não estruturado em insights acionáveis, sem comprometer a privacidade dos usuários.

</details>


<details> 
<summary>Engenharia de Dados e Pipelines de ETL</summary>

  - **Pipeline de Alta Performance (DuckDB & Pandas)**: Implementação de scripts de ETL que utilizam **DuckDB** para consultas OLAP em memória (alta velocidade em grandes volumes) e **Pandas** para limpeza e transformação refinada dos dados antes da anonimização.
  - **Extração Analítica (DuckDB)**: Utilização do DuckDB para conectar diretamente ao PostgreSQL e executar queries analíticas complexas (`InsightsExtractor`).
  - **SQL Window Functions**: Implementação de *Common Table Expressions (CTEs)* com funções de janela (`ROW_NUMBER() OVER PARTITION BY`) para rankear e selecionar inteligentemente os tickets mais relevantes de cada subcategoria, respeitando cotas por empresa.
  - **Otimização de Performance (Bulk Operations)**: Refatoração do pipeline para utilizar **Bulk Updates** (`psycopg2.extras.execute_batch`) no PostgreSQL, substituindo transações linha-a-linha e reduzindo drasticamente o *overhead* de I/O no banco.
  - **Tratamento de Dados Legados**: Criação de rotinas robustas para ingestão de bases despadronizadas, normalização de esquemas e migração segura para a estrutura relacional do PostgreSQL.
  - **Arquitetura de Pipeline**: Orquestração do fluxo `Extractor -> Generator -> Loader`, onde os dados são extraídos para arquivos intermediários (CSV), processados pela IA e carregados em massa no MongoDB.

</details>

<details> 
<summary>DevOps, SRE e Infraestrutura</summary>

  - **Orquestração com Docker**: Configuração avançada do `docker-compose` utilizando *Healthchecks* nos serviços de banco de dados (Postgres e Mongo) e `depends_on` condicionais. Isso assegura que o container de ETL (`etl-service`) inicie o processamento apenas quando a infraestrutura de persistência estiver totalmente saudável.
  - **Padrão Sidecar (Restore Watcher)**: Implementação de um container auxiliar (`etl-restore-watcher`) utilizando `inotify-tools` para monitorar em tempo real a chegada de novos arquivos de dump. Assim que um backup é detectado, o sistema dispara automaticamente o processo de restauração do banco.
  - **Orquestração Baseada em Eventos (Signals)**: Desenvolvimento de um sistema de sinalização via arquivos (`restore_complete.signal`) para coordenar a dependência entre containers. O agendador principal (`scheduler.py`) agora "aguarda" o sinal de que o restore foi concluído com sucesso antes de iniciar os jobs, prevenindo erros de execução em banco vazio ou inconsistente.
  - **Isolamento de Rede (Docker Networking)**: Configuração de uma rede interna dedicada (`bridge network`) no Docker Compose para orquestrar a comunicação entre os serviços de banco de dados e o ETL. Isso garante que os containers se comuniquem via DNS interno de forma segura, isolados do tráfego externo e da rede padrão do host.
  - **Infraestrutura GPU (NVIDIA)**: Configuração do ambiente Docker para suporte a drivers **NVIDIA (CUDA)**, permitindo o *passthrough* de recursos de hardware para aceleração do container de ETL.
  - **Rotina de Backup Automatizada**: Desenvolvimento de módulo Python (`DatabaseBackup`) que integra via `subprocess` com o **PostgreSQL Client Tools** para executar `pg_dump` de forma segura, gerando arquivos compactados e versionados por *timestamp*.
  - **Restauro Automático (Self-Healing)**: Implementação de script Shell (`restore_db.sh`) executado no *entrypoint* do container, que identifica e restaura automaticamente o backup mais recente ao iniciar o serviço.
  - **Agendamento de Jobs (Python Schedule)**: Implementação de um agendador de tarefas robusto utilizando a biblioteca `schedule`, configurado para executar o pipeline de anonimização diariamente às 03:00.
  - **Transformação em Serviço (Daemon)**: Reconfiguração da arquitetura do container de ETL no `docker-compose` para rodar como um serviço persistente (`restart: unless-stopped`).

</details>

<details> 
<summary>Segurança, Compliance e Backend</summary>

  - **Infraestrutura de Auditoria (LGPD)**: Implementação de logs de auditoria no MongoDB (`mongo_audit_service`), garantindo isolamento dos dados operacionais e performance de escrita.
  - **Engenharia de Índices e Retenção (TTL)**: Desenvolvimento de scripts Python (`setup_mongo.py`) para criação de índices compostos e **Índices TTL (Time-To-Live)** configurados para exclusão automática de logs após 5 anos, atendendo aos requisitos legais.
  - **Gestão de Segredos (HashiCorp Vault)**: Configuração do Vault para gerenciamento centralizado de credenciais de banco de dados e chaves de API, eliminando *hardcoded secrets* do código fonte.
  - **Criptografia em Atualizações de Perfil**: Correção de vulnerabilidade no serviço de usuários (`AppUserService`), implementando a codificação obrigatória de senhas (`passwordEncoder.encode`) durante o processo de atualização de perfil.
  - **Controle de Acesso (RBAC)**: Implementação no Spring Boot de distinção clara entre perfis (Admin vs. Colaborador), assegurando que dados estatísticos sensíveis sejam visíveis apenas para usuários autorizados.
  - **Sincronização de Schema (JPA/Hibernate)**: Refatoração das entidades de domínio (`User`, `Agent`, `Tickets`) para alinhar o mapeamento Objeto-Relacional com a nova estrutura do banco de dados pós-ETL.
  - **Remoção de Atributos Obsoletos**: Limpeza de código removendo campos de dados sensíveis (PII) e textos brutos que foram migrados ou anonimizados.

> A infraestrutura de segurança e auditoria garante que todas as alterações nos dados sensíveis sejam rastreáveis e que a aplicação esteja em conformidade com a LGPD.

</details>

<details>
<summary>Frontend, UI/UX e Visualização de Dados</summary>

  - **Arquitetura de Layouts**: Implementação da estrutura base para o módulo de Configurações do Usuário (`UserConfigView`), desenvolvendo componentes de layout como `Topbar.vue` com design responsivo (CSS Grid/Flexbox) e suporte a *breakpoints* móveis/desktop.
  - **Roteamento e Navegação**: Configuração de novas rotas no **Vue Router** e integração do fluxo de navegação no menu principal, permitindo acesso fluido à área de gestão de perfil.
  - **Componente de Insights (AI UI)**: Desenvolvimento do componente `InsightCard.vue` para renderizar as sugestões estratégicas geradas pelo Gemini. O componente processa a resposta bruta, limpa formatações Markdown residuais e apresenta os dados em uma lista paginada e interativa.
  - **Geração de Relatórios PDF**: Implementação de funcionalidade de exportação de dashboards para PDF. Utilizei a biblioteca `html2canvas` para capturar os gráficos renderizados no navegador como imagens (Base64) e enviá-las ao backend para compilação em um documento PDF profissional.
  - **Exportação de Dados Brutos (CSV/ZIP)**: Desenvolvimento de fluxo para download de datasets analíticos em formato ZIP, utilizando `Blob` API para gerenciar o download de arquivos binários gerados pela API.
  - **Orquestração de Dados**: Refatoração da view principal (`InsightsView`) para gerenciar o carregamento concorrente de múltiplos widgets (Gráfico de Pareto e Card de Insights) utilizando `Promise.all`, melhorando a percepção de performance da aplicação.
  - **Menu de Ações Contextuais**: Criação de um menu *dropdown* ("Mais ações") na interface principal (`InsightsView`), centralizando as opções de exportação e melhorando a usabilidade sem poluir o layout.

</details>

<details>
<summary>Portal de Privacidade e Autogestão (LGPD UI)</summary>

  - **Painel de Controle do Usuário**: Implementação do componente `MySection.vue` com arquitetura de abas (`Tabs` do PrimeVue) para centralizar a gestão de perfil, privacidade, segurança e auditoria.
  - **Módulo de Transparência (LGPD UI)**: Desenvolvimento do componente `TransparencySidebar.vue` focado em compliance. O componente centraliza o acesso a informações regulatórias (contato do DPO, Política de Privacidade) e implementa o fluxo interativo de leitura e aceite dos **Termos de Uso** utilizando modais (`Dialog`) e feedback visual (`Toast`) do PrimeVue.
  - **Aba de Privacidade (Direitos do Titular)**: Desenvolvimento do componente `PrivacyTab.vue` que exibe de forma estruturada os dados pessoais processados pelo sistema (transparência) e oferece botões de ação para **Portabilidade (CSV)** e **Eliminação de Conta**, traduzindo requisitos legais em interface funcional.
  - **Funcionalidade de Portabilidade de Dados**: Desenvolvimento de lógica no frontend (`exportCSV`) para permitir que o usuário baixe seus dados cadastrais e logs de auditoria em formato CSV diretamente pelo navegador (`Blob` API), atendendo ao direito de portabilidade da LGPD.
  - **Aba de Auditoria (Transparência)**: Desenvolvimento do componente `AuditTab.vue` que consome e exibe logs de auditoria detalhados (`auditData`) em uma `DataTable` interativa, permitindo ao usuário rastrear acessos (quem, quando, onde) e alterações em sua conta (Art. 6 da LGPD).
  - **Painel de Segurança (Gestão de Credenciais)**: Implementação do componente `SecurityTab.vue` com fluxo completo de alteração de senha via modal.
  - **Validação de Senha Forte (Real-time)**: Utilização de *Computed Properties* do Vue.js e Expressões Regulares (Regex) para validar instantaneamente a complexidade da senha (mínimo 8 caracteres, letras, números e símbolos) e a correspondência dos campos, bloqueando o envio do formulário (`isFormValid`) até que todos os critérios de segurança sejam atendidos.
  - **Fluxo de Eliminação de Conta**: Implementação de diálogo de confirmação (`Dialog`) para solicitação de exclusão de dados (Art. 18 da LGPD), com alertas claros sobre as consequências e retenção residual.
  - **UI/UX com Privacy by Design**: Implementação de lógica de mascaramento de dados sensíveis no frontend (ex: ofuscação de e-mail na Topbar), reforçando visualmente o compromisso do projeto com a privacidade.

</details>

<details>
<summary>Arquitetura Frontend, Integração e Qualidade</summary>

  - **Integração de Perfil de Usuário**: Implementação do serviço `UserService.ts` para conectar a interface de gestão de perfil à API REST. O serviço orquestra a busca de dados compostos (`getProfileInformation`) que traz tanto os dados cadastrais quanto o histórico de auditoria em uma única chamada otimizada.
  - **Integração de APIs**: Implementação da camada de serviço (`InsightCardApi.ts`) para consumo dos endpoints de IA, com tipagem estrita via TypeScript (`ProductInsight`, `InsightTheme`) para garantir consistência e segurança de tipos entre o backend e o frontend.
  - **Arquitetura de Tipos (TypeScript)**: Refatoração da estrutura de tipos, extraindo interfaces de domínio (`UserProfile`, `AuditDto`) para arquivos dedicados (`src/types/ConfigUser`), promovendo a reutilização e evitando dependências circulares entre componentes e serviços.
  - **Type Safety (TypeScript)**: Refatoração dos componentes `MySection.vue` e `TransparencySidebar.vue` para resolver erros de tipagem implícita (`implicit any`), definindo interfaces claras para dados de auditoria e métodos auxiliares.
  - **Refatoração e Manutenibilidade**: Reestruturação dos componentes Vue (`PrivacyTab`, `SecurityTab`, `AuditTab`), extraindo estilos *scoped* para arquivos CSS externos, promovendo a reutilização de classes e facilitando a manutenção do design system.
  - **Validação de Formulário**: Implementação de lógica de validação no frontend (`handleSave` em `ProfileTab.vue`) para garantir que campos obrigatórios (nome, email) não sejam salvos vazios, com feedback visual via `Toast`.

</details>


### Hard Skills

| **Categoria**              | **Tecnologia**           | **Nível**                   | **Aplicações/Detalhes**                                                                                       |
|:---------------------------|:-------------------------|:----------------------------|:--------------------------------------------------------------------------------------------------------------|
| **GenAI / LLM**            | Google Gemini API        | <span title="">★★★★☆</span> | Engenharia de prompt (Persona/Context), geração de JSON estruturado e análise de sentimentos.                 |
| **Data Science / NLP**     | Python / spaCy           | <span title="">★★★★☆</span> | Modelos de Reconhecimento de Entidades Nomeadas (NER) para anonimização e manipulação de *Doc objects*.       |
| **Engenharia de Dados**    | DuckDB / Pandas          | <span title="">★★★★☆</span> | Processamento analítico em memória (OLAP), integração Cross-Database e transformação de dados.                |
| **Banco de Dados (SQL)**   | PostgreSQL               | <span title="">★★★★☆</span> | *Window Functions*, CTEs, *Bulk Updates* (`execute_batch`) e otimização de queries complexas.                 |
| **Banco de Dados (NoSQL)** | MongoDB                  | <span title="">★★★★☆</span> | Modelagem de logs de auditoria, índices compostos, TTL para conformidade LGPD e operações de escrita em lote. |
| **Frontend Framework**     | Vue.js (Composition API) | <span title="">★★★☆☆</span> | Gestão de estado reativo (`refs`, `computed`), arquitetura de componentes, *watchers* e ciclo de vida.        |
| **Frontend UI/UX**         | PrimeVue                 | <span title="">★★★☆☆</span> | Estilização *utility-first*, design responsivo, modais, toasts e construção de layouts complexos.             |
| **Linguagem Frontend**     | TypeScript               | <span title="">★★★☆☆</span> | Tipagem estrita, definição de interfaces de domínio (`UserTypes`) e integração segura com APIs.               |
| **DevOps & Infra**         | Docker / Compose         | <span title="">★★★★☆</span> | Orquestração de serviços, *Healthchecks*, isolamento de rede (*bridge*) e volumes persistentes.               |
| **HPC / Performance**      | NVIDIA CUDA              | <span title="">★★★★☆</span> | Configuração de ambiente Docker para *passthrough* de GPU, acelerando a inferência de modelos de IA.          |
| **Automação (SRE)**        | Shell Script / Python    | <span title="">★★★★☆</span> | Scripts de *watchers* (`inotify`), agendamento de tarefas (`schedule`) e *disaster recovery* automatizado.    |
| **Segurança**              | HashiCorp Vault          | <span title="">★☆☆☆☆</span> | Gestão centralizada de segredos e credenciais, eliminando vulnerabilidades de código.                         |
| **Backend API**            | Java / Spring Boot       | <span title="">★★★☆☆</span> | Implementação de endpoints REST, Spring Security, JPA e tratamento de exceções.                               |

### Soft Skills

| **Habilidade**                                  | **Situação e Ação Real (Storytelling)**                                                                                                                                                                                                                                                                                             | **Impacto no Projeto**                                                                                                                                                                            |
|:------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Mentoria e Compartilhamento de Conhecimento** | A equipe possuía pouco conhecimento prévio sobre Inteligência Artificial. Aproveitando minha experiência na área, realizando conversas e pair programming para ensinar os conceitos de NLP ao time, previsão, entre outros.                                                                                                         | A capacitação do time reduziu a curva de aprendizado, permitindo que outros membros contribuíssem efetivamente nas tarefas de IA e tornando a implementação mais fluida e colaborativa.           |
| **Pensamento Crítico e Ético**                  | O projeto envolvia dados sensíveis e exigia adequação rigorosa à LGPD, um tema complexo e cheio de nuances legais. Dediquei-me a estudar a lei e participei dos debates sobre privacidade, questionando a viabilidade de certas features e defendendo a implementação de *Privacy by Design* desde a arquitetura do banco de dados. | Essa postura garantiu que o produto final não fosse apenas tecnicamente funcional, mas juridicamente seguro, evitando riscos de exposição de dados e assegurando a conformidade ética da solução. |
