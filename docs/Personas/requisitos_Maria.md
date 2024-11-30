# Requisitos Elicitados da Persona Maria

## 1. Introdução

Este documento apresenta os 30 requisitos elicitados para uma persona específica, denominada Maria, que representa um perfil típico de usuário com características e desafios relevantes para o contexto do sistema em questão.

## 2. Metodologia

No desenvolvimento de sistemas focados na experiência do usuário, compreender profundamente as necessidades e expectativas das personas é essencial para alinhar as soluções propostas aos objetivos e valores dos usuários finais. A elaboração do documento que reúne os requisitos elicitados para a persona Maria foi conduzida com base em uma abordagem estruturada e iterativa de engenharia de requisitos. A seguir, são detalhadas as técnicas e ferramentas utilizadas nesse processo.

### 2.1 Técnica de Elicitação de Requisitos

- **Análise de Persona:** essa técnica, amplamente utilizada na elicitação de requisitos, foi a principal abordagem adotada no projeto. Por meio dela, foi possível compreender detalhadamente os usuários e suas características, permitindo o desenvolvimento de soluções alinhadas às suas necessidades e expectativas específicas.

### 2.2 Ferramentas Utilizadas

- **Documentação:** inicialmente, a ferramenta [Google Docs](https://docs.google.com/document/d/1x-UCNFgMgGev1fhT59Rhc4gisIndJaGMOQkznRJ-p4c/edit?usp=sharing)<a id="anchor_1" href="#REF1">^1^</a> foi utilizada para realizar o levantamento dos requisitos, proporcionando um espaço colaborativo para a documentação inicial. Posteriormente, os requisitos foram organizados e priorizados no [Google Sheets](https://docs.google.com/spreadsheets/d/1YadPL0ICzcG7JGqMRdq2svKq5dxUKzE6fzfoffjsSlU/edit?gid=0#gid=0)<a id="anchor_2" href="#REF2">^2^</a>, onde também foram integrados aos requisitos de outras personas, levantados por outros membros do projeto. Por fim, as versões finais serão padronizadas e organizadas antes de serem disponibilizadas no [Repositório do GitHub](https://github.com/UnBArqDsw2024-2/2024.2_G3_Aprender_Entrega_02/tree/main)<a id="anchor_3" href="#REF3">^3^</a> da disciplina, como parte da entrega 02.

- **Comunicação:** Durante o levantamento de requisitos assim como na priorização dos requisitos, utilizamos o [Microsoft Teams](https://teams.microsoft.com/v2/)<a id="anchor_4" href="#REF4">^4^</a>, em conjunto com os demais membros do projeto, para alinhar e consolidar os requisitos levantados, promovendo uma comunicação eficiente e colaborativa.

## 3. Requisitos Elicitados

A seguir, são apresentados os requisitos funcionais e não funcionais projetados para atender às necessidades da persona Maria, uma estudante que utiliza a plataforma para se preparar de maneira eficiente para seus objetivos acadêmicos. Os requisitos funcionais descrevem as funcionalidades essenciais para oferecer uma experiência prática e personalizada, enquanto os não funcionais garantem desempenho, segurança e usabilidade adequados para que Maria possa confiar e se engajar na plataforma de forma contínua.

<center>
<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Requisitos funcionais</p></font>

| Tipo  | Descrição                                                                                           |
|-------|-----------------------------------------------------------------------------------------------------|
| RF01  | O sistema deve enviar notificações sobre o cronograma de estudos e metas do aluno.                  |
| RF02  | O sistema deve possuir explicações detalhadas das questões erradas para aprendizado contínuo.       |
| RF03  | O sistema deve possuir funcionalidades para estabelecer e acompanhar metas pessoais.                |                 |
| RF04  | O sistema deve possuir recomendações personalizadas de vídeos e artigos baseados em dificuldades.   |
| RF05  | O sistema deve possuir ferramentas como cronômetros ou temporizadores para gerenciamento de tempo.  |
| RF06  | O sistema deve disponibilizar uma aba chamada 'Dicas de Estudo', contendo orientações práticas de organização, técnicas de estudo e links úteis, acessível a partir do menu principal.|
| RF07  | O sistema deve permitir que os usuários criem grupos de estudo, definindo temas ou objetivos, e entrem em grupos existentes com base em sugestões automáticas ou busca manual.|
| RF08  | O sistema deve sugerir conexões com estudantes que tenham objetivos semelhantes, com base nas conquistas alcançadas e nas metas acadêmicas.|
| RF09  | O sistema deve oferecer um chat com suporte a mensagens de texto, envio de imagens e arquivos, permitindo interação em tempo real ou mensagens assíncronas entre os membros do grupo.|
| RF10  | O sistema deve possibilitar o compartilhamento de materiais entre os membros do grupo, suportando arquivos PDF, imagens, links e textos.|
| RF11  | O sistema deve fornecer notificações sobre interações no grupo ou novas conexões sugeridas.  |
| RF12  | O sistema deve enviar uma notificação com uma mensagem motivacional para todos os usuários todas segundas-feira e quintas-feira 8h.|
| RF13  | O sistema deve armazenar o histórico das questões respondidas pelos usuários, incluindo suas respectivas respostas e datas, e permitir que o histórico seja acessado em formato de relatório na área do usuário.|
| RF14  | O sistema deve permitir que o usuário selecione quantas questões vai querer fazer no simulado. |                 |
| RF15  | O sistema deve permitir a personalização do tempo de duração dos simulados.|
| RF16  | O sistema deve permitir o acesso a provas anteriores completas.|
| RF17  | O sistema deve fornecer 2 modos de prova, o modo Prática e o modo Simulado.|
| RF18  | O sistema deve disponibilizar o gabarito da questão assim que a questão for resolvida no modo Prática.|
| RF19  | O sistema deve permitir selecionar o tempo de prova, o número de questões e o tipo das questões no modo simulado.|
| RF20  | O sistema deve permitir a customização dos simulados para incluir mais questões de matérias específicas (como Matemática e Ciências da Natureza).|
| RF21  | O sistema deve possibilitar a seleção de disciplinas a serem priorizadas.|
| RF22  |O sistema deve ser capaz de gerar um cronograma de estudos personalizado. |
| RF23  |O sistema deve destacar as áreas que precisam de melhoria. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Ana Carolina Costa César](https://github.com/CarolCoCe), [João Leles](https://github.com/joao-artl), [Felipe Motta](https://github.com/M0tt1nh4).</p></font>
</center>


<center>
<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Requisitos não funcionais</p></font>

| Tipo  | Descrição                                                                                           |
|-------|-----------------------------------------------------------------------------------------------------|
| RNF01  | O sistema deve consumir menos de 50 MB de dados por hora durante a navegação padrão, excluindo atividades intensivas como download de materiais.                  |
| RNF02  | O sistema deve armazenar dados conforme a LGPD (Lei Geral de Proteção de Dados Pessoais).      |
| RNF03  | O sistema deve garantir que 10% das perguntas de cada simulado sejam questões previamente respondidas de forma incorreta pelo usuário. Caso não haja questões suficientes, as perguntas restantes devem ser selecionadas de forma aleatória.                |
| RNF04  | O sistema deve permitir o download das guias de estudo e resumo em formato PDF. |
| RNF05  | O sistema deve ser acessível em qualquer dispositivo com acesso à internet.|
| RNF06  | O sistema deve ser acessível em dispositivos móveis.|
| RNF07  | O sistema deve ser responsivo e adaptar-se à tela de diferentes dispositivos móveis.|

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Ana Carolina Costa César](https://github.com/CarolCoCe), [João Leles](https://github.com/joao-artl), [Felipe Motta](https://github.com/M0tt1nh4).</p></font>
</center>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> Google Docs - Requisitos Maria. Disponível em: <https://docs.google.com/document/d/1x-UCNFgMgGev1fhT59Rhc4gisIndJaGMOQkznRJ-p4c/edit?usp=sharing>. Acesso em: 25 de nov de 2024.

> <a id="REF2" href="#anchor_2">2.</a> Google Sheets - First things first. Disponível em: <https://docs.google.com/spreadsheets/d/1YadPL0ICzcG7JGqMRdq2svKq5dxUKzE6fzfoffjsSlU/edit?gid=0#gid=0>. Acesso em: 26 de nov de 2024.

> <a id="REF3" href="#anchor_3">3.</a> GitHub - 2024.2_G3_Aprender_Entrega_02. Disponível em: <https://github.com/UnBArqDsw2024-2/2024.2_G3_Aprender_Entrega_02/tree/main>. Acesso em: 26 de nov de 2024.

> <a id="REF4" href="#anchor_4">4.</a> Microsoft Teams. Disponível em: <https://teams.microsoft.com/v2/>. Acesso em: 26 de nov de 2024.

## Histórico de Versão

| Versão | Data | Data de Revisão | Descrição | Autor(es) | Revisor(es) | Detalhes da revisão |
| ------ | -------- | -------- | ----------------- | ------------------------- | ------------------------- | ------------------------- |
| `1.0` | 27/11/2024 | 29/11/2024 | Criação do documento | [Ana Carolina Costa César](https://github.com/CarolCoCe), [João Leles](https://github.com/joao-artl) e [Felipe Motta](https://github.com/M0tt1nh4) | [Giovanni Giampauli](https://github.com/giovanniacg | Tudo ok |
