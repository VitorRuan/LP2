<div align="center">
    
![banner](./capilogo.png)
</div>
<br id="topo">
<p align="center">
    <a href="#sobre">Sobre</a>  |  
    <a href="#backlogs">Backlogs & User Stories</a>  |  
    <a href="#prototipo">Protótipo & Documentação</a>  |  
    <a href="#tecnologias">Tecnologias</a>  |  
    <a href="#equipe">Equipe</a>
</p>
   
<span id="sobre">

## :bookmark_tabs: Sobre o projeto
A ideia para o desenvolvimento do projeto surgiu da necessidade de se adequar ao tema proposto pela coordenadora do curso de Desenvolvimento de Software Multiplataforma, professora Angelina Vitorino de Souza Melaré. Ela identificou uma dificuldade na secretaria acadêmica da unidade, o que nos levou a buscar a criação de um sistema/site que facilitasse o cadastro dos professores e das disciplinas que eles lecionam.

> _Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos_

:pushpin: Status do Projeto: **Em Andamento**

### 🏁 Entregas de Sprints
Cada sprint no desenvolvimento ágil resulta em uma entrega funcional e incremental do sistema. Essas entregas são versões do produto que incluem novas funcionalidades implementadas e testadas, prontas para serem demonstradas e, potencialmente, utilizadas. Observe a relação a seguir:
| Sprint | Previsão | Status | Histórico |
|:--:|:----------:|:----------------|:-------------------------------------------------:|
| 01 | 06/05/2024 | ✔️ Concluída    | [ver relatório](https://github.com/The-Bugger-Ducks/help-duck-documentation/blob/sprint-01/README.md) |
| 02 | 15/05/2024 | ✔️ Concluída    | [ver relatório](https://github.com/The-Bugger-Ducks/help-duck-documentation/blob/sprint-02/README.md) |
| 03 | 11/06/2024 | ✔️ Concluída    | [ver relatório](https://github.com/The-Bugger-Ducks/help-duck-documentation/blob/sprint-03/README.md) |

## :dart: Backlogs & User Stories
    
<div align="center">
    
![product backlog](https://user-images.githubusercontent.com/69374340/172057734-320d9e43-19e9-409a-8f2d-7d159a1aaa9a.png)
![sprint backlog](https://user-images.githubusercontent.com/69374340/172057787-dcc1ecce-1b08-464b-850e-7019dc050056.png)
![user stories](https://user-images.githubusercontent.com/69374340/172057949-daade83b-8fec-4acc-a3cf-c4a26a3d3162.png)
</div>
  
→ [Voltar ao topo](#topo)

<span id="prototipo">

## :desktop_computer: Protótipo & Documentação
Como parte do planejamento do projeto foram criados wireframes e mockups para idealização do layout, que, ao ser validado pelo cliente, foram aplicados em um protótipo construído em React, possibilitando a interação do usuário com a interface (vide [entrega da primeira sprint](https://github.com/The-Bugger-Ducks/help-duck-documentation/blob/sprint-01/README.md)).
    
Por conta da arquitetura orientada a microsserviços adotada neste projeto, houve a descentralização e isolamento de responsabilidades entre o front-end e o back-end, garantindo que as funcionalidades fossem integradas a partir do consumo das APIs disponíveis, onde a documentação desses microsserviços, um dos requisitos não funcionais desejados para o projeto, foi praticada durante todo o desenvolvimento através de ferramentas como o Swagger ou readmes dos repositórios, mapeando todos os endpoints de cada API criada relacionada ao projeto, enquanto que para outras documentações do projeto como um todo, tais como os fluxos de dados, diagramas de classe e de uso, modelagem de banco de dados e arquiteturas foram condensadas em um guia PDF.
    
> 🔗 **Links gerais** <br>
> - Documentação do software: [clique aqui para acessar](./documentacao_geral.pdf)
> - Manual do usuário: [clique aqui para acessar](./manual_usuario.pdf)
> - Links para os repositórios criados:
>    - **Frontend:** [acessar help-duck-web](https://github.com/The-Bugger-Ducks/help-duck-web)
>    - **Microsserviços (backend):**
>       - **Usuários e equipamentos:** [acessar help-duck-register](https://github.com/The-Bugger-Ducks/help-duck-register)
>       - **Autenticação:** [acessar help-duck-authentication](https://github.com/The-Bugger-Ducks/help-duck-authentication)
>       - **Relatórios:** [acessar help-duck-dashboard](https://github.com/The-Bugger-Ducks/help-duck-dashboard)
>       - **Centro de soluções:** [acessar help-duck-solution-center](https://github.com/The-Bugger-Ducks/help-duck-solution-center)
>       - **Controle de chamados:** [acessar help-duck-tickets](https://github.com/The-Bugger-Ducks/help-duck-tickets)
> - Documentações das APIs:
>    - **Microsserviço de usuários e equipamentos:** [acessar Swagger](https://help-duck-register.herokuapp.com/swagger-ui/index.html#/)
>    - **Microsserviço de controle de chamados:** [acessar Swagger](https://help-duck-ticket.herokuapp.com/swagger-ui/index.html#/)
>    - **Microsserviço de problemas e soluções:** [acessar Swagger](https://help-duck-solution-center.herokuapp.com/swagger-ui/index.html#/)

→ [Voltar ao topo](#topo)

<span id="tecnologias">

## 🛠️ Tecnologias

As seguintes ferramentas, linguagens, bibliotecas e tecnologias foram usadas na construção do projeto:

<img src="https://img.shields.io/badge/Figma-CED4DA?style=for-the-badge&logo=figma&logoColor=DC143C" alt="Figma" /> 
<img src="https://img.shields.io/badge/TypeScript-CED4DA?style=for-the-badge&logo=typescript&logoColor=007ACC" alt="Typescript" />
<img src="https://img.shields.io/badge/HTML5-CED4DA?style=for-the-badge&logo=html5&logoColor=E34F26" alt="HTML" /> 
<img src="https://img.shields.io/badge/CSS3-CED4DA?style=for-the-badge&logo=css3&logoColor=1572B6" alt="CSS" /> 	
<img src="https://img.shields.io/badge/React-CED4DA?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" /> 
<img src="https://img.shields.io/badge/Node.js-CED4DA?style=for-the-badge&logo=nodedotjs&logoColor=339933" alt="Node" />  
<img src="https://img.shields.io/badge/Java-CED4DA?style=for-the-badge&logo=java&logoColor=DC143C" alt="Java" />
<img src="https://img.shields.io/badge/MongoDB-CED4DA?style=for-the-badge&logo=mongodb&logoColor=4EA94B" alt="MongoDB" /><br>
<img src="https://img.shields.io/badge/Python-CED4DA?style=for-the-badge&logo=python&logoColor=yellow" alt="Python" />
<img src="https://img.shields.io/badge/VS_Code-CED4DA?style=for-the-badge&logo=visual%20studio%20code&logoColor=0078D4" alt="VS Code" /> 
<img src="https://img.shields.io/badge/Discord-CED4DA?style=for-the-badge&logo=discord&logoColor=7289DA" alt="Discord" /> 
<img src="https://img.shields.io/badge/GitHub-CED4DA?style=for-the-badge&logo=github&logoColor=20232A" alt="GitHub" /> 
<img src="https://img.shields.io/badge/Google%20Sheets-CED4DA?style=for-the-badge&logo=google-sheets&logoColor=34A853" alt="Google Sheets" /> 
<img src="https://img.shields.io/badge/Google%20Docs-CED4DA?style=for-the-badge&logo=google-sheets&logoColor=0D96F6" alt="Google Docs" />
    
→ [Voltar ao topo](#topo)

<span id="equipe">

## :busts_in_silhouette: Equipe

|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner | Erick Oliveira Nascimento          |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoaoM-py)              |
| Scrum Master  | Juliano Aparecido Ramalho |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/mariagabrielareis/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/MariaGabrielaReis)     |
|   Dev Team    | Leon Pereira Pinto Fagundes               |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/antonio-nepomuceno-04943720a/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Nepoun)        |
|   Dev Team    | Lucas Adami Gomes                   |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/caio-vitor-c1/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/CaioVitorDias1)        |
|   Dev Team    |Matheus Garibaldi Rodrigues                |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-camargo-915452196/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/GabrielCamargoL)   |
|   Dev Team    | Vitor Ruan Firmino de Oliveira       |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gioliveirass) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gioliveirass)          |


→ [Voltar ao topo](#topo)
