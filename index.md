## Sobre o projeto

Projeto *Freedom* designado para o evento HackatonTech XP.

### Team Member

 - Guilherme Oliveira
 - William Rempp
 - Victor Rizzo
 - Douglas Hermann
 - Luiz Ihara

### Dificuldade

Time de NOC sofre com massiva de alarmes no zabbix. 

### Objetivo

Freedom ficará analisando o zabbix de tempos em tempos. Com a ajuda de machine learning, sistema envia ações para o N1 realizar. Ao receber uma avalanche de alarmes, Freedom pega todos os alarmes, analisa os relacionados e vincula para um unico só.

### Passo a Passo
 - Freedom identificado massiva. 
 - Job pega todos chamados ativos durante a massiva e monta uma base(cmdb/host/horarios/equipe...). 
 - Machine learning agrupa os chamados que são identificados como relacionados. 
 - É enviado notificação para o n1 com os chamados relacionados. 
 - Da lista, o n1 pode interagir quais sao realmente relacionados. 
 - N1 faz um post para abrir um chamado que vai relacionar todos os outros e dar ação no zabbix em todos os alarmes.

#### Criatividade e originalidade

#### Aplicabilidade

#### Qualidade do protótipo

#### Tecnologia

#### Elemento Futuro

#### Prontidão
