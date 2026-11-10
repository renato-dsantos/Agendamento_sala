# Documento de Requisitos do Produto (PRD)

## 1. Identificação do projeto

| Campo | Valor |
|---|---|
| Projeto/repositório | Agendamento_sala |
| Nome do produto | Não confirmado |
| Versão | 1.2 |
| Status | **Rascunho / bloqueado para baseline** |
| Data | 2026-11-10 |
| Responsável | Renato dos Santos, Product Manager |
| Aprovação | Renato dos Santos, Product Manager, é o responsável pelo produto e a autoridade final de aprovação. O sign-off explícito e documentado do PRD v1.2 e a declaração do estado da baseline permanecem pendentes. |
| Changelog | Registro de alterações do PRD, apresentado após o resumo executivo |

> Este documento registra fatos, decisões explícitas do Product Manager, interpretações e pendências separadamente. Não autoriza implementação nem constitui baseline de produto. Renato dos Santos, Product Manager, é o responsável pelo produto e a autoridade final de aprovação. O sign-off explícito e documentado do PRD v1.2 e a declaração do estado da baseline permanecem pendentes; o status é Rascunho / bloqueado para baseline. Prioridades Alta/Média dos RF representam prioridade de feature e não definem, por si, prioridade de MVP.

## 2. Resumo executivo

### Proposta de produto

**Decisão/contexto informado pelo Product Manager em 2026-11-10:** desenvolver uma aplicação para organizar a alocação de salas, professores e materiais. Renato aceita tratar a necessidade de produto como hipótese a validar; nenhum problema empírico foi observado ou validado até agora. Resultados esperados, métricas de negócio e evidências para validar ou refutar a hipótese permanecem pendentes. O plano de discovery do @analyst deverá identificar público e contexto com Renato, ouvir usuários representativos sobre o processo atual com exemplos, usar registros/artefatos disponíveis quando houver, documentar evidências favoráveis e contrárias e definir sinais de confirmação/refutação. Tamanho/amostra e métricas continuam pendentes. Isso não aprova a baseline.

### Contexto e situação

Segundo a contextualização fornecida pelo responsável do produto, a iniciativa trata do gerenciamento de reservas de recursos institucionais, especificamente salas, professores e materiais. O Product Manager confirmou como capacidades pretendidas consultar disponibilidade, criar reservas, controlar aprovações aplicáveis e acompanhar a utilização. Evitar conflitos permanece um objetivo proposto, não um problema empiricamente observado.

A avaliação deverá apresentar evidências objetivas de qualidade de software, segurança da informação, rastreabilidade de requisitos, integridade e consistência dos dados, desempenho, confiabilidade, usabilidade e manutenibilidade, considerando boas práticas de Engenharia de Software e características de qualidade estabelecidas pela ISO/IEC 25010. Renato dos Santos, Product Manager, aceitou todos os valores-alvo quantitativos atualmente propostos nos RNF como critérios-alvo para validação empírica. Isso não significa que tenham sido testados ou atingidos: cargas, dados, ambiente e método de medição continuam pendentes. Características aplicáveis, critérios qualitativos e métodos também dependem de validação.

O README consultado contém apenas `# Agendamento_sala`. O responsável confirmou os três perfis e as permissões descritas na seção 6, inclusive que uma pessoa pode acumular perfis e que as permissões se somam. Essas decisões foram fornecidas pelo Product Manager, mas não constituem aprovação final do PRD. Regras operacionais ainda abertas, fluxos detalhados e decisões de solução permanecem pendentes.

### Limitações das fontes

- Renato aceita tratar a necessidade de produto como hipótese a validar; nenhum problema empírico foi observado nem validado até agora. Não foram fornecidas evidências adicionais de pesquisa com usuários, dados operacionais, mercado ou solução existente.
- As decisões explicitamente fornecidas em 2026-11-10 estão registradas neste PRD. Renato dos Santos, Product Manager e autoridade final de aprovação, ainda não registrou sign-off explícito e documentado do PRD v1.2 nem declarou o estado da baseline. Detalhes de regras, plataforma, tecnologia, integrações, prazo, governança e contexto operacional de medição continuam pendentes. Renato aceitou os valores-alvo quantitativos atualmente propostos nos RNF como critérios-alvo para validação empírica; não há evidência de testes ou de atingimento.
- As perguntas deste documento são instrumentos de descoberta, não requisitos nem decisões.

### Registro de alterações

| Data | Versão | Descrição | Autor |
|---|---|---|---|
| 2026-11-10 | 0.1 | Rascunho inicial para elicitação, baseado nas fontes disponíveis; baseline bloqueada. | Não confirmado |
| 2026-11-10 | 0.2 | Inclusão da contextualização fornecida pelo responsável; decisões operacionais e critérios mensuráveis permanecem pendentes. | Não confirmado |
| 2026-11-10 | 0.3 | Inclusão da proposta de escopo e perfis; validação como baseline e regras operacionais permanecem pendentes. | Não confirmado |
| 2026-11-10 | 0.4 | Especificação de RF/RNF com prioridades e metas iniciais propostas para validação. | Não confirmado |
| 2026-11-10 | 0.5 | Inclusão das regras recebidas e propostas adicionais para decisão. | Não confirmado |
| 2026-11-10 | 0.6 | Mapeamento de oito características de qualidade, Utility Tree e preparação para futura avaliação ATAM. | Não confirmado |
| 2026-11-10 | 0.7 | Rastreabilidade RF–HU–CA–RN–RNF–qualidade–EVD e evidências futuras planejadas. | Não confirmado |
| 2026-11-10 | 0.8 | Reestruturação na ordem final de 22 seções e inclusão de matriz inicial de riscos; baseline permanece bloqueada. | Não confirmado |
| 2026-11-10 | 0.9 | Registro das decisões fornecidas por Renato dos Santos (Product Manager): hipótese sem problema empírico observado, prioridade de MVP, permissões cumulativas, calendário, reservas parciais, recursos restritos, manutenção, movimentação e aceitação dos alvos quantitativos candidatos dos RNF para validação. Aprovação final permanece pendente; baseline bloqueada. | Renato dos Santos, Product Manager |
| 2026-11-10 | 1.0 | Identificação formal de Renato dos Santos, Product Manager, como responsável pelo produto e autoridade/aprovador final de todas as aprovações do projeto. A aprovação explícita e documentada desta baseline do PRD continua pendente; status Rascunho e bloqueio para baseline preservados. | Renato dos Santos, Product Manager |
| 2026-11-10 | 1.1 | Registro do aceite de tratar a necessidade como hipótese a validar e do plano de discovery; aceite formal de acompanhar regras residuais sem aprová-las; revisão de testabilidade dos RNF sem alterar alvos; correção dos perfis e fatias de MVP na tabela de HUs conforme catálogo v1.0. Sequência de entrega e sign-off explícito do PRD v1.1/estado da baseline permanecem pendentes; status Rascunho/bloqueado preservado. | Renato dos Santos, Product Manager |
| 2026-11-10 | 1.2 | Registro das respostas mais recentes: hipótese aceita para discovery; aceite de acompanhamento das regras residuais sem aprovação ou fechamento; detalhamento das lacunas de verificabilidade dos RNF; alinhamento da tabela de HUs ao catálogo v1.0; confirmação de Renato como autoridade final. Sign-off explícito do PRD v1.2, declaração do estado da baseline e sequência de entrega permanecem pendentes; status Rascunho / bloqueado para baseline. | Atualização do PRD com respostas do responsável; sign-off não fornecido |

## 3. Contextualização e problema

### Fatos e fontes

- O repositório está identificado como `Agendamento_sala`.
- O README contém somente um título com esse identificador.
- Em 2026-11-10, Renato dos Santos, Product Manager, informou as decisões registradas nesta versão e foi identificado como responsável pelo produto e autoridade final de aprovação. O sign-off explícito e documentado do PRD v1.2 e a declaração do estado da baseline ainda estão pendentes.
- Renato aceita tratar a necessidade como hipótese a validar. Nenhum problema empírico foi observado ou validado até agora; não há evidência empírica fornecida.
- O Product Manager confirmou três perfis — Solicitante, Responsável e Administrador — e as permissões registradas na seção 6. Os perfis podem se acumular e as permissões são somadas.
- O Product Manager definiu uma prioridade de MVP separada da prioridade Alta/Média de cada RF; a decisão está registrada na seção 5.
- A contextualização recebida destaca evidências de qualidade de software e considera boas práticas de Engenharia de Software e a ISO/IEC 25010.
- Não foram localizados Project Brief, pesquisa, requisitos detalhados ou outros documentos de produto no material consultado.
- As decisões explícitas do Product Manager estão registradas, mas Renato dos Santos, autoridade final de aprovação, ainda não registrou sign-off explícito e documentado do PRD v1.2 nem declarou o estado da baseline; o status permanece Rascunho / bloqueado para baseline.

### Interpretação e hipótese contextual

**Renato aceita tratar a necessidade como hipótese a validar; nenhum problema empírico foi observado ou validado até agora.** A oportunidade e o benefício de evitar conflitos não são evidência de problema existente. O @analyst deverá conduzir discovery identificando público/contexto com Renato, ouvindo usuários representativos sobre o processo atual com exemplos, usando registros/artefatos disponíveis quando houver, documentando evidências favoráveis e contrárias e definindo sinais de confirmação/refutação. Tamanho/amostra, métricas e resultados esperados permanecem pendentes. As permissões confirmadas da seção 6 são decisões fornecidas pelo Product Manager; não se inferem permissões adicionais nem que o PRD tenha aprovação final.

### Decisões pendentes

Permanecem pendentes a validação empírica da hipótese e dos resultados/métricas de negócio, o sign-off explícito do PRD v1.2 e a declaração do estado da baseline, os detalhes operacionais registrados nas seções 8–10 e 22, critérios de sucesso, UX, segurança, acessibilidade, plataforma, integrações, restrições, prazo e governança. O escopo prioritário de MVP foi proposto pelo Product Manager conforme seção 5. Renato dos Santos, Product Manager, aceitou os valores-alvo quantitativos atualmente propostos nos RNF como critérios-alvo para validação empírica; eles ainda não foram testados e não há evidência de atingimento.

## 4. Objetivos do produto

O objetivo proposto é desenvolver e validar uma aplicação para organizar a alocação de salas, professores e materiais, apoiar consulta de disponibilidade, reservas, aprovações aplicáveis e acompanhamento de utilização. Renato aceita a necessidade como hipótese para discovery; evitar conflitos é um benefício pretendido, não um problema empiricamente observado ou validado. O plano de discovery deverá validar público/contexto e processo atual com usuários representativos e evidências disponíveis, documentando sinais favoráveis e contrários. Resultados esperados, tamanho/amostra e métricas de negócio ainda precisam de definição; o sign-off do PRD v1.2 e a declaração do estado da baseline permanecem pendentes.

## 5. Escopo e limitações

### Escopo proposto e prioridade de MVP

**Decisão fornecida pelo Product Manager em 2026-11-10:** a prioridade do MVP é o núcleo obrigatório formado por RF001–RF006, RF008, RF010, RF013 e RF014. RF007, RF009, RF011 e RF012 ficam para priorização posterior conforme tempo/necessidade, sem serem removidos do escopo total do produto. Esta classificação de MVP é independente das prioridades de feature Alta/Média registradas por RF e não as altera. A decisão não constitui aprovação final do PRD nem baseline.

O escopo total proposto continua abrangendo gestão de reservas de salas, professores e materiais, consulta de disponibilidade, aprovação de reservas especiais, bloqueios/manutenção, movimentação, auditoria, notificações, relatórios, interface e documentação, conforme RF001–RF014. Detalhes e critérios ainda pendentes permanecem explicitados nas seções correspondentes.

### Limitação: decomposição em epics

**Nenhum epic proposto ou aprovado.** A decomposição em epics depende da validação do problema, do MVP e dos requisitos. Este PRD preliminar não cria stories ou plano de implementação.

## 6. Perfis de usuários e permissões

Os três perfis e as permissões abaixo foram informados explicitamente por Renato dos Santos, Product Manager, em 2026-11-10. As permissões listadas não devem ser extrapoladas. Uma pessoa pode acumular perfis e, nesse caso, as permissões são somadas. Essa decisão não equivale à aprovação final do PRD.

#### Solicitante

Professor ou coordenador que necessita reservar recursos institucionais.

Responsabilidades/permissões propostas:
- Consultar disponibilidade de salas, professores e materiais.
- Criar reservas.
- Alterar e cancelar suas próprias reservas.

#### Responsável

Perfil com as permissões confirmadas abaixo; “Responsável” inclui diretores para aprovação de reservas especiais conforme RN018.

Responsabilidades/permissões propostas:
- Consultar disponibilidade de salas, professores e materiais.
- Criar reservas e alterar/cancelar suas próprias reservas.
- Aprovar reservas especiais.
- Registrar retirada e devolução de materiais/equipamentos.
- Consultar todos os agendamentos e relatórios gerais.

#### Administrador

Perfil com as permissões de gestão expressamente confirmadas abaixo.

Responsabilidades/permissões propostas:
- Consultar disponibilidade de salas, professores e materiais.
- Criar reservas e alterar/cancelar suas próprias reservas.
- Aprovar reservas especiais.
- Gerenciar salas, professores, materiais e bloqueios.
- Registrar retirada e devolução de materiais/equipamentos.
- Consultar todos os agendamentos e relatórios gerais.
- Classificar recursos restritos.

#### Limites e pendências dos perfis

- Não foram informadas permissões além das listadas acima; não se presume gestão de usuários/permissões, edição de reservas alheias, justificativa de reprovação ou outros poderes.
- A definição operacional de “reserva especial” e a classificação/limiar de “alto custo” permanecem pendentes conforme seção 10.
- Regras de alteração/cancelamento, movimentação e outros limites operacionais permanecem pendentes nas regras de negócio.
- Não foi adicionada persona “Diretor”: diretores estão incluídos no papel de Responsável para aprovação de recursos restritos, conforme seção 10.

## 7. Funcionalidades principais

| Grupo funcional | RF |
|---|---|
| Acesso, perfis e recursos | RF001–RF002 |
| Pesquisa e disponibilidade | RF003 |
| Reservas | RF004 |
| Conflitos e concorrência | RF005–RF006 |
| Aprovação, bloqueio e manutenção | RF007–RF008 |
| Movimentação, auditoria e histórico | RF009–RF010 |
| Notificações e indicadores | RF011–RF012 |
| Interface e documentação | RF013–RF014 |

Esta visão agrupada não substitui os identificadores e descrições formais abaixo.

## 8. Requisitos funcionais

Os requisitos abaixo organizam o escopo do produto e comportamentos verificáveis. As decisões explicitamente fornecidas pelo Product Manager estão refletidas, mas a aprovação final do PRD continua pendente. Em cada RF, a prioridade Alta/Média (ou P1/P2 quando assim registrada) é prioridade de feature, não a priorização do MVP: núcleo obrigatório e itens posteriores estão separados na seção 5. “Sistema” identifica validações ou registros automáticos, não um perfil de usuário.

### RF001 — Autenticação e autorização

- **Descrição:** Autenticar usuários; controlar o acesso conforme os perfis Solicitante, Responsável e Administrador e as permissões confirmadas na seção 6; impedir acesso a funcionalidades não autorizadas; permitir encerrar a sessão.
- **Perfil responsável:** Solicitante, Responsável e Administrador (usuários); Sistema (autenticação, aplicação de autorização e encerramento de sessão). Política de autenticação: a confirmar.
- **Prioridade:** P1 — proposta para validação, devido ao risco de acesso indevido a funções e dados.
- **Critérios de aceitação:** (1) Um usuário pode iniciar sessão após autenticação. (2) A tentativa de acessar uma funcionalidade não autorizada ao perfil é impedida. (3) O usuário pode encerrar a sessão. (4) Os perfis e permissões efetivos podem ser verificados em uma matriz aprovada, ainda pendente.

### RF002 — Gerenciamento de recursos

- **Descrição:** Permitir ao Administrador gerenciar salas, professores, materiais e bloqueios; os três perfis podem consultar a disponibilidade de salas, professores e materiais. O cadastro de professores inclui matrícula/número de registro.
- **Perfil responsável:** Administrador (gerenciar salas, professores, materiais e bloqueios); Solicitante, Responsável e Administrador (consultar disponibilidade); Sistema (aplicar as regras registradas).
- **Prioridade:** P1 — proposta para validação, por habilitar a gestão dos recursos usados nas reservas.
- **Critérios de aceitação:** (1) O Administrador consegue gerenciar salas, professores, materiais e bloqueios. (2) Os três perfis conseguem consultar disponibilidade de salas, professores e materiais. (3) Não se inferem permissões de gestão adicionais para Solicitante ou Responsável.

### RF003 — Pesquisa e disponibilidade

- **Descrição:** Consultar disponibilidade de salas, professores e materiais. Filtros por características, competências e quantidade permanecem sujeitos a definição.
- **Perfil responsável:** Solicitante, Responsável e Administrador (consultar disponibilidade); Sistema (aplicar filtros definidos e apresentar resultados).
- **Prioridade:** P1 — proposta para validação, pois apoia a escolha de recursos disponíveis.
- **Critérios de aceitação:** (1) Os três perfis podem consultar disponibilidade de salas, professores e materiais. (2) A disponibilidade apresentada corresponde à data/horário consultados e às regras operacionais aprovadas. (3) Critérios de filtro adicionais, intervalos e disponibilidade por tipo/quantidade permanecem pendentes.

### RF004 — Reservas

- **Descrição:** Os três perfis podem criar reservas e alterar/cancelar suas próprias reservas; Responsável e Administrador podem consultar todos os agendamentos. Registrar data, hora inicial, hora final e recursos associados, conforme regras a definir.
- **Perfil responsável:** Solicitante, Responsável e Administrador (criar reservas e alterar/cancelar suas próprias); Responsável e Administrador (consultar todos os agendamentos); Sistema (registrar dados e status).
- **Prioridade:** P1 — proposta para validação, por representar o fluxo central de agendamento.
- **Critérios de aceitação:** (1) Cada perfil pode criar uma reserva. (2) Cada perfil pode alterar ou cancelar apenas suas próprias reservas. (3) Responsável e Administrador podem consultar todos os agendamentos. (4) Limites, estados e regras operacionais adicionais de alteração/cancelamento permanecem pendentes.

### RF005 — Prevenção e apresentação de conflitos

- **Descrição:** Impedir sobreposição de reservas para a mesma sala, professor ou material/equipamento; considerar intervalos de utilização e apresentar mensagens claras quando houver conflito.
- **Perfil responsável:** Solicitante, Responsável e Administrador (podem criar reservas); Sistema (verificação dos intervalos, bloqueio de conflito e apresentação do resultado).
- **Prioridade:** P1 — proposta para validação, pelo risco de alocação conflitante.
- **Critérios de aceitação:** (1) Dadas duas solicitações que se sobreponham no intervalo de utilização do mesmo recurso, o Sistema identifica o conflito e não permite confirmar ambas. (2) A verificação contempla sala, professor e material/equipamento. (3) A mensagem informa que há conflito de disponibilidade. (4) O tratamento de limites do intervalo e de horários adjacentes fica pendente de decisão; este critério não define se intervalos adjacentes conflitam.

### RF006 — Concorrência e dupla reserva

- **Descrição:** Evitar que solicitações simultâneas para o mesmo recurso gerem reservas duplicadas; manter consistência do resultado e registrar o resultado das tentativas.
- **Perfil responsável:** Solicitante, Responsável e Administrador (podem criar reservas); Sistema (verificação de concorrência, consistência e registro).
- **Prioridade:** P1 — proposta para validação, dado o risco de duplicidade quando há disputa pelo recurso.
- **Critérios de aceitação:** (1) Em um ensaio com duas solicitações simultâneas para intervalos conflitantes do mesmo recurso, no máximo uma pode resultar em reserva confirmada. (2) O resultado de cada tentativa fica registrado e pode ser verificado. (3) A disponibilidade e o status apresentados após as tentativas não indicam duas reservas confirmadas para o mesmo conflito. (4) O critério não prescreve tecnologia ou mecanismo de implementação.

### RF007 — Aprovação de reservas restritas

- **Descrição:** Reservas especiais de recursos restritos dependem de aprovação do Responsável ou Administrador antes da confirmação. Recursos citados: equipamentos de alto custo e auditórios; o Administrador os classifica. O limiar de “alto custo” permanece pendente.
- **Perfil responsável:** Responsável e Administrador (aprovar reservas especiais); Administrador (classificar recursos restritos); Solicitante, Responsável e Administrador (podem criar reservas).
- **Prioridade:** P1 — proposta para validação, devido ao risco de uso de recurso sujeito a aprovação sem decisão.
- **Critérios de aceitação:** (1) Reserva especial para recurso restrito não é confirmada sem aprovação. (2) Responsável ou Administrador pode aprovar a reserva especial. (3) O Administrador classifica equipamentos de alto custo e auditórios como recursos restritos. (4) Ao reprovar uma solicitação, Responsável ou Administrador deve informar justificativa; a reprovação não é concluída sem esse preenchimento. (5) Critério objetivo de alto custo, definição de outras reservas especiais e demais regras de decisão permanecem pendentes.

### RF008 — Bloqueios e manutenção

- **Descrição:** Bloquear temporariamente salas e materiais/equipamentos, registrar períodos de manutenção e impedir reservas durante períodos de indisponibilidade; registrar motivo e responsável pelo bloqueio.
- **Perfil responsável:** Administrador (gerenciar bloqueios); Sistema (considerar indisponibilidade na consulta e reserva e tratar reservas futuras afetadas conforme RN017).
- **Prioridade:** P1 — proposta para validação, para evitar alocações em períodos indisponíveis.
- **Critérios de aceitação:** (1) O Administrador pode gerenciar bloqueios. (2) A disponibilidade e novas reservas respeitam bloqueios registrados. (3) Se manutenção afetar reserva futura, aplica-se o redirecionamento para sala disponível e aviso ao solicitante conforme RN017; contingência quando não houver sala permanece pendente.

### RF009 — Retirada e devolução

- **Descrição:** Responsável e Administrador podem registrar retirada e devolução somente para reserva confirmada e aprovada. Restrições de janela, atraso e devolução parcial permanecem pendentes.
- **Perfil responsável:** Responsável e Administrador (registrar retirada/devolução); Sistema (validar elegibilidade da reserva).
- **Prioridade:** P2 — proposta para validação, por apoiar o acompanhamento operacional posterior à reserva.
- **Critérios de aceitação:** (1) Responsável ou Administrador pode registrar movimentação vinculada somente a reserva confirmada e aprovada. (2) Movimentação vinculada a reserva não confirmada ou não aprovada não é elegível. (3) Janela de movimentação, atraso, devolução parcial e demais ocorrências permanecem pendentes.

### RF010 — Auditoria e histórico

- **Descrição:** Registrar criação, alteração e cancelamento de reservas; alterações cadastrais relevantes; aprovações e reprovações, incluindo usuário, data/hora e operação; preservar histórico para consulta autorizada.
- **Perfil responsável:** Sistema (registro e preservação do histórico); Responsável e Administrador (consultar auditoria).
- **Prioridade:** P1 — proposta para validação, por apoiar rastreabilidade e responsabilização.
- **Critérios de aceitação:** (1) As operações incluídas no escopo de auditoria geram registros verificáveis. (2) Responsável e Administrador podem consultar auditoria. (3) A política de retenção e os detalhes dos eventos/alterações registrados permanecem pendentes.

### RF011 — Notificações

- **Descrição:** Funcionalidade futura/depriorizada no MVP. O conteúdo, os eventos, destinatários e a escolha entre notificação simulada ou integração externa ainda não foram definidos.
- **Perfil responsável:** Sistema (gerar notificações); perfis destinatários: a confirmar; Responsável e Solicitante podem ser destinatários conforme decisão pendente.
- **Prioridade:** P2 — prioridade de feature existente; fora do núcleo obrigatório do MVP e sujeita a priorização posterior conforme tempo/necessidade.
- **Critérios de aceitação:** (1) Para cada evento incluído no escopo, é possível verificar a geração de uma notificação correspondente. (2) O conteúdo permite identificar o evento e o status/pendência relacionada. (3) Mecanismo de envio, destinatários, preferências e momento de entrega permanecem a confirmar; não se presume integração externa.

### RF012 — Relatórios e indicadores

- **Descrição:** Funcionalidade futura/depriorizada no MVP. Conteúdo, fórmulas, filtros e indicadores de relatórios ainda não foram definidos.
- **Perfil responsável:** Responsável e Administrador (consultar relatórios gerais); conteúdo e dados apresentados permanecem pendentes.
- **Prioridade:** P2 — prioridade de feature existente; fora do núcleo obrigatório do MVP e sujeita a priorização posterior conforme tempo/necessidade.
- **Critérios de aceitação:** (1) Relatórios gerais podem ser consultados por Responsável e Administrador. (2) Conteúdo, filtros, período, fórmulas e critérios de validação dos relatórios serão definidos antes da implementação desta funcionalidade futura.

### RF013 — Interface e usabilidade

- **Descrição:** Oferecer interface responsiva, erros compreensíveis, consulta facilitada de disponibilidade, identificação visual de status e diferenciação de funções por perfil.
- **Perfil responsável:** Solicitante, Responsável e Administrador (usuários); Sistema (apresentar interface, mensagens, status e funções de acordo com o perfil).
- **Prioridade:** P1 — proposta para validação, por afetar a execução dos fluxos centrais por todos os perfis.
- **Critérios de aceitação:** (1) A interface se adapta a desktop, tablet e celular; a cobertura de navegadores segue o alvo aceito na seção 9, com matriz concreta ainda pendente. (2) Estados de reserva são identificáveis visualmente. (3) Erros apresentados permitem compreender que a operação não foi concluída e qual situação ocorreu. (4) As funções disponíveis refletem o perfil autenticado e as autorizações aprovadas. (5) A facilidade de concluir o fluxo será verificada conforme RNF010.

### RF014 — Documentação

- **Descrição:** Manter documentação dos fluxos, regras e permissões incluídos no escopo. Existência de API e eventual documentação de endpoints, parâmetros, respostas e erros ainda não foram definidas.
- **Perfil responsável:** Responsável pela documentação: a confirmar; documentação da API só se aplica caso uma API seja definida.
- **Prioridade:** P2 — proposta para validação, para apoiar compreensão e manutenção dos contratos e fluxos públicos.
- **Critérios de aceitação:** (1) Os fluxos, regras e permissões definidos estão documentados. (2) Caso uma API seja definida, documentar endpoints, parâmetros, respostas e códigos de erro. (3) Existência de API, titularidade e formato da documentação permanecem pendentes.

### Pendências de elicitação dos RF

- Definir política de autenticação e detalhes de autorização além das permissões confirmadas na seção 6; os perfis podem se acumular e as permissões são somadas.
- Definir quando um professor atua como solicitante e quando é um recurso consultável/alocável, sem inferir permissões além das confirmadas.
- Resolver as questões abertas de RN013–RN019 e detalhes operacionais remanescentes; aprovação final do PRD continua pendente.
- Definir política de retenção de auditoria; Responsável e Administrador podem consultá-la.
- Decidir entre notificações simuladas ou API externa, destinatários e eventos/destinos de cada notificação.
- Definir escopo, filtros, fórmulas e perfis autorizados dos relatórios.
- Confirmar se existe API e quem responde pela documentação dos fluxos e regras.

## 9. Requisitos não funcionais

Os RNF estão organizados por características de qualidade da ISO/IEC 25010, sem afirmar uma edição específica. Em 2026-11-10, o Product Manager aceitou todos os valores-alvo quantitativos atualmente propostos nos RNF para validação empírica. Essa aceitação não valida os RNF por testes, não demonstra que resultados foram atingidos e não aprova a baseline. Cenário, dados, dependências, ambiente e método de medição continuam pendentes. Prioridades P1/P2/P3 seguem a escala de prioridade de feature registrada, não a priorização de MVP.

### Segurança

#### RNF001 — Controle de acesso e autorização por perfil

- **Descrição:** O acesso a funções e dados deve respeitar as permissões aprovadas para Solicitante, Responsável e Administrador.
- **Perfil responsável:** Sistema (aplicar as permissões); Solicitante, Responsável e Administrador (perfis afetados). Pessoa/perfil responsável por validar a matriz de permissões e os resultados: a confirmar.
- **Rastreabilidade:** RF001, RF002, RF004, RF010, RF012.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** 100% dos casos da matriz de permissões aprovada devem permitir ou negar o acesso conforme esperado; alvo aceito pelo Product Manager para validação empírica. A matriz e seu contexto de aplicação permanecem pendentes; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Para cada combinação de perfil e função/dado na matriz aprovada, o acesso é permitido ou negado conforme esperado. (2) Comparar os resultados com o alvo aceito de 100% dos casos da matriz produzindo o resultado esperado. (3) Registrar os resultados; a aprovação da matriz permanece pendente e não há evidência de atingimento.

#### RNF002 — Proteção de credenciais e comunicação

- **Descrição:** Credenciais não devem ser armazenadas em texto simples e a comunicação que as transporta deve estar protegida, sem prescrever tecnologia.
- **Perfil responsável:** Sistema (proteger credenciais armazenadas e em trânsito); Solicitante, Responsável e Administrador (perfis cujas credenciais podem ser tratadas). Pessoa/perfil responsável por validar armazenamento, comunicação e operação: a confirmar.
- **Rastreabilidade:** RF001.
- **Prioridade:** P1 — proposta para validação, por risco de exposição de credenciais.
- **Alvo:** Nenhuma credencial armazenada em texto simples; verificação de proteção em todos os fluxos de comunicação de credenciais. O critério é proposto para validação.
- **Critérios de aceitação / verificação:** (1) A revisão do armazenamento não identifica credenciais em texto simples. (2) Todos os fluxos identificados de comunicação de credenciais apresentam proteção verificável no ambiente de validação. (3) O resultado da revisão de armazenamento e de cada fluxo é registrado; tecnologia e método específicos permanecem sem prescrição.

#### RNF003 — Rejeição de operações não autorizadas

- **Descrição:** Operações não autorizadas devem ser rejeitadas sem executar a ação solicitada nem expor dados protegidos.
- **Perfil responsável:** Sistema (rejeitar operações e proteger dados); Solicitante, Responsável e Administrador (perfis que podem originar operações). Pessoa/perfil responsável por validar os cenários e resultados: a confirmar.
- **Rastreabilidade:** RF001 e RF010.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** 100% dos cenários não autorizados definidos na matriz aprovada devem ser rejeitados; alvo aceito pelo Product Manager para validação empírica. A matriz e os cenários permanecem pendentes; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Cada cenário não autorizado da matriz aprovada é rejeitado. (2) 100% desses cenários não alteram o estado solicitado nem expõem dados protegidos. (3) O resultado de cada caso negativo é registrado para comparação com a matriz.

### Eficiência de desempenho

#### RNF004 — Tempo de resposta de consultas

- **Descrição:** Consultas de disponibilidade e de dados/indicadores cobertos pelo escopo devem responder dentro da meta validada.
- **Perfil responsável:** Sistema (responder às consultas); Solicitante, Responsável e Administrador (perfis consumidores, conforme autorização). Pessoa/perfil responsável por definir o ensaio, medir e validar os resultados: a confirmar.
- **Rastreabilidade:** RF002, RF003, RF010 e RF012.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** p95 ≤ 2 s; alvo aceito pelo Product Manager para validação empírica. Cenário, volume de dados, dependências, ambiente e método de medição precisam ser confirmados; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Medir o tempo entre requisição e resposta em carga representativa aprovada, documentando conjunto de dados, dependências e ambiente. (2) Comparar o percentil 95 medido ao alvo aceito de ≤ 2 s. (3) Registrar resultado e condições do ensaio; ambiente e método de medição permanecem pendentes e não há evidência de atingimento.

#### RNF005 — Processamento de reservas

- **Descrição:** O processamento de uma tentativa de reserva, incluindo o resultado de disponibilidade/conflito, deve responder dentro da meta validada.
- **Perfil responsável:** Solicitante, Responsável e Administrador (podem criar reservas); Sistema (processar a tentativa e apresentar o resultado). Pessoa responsável por definir o ensaio, medir e validar resultados: a confirmar.
- **Rastreabilidade:** RF004, RF005, RF006 e RF007.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** p95 ≤ 3 s; alvo aceito pelo Product Manager para validação empírica. Cenário, carga, dependências, ambiente e método de medição precisam ser confirmados; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Medir tentativas representativas originadas pelos três perfis, incluindo resultados com conflito e aprovação pendente, no ambiente e carga definidos para validação. (2) Comparar o percentil 95 medido ao alvo aceito de ≤ 3 s. (3) Registrar condições e resultados do ensaio; cenário, carga e método de medição permanecem pendentes e não há evidência de atingimento.

#### RNF006 — Acessos simultâneos

- **Descrição:** O serviço deve manter respostas e consistência verificáveis sob acessos simultâneos no cenário de validação.
- **Perfil responsável:** Sistema (processar acessos simultâneos e preservar consistência); Solicitante, Responsável e Administrador (podem originar tentativas de reserva). Pessoa responsável por definir, executar e validar o ensaio: a confirmar.
- **Rastreabilidade:** RF003, RF005 e RF006.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** Ensaio com 50 usuários simultâneos; alvo aceito pelo Product Manager para validação empírica, não evidência de capacidade testada ou atingida. Duração, perfil de carga e dados devem ser confirmados.
- **Critérios de aceitação / verificação:** (1) Executar ensaio com 50 usuários simultâneos, duração, perfil de carga e dados definidos para validação. (2) Registrar tempos de resposta, erros e resultados das reservas observados durante o ensaio. (3) Verificar duplicatas confirmadas nos cenários de conflito conforme RNF007. (4) Comparar os resultados ao alvo aceito; carga e método permanecem pendentes e não há evidência de atingimento.

### Confiabilidade

#### RNF007 — Integridade e prevenção de duplicatas

- **Descrição:** Resultados de reserva devem permanecer consistentes e não confirmar duplicatas para intervalos conflitantes do mesmo recurso, inclusive sob solicitações simultâneas.
- **Perfil responsável:** Sistema (preservar consistência e impedir confirmações duplicadas); Solicitante, Responsável e Administrador (podem originar reservas). Pessoa responsável por definir limites dos intervalos e validar os ensaios: a confirmar.
- **Rastreabilidade:** RF005 e RF006.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** Zero duplicatas confirmadas nos cenários de conflito definidos; alvo aceito pelo Product Manager para validação empírica. Cenários e limites de intervalos ainda precisam ser definidos; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Repetir ensaios simultâneos com dados e limites de intervalo aprovados. (2) O número de duplicatas confirmadas para o mesmo recurso e intervalo conflitante é zero. (3) Conferir reservas confirmadas e registros das tentativas; limites e cenários dependem de validação.

#### RNF008 — Disponibilidade

- **Descrição:** A aplicação deve estar disponível conforme meta acordada durante o período de operação definido.
- **Perfil responsável:** Sistema (manter e permitir observar a disponibilidade); Solicitante, Responsável e Administrador (perfis beneficiados pela disponibilidade). Pessoa/perfil responsável pela operação, monitoramento e validação da disponibilidade: a confirmar.
- **Rastreabilidade:** RF001 a RF014, conforme escopo de serviço validado.
- **Prioridade:** P2 — proposta para validação.
- **Alvo:** Disponibilidade mensal ≥ 99,5%; alvo aceito pelo Product Manager para validação empírica. Janela de serviço, exclusões, dependências, fórmula e método de cálculo precisam ser confirmados; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Registrar períodos disponíveis e indisponíveis durante a janela de serviço aprovada. (2) Calcular a disponibilidade mensal conforme fórmula e regras de contabilização acordadas. (3) Comparar o resultado ao alvo aceito de ≥ 99,5%; registrar também eventos excluídos e sua justificativa aprovada. Janela e método permanecem pendentes e não há evidência de atingimento.

#### RNF009 — Recuperação de falhas

- **Descrição:** A recuperação após falha deve preservar a consistência dos registros de reserva e históricos, respeitando objetivos de recuperação acordados.
- **Perfil responsável:** Sistema (recuperar o serviço e os registros conforme os objetivos aprovados); Solicitante, Responsável e Administrador (perfis beneficiados pela recuperação). Pessoa/perfil responsável pela operação de recuperação e validação dos resultados: a confirmar.
- **Rastreabilidade:** RF004, RF006, RF010 e RF011.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** RTO ≤ 4 h e RPO ≤ 15 min; alvos aceitos pelo Product Manager para validação empírica, não resultados demonstrados nem aprovação final da baseline. Falhas cobertas, dependências e método de cálculo devem ser confirmados; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Simular cada cenário de falha aprovado e medir o tempo de recuperação e o ponto de recuperação dos dados. (2) Comparar os resultados aos alvos aceitos de RTO ≤ 4 h e RPO ≤ 15 min. (3) Após a recuperação, verificar a consistência dos registros de reserva e históricos. (4) Registrar cenários, medidas e resultados; falhas cobertas e método dependem de validação empírica, sem evidência atual de atingimento.

### Capacidade de interação / Usabilidade

#### RNF010 — Conclusão dos fluxos principais

- **Descrição:** Usuários representativos devem conseguir concluir os fluxos principais de consulta e reserva sem ajuda, conforme tarefas e perfis definidos.
- **Perfil responsável:** Solicitante (perfil usuário principal dos fluxos de consulta e reserva); Responsável (quando os fluxos incluírem aprovação); Sistema (disponibilizar os fluxos). Pessoa/perfil responsável por definir e conduzir a validação com usuários: a confirmar.
- **Rastreabilidade:** RF003, RF004, RF007 e RF013.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** Pelo menos 80% dos participantes de teste concluem o fluxo principal sem ajuda; alvo aceito pelo Product Manager para validação empírica. Participantes, tarefas e tamanho da amostra devem ser confirmados; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Aplicar tarefas e critérios de conclusão previamente definidos a participantes representativos dos perfis incluídos. (2) Registrar, por participante, conclusão ou não do fluxo sem ajuda e dificuldades observadas. (3) Comparar o resultado ao alvo aceito de pelo menos 80% de conclusão sem ajuda; tarefas, participantes e amostra dependem de validação e não há evidência de atingimento.

#### RNF011 — Clareza de mensagens e navegação

- **Descrição:** Mensagens de erro e estados devem ser compreensíveis, e a navegação deve permitir localizar e acompanhar disponibilidade, reservas e status.
- **Perfil responsável:** Solicitante, Responsável e Administrador (perfis usuários a considerar na validação); Sistema (apresentar mensagens, estados e navegação). Pessoa/perfil responsável por definir tarefas e validar a compreensão: a confirmar.
- **Rastreabilidade:** RF003, RF004, RF005, RF007, RF009, RF011 e RF013.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** Pelo menos 80% de identificação correta do status/tela solicitada; alvo quantitativo aceito pelo Product Manager para validação empírica. A ausência de erro crítico é critério qualitativo, cuja definição permanece pendente. Tarefas, participantes e amostra também precisam ser confirmados; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Em tarefas definidas, registrar se participantes interpretam corretamente mensagens e identificam o status/tela solicitada. (2) Avaliar erros críticos conforme critério de criticidade ainda a definir. (3) Comparar a identificação correta do status/tela ao alvo aceito de pelo menos 80%. (4) Tarefas, amostra e perfis participantes dependem de validação empírica; não há evidência de atingimento.

### Manutenibilidade

#### RNF012 — Rastreabilidade e evolução da documentação

- **Descrição:** Requisitos, regras e documentação dos fluxos/API devem ser organizados de modo que mudanças, correções e seus impactos possam ser localizados e atualizados sem inconsistência documental.
- **Perfil responsável:** Pessoa/perfil responsável por manter requisitos, regras e documentação: a confirmar. Solicitante, Responsável e Administrador (perfis potencialmente usuários da documentação, conforme conteúdo e acesso a confirmar).
- **Rastreabilidade:** RF010 e RF014; aplicável ao conjunto de RF/RNF.
- **Prioridade:** P2 — proposta para validação.
- **Alvo:** 100% das alterações incluídas em uma amostra de revisão devem apontar os requisitos/fluxos afetados e atualizar a documentação correspondente; alvo aceito pelo Product Manager para validação empírica. Definição da amostra e método permanecem pendentes; não há evidência de atingimento.
- **Critérios de aceitação / verificação:** (1) Revisar amostra acordada de mudanças/correções e identificar, para cada item, requisitos e fluxos afetados. (2) 100% dos itens da amostra têm referências correspondentes atualizadas na documentação, sem inconsistências entre requisitos, regras e fluxos/API cobertos. (3) Registrar amostra e resultados; processo de mudança e responsável pela manutenção permanecem a confirmar.

### Compatibilidade

#### RNF013 — Navegadores e adaptação de tela

- **Descrição:** A interface deve funcionar em navegadores modernos acordados e se adaptar a desktop, tablet e celular sem perda dos fluxos incluídos no escopo.
- **Perfil responsável:** Sistema (apresentar a interface e permitir os fluxos nos ambientes suportados); Solicitante, Responsável e Administrador (perfis usuários beneficiados). Pessoa/perfil responsável por validar a matriz de suporte e os resultados: a confirmar.
- **Rastreabilidade:** RF013.
- **Prioridade:** P1 — proposta para validação.
- **Alvo:** Cobrir as duas versões estáveis mais recentes dos navegadores selecionados; alvo aceito pelo Product Manager para validação empírica. A seleção de navegadores, dispositivos, sistemas operacionais e critérios de suporte permanece pendente; não há evidência de teste ou atingimento.
- **Critérios de aceitação / verificação:** (1) Executar os fluxos principais em cada navegador, dispositivo e sistema operacional da matriz aprovada, incluindo as duas versões estáveis mais recentes dos navegadores selecionados. (2) Os fluxos são concluídos e os estados são apresentados em cada combinação testada. (3) Não há conteúdo ou controles inacessíveis devido a quebra de layout. (4) Matriz e critérios de suporte permanecem sujeitos a validação.

### Revisão de testabilidade dos RNF

Esta revisão incorpora o parecer de QA sobre testabilidade; não cria RNF, não altera os requisitos nem seus alvos quantitativos e não representa execução ou resultado de teste. Os alvos quantitativos foram aceitos por Renato para validação empírica, sem evidência de atingimento. “Preparação de teste pendente” indica cenário, dados, ambiente ou protocolo a preparar; “critério de aprovação parcial por definir” indica que o requisito não tem ainda um limiar/regra suficiente para concluir aprovação naquele aspecto.

| ID | Estado de testabilidade | Lacuna/ação de testabilidade |
|---|---|---|
| RNF001 | Verificável em princípio | Preparação de teste pendente: aprovar a matriz de permissões e definir cenários, dados e ambiente de validação. |
| RNF002 | Parcialmente verificável | Preparação de teste pendente: identificar fluxos de comunicação de credenciais. Critério de aprovação parcial por definir: escopo do transporte e critério verificável para “comunicação protegida”. |
| RNF003 | Verificável em princípio | Preparação de teste pendente: definir matriz de casos não autorizados, dados e ambiente de verificação. |
| RNF004 | Verificável em princípio | Preparação de teste pendente: definir consultas, carga representativa, dados, dependências, ambiente e método de medição do p95 aceito. |
| RNF005 | Verificável em princípio | Preparação de teste pendente: definir cenários de reserva, carga, dados, dependências, ambiente e método de medição do p95 aceito. |
| RNF006 | Parcialmente verificável | O ensaio com 50 usuários simultâneos está definido. Preparação de teste pendente: duração, perfil de carga, dados e ambiente. Critério de aprovação parcial por definir: limite aceitável de tempo de resposta e de erro sob 50 usuários simultâneos. |
| RNF007 | Verificável em princípio | Preparação de teste pendente: definir cenários reproduzíveis de conflito, dados, limites de intervalo e ambiente. |
| RNF008 | Parcialmente verificável | O alvo de disponibilidade mensal ≥ 99,5% está definido. Critério de aprovação parcial por definir: fórmula de disponibilidade, janela de serviço e exclusões. |
| RNF009 | Verificável em princípio | Preparação de teste pendente: definir falhas cobertas, dependências, dados e método para medir RTO/RPO e verificar consistência após recuperação. |
| RNF010 | Verificável em princípio | Preparação de teste pendente: definir usuários representativos, tarefas, amostra e protocolo para medir conclusão sem ajuda. |
| RNF011 | Parcialmente verificável | O alvo de 80% de identificação correta de status/tela está definido. Critério de aprovação parcial por definir: definição de erro crítico e protocolo de compreensão, incluindo tarefas e como registrar interpretação. |
| RNF012 | Verificável em princípio | Preparação de teste pendente: definir amostra de mudanças, critérios de rastreabilidade/documentação e procedimento de revisão. |
| RNF013 | Verificável em princípio | Preparação de teste pendente: aprovar matriz de navegadores, versões, dispositivos e sistemas operacionais e definir fluxos a executar. |

### Pendências de validação dos RNF

- Confirmar cenário operacional, volume e perfil de dados, dependências, ambiente e método de medição de cada alvo quantitativo aceito.
- Validar empiricamente os alvos aceitos de tempos p95, 50 usuários simultâneos, disponibilidade mensal, RTO/RPO e percentuais de testes de usabilidade; conforme os resultados, propor ajustes, se necessário.
- Definir janela de serviço e cálculo de disponibilidade; falhas e dependências cobertas por recuperação.
- Definir matriz de autorização, critérios de segurança, participantes/tarefas de usabilidade e matriz de navegadores/dispositivos.
- Confirmar o processo e a amostra de mudanças usados para verificar manutenibilidade e rastreabilidade.
- Confirmar quem valida as metas e os resultados dos RNF e quem responde pela manutenção, monitoramento ou operação aplicável; os perfis/pessoas responsáveis ainda não foram definidos.

## 10. Regras de negócio

As regras RN001–RN012 preservam propostas anteriormente registradas; seu estado específico é indicado individualmente e não se presume decisão onde ela não foi fornecida. RN013–RN019 registram decisões explícitas fornecidas por Renato dos Santos, Product Manager, em 2026-11-10, com pendências residuais identificadas. Renato aceita formalmente manter as regras e detalhes residuais acompanhados como pendências nesta etapa. Esse aceite não transforma propostas em regras aprovadas, não fecha o conteúdo residual e não aprova a baseline; o PRD permanece Rascunho / bloqueado para baseline.

**Responsabilidade e revisão:** Renato é o owner das decisões restantes, com especialistas operacionais a designar. A data de reavaliação dessas pendências continua pendente. O aceite é somente para acompanhamento: não aprova as regras, não fecha o conteúdo residual e não constitui sign-off da baseline. As decisões já tomadas permanecem como registradas e não são reabertas; o acompanhamento se limita às pendências.

### Regras recebidas do responsável

#### RN001 — Exclusividade de reserva de sala

- **Definição:** Uma sala não pode possuir duas reservas confirmadas com horários sobrepostos.
- **Estado:** Regra anteriormente proposta; aprovação final do PRD e validação como baseline pendentes.
- **Requisitos relacionados:** RF004, RF005 e RF006.

#### RN002 — Exclusividade de alocação de professor

- **Definição:** Um professor não pode estar alocado em duas atividades simultâneas.
- **Estado:** Regra anteriormente proposta; aprovação final do PRD e validação como baseline pendentes.
- **Requisitos relacionados:** RF004, RF005 e RF006.

#### RN003 — Disponibilidade de materiais por quantidade

- **Definição:** Um material/equipamento não pode ser reservado por dois solicitantes no mesmo período, considerando sua quantidade disponível.
- **Estado:** Regra anteriormente proposta; disponibilidade por tipo/quantidade e limites de intervalo permanecem pendentes; aprovação final do PRD pendente.
- **Requisitos relacionados:** RF003, RF004, RF005 e RF006.

#### RN004 — Reserva conjunta de recursos

- **Definição:** Uma reserva poderá envolver simultaneamente uma sala, um professor e vários materiais.
- **Estado:** Regra anteriormente proposta; disponibilidade conjunta e confirmação parcial devem seguir RN014; aprovação final do PRD pendente.
- **Requisitos relacionados:** RF004.

#### RN005 — Disponibilidade conjunta

- **Definição:** A disponibilidade deverá considerar todos os recursos solicitados.
- **Estado:** Regra anteriormente proposta; detalhes de disponibilidade por recurso permanecem pendentes; aprovação final do PRD pendente.
- **Requisitos relacionados:** RF003, RF004 e RF005.

#### RN006 — Indisponibilidade por manutenção ou bloqueio

- **Definição:** Recursos em manutenção ou bloqueados não poderão ser reservados.
- **Estado:** Regra anteriormente proposta; o Product Manager confirmou o calendário de operação em RN013. Tratamento de manutenção que afete reservas futuras está em RN017. Aprovação final do PRD pendente.
- **Requisitos relacionados:** RF003, RF004 e RF008.

#### RN007 — Aprovação de recursos restritos

- **Definição:** Recursos classificados como restritos dependerão de aprovação.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10: reservas especiais de recursos restritos precisam de aprovação de Responsável ou Administrador. Categorias, classificação e limiar estão detalhados em RN018. Aprovação final do PRD pendente.
- **Requisitos relacionados:** RF004 e RF007.

#### RN008 — Histórico de reservas canceladas

- **Definição:** Reservas canceladas deverão permanecer no histórico.
- **Estado:** Proposta anterior; não foi confirmada na resposta do Product Manager. Aprovação final do PRD pendente.
- **Requisitos relacionados:** RF004 e RF010.

#### RN009 — Revalidação de reservas alteradas

- **Definição:** Alterações de reservas deverão passar novamente pelas validações necessárias.
- **Estado:** Proposta anterior; revalidação após alteração não foi definida pelo Product Manager e permanece pendente; aprovação final do PRD pendente.
- **Requisitos relacionados:** RF004, RF005, RF007 e RF008.

#### RN010 — Intervalo de utilização para conflitos

- **Definição:** O sistema deverá considerar horários inicial e final para identificar sobreposições.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10: horários inicial e final são considerados; inclusividade/exclusividade e adjacência permanecem pendentes, conforme RN013. Aprovação final do PRD pendente.
- **Requisitos relacionados:** RF004 e RF005.

#### RN011 — Respeito à quantidade disponível de equipamentos

- **Definição:** A quantidade de equipamentos disponíveis deverá ser respeitada.
- **Estado:** Disponibilidade por tipo e quantidade não foi definida na resposta do Product Manager; regra permanece pendente. Aprovação final do PRD pendente.
- **Requisitos relacionados:** RF003, RF004, RF005 e RF006.

#### RN012 — Retirada e devolução vinculadas à reserva

- **Definição:** Retirada e devolução deverão estar vinculadas a uma reserva válida.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10: retirada/devolução somente para reserva confirmada e aprovada; detalhes constam em RN019. Aprovação final do PRD pendente.
- **Requisitos relacionados:** RF004 e RF009.

### Decisões fornecidas pelo Product Manager e pendências residuais

#### RN013 — Calendário e limites de intervalo

- **Definição:** Calendário de operação de segunda a sexta-feira, das 08:00 às 23:00, no fuso GMT−3. A regra usa horários inicial e final para tratar disponibilidade/conflitos.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10; inclusividade/exclusividade dos limites e tratamento de intervalos adjacentes permanecem pendentes. Aprovação final do PRD pendente; baseline bloqueada.
- **Requisitos relacionados:** RF004 e RF005.
- **Pergunta/decisão aberta:** Os limites dos intervalos são inclusivos ou exclusivos? Intervalos adjacentes conflitam?

#### RN014 — Confirmação parcial de recursos

- **Definição:** O Product Manager autorizou confirmar uma reserva parcial quando parte dos recursos solicitados não estiver disponível.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10; apresentação da disponibilidade parcial, consentimento/confirmação do solicitante e disponibilidade por tipo/quantidade não foram definidos. Aprovação final do PRD pendente; baseline bloqueada.
- **Requisitos relacionados:** RF004, RF005 e RF006.
- **Pergunta/decisão aberta:** Como apresentar recursos disponíveis/não atendidos e se/como solicitar confirmação do solicitante? Qual disponibilidade de cada tipo/quantidade deve ser considerada?

#### RN015 — Bloqueio e expiração durante aprovação pendente

- **Definição:** Uma solicitação pendente de aprovação bloqueia o recurso e a quantidade solicitada por até 24 horas. Se não for aprovada nesse prazo, expira.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10; estado/registro de expiração e momento exato de liberação do recurso e quantidade permanecem pendentes. Aprovação final do PRD pendente; baseline bloqueada.
- **Requisitos relacionados:** RF003, RF004 e RF007.
- **Pergunta/decisão aberta:** Como registrar a expiração e em que momento exato liberar recurso e quantidade após expiração ou reprovação?

#### RN016 — Liberação após cancelamento

- **Definição:** O cancelamento de uma reserva libera o recurso.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10; detalhes do registro histórico e do momento/liberação de recursos e quantidades continuam sujeitos a definição. Aprovação final do PRD pendente; baseline bloqueada.
- **Requisitos relacionados:** RF003, RF004, RF005 e RF010.
- **Pergunta/decisão aberta:** Como a liberação se aplica a materiais/equipamentos e quantidades? Como conciliar liberação e histórico de auditoria?

#### RN017 — Manutenção que afeta reservas futuras

- **Definição:** Se manutenção afetar uma reserva futura, redirecionar a reserva para outra sala disponível e informar o solicitante.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10; contingência quando não existir sala alternativa, eventual confirmação pelo solicitante e regras para professor/materiais permanecem pendentes. Aprovação final do PRD pendente; baseline bloqueada.
- **Requisitos relacionados:** RF004, RF008 e RF010.
- **Pergunta/decisão aberta:** O que ocorre se não houver sala disponível? A confirmação do solicitante é necessária? Como tratar professor e materiais vinculados?

#### RN018 — Classificação e aprovação de recursos restritos

- **Definição:** Equipamentos de alto custo e auditórios são recursos restritos. O Administrador classifica os recursos; Responsável (incluindo diretores neste papel) e Administrador aprovam reservas especiais.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10; limiar objetivo para “alto custo” permanece pendente. Aprovação final do PRD pendente; baseline bloqueada.
- **Requisitos relacionados:** RF002, RF007 e RF010.
- **Pergunta/decisão aberta:** Qual é o critério objetivo para classificar equipamento como de alto custo e como alterações de classificação afetam solicitações/reservas existentes?

#### RN019 — Elegibilidade para retirada e devolução

- **Definição:** Retirada e devolução só podem ocorrer para reserva confirmada e aprovada.
- **Estado:** Decisão fornecida pelo Product Manager em 2026-11-10; período/janela, atraso e devolução parcial permanecem pendentes. Aprovação final do PRD pendente; baseline bloqueada.
- **Requisitos relacionados:** RF004, RF007, RF009 e RF010.
- **Pergunta/decisão aberta:** Qual janela permite movimentação? Como tratar atraso e devolução parcial?

### Pendências de elicitação das regras de negócio

- Renato decidirá o conteúdo das regras ainda em aberto e as propostas anteriores ainda não confirmadas, com especialistas operacionais a designar; intervalos inclusivos/exclusivos e adjacência permanecem abertos.
- Resolver as pendências residuais descritas em RN013–RN019. O aceite formal de acompanhá-las nesta etapa não as fecha nem aprova regras ou baseline; a data de reavaliação continua pendente.

## 11. Histórias de usuário

HU001–HU014 estão em rascunho para validação, não são baseline nem stories prontas para implementação. O [catálogo de histórias v1.0](stories/catalogo-historias-usuario.md) é a fonte dos perfis detalhados, descrições, relações e critérios de aceitação (AC); a tabela abaixo resume os perfis e fatias de MVP sem contradizer esse catálogo. Prioridade de feature permanece distinta da fatia de MVP.

| HU | Título | Perfil proposto | RF principal | Prioridade proposta | Fatia de MVP |
|---|---|---|---|---|---|
| HU001 | Acessar a aplicação com segurança | Solicitante, Responsável e Administrador | RF001 | Alta | Núcleo obrigatório |
| HU002 | Gerenciar recursos institucionais | Administrador gerencia; os três perfis consultam disponibilidade | RF002 | Alta | Núcleo obrigatório |
| HU003 | Pesquisar recursos disponíveis | Solicitante, Responsável e Administrador | RF003 | Alta | Núcleo obrigatório |
| HU004 | Solicitar e acompanhar reservas | Os três perfis podem criar, alterar e cancelar as próprias reservas; Responsável e Administrador consultam todos os agendamentos | RF004 | Alta | Núcleo obrigatório |
| HU005 | Impedir conflitos de recursos | Solicitante, Responsável e Administrador iniciam reservas | RF005 | Alta | Núcleo obrigatório |
| HU006 | Evitar dupla reserva simultânea | Solicitante, Responsável e Administrador iniciam reservas | RF006 | Alta | Núcleo obrigatório |
| HU007 | Avaliar solicitações de recursos restritos | Responsável e Administrador | RF007 | Alta | Pós-MVP/a priorizar |
| HU008 | Registrar bloqueios e manutenção | Administrador | RF008 | Alta | Núcleo obrigatório |
| HU009 | Registrar movimentação e ocorrências de materiais | Responsável e Administrador | RF009 | Média | Pós-MVP/a priorizar |
| HU010 | Consultar histórico e auditoria | Responsável e Administrador | RF010 | Alta | Núcleo obrigatório |
| HU011 | Receber notificações de eventos | Destinatário pendente | RF011 | Média | Pós-MVP/a priorizar |
| HU012 | Consultar relatórios e indicadores | Responsável e Administrador | RF012 | Média | Pós-MVP/a priorizar |
| HU013 | Usar interface responsiva e compreensível | Solicitante, Responsável e Administrador | RF013 | Alta | Núcleo obrigatório |
| HU014 | Disponibilizar documentação dos fluxos e contratos | Audiência e responsável pela documentação pendentes | RF014 | Média | Núcleo obrigatório |

## 12. Critérios de aceitação

A convenção `HUxxx-CAyy` identifica o critério `yy`, com dois dígitos, dentro da HU `HUxxx`. AC, campos, cobertura, relações e prioridades no [catálogo v1.0](stories/catalogo-historias-usuario.md) são a referência canônica; não se duplica conteúdo. A [matriz da seção 17](#17-matriz-de-rastreabilidade) conserva as ligações e faixas.

| HU | Faixa de critérios existente |
|---|---|
| HU001 | 01–04 |
| HU002 | 01–04 |
| HU003 | 01–06 |
| HU004 | 01–10 |
| HU005 | 01–05 |
| HU006 | 01–05 |
| HU007 | 01–06 |
| HU008 | 01–03 |
| HU009 | 01–05 |
| HU010 | 01–05 |
| HU011 | 01–06 |
| HU012 | 01–03 |
| HU013 | 01–06 |
| HU014 | 01–05 |

## 13. Requisitos de qualidade — ISO/IEC 25010

Esta seção relaciona os requisitos atuais às oito características de qualidade solicitadas, usando os nomes fornecidos. O PRD não seleciona uma edição ou modelo da ISO/IEC 25010: a edição/modelo aplicável precisa ser confirmada, especialmente o enquadramento de “Flexibilidade”. Este mapeamento orienta validação e coleta de evidências; não declara conformidade, certificação, resultados atingidos nem aprovação final do PRD. RF, RN e prioridades permanecem no estado registrado nas seções 8–10.

Em todos os casos, Renato dos Santos, Product Manager, aceitou os valores-alvo quantitativos atualmente propostos nos RNF como critérios-alvo para validação empírica. Não foram testados e não há evidência de atingimento. Indicadores qualitativos acrescentados aqui permanecem exploratórios e sem alvo aprovado.

### 13.1 Adequação funcional

- **Descrição:** Avaliar se as funções e regras especificadas cobrem e produzem corretamente os resultados esperados nos fluxos validados, sem inferir comportamento ainda pendente.
- **Importância para o projeto:** A proposta de produto depende de consultar e alocar recursos, evitar conflitos e acompanhar reservas; lacunas ou resultados incorretos podem frustrar esses objetivos. A importância é provisória.
- **Requisitos relacionados:** RF001–RF014; RN001–RN019 conforme pertinência; RNF001–RNF013 quando verificam o resultado funcional. HU001–HU014 constam como histórias em rascunho para validação no [catálogo](stories/catalogo-historias-usuario.md), sem aprovação de baseline. A matriz inicial de relações e sua manutenção estão na seção 17.
- **Indicadores e critério:** Cobertura rastreável de requisito → critério de aceitação (AC) → caso de verificação, e completude/correção dos fluxos e regras aprovados. Cobertura de 100% após baseline aprovada é apenas candidata, ainda não compromisso. Não se considera falha uma questão cujo comportamento permaneça explicitamente pendente.
- **Evidências objetivas:** Matriz de rastreabilidade aprovada; casos e resultados de verificação por fluxo/regra; defeitos, exceções e requisitos sem caso associados; registro de decisões pendentes e de como foram excluídas do julgamento.

### 13.2 Eficiência de desempenho

- **Descrição:** Avaliar tempos de resposta e comportamento sob carga nos fluxos de consulta, reserva e acesso simultâneo.
- **Importância para o projeto:** A demora pode dificultar a consulta de disponibilidade e a conclusão de uma reserva, sobretudo em disputa por recurso. Prioridade e perfil de carga ainda precisam de validação.
- **Requisitos relacionados:** RF003–RF006; RNF004–RNF006.
- **Indicadores e critério:** RNF004 tem alvo aceito pelo Product Manager de p95 de consultas ≤ 2 s; RNF005, p95 de reservas ≤ 3 s; RNF006, ensaio com 50 usuários simultâneos. Esses valores são critérios-alvo para validação empírica, não resultados. Registrar também taxas de erro e resultados funcionais. Cenários, dados, dependências, ambiente e método permanecem pendentes.
- **Evidências objetivas:** Relatório de carga com condições, perfil e volume de dados, ambiente e dependências; p95 observado por tipo de operação; erros, tempos e resultados de reservas; comparação explícita aos alvos aceitos. Não há evidência de testes ou de atingimento.

### 13.3 Compatibilidade

- **Descrição:** Avaliar se a interface e os fluxos definidos funcionam em combinações selecionadas de navegador, dispositivo e ambiente.
- **Importância para o projeto:** Os perfis propostos podem acessar o produto em contextos distintos; a cobertura necessária não foi confirmada.
- **Requisitos relacionados:** RF013; RNF013.
- **Indicadores e critério:** Conclusão dos fluxos e apresentação de estados em desktop, tablet e celular, nas combinações da matriz a aprovar. O alvo aceito pelo Product Manager para validação empírica é cobrir as duas versões estáveis mais recentes dos navegadores selecionados; a seleção de navegadores e a matriz concreta ainda estão pendentes. Não há evidência de teste ou atingimento.
- **Evidências objetivas:** Matriz aprovada de navegadores/dispositivos/sistemas operacionais; resultados dos fluxos por combinação; capturas de tela e registro de problemas de layout ou controles inacessíveis.

### 13.4 Usabilidade

- **Descrição:** Avaliar a capacidade de usuários representativos de concluir tarefas, entender mensagens e identificar estados de consulta/reserva.
- **Importância para o projeto:** Fluxos de pesquisa, reserva e aprovação dependem de interpretação correta de disponibilidade e status. Participantes, tarefas e critérios críticos permanecem por definir.
- **Requisitos relacionados:** RF003, RF004, RF007 e RF013; RNF010 e RNF011.
- **Indicadores e critério:** RNF010 tem alvo aceito pelo Product Manager de 80% de conclusão sem ajuda; RNF011, 80% de identificação correta de status/tela. São critérios-alvo para validação empírica, não resultados. Ausência de erro crítico de compreensão é critério qualitativo cuja definição permanece pendente. Indicadores adicionais sem alvo: tarefas concluídas, erros, pedidos de ajuda, interpretação de mensagens e observações dos participantes.
- **Evidências objetivas:** Plano e protocolo de teste com participantes e tarefas definidos; taxas por tarefa e perfil; erros, pedidos de ajuda e observações registradas; critérios de criticidade acordados e comparação transparente aos alvos aceitos. A aceitação pelo Product Manager não é resultado de teste.

### 13.5 Confiabilidade

- **Descrição:** Avaliar consistência de reservas e histórico, continuidade do serviço e recuperação, incluindo cenários de concorrência e indisponibilidade.
- **Importância para o projeto:** Duplicidade, perda de registros ou indisponibilidade podem afetar a alocação dos recursos e a confiança no estado apresentado. A importância e as janelas operacionais precisam de validação.
- **Requisitos relacionados:** RF004–RF010; RN001–RN017 conforme pertinência; RNF007–RNF009.
- **Indicadores e critério:** Zero duplicatas confirmadas nos cenários de conflito (RNF007); disponibilidade mensal ≥ 99,5% (RNF008); RTO ≤ 4 h e RPO ≤ 15 min (RNF009). São alvos aceitos pelo Product Manager para validação empírica, sem evidência de teste ou atingimento. Os limites de intervalo, política de aprovação pendente, janela de serviço e falhas cobertas ainda dependem de definição.
- **Evidências objetivas:** Relatórios reproduzíveis de concorrência e consistência; registros de tentativas e reservas confirmadas; medição de disponibilidade com método/janela aprovados; relatório de recuperação e verificação de reservas e histórico recuperados.

### 13.6 Segurança

- **Descrição:** Avaliar autenticação, autorização, proteção de credenciais e rejeição de operações não autorizadas, conforme matriz validada.
- **Importância para o projeto:** O produto proposto distingue perfis e trata reservas e histórico; acesso indevido pode expor dados ou permitir ações impróprias. As permissões confirmadas constam na seção 6; detalhes da matriz de funções/dados e obrigações aplicáveis permanecem pendentes.
- **Requisitos relacionados:** RF001, RF007, RF010 e RF014; RNF001–RNF003; RN018 se a autoridade de classificação de recursos restritos for pertinente.
- **Indicadores e critério:** 100% dos casos da matriz de acesso e dos cenários não autorizados devem produzir o resultado esperado, conforme RNF001/RNF003; esse alvo quantitativo foi aceito pelo Product Manager para validação empírica, sem evidência de teste ou atingimento. A ausência de credenciais em texto simples e de exposição de dados protegidos são critérios qualitativos a verificar; seu escopo e método, assim como a matriz, permanecem pendentes. A matriz deve respeitar as permissões confirmadas na seção 6.
- **Evidências objetivas:** Matriz de acesso aprovada; resultados de testes de autorização e casos negativos; revisão registrada de armazenamento/comunicação de credenciais e exposição de dados; lista de achados e resolução, sem declarar certificação.

### 13.7 Manutenibilidade

- **Descrição:** Avaliar se alterações de requisitos, regras e fluxos podem ser localizadas e refletidas em documentação consistente.
- **Importância para o projeto:** Regras e responsabilidades ainda estão sendo elicitadas; a capacidade de manter coerência pode reduzir ambiguidades futuras. Processo e responsáveis não estão definidos.
- **Requisitos relacionados:** RF010 e RF014; RNF012.
- **Indicadores e critério:** RNF012 tem alvo aceito pelo Product Manager de que 100% da amostra de mudanças esteja vinculada aos requisitos/fluxos afetados e à documentação atualizada, para validação empírica. A amostra e o método permanecem pendentes; não há evidência de teste ou atingimento. Indicadores qualitativos sem alvo: lacunas de rastreabilidade, inconsistências encontradas e clareza do impacto documentado.
- **Evidências objetivas:** Amostra de mudanças definida; revisão registrada com requisito/fluxo impactado, documentação correspondente, inconsistências e conclusão por item. A amostra e o critério de suficiência precisam ser aprovados.

### 13.8 Flexibilidade

- **Descrição:** Explorar a capacidade de acomodar mudanças validadas em dados de recursos e critérios de pesquisa/classificação, sem presumir arquitetura ou requisito novo.
- **Importância para o projeto:** A proposta inclui gestão de recursos e filtros, enquanto atributos, vocabulários e critérios operacionais ainda podem mudar. A relevância precisa ser confirmada pelo responsável.
- **Requisitos relacionados:** Não há RNF explícito atual para Flexibilidade. RF002, RF003, RF008 e RF014 podem ser avaliados quanto à evolução; RN018 pode ser relevante para mudança de classificação de recursos restritos. Isso não aprova nem cria requisito.
- **Indicadores e critério:** Indicador exploratório: em cenário de mudança validada, registrar impacto (requisitos, fluxos e documentação afetados), esforço observado, regressões e lacunas. A meta é pendente; não se propõe percentual nem limite de esforço.
- **Evidências objetivas:** Cenário de mudança escolhido pelo responsável; análise registrada dos impactos e esforço observado; resultados de regressão e inconsistências documentais; pergunta e decisão futura do responsável sobre pertinência e eventual requisito/meta.

### Perguntas pendentes de qualidade

- Qual edição/modelo da ISO/IEC 25010 é aplicável e como “Flexibilidade” deve ser enquadrada?
- Quais cenários, ambientes, amostras e evidências são suficientes para validar empiricamente os alvos aceitos pelo Product Manager?
- Quais cenários, ambientes, amostras e evidências são suficientes para validar empiricamente os alvos aceitos pelo Product Manager?
Estrutura proposta: Utility → característica de qualidade → cenário. Os cenários abaixo são hipóteses para orientar validação, não requisitos de baseline aprovados. Em cada cenário, importância e dificuldade são **estimativas iniciais para discussão com responsável e arquitetos**; os níveis baixa/média/alta são relativos e não estimam prazo ou custo real. Os alvos quantitativos dos RNF foram aceitos pelo Product Manager para validação empírica, não são resultados demonstrados e não têm evidência de atingimento; quando não há alvo quantitativo, isso é indicado.
- Quais prioridades, estimativas Utility e decisões sobre Flexibilidade devem ser confirmadas pelo responsável e pelos arquitetos?

## 14. Cenários de qualidade

Os cenários CQ consolidam os estímulos que dão base à preparação ATAM (seção 15) e à Utility Tree (seção 16). São hipóteses, não requisitos aprovados; CQ não conflita com IDs de requisitos.

| ID | Cenário | Requisitos principais |
|---|---|---|
| CQ001 | Avaliador percorre fluxos/regras aprovados, verificando resultado e rastreabilidade requisito–AC–caso. | RF001–RF014; RN001–RN019; RNF001–RNF013 |
| CQ002 | Consultas e reservas, inclusive conflitos, são executadas sob carga; medem-se latência, erros e resultado funcional. | RF003–RF006, RF012; RNF004–RNF006 |
| CQ003 | Usuário conclui fluxos em desktop/tablet/celular e navegadores aprovados com controles acessíveis. | RF013; RNF013 |
| CQ004 | Participantes representativos pesquisam, reservam e interpretam status sem instrução passo a passo. | RF003, RF004, RF007, RF013; RNF010–RNF011 |
| CQ005 | Após reservas, cancelamento/manutenção e falha controlada, comparam-se disponibilidade, registros e histórico. | RF004–RF010; RNF007–RNF009 |
| CQ006 | Casos autorizados/não autorizados são testados conforme matriz; verificam-se rejeição, estado e exposição. | RF001, RF007, RF010, RF014; RNF001–RNF003 |
| CQ007 | Mudança validada em regra/fluxo é rastreada até requisitos/documentação e inconsistências. | RF010, RF014; RNF012 |
| CQ008 | Impacto, esforço e regressões de mudança validada em atributo, filtro ou classificação restrita são analisados. | RF002, RF003, RF008, RF014; RN018; sem RNF explícito para Flexibilidade |
| CQ009 | Duas tentativas simultâneas para o mesmo projetor/material e intervalo têm quantidade, resultados e histórico observáveis. | RF003–RF006; RN001, RN003, RN010–RN017 conforme decisão; RNF006–RNF007 |

Nos cenários que usam valores quantitativos dos RNF, esses valores são alvos aceitos pelo Product Manager para validação empírica, não evidência de teste ou atingimento. Seleção de navegadores, critérios de acessibilidade e definições de cenário/carga continuam pendentes.

As nove estruturas detalhadas, com estímulo, origem, ambiente, resposta, medida, requisitos, importância e dificuldade, permanecem na seção 16.

## 15. Preparação para avaliação ATAM

Esta seção prepara uma possível avaliação futura com o método ATAM; não realiza uma avaliação ATAM, não identifica decisões existentes e não seleciona arquitetura, tecnologia ou mitigação. O escopo futuro deve ser confirmado após validação do problema, do sistema que será avaliado e das partes interessadas. As prioridades abaixo são provisórias, derivadas do contexto e dos requisitos candidatos, e não equivalem a aprovação de prioridade de produto.

### 15.1 Objetivo, escopo e atributos priorizados

Objetivo futuro: examinar como cenários de qualidade relevantes podem interagir com decisões arquiteturais que venham a ser documentadas, identificando riscos, pontos sensíveis e trade-offs para decisão dos responsáveis. O escopo deverá especificar sistema, limites, stakeholders, requisitos aprovados, documentação arquitetural disponível e critérios de sucesso antes da sessão.

Conjunto inicial de atributos a priorizar para discussão: **segurança, confiabilidade, eficiência de desempenho, adequação funcional e usabilidade**; **compatibilidade, manutenibilidade e Flexibilidade** permanecem relevantes e devem ser consideradas na priorização. Esta ordenação é provisória; não escolhe solução nem estabelece compromisso de qualidade.

### 15.2 Cenários de qualidade a levar à avaliação

Os cenários CQ002–CQ009 da seção 14 compõem a entrada preliminar para a avaliação; usar as nove estruturas completas da seção 16 para estímulos, ambiente, resposta e medidas. Reserva pendente, atomicidade e limites de intervalo continuam sujeitos às decisões RN013–RN017; nenhuma política é antecipada.

### 15.3 Riscos hipotéticos e pontos sensíveis

Os itens abaixo são perguntas de avaliação, não afirmações de que riscos existam na arquitetura. O estado atual não documenta arquitetura que permita confirmar ou descartar essas condições. A evidência indicada deve ser produzida na avaliação futura.

| Condição de risco hipotética | Efeito possível | Requisitos envolvidos | Pergunta ou evidência para avaliação |
|---|---|---|---|
| Verificação de conflito e confirmação concorrente podem observar estados diferentes. | Duas tentativas podem parecer elegíveis, com duplicidade ou divergência de disponibilidade. | RF003–RF006; RN001–RN005, RN010–RN011; RNF006–RNF007. | Como o cenário concorrente é representado nas decisões documentadas? Executar ou analisar um cenário reproduzível e inspecionar resultados e registros. |
| Disponibilidade de material pode depender da quantidade cadastrada, emprestada ou simultaneamente solicitada. | Excesso ou subutilização de unidades e resultados incorretos de busca/reserva. | RF002–RF006; RN003, RN011; RNF007. | Quais estados/quantidades entram no cálculo aprovado? Evidenciar dados do cenário e reconciliação entre quantidade disponível e alocada. |
| Permissões por perfil, escopo de responsável ou acúmulo de perfis podem ser ambíguos. | Acesso indevido ou bloqueio de operação legítima; exposição de dados. | RF001, RF002, RF004, RF007, RF010, RF012; RNF001–RNF003. | Existe matriz aprovada? Comparar decisões e resultados de casos permitidos/não permitidos, inclusive perfil acumulado se validado. |
| Relatórios podem competir por recursos com consultas de disponibilidade ou reservas. | Aumento de latência, erros ou degradação de fluxos prioritários. | RF003–RF006, RF012; RNF004–RNF006. | Sob perfil de carga aprovado com relatórios, quais p95, erros e resultados funcionais são observados? |
| Transições de aprovação, cancelamento e manutenção podem alterar disponibilidade em momentos distintos. | Indisponibilidade incorreta, recurso liberado cedo/tarde ou conflito em reserva existente. | RF004, RF007–RF008; RN007, RN009, RN015–RN017. | Quais transições e políticas foram decididas? Mapear estados antes/depois e verificar disponibilidade e histórico em cada cenário. |
| Recuperação ou retomada após falha pode restaurar serviço e registros em pontos diferentes. | Reserva, auditoria, notificação ou estado de disponibilidade inconsistente após retomada. | RF004, RF006, RF010–RF011; RNF008–RNF009. | Quais falhas e dependências estão no escopo? Registrar ponto/tempo de recuperação e comparar dados recuperados com operações confirmadas. |
| Notificações podem usar mecanismo opcional simulado ou integração externa. | Atraso, indisponibilidade de dependência ou divergência entre evento e mensagem. | RF007, RF009, RF011; RNF009. | Qual alternativa e garantias são aprovadas? Evidenciar comportamento do evento quando o mecanismo/dependência não está disponível, se aplicável. |
| Catálogo, atributos de recursos, critérios de busca ou regras de classificação podem evoluir. | Mudanças podem afetar filtros, documentação, permissões e reservas existentes. | RF002–RF003, RF008, RF014; RN018; RNF012. | Qual cenário de mudança validada será usado? Registrar elementos afetados, esforço observado e regressões, sem presumir facilidade ou mecanismo. |
| Volume ou sensibilidade de auditoria pode crescer ou incluir dados de acesso restrito. | Consultas mais lentas, retenção inadequada ou exposição de informação. | RF001, RF010, RF012, RF014; RNF001–RNF004, RNF012. | Qual volume, retenção, sensibilidade e matriz de acesso foram aprovados? Evidenciar revisão de acesso, consulta e desempenho em cenário acordado. |

### 15.4 Trade-offs para discussão

| Conflito | Lados positivos e negativos a avaliar | Perguntas para a avaliação |
|---|---|---|
| Segurança vs. desempenho | Controles e verificações mais abrangentes podem reduzir exposição e ações não autorizadas; podem também acrescentar trabalho e latência aos fluxos. Simplificações podem reduzir custo/tempo de operação, mas ampliar risco de acesso indevido. | Que verificações ocorrem nos fluxos críticos? Qual latência e quais resultados de segurança foram medidos por cenário? Que dados podem ser expostos se uma verificação falhar ou for omitida? |
| Consistência vs. disponibilidade | Preservar estado coerente de reserva/histórico pode restringir operações durante falha ou incerteza; manter operações disponíveis pode permitir resultados temporariamente divergentes. | Qual consistência é necessária em reserva, disponibilidade, auditoria e recuperação? Que comportamento é aceitável durante falha e como é verificado após retomada? |
| Concorrência vs. integridade | Atender tentativas concorrentes pode aumentar vazão e reduzir espera; disputa por recurso e quantidade aumenta risco de confirmação duplicada ou estado inconsistente se não controlada. | Quais limites de concorrência e intervalos serão validados? Como demonstrar resultado, quantidade e histórico em tentativas simultâneas sem antecipar decisão de implementação? |
| Flexibilidade vs. complexidade de manutenção | Acomodar novos atributos, filtros e regras pode facilitar evolução validada; generalização excessiva pode aumentar a complexidade de compreensão, documentação e teste. | Quais mudanças são plausíveis e validadas? Qual impacto, esforço observado, regressões e custo de manutenção aparecem em cenários concretos? A pertinência de Flexibilidade será confirmada? |

Nenhuma mitigação ou lado é recomendado nesta versão. Perguntas, condições de risco e trade-offs deverão ser reavaliados com arquitetura e requisitos aprovados disponíveis.

## 16. Utility Tree

Estrutura proposta: Utility → característica de qualidade → cenário. Os cenários abaixo são hipóteses para orientar validação, não requisitos de baseline aprovados. Em cada cenário, importância e dificuldade são **estimativas iniciais para discussão com responsável e arquitetos**; os níveis baixa/média/alta são relativos e não estimam prazo ou custo real. Os alvos quantitativos dos RNF foram aceitos pelo Product Manager para validação empírica, não são resultados demonstrados e não têm evidência de atingimento; quando não há alvo quantitativo, isso é indicado.

### CQ001 — Adequação funcional

**Cenário:** Um avaliador percorre os fluxos e regras aprovados e verifica sua rastreabilidade.

- **Estímulo:** Executar um conjunto aprovado de tarefas e casos de regra, incluindo resultado esperado e exceções decididas.
- **Origem do estímulo:** Responsável de produto, usuários representativos ou equipe de validação, conforme validação a definir.
- **Ambiente:** Versão e dados de teste identificados, matriz de requisitos aprovada e casos de verificação controlados.
- **Resposta esperada:** Cada caso executado produz resultado verificável conforme requisito/regra aprovada; pendências são identificadas, sem presumir comportamento.
- **Medida de resposta:** Cobertura requirement→AC→caso; resultados corretos, falhas e itens sem cobertura. Cobertura de 100% pós-baseline é candidata, não compromisso.
- **Requisitos/RFs/RNF/RNs relacionados:** RF001–RF014; RN001–RN019 conforme pertinência; RNF001–RNF013; HU001–HU014 onde aplicável em artefatos de validação.
- **Importância:** Alta, estimativa inicial: os fluxos compõem a proposta central, ainda não validada.
- **Dificuldade de implementação:** Média, estimativa inicial: depende de fluxos e regras aprovados; não é prazo/custo real.

### CQ002 — Eficiência de desempenho

**Cenário:** Durante consultas e reservas sob carga representativa, usuários recebem respostas mensuráveis.

- **Estímulo:** Executar pesquisas de disponibilidade e tentativas de reserva, incluindo resultados conflitantes, sob carga definida.
- **Origem do estímulo:** Usuários e gerador de carga de validação.
- **Ambiente:** Dados, dependências, perfil de carga, duração e ambiente de ensaio a aprovar; alvo aceito de 50 usuários simultâneos para validação empírica.
- **Resposta esperada:** Operações retornam resultado observável e as medições registram latência, erros e resultado funcional, sem presumir mecanismo técnico.
- **Medida de resposta:** p95 de consultas e reservas e taxas de erro; p95 ≤ 2 s, p95 ≤ 3 s e ensaio com 50 usuários são alvos RNF004–RNF006 aceitos pelo Product Manager para validação empírica. Cenário, carga e ambiente ainda estão pendentes; não há evidência de teste ou atingimento.
- **Requisitos/RFs/RNF/RNs relacionados:** RF003–RF006; RNF004–RNF006; RN001–RN011 conforme cenário.
- **Importância:** Alta, estimativa inicial: consulta/reserva são fluxos centrais propostos.
- **Dificuldade de implementação:** Alta, estimativa inicial: carga, dados e concorrência exigem cenário controlado; não é prazo/custo real.

### CQ003 — Compatibilidade

**Cenário:** Usuário executa fluxos selecionados em desktop, tablet e celular, nos navegadores aprovados.

- **Estímulo:** Abrir a interface e concluir tarefas principais em cada combinação da matriz.
- **Origem do estímulo:** Solicitante, Responsável e Administrador; combinações finais a confirmar.
- **Ambiente:** Matriz de dispositivos, navegadores, versões e sistemas operacionais ainda a aprovar; cobrir as duas versões estáveis mais recentes dos navegadores selecionados é alvo aceito pelo Product Manager para validação empírica.
- **Resposta esperada:** Fluxos são concluídos, estados e controles permanecem acessíveis e não há perda por quebra de layout.
- **Medida de resposta:** Matriz executada, conclusão por combinação, falhas e capturas de tela; o alvo de duas versões estáveis mais recentes foi aceito pelo Product Manager para validação empírica, enquanto a matriz detalhada permanece pendente.
- **Requisitos/RFs/RNF/RNs relacionados:** RF013; RNF013.
- **Importância:** Média, estimativa inicial: a necessidade de combinações ainda não foi confirmada com usuários.
- **Dificuldade de implementação:** Média, estimativa inicial: a quantidade de combinações e fluxos depende da matriz aprovada; não é prazo/custo real.

### CQ004 — Usabilidade

**Cenário:** Participantes representativos pesquisam disponibilidade, solicitam reserva e interpretam seu estado.

- **Estímulo:** Realizar tarefas previamente definidas sem instrução passo a passo.
- **Origem do estímulo:** Participantes representativos dos perfis e pessoas responsáveis pela avaliação, ainda a selecionar.
- **Ambiente:** Protótipo ou versão de teste, tarefas e critérios de sucesso/criticidade definidos antes da sessão.
- **Resposta esperada:** Participantes concluem tarefas e interpretam mensagens/estados; dificuldades e erros são observados e registrados.
- **Medida de resposta:** Taxa de conclusão sem ajuda, acerto de identificação de status/tela, erros e observações. Os alvos aceitos pelo Product Manager são 80% em RNF010/RNF011 para validação empírica; tarefas, amostra e critérios qualitativos permanecem pendentes, sem evidência de teste ou atingimento.
- **Requisitos/RFs/RNF/RNs relacionados:** RF003, RF004, RF007, RF013; RNF010–RNF011; RN007, RN015 conforme fluxo decidido.
- **Importância:** Alta, estimativa inicial: tarefas de consulta/reserva são centrais e envolvem mais de um perfil proposto.
- **Dificuldade de implementação:** Média, estimativa inicial: depende de recrutamento, tarefas e critérios validados; não é prazo/custo real.

### CQ005 — Confiabilidade

**Cenário:** Após solicitações e uma falha controlada, reservas, histórico e disponibilidade são verificados.

- **Estímulo:** Executar operações de reserva, cancelamento ou manutenção e aplicar cenário de falha/recuperação aprovado.
- **Origem do estímulo:** Usuário de teste e avaliador da recuperação.
- **Ambiente:** Ambiente controlado com dados registrados antes/depois e falha coberta pelo plano aprovado.
- **Resposta esperada:** Resultados de reserva e histórico permanecem verificáveis; após recuperação, registros e disponibilidade são comparados aos dados esperados. Política de reserva pendente não é inferida.
- **Medida de resposta:** Duplicatas em cenários aprovados, consistência observada, disponibilidade e RTO/RPO. Zero duplicatas, ≥99,5%, RTO≤4h e RPO≤15min são alvos RNF007–RNF009 aceitos pelo Product Manager para validação empírica. Cenários, janela e falhas cobertas permanecem pendentes; não há evidência de teste ou atingimento.
- **Requisitos/RFs/RNF/RNs relacionados:** RF004–RF010; RN001–RN017 conforme pertinência; RNF007–RNF009.
- **Importância:** Alta, estimativa inicial: estado confiável de reservas é central à finalidade proposta.
- **Dificuldade de implementação:** Alta, estimativa inicial: falhas, janelas e políticas operacionais ainda precisam de definição; não é prazo/custo real.

### CQ006 — Segurança

**Cenário:** Um usuário tenta executar ações não autorizadas e consultar dados fora de sua permissão aprovada.

- **Estímulo:** Executar casos positivos e negativos definidos pela matriz de autorização, inclusive acesso a aprovação, auditoria e classificação restrita quando aplicável.
- **Origem do estímulo:** Avaliador usando perfis e operações de teste.
- **Ambiente:** Matriz de perfis/funções aprovada e dados não produtivos; operações e dados protegidos identificados.
- **Resposta esperada:** Ações autorizadas seguem o esperado; ações não autorizadas são rejeitadas sem mudança de estado ou exposição de dados. Credenciais não aparecem em texto simples.
- **Medida de resposta:** Casos da matriz com resultado esperado (100% é alvo quantitativo aceito pelo Product Manager para validação empírica), rejeições, mudanças indevidas, exposição observada e revisão de credenciais (RNF001–RNF003). Matriz e método permanecem pendentes; não há evidência de teste ou atingimento.
- **Requisitos/RFs/RNF/RNs relacionados:** RF001, RF007, RF010, RF014; RNF001–RNF003; RN018 se pertinente.
- **Importância:** Alta, estimativa inicial: há perfis e ações distintas; as permissões confirmadas estão na seção 6, enquanto detalhes adicionais continuam pendentes.
- **Dificuldade de implementação:** Alta, estimativa inicial: a matriz e o escopo de dados ainda precisam de aprovação; não é prazo/custo real.

### CQ007 — Manutenibilidade

**Cenário:** Uma mudança validada em regra ou fluxo é rastreada até requisitos e documentação afetados.

- **Estímulo:** Selecionar mudança de amostra e solicitar avaliação de impacto e atualização dos artefatos correspondentes.
- **Origem do estímulo:** Responsável pela mudança e pessoa responsável pela documentação, ainda a designar.
- **Ambiente:** Requisitos, regras, fluxos e documentação versionados e disponíveis para a amostra aprovada.
- **Resposta esperada:** Requisitos/fluxos afetados e documentação correspondente são localizados; inconsistências e itens sem vínculo ficam registrados.
- **Medida de resposta:** Percentual da amostra rastreada e atualizada; 100% é alvo RNF012 aceito pelo Product Manager para validação empírica, além de contagem qualitativa de inconsistências. Amostra e método permanecem pendentes; não há evidência de teste ou atingimento.
- **Requisitos/RFs/RNF/RNs relacionados:** RF010, RF014; RNF012; conjunto de RF/RN aplicável à mudança.
- **Importância:** Média, estimativa inicial: há regras e manutenção documental em definição, mas processo e responsáveis não definidos.
- **Dificuldade de implementação:** Média, estimativa inicial: depende de amostra e artefatos disponíveis; não é prazo/custo real.

### CQ008 — Flexibilidade

**Cenário:** Uma mudança validada em atributo de recurso, critério de busca ou classificação restrita é analisada quanto a impacto e regressão.

- **Estímulo:** Apresentar mudança selecionada pelo responsável, sem pressupor que ela será implementada ou que represente requisito aprovado.
- **Origem do estímulo:** Responsável de produto ou operação.
- **Ambiente:** Artefatos de requisitos, fluxos e documentação disponíveis; eventual avaliação em versão de teste somente se autorizada.
- **Resposta esperada:** O impacto, fluxos afetados, esforço observado e regressões são registrados e uma pergunta de decisão é encaminhada ao responsável.
- **Medida de resposta:** Indicador exploratório qualitativo: impacto (requisitos/fluxos/documentação), esforço e regressões observadas. Meta pendente; sem percentual ou limite proposto.
- **Requisitos/RFs/RNF/RNs relacionados:** Sem RNF explícito; RF002, RF003, RF008 e RF014; RN018 se relevante.
- **Importância:** Média, estimativa inicial: cadastro e filtros podem evoluir, mas essa necessidade ainda não foi validada.
- **Dificuldade de implementação:** Média, estimativa inicial: depende de mudança concreta e critério acordado; não é prazo/custo real.

### CQ009 — Cenário transversal de concorrência

**Cenário:** Dois solicitantes tentam reservar ao mesmo tempo o mesmo projetor/material e intervalo.

- **Estímulo:** Disparar duas tentativas concorrentes para o mesmo recurso e período, registrando a quantidade disponível e os resultados.
- **Origem do estímulo:** Dois solicitantes de teste ou dois clientes de ensaio sob controle do avaliador.
- **Ambiente:** Dados de recurso/quantidade e limites de intervalo documentados; ambiente de teste com resultados e histórico observáveis.
- **Resposta esperada:** O sistema apresenta o resultado observável de cada tentativa e não confirma mais alocações conflitantes do que RN003/RN011 e as regras aprovadas permitem. RF006 e RN001/RN003 são testáveis como propostas, mas reservas pendentes, atomicidade e intervalos adjacentes continuam sujeitos a decisão em RN013–RN017; o cenário não decide essas políticas.
- **Medida de resposta:** Número de confirmações conflitantes/duplicadas, resultado de cada tentativa, quantidade remanescente e registros correspondentes; zero duplicatas é o alvo RNF007 aceito pelo Product Manager para validação empírica, sujeito às regras e intervalos definidos, sem evidência de teste ou atingimento.
- **Medida de resposta:** Número de confirmações conflitantes/duplicadas, resultado de cada tentativa, quantidade remanescente e registros correspondentes; zero duplicatas é o alvo RNF007 aceito pelo Product Manager para validação empírica, sujeito às regras e intervalos definidos, sem evidência de teste ou atingimento.
- **Requisitos/RFs/RNF/RNs relacionados:** RF003–RF006; RN001, RN003, RN010–RN011, RN013–RN017 conforme decisões; RNF006–RNF007.
- **Importância:** Alta, estimativa inicial: concorrência e quantidade são explicitamente contempladas nas propostas de requisitos.
- **Dificuldade de implementação:** Alta, estimativa inicial: depende de condições reproduzíveis e decisões pendentes sobre intervalos e estados; não é prazo/custo real.

### Decisões pendentes da Utility Tree

- Confirmar quais cenários representam necessidades reais e quais devem ser removidos ou reformulados.
- Definir estímulo, origem, ambiente, resposta e medidas, incluindo evidências para validar empiricamente os alvos aceitos pelo Product Manager e critérios qualitativos sem alvo.
- Definir estímulo, origem, ambiente, resposta e medidas, incluindo evidências para validar empiricamente os alvos aceitos pelo Product Manager e critérios qualitativos sem alvo.
- Confirmar prioridades e pontuações de importância/dificuldade com responsável e arquitetos; estimativas atuais não são prazo/custo.
- Decidir a pertinência de Flexibilidade, seu enquadramento no modelo de qualidade aplicável e se será necessário requisito explícito.
- Resolver as decisões de regra necessárias para ensaios de concorrência, reserva pendente, atomicidade e limites de intervalo antes de tratá-los como critérios aprovados.

## 17. Matriz de rastreabilidade

Esta estrutura documenta relações propostas entre os identificadores canônicos já usados neste PRD e no catálogo. Os IDs RF001–RF014, RNF001–RNF013, RN001–RN019 e HU001–HU014 não devem ser reutilizados para outro item; correções de título ou texto preservam o identificador, salvo decisão de versionamento registrada. A convenção `HUxxx-CAyy` identifica o critério `yy` numerado dentro da HU `HUxxx` em [docs/stories/catalogo-historias-usuario.md](stories/catalogo-historias-usuario.md). O hífen e o número com dois dígitos são notação da matriz: não alteram nem renumeram os critérios existentes no catálogo.

A matriz abaixo é inicial e não constitui baseline aprovada; evidências ainda não foram coletadas. As decisões explícitas do Product Manager estão registradas nas seções correspondentes. Renato dos Santos é a autoridade final de aprovação; seu sign-off explícito do PRD v1.2 e a declaração do estado da baseline continuam pendentes. Uma relação só é indicada quando sustentada pela rastreabilidade declarada no requisito/regra ou pelo vínculo explícito da HU; relações de regras propostas ou condicionais estão marcadas como tal. `NI` significa “não identificado nesta matriz”, não ausência definitiva de relação.

| RF | HU e critérios de aceitação | RN relacionadas | RNF relacionadas | Qualidades | Evidências EVD planejadas |
|---|---|---|---|---|---|
| RF001 | HU001-CA01–04 | NI | RNF001–003; RNF008*; RNF012† | AF, SG | EVD001, EVD002, EVD008, EVD014 |
| RF002 | HU002-CA01–04 | RN006**, RN018** | RNF001, RNF004; RNF008*; RNF012† | AF, ED, SG, MT | EVD001, EVD005, EVD008, EVD010, EVD011, EVD014 |
| RF003 | HU003-CA01–06 | RN003*, RN005*, RN006*, RN010*, RN011*, RN013** | RNF004, RNF006, RNF010, RNF011; RNF008*; RNF012† | AF, ED, US, CF, CP | EVD004, EVD005, EVD006, EVD008, EVD009, EVD012, EVD013, EVD014 |
| RF004 | HU004-CA01–10 | RN004*, RN005*, RN008*, RN009*, RN013**, RN014**, RN015**, RN016**, RN017** | RNF001, RNF005, RNF009, RNF010, RNF011; RNF008*; RNF012† | AF, ED, CF, US | EVD003, EVD004, EVD005, EVD007, EVD008, EVD010, EVD014, EVD015 |
| RF005 | HU005-CA01–05 | RN001*, RN002*, RN003*, RN010*, RN011*, RN013** | RNF005–007, RNF011; RNF008*; RNF012† | AF, ED, CF | EVD004, EVD005, EVD008, EVD009, EVD010, EVD014 |
| RF006 | HU006-CA01–05 | RN001*, RN002*, RN003*, RN010*, RN011*, RN013** | RNF005–007, RNF009; RNF008*; RNF012† | AF, ED, CF | EVD004, EVD005, EVD008, EVD009, EVD010, EVD014 |
| RF007 | HU007-CA01–06 | RN007*, RN015**, RN018** | RNF005, RNF010, RNF011; RNF008*; RNF012† | AF, SG, US, CF | EVD001, EVD003, EVD007, EVD008, EVD014 |
| RF008 | HU008-CA01–03 | RN006*, RN017** | NI; RNF008*; RNF012† | AF, ED, CF | EVD001, EVD005, EVD007, EVD008, EVD010, EVD015 |
| RF009 | HU009-CA01–05 | RN012*, RN019** | RNF011; RNF008*; RNF012† | AF, CF | EVD008, EVD010, EVD014 |
| RF010 | HU010-CA01–05 | RN008*, RN016**, RN017**, RN018** | RNF001, RNF003, RNF004, RNF009; RNF008*; RNF012 | AF, SG, CF, MT | EVD001, EVD003, EVD007, EVD008, EVD011, EVD014 |
| RF011 | HU011-CA01–06 | RN015**, RN016**, RN017** | RNF009, RNF011; RNF008*; RNF012† | AF, CF | EVD008, EVD014 |
| RF012 | HU012-CA01–03 | NI | RNF001, RNF004; RNF008*; RNF012† | AF, ED, SG | EVD005, EVD006, EVD008, EVD009, EVD010, EVD014 |
| RF013 | HU013-CA01–06 | RN001*, RN002*, RN003*, RN005*, RN006*, RN007*, RN010*, RN011*, RN015**, RN018** | RNF010, RNF011, RNF013; RNF008*; RNF012† | AF, SG, US, CP | EVD001, EVD005, EVD008, EVD012, EVD013, EVD014 |
| RF014 | HU014-CA01–05 | RN001*–RN012* e RN013**–RN019** (referência documental, não relação funcional) | RNF012; RNF008* | AF, MT, FL | EVD008, EVD011, EVD014 |

**Legenda de status e qualidade:** `*` regra anteriormente recebida como proposta, ainda sujeita à aprovação final; `**` regra com detalhes/condições residuais pendentes. RN013–RN019 registram decisões fornecidas pelo Product Manager em 2026-11-10, sem aprovação final do PRD. RNF008* é transversal ao serviço e só se aplica conforme escopo operacional validado. RNF012† é transversal ao conjunto de RF/RNF para manutenção documental; a rastreabilidade explícita indicada em sua definição aponta RF010 e RF014. `AF` = adequação funcional; `ED` = eficiência de desempenho; `CP` = compatibilidade; `US` = usabilidade; `CF` = confiabilidade; `SG` = segurança; `MT` = manutenibilidade; `FL` = flexibilidade. Qualidade marcada é dimensão a avaliar, não resultado demonstrado. EVD nas linhas são referências a registros planejados definidos na seção 18. EVD015 é evidência transversal de serviço associada a todos os RF marcados com RNF008*, embora possa não se repetir em cada lista de evidências por linha.

**Regras de manutenção da matriz:** ao alterar identificador, requisito ou critério de aceitação, revisar todas as ligações afetadas; registrar versão, motivo e decisão; associar o item a um caso de verificação e à evidência correspondente; não deixar itens de baseline aprovada sem cobertura. Enquanto um item ainda não tiver evidência antes da execução, seu estado é “planejado”, nunca “comprovado”. Lacunas `NI` permanecem rastreáveis para validação e não devem ser preenchidas por conveniência.

## 18. Evidências objetivas de qualidade

Este catálogo define registros que poderão ser produzidos após validação do escopo, dos critérios e dos métodos. Todos os itens abaixo estão **Planejados — ainda não produzidos**. Funcionalidade aparentemente implementada não basta como evidência: é necessário registro reproduzível, resultado medido ou artefato verificável, com condições, dados e resultado identificados. Os alvos quantitativos da seção 9 foram aceitos pelo Product Manager para validação empírica; aceitação não significa teste realizado, resultado atingido ou baseline aprovada. Esta seção não declara conformidade ou certificação.

| ID | Evidência/registro a produzir | Requisitos, regras e qualidades que poderá comprovar | Como obter e medir/verificar | Status |
|---|---|---|---|---|
| EVD001 | Matriz de controle de acesso e resultados de testes positivos/negativos. | RF001, RF002, RF007, RF010, RF012; RNF001 e RNF003; RN018; segurança e adequação funcional. O alvo quantitativo de 100% foi aceito pelo Product Manager para validação empírica, ainda sem teste ou evidência de atingimento. | Registrar as permissões confirmadas na seção 6 e definir detalhes adicionais na matriz; executar casos autorizados e não autorizados; comparar resultado observado à expectativa e registrar mudanças de estado/exposição. | Planejada — ainda não produzida |
| EVD002 | Revisão da proteção de credenciais e comunicação. | RF001; RNF002; segurança. | Identificar fluxos de credenciais e revisar armazenamento e transporte no ambiente acordado; registrar escopo, verificações, achados e resolução. | Planejada — ainda não produzida |
| EVD003 | Amostra ou exportação verificável da trilha de auditoria conforme RF010. | RF010 e eventos de aprovação/reprovação de RF007; RN008, RN016–RN018 se aprovadas; adequação funcional, confiabilidade e manutenibilidade. | Executar operações de escopo validado; conferir ator, data/hora, operação, preservação do evento anterior e acesso autorizado; registrar amostra e critérios de seleção. | Planejada — ainda não produzida |
| EVD004 | Execução reproduzível de tentativas simultâneas e resultado de dupla reserva. | RF005–RF006; RN001–RN003, RN010–RN011 e RN013 conforme validação; RNF006–RNF007; desempenho, adequação funcional e confiabilidade. | Registrar dados, intervalos, quantidade, concorrência, sequência e resultados de cada tentativa; repetir conforme plano aprovado e contar confirmações conflitantes/duplicadas. | Planejada — ainda não produzida |
| EVD005 | Relatório de desempenho com p95 de consulta/reserva, carga, erros e condições do ensaio. | RF002–RF006, RF010 e RF012; RNF004–RNF006; eficiência de desempenho. P95 ≤ 2 s, p95 ≤ 3 s e 50 usuários são alvos aceitos pelo Product Manager para validação empírica, sem evidência de teste ou atingimento. | Definir cenário, conjunto de dados, dependências, perfil/duração de carga e ambiente; coletar latências e erros, calcular p95 e comparar separadamente com os alvos aceitos. | Planejada — ainda não produzida |
| EVD006 | Relatórios de utilização por sala/material/professor com período, filtros, origem de dados e fórmula verificados. | RF012; eficiência de desempenho e adequação funcional. | Gerar relatório para período e filtros acordados; documentar origem, fórmula e conjunto de referência; recalcular amostra e comparar valores apresentados. | Planejada — ainda não produzida |
| EVD007 | Registro de decisões de aprovação/reprovação com ator, data, status e justificativa quando reprovada. | RF007 e RF010; RN007 e RN015 quando aprovadas; adequação funcional, segurança e confiabilidade. | Executar casos de aprovação e reprovação definidos; conferir ator, data, status e justificativa; verificar bloqueio/resultado da reserva conforme política aprovada. | Planejada — ainda não produzida |
| EVD008 | Matriz e documentação de rastreabilidade versionadas, incluindo esta estrutura. | RF001–RF014, RNF001–RNF013 e RN001–RN019 conforme pertinência; adequação funcional e manutenibilidade. | Versionar alterações com motivo e decisão; conferir ligações RF–HU–CA–RN–RNF–qualidade–caso–evidência e identificar itens sem cobertura. Estado atual deste material continua inicial e não aprovado. | Planejada — ainda não produzida |
| EVD009 | Indicador de conflitos detectados/rejeitados e duplicatas evitadas, com definição de métricas e denominadores. | RF005–RF006 e RF012; RN001–RN003, RN010–RN011 conforme validação; RNF007; adequação funcional e confiabilidade. | Acordar definições, eventos incluídos, numerador, denominador e período; calcular com registros verificáveis e reconciliar amostra de ocorrências. Definições e denominadores estão pendentes. | Planejada — ainda não produzida |
| EVD010 | Evidência de integridade/conciliação de reservas, recursos, quantidades, estados e histórico, incluindo cenários de concorrência/recuperação quando aprovados. | RF002–RF010 e RF012; RN001–RN012 e RN013, RN014, RN015, RN016, RN017, RN018, RN019 conforme aplicabilidade e aprovação; RNF007 e RNF009; confiabilidade e adequação funcional. | Preparar conjunto de origem e regras de conciliação; comparar reservas, recursos, quantidades, estados e histórico antes/depois de operações acordadas; registrar divergências e cenários executados. | Planejada — ainda não produzida |
| EVD011 | Histórico versionado de alterações em requisitos, regras, HUs/ACs e decisões, com responsável e justificativa. | RF010, RF014 e conjunto de requisitos/regras alterados; RNF012; manutenibilidade e flexibilidade. | Registrar versão anterior/nova, identificadores afetados, motivo, decisão, responsável e ligações revisadas; verificar amostra de mudanças e consistência documental. | Planejada — ainda não produzida |
| EVD012 | Relatório de usabilidade com tarefas, perfis, conclusão, erros/ajuda e resultados. | RF003, RF004, RF007 e RF013; RNF010–RNF011; usabilidade. Os alvos de 80% foram aceitos pelo Product Manager para validação empírica, ainda sem teste ou evidência de atingimento. | Definir participantes, perfis, tarefas, critérios de conclusão/criticidade e protocolo; registrar conclusão, erros, ajuda e interpretação por tarefa; comparar com os alvos aceitos sem presumir atingimento. | Planejada — ainda não produzida |
| EVD013 | Relatório de compatibilidade com navegadores/dispositivos, resultados, capturas e falhas. | RF013; RNF013; compatibilidade. Alvo das duas versões estáveis mais recentes aceito pelo Product Manager para validação empírica; matriz detalhada ainda pendente. | Definir matriz de navegador, dispositivo e sistema operacional; executar fluxos selecionados em cada combinação; registrar resultado, capturas, falhas e limitações. | Planejada — ainda não produzida |
| EVD014 | Relatório de validação funcional por critérios de aceitação, com passou/falhou/não executado e defeitos. | RF001–RF014 e suas HU/CA; RN/RNF somente conforme ligações validadas na matriz; adequação funcional e qualidades correspondentes ao caso. | Associar cada caso ao ID RF/HU-CA e versão; registrar pré-condições, dados, resultado esperado/observado, status e defeitos; manter itens não executados distintos dos aprovados. | Planejada — ainda não produzida |
| EVD015 | Registro planejado para comprovar a disponibilidade do serviço para RF001–RF014, conforme escopo operacional aprovado, e a recuperação, especialmente ligada a RF004, RF006, RF010 e RF011; inclui medição da janela de serviço e RTO/RPO. | RF001–RF014 para disponibilidade, conforme escopo operacional aprovado; RF004, RF006, RF010 e RF011 para recuperação; RNF008–RNF009; confiabilidade. Disponibilidade ≥ 99,5%, RTO ≤ 4 h e RPO ≤ 15 min são alvos aceitos pelo Product Manager para validação empírica, sem evidência de teste ou atingimento. | Após definir janela, exclusões, cenários de falha e método, registrar períodos e pontos de recuperação; calcular disponibilidade, RTO/RPO observados e conferir integridade dos dados recuperados. | Planejada — ainda não produzida |

**Pendências para tornar a coleta executável:** designar quem aprova métricas, fórmulas e denominadores; definir ambiente, conjunto de dados, dependências e condições de ensaio; decidir acesso, sensibilidade e retenção dos registros; e nomear responsáveis pela coleta, revisão e validação. Nenhum dono, ferramenta, arquitetura, frequência de produção ou obrigação de retenção é definido nesta versão.

## 19. Riscos e estratégias de mitigação

Matriz inicial funcional, operacional e de qualidade. Probabilidade e impacto são **estimativas iniciais para validação**, não fatos ou classificação aprovada. Cada probabilidade é estimada por ausência de dados operacionais, sem frequência observada. Mitigações são requisitos, controles, procedimentos e evidências, sem escolha técnica; mitigação planejada não elimina risco até execução e evidência.

| ID | Categoria | Risco, causa e efeito | Probabilidade (estimativa) | Impacto (estimativa) | Mitigação planejada | Requisitos relacionados | Indicador/evidência | Owner |
|---|---|---|---|---|---|---|---|
| RISK001 | Funcional/qualidade | Reservas simultâneas conflitantes podem ser aceitas se verificação/confirmação divergir; efeito: dupla alocação e disponibilidade incorreta. | Média — estimativa inicial por ausência de dados operacionais. | Alta — estimativa inicial para validação. | Validar RN001–RN005 e limites RN010/RN013; definir cenários/critério e ensaiar. | RF003–RF006; RN001–RN005, RN010–RN011, RN013; RNF006–RNF007. | EVD004 ensaios, EVD009 indicador, EVD010 conciliação. | A definir |
| RISK002 | Funcional/operacional | Professor alocado incorretamente por identidade, disponibilidade ou vínculo ambíguo; efeito: conflito de agenda ou reserva inadequada. | Média — estimativa inicial por ausência de dados operacionais. | Alta — estimativa inicial para validação. | Validar papel duplo, competência, RN002, fluxo e autorização; comparar com dados de referência. | RF002–RF005; RN002, RN004–RN005, RN010; RNF001, RNF007. | EVD001, EVD004, EVD010, EVD014. | A definir |
| RISK003 | Operacional/funcional | Equipamento indisponível ou quantidade divergente por bloqueio/manutenção/movimentação não registrada; efeito: reserva não atendida ou excesso. | Média — estimativa inicial por ausência de dados operacionais. | Alta — estimativa inicial para validação. | Validar cadastro/quantidade e RN003/006/011/012; definir procedimento e reconciliar disponibilidade. | RF002–RF005, RF008–RF009; RN003, RN006, RN011–RN012; RNF007. | EVD004, EVD010, EVD014. | A definir |
| RISK004 | Funcional/operacional | Aprovação pode confirmar cedo, ficar sem decisão ou omitir justificativa; causa: termos/transições pendentes. | Média — estimativa inicial por ausência de dados operacionais. | Alta — estimativa inicial para validação. | Definir recurso restrito, solicitante, decisores e estados; validar RN007/RN015 e testar fluxos. | RF007, RF010–RF011; RN007, RN015, RN018; RNF001, RNF003, RNF011. | EVD001, EVD003, EVD007, EVD014. | A definir |
| RISK005 | Segurança/operacional | Alteração não autorizada em reserva, recurso, permissão ou classificação se matriz não for aprovada/aplicada; efeito: mudança indevida/exposição. | Média — estimativa inicial por ausência de dados operacionais. | Alta — estimativa inicial para validação. | Aprovar matriz perfil/função/dado e autoridade RN018; revisar operações autorizadas/não autorizadas. | RF001–RF002, RF007, RF010; RN018; RNF001–RNF003. | EVD001, EVD002, EVD003. | A definir |
| RISK006 | Qualidade/operacional | Histórico perdido/indisponível por retenção e recuperação não definidas; efeito: rastreabilidade comprometida. | Baixa — estimativa inicial por ausência de dados operacionais, não frequência observada. | Alta — estimativa inicial para validação. | Validar escopo, retenção/acesso e RN008/RN016/RN017; definir conferência/recuperação e verificar preservação. | RF010; RN008, RN016–RN018; RNF009, RNF012. | EVD003, EVD011, EVD015, EVD010. | A definir |
| RISK007 | Qualidade/funcional | Inconsistência entre reservas, recursos, quantidades, status ou histórico por regras ambíguas/operações divergentes; efeito: decisões/indicadores incorretos. | Média — estimativa inicial por ausência de dados operacionais. | Alta — estimativa inicial para validação. | Aprovar definições/estados e regras aplicáveis; definir reconciliações e cenários verificáveis. | RF002–RF012; RN001–RN019 pertinentes; RNF007, RNF009, RNF012. | EVD010, EVD004, EVD006 contra fonte, EVD014. | A definir |
| RISK008 | Operacional/qualidade | Indisponibilidade interrompe consulta/reserva; janela e dependências não levantadas; efeito: fluxos não concluídos/atrasos. | Média — estimativa inicial por ausência de dados operacionais. | Alta — estimativa inicial para validação. | Definir período, dependências, exclusões e método; validar empiricamente os alvos de RNF008/009 aceitos pelo Product Manager, sem presumir teste ou atingimento. | RF001–RF014 conforme serviço; RNF008–RNF009. | EVD015 disponibilidade/RTO/RPO e integridade; EVD005 desempenho correlato. | A definir |

Owners e estimativas devem ser revistos com dados. Nenhuma mitigação foi executada/evidenciada; revisão não equivale a aceitação do risco.

## 20. Critérios de sucesso do produto

Renato aceita a necessidade como hipótese para discovery; nenhum problema empírico foi observado ou validado, e não há metas de negócio/contexto-base informadas. O discovery do @analyst deverá identificar público/contexto com Renato, ouvir usuários representativos sobre o processo atual com exemplos, usar registros/artefatos disponíveis quando houver, documentar evidências favoráveis e contrárias e definir sinais de confirmação/refutação. Tamanho/amostra, resultados esperados e métricas continuam pendentes. Renato aceitou os alvos quantitativos dos RNF para validação empírica; não são metas de negócio, não foram testados e não há evidência de atingimento. Renato é a autoridade final de aprovação; o sign-off explícito do PRD v1.2 e a declaração do estado da baseline permanecem pendentes.

### Sucesso do produto — propostas a validar

- Requisitos baseline aprovados, claros e rastreáveis a objetivos, histórias, critérios e evidências.
- Fluxos essenciais observados e aceitos por perfis validados.
- Regras de conflito/quantidade verificadas sem duplicidade nos cenários definidos e aprovados.
- Indicadores de utilização reconciliados com dados-fonte e fórmulas acordadas.
- Evidências de qualidade pertinentes entregues e avaliadas, conforme seção 18.

### Sucesso do processo de elicitação e critérios para baseline

1. Discovery documenta a hipótese, público/contexto e evidências favoráveis e contrárias; não pressupõe que o problema esteja confirmado.
2. Objetivos/métricas têm definição, medição, linha de base quando disponível, meta/horizonte ou ficam formalmente pendentes para investigação.
3. Usuários, necessidades prioritárias e fluxos são validados por responsável competente.
4. Regras/exceções são documentadas e têm responsáveis de validação.
5. MVP, exclusões e critérios de avaliação são aprovados.
6. RF/RNF de baseline são claros, verificáveis e rastreáveis; a prioridade de MVP está registrada, e os alvos quantitativos aceitos pelo Product Manager têm contexto/método de medição definidos e evidências empíricas planejadas; incertezas permanecem pendentes.
7. Restrições, integrações, plataformas, riscos, dependências, prazo e governança estão registrados.
8. Renato registra explicitamente o sign-off do PRD v1.2 e declara o estado da baseline; pendências impeditivas são resolvidas ou aceitas formalmente com owner/data de revisão, sem presumir que o aceite para acompanhamento aprove regras ou baseline.

Até atender esses critérios, status permanece **Rascunho / bloqueado para baseline**. As decisões fornecidas pelo Product Manager não substituem a aprovação final; os alvos quantitativos foram aceitos para validação empírica, não como resultados comprovados.

## 21. Restrições e itens fora do escopo

### Pressupostos técnicos e restrições

O Product Manager informou que não há limites conhecidos de orçamento, prazo, equipe ou tecnologia. Stack, plataforma, integrações e política de operação/retenção não foram definidos. Fora do escopo desta versão: implementação/código, banco de dados, tecnologias, frameworks e arquitetura. Histórias formais são competência de @SM. O catálogo de HUs v1.0 permanece inalterado e é a fonte dos critérios detalhados; esta revisão alinha apenas o resumo de perfis e fatias de MVP na tabela da seção 11.

**Nenhum pressuposto técnico foi confirmado.** Linguagens, frameworks, arquitetura, estrutura de repositório, hospedagem, estratégia de testes, APIs, bibliotecas e destino de implantação não são definidos por este documento. A alternativa entre notificações simuladas e API externa permanece pendente (RF011); a existência de API permanece pendente (RF014).

Nenhuma obrigação legal/regulatória foi informada; não se presume ausência de obrigações. Outras restrições contratuais, organizacionais, operacionais ou de infraestrutura precisam ser levantadas antes de orientar decisões técnicas. As metas RNF não determinam arquitetura ou tecnologia.

## 22. Dúvidas e decisões pendentes

As respostas mais recentes de Renato dos Santos, autoridade final de aprovação, ficam distinguidas da seguinte forma:

- **Hipótese:** aceita para discovery e validação; não é problema observado nem evidência. O plano de discovery existente permanece.
- **Regras residuais:** aceite formal somente para acompanhamento nesta etapa, sem aprovação das regras, fechamento do conteúdo ou sign-off da baseline. Renato é owner; especialistas operacionais serão designados e a data de reavaliação está pendente. Decisões já tomadas não são reabertas.
- **RNF:** a revisão de verificabilidade está registrada na seção 9. Os alvos quantitativos aceitos por Renato continuam sendo apenas para validação empírica; nenhum teste ou atingimento foi demonstrado.
- **Sign-off e baseline:** Renato é a autoridade final. O rótulo “Registrar o sign-off:” foi apresentado sem valor e nenhum texto de aprovação foi fornecido nesta interação. O sign-off explícito e documentado do PRD v1.2 e a declaração do estado da baseline permanecem pendentes; o status segue Rascunho / bloqueado para baseline.
- **Sequência de entrega:** nenhum conteúdo de sequência foi fornecido; a decisão permanece pendente e não se presume ordem de implementação.

As demais decisões explícitas do Product Manager estão registradas nas seções correspondentes. A aceitação de valores-alvo para validação empírica não demonstra teste ou atingimento nem equivale à aprovação da baseline.

### Aprovação e validação de negócio

- **Ação pendente de Renato:** registrar o sign-off explícito e documentado do PRD v1.2 e declarar a decisão sobre o estado da baseline. O campo de sign-off veio sem valor; não há aprovação registrada. Até essas decisões, o PRD permanece Rascunho / bloqueado para baseline.
- Qual resultado de negócio e quais métricas/linha de base permitirão validar a hipótese de produto? O Product Manager informou que nenhum problema empírico foi observado até agora; não há evidência empírica fornecida.
- O discovery do @analyst deve levantar público/contexto com Renato, ouvir usuários representativos sobre o processo atual com exemplos, usar registros/artefatos disponíveis quando houver, documentar evidências favoráveis e contrárias e definir sinais de confirmação/refutação. Tamanho/amostra, métricas e resultados continuam pendentes.

### Operação e regras residuais

- Owner das decisões restantes: Renato, com especialistas operacionais a designar. A data de reavaliação das pendências residuais continua pendente.
- Os limites dos intervalos são inclusivos ou exclusivos? Intervalos adjacentes conflitam?
- Como apresentar reserva parcial, recursos não disponíveis e disponibilidade por tipo/quantidade; quando e como o solicitante confirma?
- Qual critério objetivo classifica equipamento como “alto custo”? Como registrar expiração de solicitação pendente e qual o momento exato de liberação do recurso e quantidade após 24 horas ou reprovação?
- O que ocorre se manutenção afetar reserva futura e não houver outra sala disponível? A confirmação do solicitante é necessária? Como tratar professor e materiais da reserva afetada?
- Qual janela se aplica à retirada/devolução? Como tratar movimentação fora do período, atraso e devolução parcial?
- Como professores são identificados/relacionados como solicitantes e recursos, além do número de matrícula/registro informado?

### Notificações, relatórios e API

- Notificações serão simuladas ou externas? Quais eventos, conteúdo, destinatários, canal e momento de entrega?
- Qual conteúdo, período, filtros, fórmulas e critérios de validação compõem os relatórios gerais?
- A existência de API ainda não foi definida. Caso seja definida, quem mantém sua documentação? Qual documentação dos fluxos/regras é necessária independentemente de API?

### Dados, privacidade e acessibilidade

- Qual período de retenção se aplica aos dados e à auditoria? O acesso à auditoria por Responsável e Administrador está definido; retenção permanece pendente.
- Quais obrigações legais/regulatórias se aplicam e quem as valida? Nenhuma obrigação foi informada; não se presume ausência de obrigação.
- Qual critério de acessibilidade será adotado e como será validado?

### Validação empírica e contexto operacional

- Quais cargas, volumes/perfis de dados, dependências, ambiente, janela operacional e método de medição serão usados para validar empiricamente os alvos quantitativos aceitos pelo Product Manager? Esses elementos permanecem pendentes; os valores não foram testados e não há evidência de atingimento.
- Quais tarefas, participantes e critérios de criticidade serão usados na validação de usabilidade? Qual matriz de navegador/dispositivo será coberta?
- Qual janela de serviço, exclusões e método de contabilização serão usados para disponibilidade; quais falhas/dependências serão cobertas pela recuperação?

### Sequência de entrega

- Nenhum conteúdo de sequência de entrega foi fornecido nesta interação. Defini-la permanece pendente; este PRD não presume ordem de implementação nem cria epic ou plano.

O Product Manager informou que não há limites conhecidos de orçamento, prazo, equipe ou tecnologia. Essa resposta não confirma que tais restrições não existam; apenas registra que não são conhecidas até o momento. O critério de acessibilidade não foi definido. Histórias formais são competência de @SM e serão alinhadas separadamente se necessário; esta atualização não altera o catálogo de HUs.