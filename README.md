
# Projeto-Interdisciplinar-I
Projeto acadêmico produzido a partir da articulação entre os componentes cursados em Gestão da Tecnologia da Informação, visando favorecer a construção de conhecimentos e habilidades necessárias para a prática profissional.

# Gestão Unificada de Informações do Agente (GUIA)
![WhatsApp Image 2025-08-27 at 19 43 43](https://github.com/user-attachments/assets/ef940962-bb86-4d44-b287-a067789c85b0)

# 1 - Identificação

__a) Identidade Visual__

O G.U.I.A. transmite confiança e proximidade, com cores suaves e ícones amigáveis que reforçam o papel do ACS como elo entre comunidade e saúde.

__b) Equipe__
  - Alessandro Sondey
  - Milena Pianaro
 
__c) Data de criação:__ 06/08/2025

# 2 - Concepção

__a) Conceito__

Este sistema será desenvolvido visando a otimização do trabalho dos Agentes Comunitários de Saúde, oferecendo ferramentas digitais que facilitam o acompanhamento dos usuários do Sistema Único de Saúde (SUS). Ele centralizará informações, automatizará tarefas recorrentes e melhorará a comunicação entre agentes e supervisores, promovendo mais eficiência e qualidade no atendimento.

<br>

Funcionalidades Principais:

📍 Geolocalização e Roteirização Inteligente Geração de rotas otimizadas para visitas domiciliares, com visualização em mapa das áreas já cobertas e das que ainda precisam ser atendidas. Isso ajuda o agente a planejar melhor seus deslocamentos e priorizar atendimentos.

🗺️ Mapa de Áreas de Risco construídas a partir de informações do agente para ajudar na organização da sua locomoção e das ferramentas necessárias para determinadas regiões, visando contribuir para a segurança do agente e também para o monitoramento e acompanhamento de surtos e epidemias.

🗂️ Registro Digital de Visitas Ficha eletrônica individual para cada paciente, contendo dados pessoais, histórico de saúde, registros de visitas anteriores e observações relevantes. Tudo acessível de forma rápida e segura.

🔔 Alertas e Lembretes Personalizados Notificações automáticas para eventos importantes, como datas de vacinação, acompanhamento de gestantes, idosos ou pacientes com doenças crônicas. O agente pode configurar lembretes para garantir que nenhum atendimento seja esquecido.

💬 Comunicação Integrada: Canal de comunicação direto entre agentes e população, via chat interno integração com o WhatsApp, facilitando o compartilhamento de informações e dúvidas.

<br>

__b) Justificativa__

O aplicativo G.U.I.A foi ideado para enfrentar os desafios vividos pelos Agentes Comunitários de Saúde (ACS), que, apesar de serem fundamentais na Atenção Primária e na consolidação do SUS, sofrem com desvalorização, sobrecarga de funções, falta de recursos e ausência de ferramentas adequadas. A pesquisa realizada em Pinhais/PR evidencia a rotina intensa desses profissionais, que acompanham centenas de famílias, lidam com limitações tecnológicas e enfrentam obstáculos estruturais e sociais que comprometem a continuidade do cuidado. Nesse contexto, o G.U.I.A surge como uma solução tecnológica e simbólica, oferecendo funcionalidades como roteirização inteligente, registros offline, alertas e canais de comunicação, com o objetivo de valorizar o trabalho dos ACS, reduzir a sobrecarga, ampliar a eficiência e fortalecer a rede de atenção preventiva, em alinhamento às diretrizes digitais do SUS e ao ODS 3 — Saúde e Bem-Estar.

<br>

__c) Objetivos__

O objetivo principal é o desenvolvimento de um aplicativo móvel voltado para apoiar os Agentes Comunitários de Saúde, com o objetivo de otimizar suas atividades, centralizar informações e fortalecer a Atenção Primária à Saúde. Entre os objetivos específicos, destacam-se: reunir em uma plataforma digital os registros de visitas e dados dos pacientes; oferecer geolocalização e roteirização inteligente para facilitar deslocamentos; criar alertas e lembretes personalizados para acompanhamento de vacinas, pré-natal e doenças crônicas; estabelecer canais diretos de comunicação entre agentes, equipes de saúde e comunidade; garantir funcionamento offline em áreas sem conectividade; e apoiar gestores com relatórios dinâmicos para monitoramento de indicadores de saúde comunitária.

<br>

__d) Escopo do produto__

__- Descrição do produto__

O G.U.I.A. (Gestão Unificada de Informações do Agente) será um aplicativo móvel voltado para apoiar o trabalho dos Agentes Comunitários de Saúde (ACS) e supervisores da atenção básica. Seu objetivo é centralizar informações de campo, organizar rotas e agendas de visitas, facilitar a comunicação entre equipes e disponibilizar relatórios sintéticos para acompanhamento das atividades. O aplicativo foi concebido para funcionar mesmo em ambientes com conectividade limitada, garantindo operação offline e sincronização posterior dos dados.

__- Principais entregas__

- Protótipo interativo com interfaces de cadastro, agenda, mapas e fichas de registro.
    
- Aplicativo funcional para dispositivos Android, com módulos de autenticação, coleta de dados, geolocalização, notificações e mensageria.

__- Critérios de aceite__

- Interfaces intuitivas e acessíveis, com navegação simples e feedback claro.

- Funcionamento offline com sincronização confiável dos dados.

- Relatórios compreensíveis e úteis para supervisão.

- Aderência ao guia de estilo e princípios de acessibilidade.

- Tempo de resposta inferior a 2 segundos nas principais operações locais.

- Cobertura de pelo menos 80% das funcionalidades previstas no backlog inicial.

- Redução mensurável de inconsistências nos registros de campo em comparação ao processo manual.

# 3 - Design do software

__a) Design Centrado no Usuário__ (https://www.designkit.org/methods.html)

<br>

__b) Persona__

**<img width="200" height="300" alt="Copilot_20250827_203004" src="https://github.com/user-attachments/assets/e775928d-76c0-4c3b-a594-80032a88c6e6" />**

__Maria Eduarda, Agente Comunitária de Saúde__

__Idade:__ 34 anos 

__Sexo:__ Feminino 

__Estado civil:__ Casada 

__Filhos:__ 1 filho 

__Escolaridade:__ Ensino Médio Completo, cursando Ensino Superior em Saúde Coletiva 

__Local de atuação:__ Comunidade periférica urbana 

__Tempo de experiência como ACS:__ 7 anos

<br>

__🧭 Perfil Profissional__

Maria Eduarda é uma agente comunitária dedicada, que conhece profundamente a realidade da comunidade onde atua. Ela realiza visitas domiciliares diariamente, acompanhando gestantes, idosos, pacientes crônicos e famílias em situação de vulnerabilidade. Seu trabalho exige organização, empatia e agilidade para lidar com múltiplas demandas.

Apesar de dominar bem os processos do SUS, ela sente que poderia ser mais eficiente se tivesse ferramentas digitais que facilitassem o registro de informações, o planejamento das visitas e a comunicação com sua equipe.

__📱 Necessidades e Expectativas__

__Facilidade no registro de dados:__ Quer substituir o papel por um sistema intuitivo que permita cadastrar pacientes e atualizar informações de forma rápida durante as visitas.

__Roteirização inteligente:__ Precisa de ajuda para organizar seus trajetos diários, evitando deslocamentos desnecessários e otimizando o tempo.

__Lembretes e alertas:__ Valoriza notificações que a ajudem a lembrar de datas importantes, como vacinas, pré-natal e acompanhamento de pacientes com doenças crônicas.

__Comunicação fluida:__ Deseja se comunicar com outros agentes e supervisores de forma prática, sem depender exclusivamente de grupos de WhatsApp.

__Acesso fácil e offline:__ Como nem sempre há sinal de internet nas áreas que visita, espera que o sistema funcione mesmo em modo offline.

<br>

__c) Storyboard (contexto de uso)__
https://www.canva.com/design/DAGzK8zLpnQ/Wv83KsZ-zZKjMH3oPZ5Zkg/edit
<br>

__d) UI Design (guia de estilo)__

- Verde-petróleo (fundo principal): #009688
- Amarelo-dourado (coração e detalhe inferior): #F9C233
- Verde-claro (detalhe da folha): #6FBF73
- Branco (ícones e mão): #FFFFFF
- Cinza-escuro (texto G.U.I.A): #004D40
- Cinza-claro (texto secundário): #00796B
<br>

__e) Prototipação do MVP (Figma)__

__Link:__ https://www.figma.com/proto/n9gjPc6w9RrYTWbxgc1Q7J/GUIA?t=q8LzyVarXPUjFwIS-0

# 4 - Desenvolvimento 

a) Processo de software (scrum, xp, kanban,..) 
b) Recursos utilizados (tecnologias, ferramentas de apoio, linguagem de programação, equipamentos, rede); 
c) Resultados esperados
d) Instruções para download e execução 
e) Licença de uso e distribuição 

# 5 - Estratégia de marketing digital para divulgar o produto e criar engajamento com público alvo

A definir

# 6 - Gestão do Projeto – Arquivos do Projeto

__Projeto 1:__ https://drive.google.com/file/d/1ACvctgJ5pA8grGD7vTZK4M0ttRkjW0zH/view?usp=sharing

__Projeto 2:__ https://drive.google.com/file/d/17j9qdkMaZCKHT3Q6JzyzwjsvHgxClnA9/view?usp=drive_link

__Contexto sequenciador - MVP e incrementos:__ www.figma.com/proto/n9gjPc6w9RrYTWbxgc1Q7J/GUIA?t=q8LzyVarXPUjFwIS-0

__Detalhamento das atividades do projeto:__ A desenvolver

__Cronograma MVP + incrementos:__

| Mês/Ano   | Atividades Principais                                                                 |
|-----------|----------------------------------------------------------------------------------------|
| ago. 2025 | Planejamento inicial do projeto; definição da abordagem metodológica e escopo geral    |
| set. 2025 | Aplicação de formulário semiestruturado; construção da persona e storyboard            |
| out. 2025 | Desenvolvimento do Guia de Estilo; início do protótipo interativo (Figma/Quant-UX)     |
| nov. 2025 | Configuração de repositório; protótipo interativo (Figma/Quant-UX) e apresentação da proposta |
| fev. 2026 | Sprint 1: Gestão de usuários e segurança; coleta de dados e sistema de mensagens       |
| mar. 2026 | Sprint 2: Geolocalização e roteirização                                                |
| abr. 2026 | Sprint 3: Calendários; alertas personalizados; relatórios e dashboards                 |
| mai. 2026 | Sprint 4: Operação offline e sincronização; testes e documentação                      |
| jun. 2026 | Testes de validação; refinamentos finais; documentação e apresentação do produto       |

 
# 7 - Métricas para monitoração e acompanhamento do projeto 

# 8 - Relatório de encerramento e lições aprendidas 

Relatório Técnico
Plano de Negócio
Artigo
Extras: 
Modelagem UML (casos de uso, atividades, sequência, classes)
Modelagem banco de dados (DER e Modelo de dados no Workbench) 
Resultados da Entrevista com o usuário 
Termo Livre de Consentimento




💬 Frase que representa Maria Eduarda:
"Meu trabalho é cuidar das pessoas, mas para isso preciso de ferramentas que cuidem da minha rotina também."
