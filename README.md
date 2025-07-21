# Projeto de Portfólio de QA: Teste de Autenticação e Cadastro de Usuário

## 📜 Descrição Geral
Este projeto demonstra a aplicação prática de um processo completo de Quality Assurance (QA) para as funcionalidades de **Autenticação** e **Cadastro** de um sistema fictício. O objetivo é apresentar o fluxo de trabalho de ponta a ponta, desde o planejamento de requisitos em uma metodologia ágil até o design, execução e reporte de testes.

---

## 🛠️ Ferramentas Utilizadas
* **Jira:** Utilizado para o gerenciamento ágil do projeto, criação de histórias de usuário (User Stories), definição de critérios de aceite e organização do trabalho em Sprints.
* **Qase.io:** Utilizado como sistema de gerenciamento de testes (TMS) para documentar suítes de teste, escrever casos de teste detalhados, executar ciclos de teste e registrar resultados.

---

## ⚙️ O Processo de QA em Ação

O fluxo de trabalho foi estruturado para garantir a máxima cobertura e rastreabilidade entre os requisitos do negócio e os testes executados.

### 1. Planejamento Ágil e Definição de Requisitos (Jira)
O projeto iniciou-se no Jira, onde as funcionalidades foram detalhadas em Histórias de Usuário. Para cada história, foram definidos Critérios de Aceite claros, que serviram como base para a criação dos casos de teste, garantindo que o desenvolvimento e os testes estivessem perfeitamente alinhados.

**Evidência:** Board Scrum no Jira com histórias para cadastro e login, e detalhe de uma História com seus Critérios de Aceite.
![Jira Board com User Stories e Critérios de Aceite](https://lucasqati.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog?sprintCompleted=&atlOrigin=eyJpIjoiOGZkZTFmMzRkMjllNDZiYjlmNWQ1N2QzMTYwZjQ1ZjUiLCJwIjoiaiJ9)
<img width="1919" height="951" alt="image" src="https://github.com/user-attachments/assets/6210e654-2dec-4405-b7f2-a9d931b9a244" />


### 2. Design e Estruturação de Testes (Qase.io)
Com base nos requisitos do Jira, a suíte de testes `Autenticação de Usuário - Login` foi criada no Qase.io. Os casos de teste foram escritos utilizando o padrão **Gherkin (Given/When/Then)**, o que torna o teste compreensível tanto para perfis técnicos quanto para não técnicos.
<img width="1919" height="955" alt="image" src="https://github.com/user-attachments/assets/82fa145d-3299-4e1a-978f-e68050e0d90b" />


**Evidência:** Casos de teste detalhados no padrão Gherkin.
![Detalhe de um Caso de Teste em Gherkin no Qase.io]
<img width="1919" height="992" alt="image" src="https://github.com/user-attachments/assets/39cc9b91-ec6e-40ee-94d1-faed3a5f8187" />
<img width="1919" height="994" alt="image" src="https://github.com/user-attachments/assets/1482c672-6c88-4dd0-aac5-674483b9dfb2" />

A estrutura da suíte de testes foi planejada para cobrir cenários positivos, negativos e de validação de campos.

**Evidência:** Repositório de testes com a suíte "Autenticação de Usuário - Login".
![Repositório de Testes no Qase.io](https://app.qase.io/project/ASDL?case=4&suite=1&tab=properties)

### 3. Execução de Testes e Identificação de Falhas
O ciclo de testes foi executado para validar as funcionalidades. O histórico de execuções no Qase demonstra um cenário realista: **testes que inicialmente falharam**, indicando a identificação de bugs no sistema. Este é o principal objetivo do processo de QA: encontrar defeitos antes que cheguem ao usuário final.

**Evidência:** Histórico de um caso de teste mostrando execuções com status **"Failed"**, provando a identificação de bugs.
![Histórico de Execução com Testes Falhos](http://googleusercontent.com/file_content/0)

### 4. Relatórios e Validação Final (Ciclo de Reteste)
Após o reporte e a correção dos bugs identificados, um novo ciclo de testes (reteste) foi executado. O relatório final da "Express run" comprova que **todos os 5 casos de teste passaram com sucesso**, validando que as correções foram eficazes e que a funcionalidade atingiu os critérios de qualidade esperados.

**Evidência:** Dashboard da execução de teste final com 100% de aprovação.
![Relatório de Test Run com 100% de Sucesso](http://googleusercontent.com/file_content/1)

---

## 💡 Habilidades Demonstradas
* **Planejamento Ágil:** Experiência com Jira, criação de User Stories e definição de Critérios de Aceite.
* **Gestão de Testes:** Domínio de ferramentas de TMS como o Qase.io.
* **Design de Casos de Teste:** Habilidade na escrita de testes estruturados usando o padrão BDD (Gherkin).
* **Análise de Cenários:** Capacidade de criar testes para caminhos felizes, cenários negativos e de validação.
* **Execução e Reporte:** Execução de ciclos de teste, identificação de falhas e análise de resultados.
* **Rastreabilidade:** Entendimento do ciclo de vida de um defeito, desde o requisito até a validação final.
