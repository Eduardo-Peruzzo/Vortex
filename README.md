# Integrantes do grupo:
- Eduardo Barros Peruzzo
- Pedro dos Santos Carlos da Silva
- Mateus de Macedo Coelho Sachinho
- Estevão Batista de Moraes

# Repositórios de cada integrante:
- Eduardo: https://github.com/Eduardo-Peruzzo/react-base-project
- Pedro: https://github.com/Pedroselecto/react-base-project
- Mateus: https://github.com/MateusSachinho/react-base-project
- Estevão: https://github.com/EstevaoMO/react-base-project

# Propósito do sistema:
O propósito de um sistema é o motivo pelo qual tal sistema existe, e está muito relacionado ao  _Why_ (Por Quê) da metodologia 5W2H. O propósito do sistema de portfólios do IBMEC é exibir os projetos realizados pelos alunos da faculdade, mostrando brevemente do que se trata cada projeto e quem o fez.

# 5W2H
A metodologia 5W2H é uma ferramenta de gestão usada para definir os direcionamentos e objetivos de um plano ou projeto. Ela consiste basicamente de 7 perguntas simples que devem ser respondidas na fase inicial do projeto. As perguntas são:
- **What (o quê?)**: Descrição geral do que será o sistema em questão, sendo um resumo simples.
- **Why (por quê?)**: Motivos pelos quais o sistema será feito, qual é o seu propósito.
- **Where (onde?)**: Locais em que a ação será feita, podendo ser uma localização real ou um ambiente virtual.
- **When (quando?)**: Em que momento o sistema será executado, e quais serão os prazos, além de quando poderá ser utilizado pelos usuários.
- **Who (quem?)**: Quem serão os responsáveis pela criação do sistema, e quem vai o utilizar.
- **How (como?)**: Detalhamento de como será feito o sistema, quais serão os métodos utilizados, além de como ele será utilizado.
- **How much (quanto?)**: Qual o custo do projeto, podendo ser definido de diversas formas, como financeiramente (custo em dinheiro) ou em horas trabalhadas, por exemplo.

Utilizando essa ferramenta para planejar o sistema dos portfólios do IBMEC, as perguntas podem ser respondidas da seguinte maneira:
- **What (o quê?)**: Sistema de porfólios do IBMEC.
- **Why (por quê?)**: Criar um ambiente onde seja possível exibir os projetos criados no IBMEC para o resto do mundo, de maneira atrativa e inovadora.
- **Where (onde?)**: Uma página online.
- **When (quando?)**: No final do período (2024.2) o sistema será terminado e pode ser utilizado quando empresas forem buscar projetos feitos pelos alunos da IBMEC.
- **Who (quem?)**: Alunos da turma de Projeto Front-End irão criar o sistema, para que os alunos do IBMEC o utilizem, bem como outras empresas para acessar o sistema.
- **How (como?)**: Utilizando conhecimentos sobre as linguagens usadas para a criação de sites na internet e sobre design gráfico. Ele poderá ser utilizado de duas formas, alunos poderão colocar seus projetos no sistema (por meio de um administrador), e também será usado por empresas para buscar e descobrir projetos feitos na IBMEC.
- **How much (quanto?)**: Alguns meses de trabalho.

# Requisitos do sistema
## Requisitos funcionais:
Os requisitos funcionais descrevem as funcionalidades específicas que um sistema deve ter. Eles definem as ações que o sistema deve ser capaz de realizar e as interações que deve suportar.
- O sistema deverá mostrar os projetos de vários alunos para que o cliente possa explorar os projetos:
  - O portfólio será mostrado em diversas páginas (como o google);
  - O estilo fica a critério do desenvolvedor.
- O sistema deverá mostrar uma descrição do projeto, imagens, alunos participantes, tecnologias utilizadas e o início-fim do projeto;
- O sistema deverá possuir um filtro de nome/curso para facilitar a pesquisa sobre projetos específicos;
- O sistema deverá possuir uma opção de carregar (próxima página) mais projetos quando o usuário chegar ao fim da página:
  - Ao carregar mais projetos o sistema levará o usuário para a próxima página, ou o usuário poderá escolher uma página diretamente.
- O sistema deverá possibilitar que alunos cadastrem novos projetos:
  - Os alunos devem recorrer ao Administrador para cadastrar novos projetos.
- O sistema deve possuir um endereço separado para que o administrador possa fazer login, além disso, deve deve ter um botão de logout exclusivo para o mesmo;
- O sistema deve ter um meio para retornar ao site da Ibmec;
- O sistema deve ter um link de "home" para voltar à página principal;
- O sistema deve possuir um link "sobre nós" em cada projeto que diz respeito sobre seus desenvolvedores, e também deve haver um "sobre nós" para os desenvolvedores do próprio sistema;

## Requisitos não-funcionais:
Os requisitos não-funcionais descrevem as qualidades ou atributos do sistema, como o desempenho do próprio
- O sistema deverá ter a identidade visual da IBMEC;
- O sistema deverá possuir as opções de língua inglesa e portuguesa;
- O sistema deverá ser feito em React;
- O sistema deverá poder ser utilizado em celulares e computadores;
- O sistema deve fazer com que o botão de voltar do navegador volte para a mesma página da listagem que estava antes, ao invés de voltar para a página 1;
- O sistema deve exibir os projetos em ordem cronológica na página principal;
