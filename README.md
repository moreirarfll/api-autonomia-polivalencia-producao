<h1 align="center">🏭 Projeto — Autonomia e Polivalência na Produção</h1><h3 align="center">Conclusão do Projeto Integrador | Planejamento Produtivo + Gestão de Operadores + Apoio à Decisão</h3><p align="center"><strong>FATEC São José dos Campos — Gestão da Produção Industrial</strong></p><!-- IMAGEM: capa da apresentação ou identidade visual do projeto. Substituir o caminho abaixo. -->

👥 Participantes do Projeto
Preencher os nomes e as funções oficiais da equipe antes da publicação. Essas informações não constam na apresentação analisada.

Nome	Função no Projeto
[Nome do integrante 1]	[Função]
[Nome do integrante 2]	[Função]
[Nome do integrante 3]	[Função]
[Nome do integrante 4]	[Função]
[Nome do integrante 5]	[Função]


👤 Cliente e Representação
O projeto foi desenvolvido a partir de um desafio operacional apresentado pela empresa parceira Freudenberg, com foco no aumento da autonomia da liderança de produção e no melhor aproveitamento da polivalência dos operadores.

Representante do cliente: [Nome e cargo]
Professor(a) orientador(a) / representante acadêmico(a): [Nome]
Validações realizadas: [Inserir informações ou link para os registros de feedback e validação]
📌 Descrição Geral
Este repositório documenta o desenvolvimento do projeto Autonomia e Polivalência na Produção, cujo objetivo é transformar informações operacionais em uma ferramenta de apoio à decisão para a liderança do setor produtivo.

O desafio identificado foi a dependência recorrente do Planejamento, Programação e Controle da Produção (PCP) para decisões relacionadas à disponibilidade de operadores, à cobertura de ausências e aos impactos das faltas sobre as metas de produção e as etapas seguintes do processo.

Para enfrentar esse problema, foi estruturada uma solução que integra planejamento produtivo, capacidade, escala e presença de operadores, matriz de polivalência e simulação de cenários de falta. A proposta é permitir que o líder consulte informações relevantes e avalie alternativas com maior agilidade, reduzindo a necessidade de acionar o PCP a todo momento.

O desenvolvimento foi organizado em três sprints, desde o entendimento do problema até a consolidação de uma solução analítica e visual.
🎯 Objetivos do projeto
- Ampliar a autonomia da liderança nas decisões operacionais do dia a dia.
- Dar visibilidade às metas, à produção realizada e à capacidade disponível.
- Identificar operadores habilitados a cobrir ausências por meio da matriz de polivalência.
- Simular perdas de produção e avaliar possibilidades de recuperação.
- Antecipar impactos de uma falta nos processos seguintes.
- Integrar informações de pessoas e produção em uma ferramenta de consulta.
🔧 Principais entregas
- Planilha estruturada como base do modelo de planejamento.
- Simulação de cenários de falta de operadores.
- Escala, acompanhamento de presença e matriz de polivalência.
- Protótipo visual com filtros, indicadores e apoio à tomada de decisão.
- Definição dos indicadores para avaliação da solução.
🖥️ Visão geral da solução
A solução centraliza dados operacionais em uma estrutura que permite acompanhar a produção, verificar a disponibilidade dos operadores e testar cenários de ausência.
<!-- IMAGEM: visão geral da ferramenta de apoio à decisão. -->

Acesso à ferramenta/protótipo: [Inserir link, se houver]
Acesso à planilha: [Inserir link, se autorizado]
Observação sobre permissões: [Indicar restrições de acesso, se aplicável]
📅 Evolução do Projeto — 3 Sprints
📅 Sprint 1 — Diagnóstico e Definição do Desafio
✔ Entregas principais
- Mapeamento do problema operacional.
- Definição do objetivo do projeto.
- Compreensão da dependência da liderança em relação ao PCP.
- Identificação das informações necessárias para apoiar decisões sobre produção e operadores.
Resultado da sprint: entendimento do desafio e direcionamento inicial da solução.
📸 Registros da Sprint 1
<!-- IMAGEM: diagnóstico do problema, fluxograma ou apresentação da Sprint 1. -->

📅 Sprint 2 — Estruturação do Modelo e Protótipo
✔ Entregas principais
- Estruturação da planilha de planejamento.
- Análises de capacidade produtiva e presença dos operadores.
- Desenvolvimento de cenários de ausência.
- Organização da matriz de polivalência.
- Desenvolvimento de um protótipo interativo para visualização das informações.
Resultado da sprint: transformação do diagnóstico em uma solução estruturada, analítica e visual.
📸 Registros da Sprint 2
<!-- IMAGEM: planilha, matriz ou protótipo produzido na Sprint 2. -->

<!-- IMAGEM: interface do protótipo desenvolvido. -->

📅 Sprint 3 — Validação e Consolidação da Solução
✔ Entregas principais
- Consolidação das informações de produção, capacidade e disponibilidade de operadores.
- Teste das premissas com dados reais.
- Ajustes nas regras do modelo.
- Definição dos indicadores finais de acompanhamento.
- Validação da aplicabilidade da ferramenta.
- Integração dos recursos em uma visão de apoio à decisão.
A estrutura consolidada contempla três frentes:
1. Planejamento produtivo: metas por turno, produção realizada e identificação de desvios.
2. Gestão de pessoas: presença dos operadores, identificação de profissionais aptos à cobertura e consulta à matriz de polivalência.
3. Simulação de cenários: análise de faltas, capacidade disponível e estimativa da necessidade de recuperação da produção.
Resultado da sprint: consolidação dos recursos desenvolvidos nas etapas anteriores em uma solução integrada para avaliação e consulta operacional.
📸 Registros da Sprint 3
<!-- IMAGEM: visão consolidada da Sprint 3. -->

🛠️ Entregas Técnicas
📊 Entrega 1 — Planilha de Planejamento Produtivo
A planilha funciona como base central do modelo, reunindo parâmetros configuráveis, metas por turno, produção realizada, informações de pessoas e cenários de exceção.

Na configuração apresentada na entrega final, o modelo considera:
Parâmetro	Configuração apresentada
Meta mensal	78.000 (configurável)
Processos conectados	3
Turnos parametrizados	3
Horizonte de planejamento	30 dias


Esses parâmetros permitem organizar as informações essenciais para o acompanhamento da produção e a análise de sua capacidade.
📸 Planilha de planejamento
<!-- IMAGEM: aba de parâmetros e planejamento da planilha. -->

⚠️ Entrega 2 — Simulação de Falta de Operadores
O modelo analisa a ausência de um operador não apenas como uma ocorrência isolada, mas como um evento capaz de afetar a produção e as etapas seguintes da cadeia.

A análise é dividida em três etapas:
1. Quantificação da perda: identifica a meta do turno comprometida e seu percentual em relação à meta diária.
2. Avaliação da recuperação: verifica a capacidade produtiva disponível e calcula a produção extra necessária por dia.
3. Priorização da ação: considera o impacto no processo seguinte, o PN/cliente afetado e a recomendação operacional apresentada pelo modelo.
O cenário também considera uma defasagem de um dia entre os processos, representando o buffer/estoque em processo (WIP).
📸 Simulador de cenários
<!-- IMAGEM: aba Cenário - Falta Operador da planilha. -->

👷 Entrega 3 — Escala, Presença e Matriz de Polivalência
A disponibilidade dos operadores passou a fazer parte do planejamento, permitindo analisar tanto quem está presente em determinado turno quanto quem possui habilitação para atuar em outros postos.
Escala e presença
- Acompanhamento da alocação dos operadores por turno.
- Identificação de ausências.
- Visualização de lacunas de cobertura.
Matriz de polivalência
- Consulta às habilidades e habilitações dos operadores por processo ou posto.
- Identificação de profissionais aptos à substituição.
- Apoio à análise de alternativas de cobertura em situações de falta.
📸 Escala e matriz de polivalência
<!-- IMAGEM: tabela de escala e presença. -->

<!-- IMAGEM: tela da matriz de polivalência, com filtro por operador ou turno. -->

💻 Entrega 4 — Ferramenta Visual de Apoio à Decisão
O protótipo reúne acompanhamento produtivo, filtros, presença dos operadores, indicadores e simulação de cenários em uma única interface.

A intenção é facilitar a interpretação das informações e apoiar decisões mais rápidas e organizadas diretamente no setor de produção.
📸 Interface da ferramenta
<!-- IMAGEM: visão principal da ferramenta de apoio. -->

<!-- IMAGEM OPCIONAL: detalhe dos filtros ou do resultado de uma simulação. -->

📈 Indicadores de Avaliação da Solução
Indicador	Finalidade
Aderência à meta de produção	Avaliar quanto da meta estabelecida foi efetivamente produzido.
Índice de cobertura de operadores	Demonstrar a capacidade de substituir operadores ausentes por profissionais habilitados.
Perda de produção	Quantificar a produção não realizada devido à indisponibilidade de operadores.
Capacidade de recuperação	Avaliar quanto da produção perdida pode ser recuperada em turnos ou dias posteriores.
Impacto no processo seguinte	Identificar como uma redução produtiva pode afetar a continuidade das operações seguintes.


<!-- IMAGEM OPCIONAL: painel ou quadro dos indicadores. -->

✅ Resultados e Benefícios Esperados
A solução foi desenvolvida com a expectativa de proporcionar:
- Maior visibilidade da capacidade produtiva.
- Melhor organização da disponibilidade de operadores.
- Menor dependência de profissionais específicos.
- Identificação antecipada de riscos de interrupção.
- Maior integração entre planejamento e operação.
O foco é transformar informações sobre pessoas e produção em decisões mais rápidas e organizadas.

Nota: os itens acima são benefícios esperados, conforme a apresentação final; não representam ganhos quantitativos comprovados de implantação.
📸 Resultados e apresentação final
<!-- IMAGEM: slide de benefícios, foto da Feira de Soluções ou registro da apresentação final. -->

📌 Backlog Geral do Projeto
Item	Descrição	Status na apresentação
1	Mapeamento do problema e definição do objetivo	✔ Desenvolvido na Sprint 1
2	Estruturação do modelo de planejamento	✔ Apresentado
3	Análise de capacidade e cenários de falta	✔ Apresentado
4	Escala, presença e matriz de polivalência	✔ Apresentado
5	Protótipo visual de apoio à decisão	✔ Apresentado
6	Consolidação dos indicadores e validação da solução	✔ Descrita na Sprint 3


Quadro de acompanhamento: [Inserir link do Trello, GitHub Projects ou outra ferramenta utilizada]
<!-- IMAGEM OPCIONAL: quadro de backlog ou cronograma das sprints. -->

🏁 Conclusão
O projeto Autonomia e Polivalência na Produção evoluiu do diagnóstico de um problema operacional para a estruturação de uma ferramenta integrada de apoio à decisão.

Ao reunir dados de capacidade produtiva, metas, presença e polivalência dos operadores, a solução oferece à liderança condições para identificar ausências, consultar possibilidades de cobertura e analisar impactos na produção.

A proposta é tornar as decisões operacionais mais ágeis e fundamentadas em informações acessíveis, contribuindo para a continuidade do processo produtivo e reduzindo a necessidade de consultar o PCP a cada ocorrência.
<h3 align="center">🔧 Desenvolvido no Projeto Integrador — Gestão da Produção Industrial | FATEC São José dos Campos</h3><p align="center"><strong>[Nome do grupo] • [Ano/Semestre]</strong></p>
