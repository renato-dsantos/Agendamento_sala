# Catálogo de histórias de usuário

## Metadados

| Campo | Valor |
|---|---|
| Referência-fonte | [PRD](../prd.md) |
| Versão do PRD | 1.2 |
| Status do catálogo | Rascunho para validação |
| Baseline | Bloqueada; Renato dos Santos é a autoridade/aprovador final confirmada, mas o sign-off explícito e documentado do PRD v1.2 ainda está pendente. Estas HUs continuam em rascunho e não estão prontas para implementação |

**Prioridade de feature:** Alta/Média segue a prioridade do RF relacionado no PRD; permanece distinta da fatia de MVP. As prioridades são preservadas, não aprovadas como baseline.

Renato dos Santos é o Product Manager, responsável pelo produto e autoridade/aprovador final confirmado de todas as aprovações do projeto. O sign-off explícito e documentado do PRD v1.2 ainda está pendente; por isso, o catálogo e as HUs continuam em rascunho, e a baseline permanece bloqueada. Somente as questões residuais explicitadas permanecem pendentes.

## HU001 — Acessar a aplicação com segurança

**ID e título:** HU001 — Acessar a aplicação com segurança

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Solicitante, Responsável e Administrador. Uma pessoa pode acumular perfis, com permissões cumulativas. A política de autenticação e a matriz aprovada de autorização permanecem pendentes.

**Descrição:** Como usuário de um ou mais perfis, quero autenticar-me e encerrar minha sessão, para acessar somente as funcionalidades autorizadas aos perfis que acumulo.

**Critérios de aceitação:**
1. Dado um usuário, quando apresentar credenciais aceitas, então consegue iniciar sessão.
2. Dado um usuário autenticado, quando tentar acessar uma funcionalidade não autorizada ao seu perfil, então o acesso é impedido.
3. Quando o usuário encerrar a sessão, então a sessão deixa de permitir acesso autenticado.
4. A aplicação permite verificar os perfis e permissões efetivos conforme uma matriz de autorização aprovada; a matriz continua pendente e não se presume autorização além das permissões confirmadas.

**RF relacionados:** RF001 (principal).

**RN relacionados:** Nenhuma RN direta identificada no PRD; permissões confirmadas na seção 6 do PRD e matriz de autorização pendente.

**Prioridade:** Alta — proposta para validação (RF001, P1).

## HU002 — Gerenciar recursos institucionais

**ID e título:** HU002 — Gerenciar recursos institucionais

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Administrador gerencia salas, professores, materiais e bloqueios. Solicitante, Responsável e Administrador consultam disponibilidade. Administrador classifica recursos restritos.

**Descrição:** Como Administrador, quero gerenciar salas, professores, materiais e bloqueios, para manter os recursos institucionais e sua disponibilidade registrados para consulta e reserva.

**Critérios de aceitação:**
1. O Administrador consegue gerenciar salas, professores, materiais e bloqueios; não se inferem permissões de gestão adicionais para os outros perfis.
2. Os três perfis conseguem consultar a disponibilidade de salas, professores e materiais. O cadastro de professor inclui matrícula/número de registro, dado identificado cuja finalidade e retenção permanecem pendentes.
3. Bloqueios e manutenção registrados são considerados na disponibilidade; o tratamento de reservas futuras afetadas segue HU008 e RN017.
4. O Administrador classifica como restritos equipamentos de alto custo e auditórios; o critério objetivo para “alto custo” permanece pendente.

**RF relacionados:** RF002 (principal).

**RN relacionados:** RN006 (detalhes residuais de disponibilidade); RN018 (categorias e autoridade definidas; limiar objetivo de alto custo pendente).

**Prioridade:** Alta — proposta para validação (RF002, P1).

## HU003 — Pesquisar recursos disponíveis

**ID e título:** HU003 — Pesquisar recursos disponíveis

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Solicitante, Responsável e Administrador consultam e pesquisam disponibilidade. Sistema aplica filtros e apresenta resultados.

**Descrição:** Como usuário Solicitante, Responsável ou Administrador, quero pesquisar recursos por tipo, características e disponibilidade, para identificar opções compatíveis com minha necessidade.

**Critérios de aceitação:**
1. A pesquisa aceita filtros aplicáveis por tipo de recurso, capacidade de sala, localização, competência de professor, data/horário e tipo/quantidade de materiais; vocabulários e filtros permanecem sujeitos a definição.
2. A disponibilidade consultada respeita o calendário de segunda a sexta-feira, das 08:00 às 23:00, GMT−3; inclusividade/exclusividade dos limites e intervalos adjacentes permanecem pendentes.
3. Os resultados correspondem aos filtros informados e apresentam a disponibilidade para a data e o horário consultados, sem presumir valores além dos cadastrados.
4. Disponibilidade por tipo e quantidade de materiais/equipamentos permanece pendente. Uma reserva pode ser confirmada parcialmente para os recursos disponíveis; apresentação da seleção/falhas e eventual consentimento permanecem pendentes.
5. Recursos bloqueados ou em manutenção não são apresentados como disponíveis no período correspondente.
6. A consulta considera horários inicial e final; limites e tratamento de horários adjacentes continuam pendentes conforme RN013.

**RF relacionados:** RF003 (principal).

**RN relacionados:** RN003, RN005, RN006 e RN011 (detalhes de quantidade/disponibilidade pendentes); RN010 e RN013 (calendário definido; limites e adjacência pendentes); RN014 (confirmação parcial definida; apresentação e consentimento pendentes).

**Prioridade:** Alta — proposta para validação (RF003, P1).

## HU004 — Solicitar e acompanhar reservas

**ID e título:** HU004 — Solicitar e acompanhar reservas

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Solicitante, Responsável e Administrador podem criar reservas e alterar/cancelar as próprias. Responsável e Administrador consultam todos os agendamentos. Uma pessoa que acumule perfis reúne suas permissões.

**Descrição:** Como Solicitante, Responsável ou Administrador, quero criar, consultar, alterar e cancelar minhas próprias reservas com período, recursos e horários, para acompanhar minhas solicitações e seus status.

**Critérios de aceitação:**
1. Uma reserva registra período de calendário, fuso GMT−3, horários inicial e final e recursos associados; regras de limites e intervalos adjacentes permanecem pendentes.
2. Solicitante, Responsável e Administrador podem criar reservas; Responsável e Administrador podem consultar todos os agendamentos.
3. Cada perfil pode alterar ou cancelar somente as próprias reservas; os limites operacionais adicionais permanecem pendentes.
4. A reserva pode associar recursos conjuntamente e a disponibilidade considera os recursos solicitados, conforme RN004 e RN005; disponibilidade por tipo/quantidade permanece pendente.
5. Uma reserva pode ser confirmada parcialmente com os recursos disponíveis mesmo quando outros solicitados não estão disponíveis; como apresentar a seleção/falhas e solicitar consentimento, se aplicável, permanece pendente.
6. Uma solicitação de recurso restrito pendente de aprovação bloqueia recurso e quantidade por até 24 horas e expira se não aprovada nesse prazo.
7. O estado/registro da expiração e o momento exato de liberação do recurso e da quantidade após expiração ou reprovação permanecem pendentes.
8. Cancelar uma reserva libera o recurso; a preservação do histórico segue a regra correlata, sem detalhamento adicional presumido.
9. A validade dos horários respeita o calendário de segunda a sexta-feira, das 08:00 às 23:00, GMT−3; limites e adjacência permanecem pendentes. Revalidação após alteração permanece pendente conforme RN009.
10. Se manutenção afetar reserva futura, ela é redirecionada para outra sala disponível e o solicitante é informado; ausência de sala, confirmação do solicitante e efeitos sobre professor/materiais permanecem pendentes conforme RN017.

**RF relacionados:** RF004 (principal).

**RN relacionados:** RN004, RN005, RN008 e RN009 (propostas anteriores; confirmação/histórico e revalidação ainda pendentes); RN013 (calendário definido, limites/adjacência pendentes); RN014–RN017 (decisões registradas, com pendências residuais descritas nos critérios).

**Prioridade:** Alta — proposta para validação (RF004, P1).

## HU005 — Impedir conflitos de recursos

**ID e título:** HU005 — Impedir conflitos de recursos

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Solicitante, Responsável e Administrador podem criar reservas. Sistema verifica conflitos e apresenta o resultado.

**Descrição:** Como Solicitante, Responsável ou Administrador, quero que a aplicação verifique conflitos de horário dos recursos solicitados, para não confirmar uma reserva incompatível com outra já existente.

**Critérios de aceitação:**
1. Dadas duas solicitações sobrepostas para a mesma sala, a aplicação identifica o conflito e não permite confirmar ambas.
2. A verificação considera sobreposição de sala, professor alocado e materiais/equipamentos; disponibilidade por tipo/quantidade de materiais permanece pendente.
3. O calendário de operação é de segunda a sexta-feira, das 08:00 às 23:00, GMT−3.
4. A comparação considera horários inicial e final; inclusividade/exclusividade dos limites e tratamento de horários adjacentes permanecem pendentes conforme RN013.
5. Quando houver conflito, a aplicação apresenta mensagem informando que a disponibilidade impede a confirmação; a confirmação parcial de outros recursos é possível conforme HU004/RN014.

**RF relacionados:** RF005 (principal).

**RN relacionados:** RN001, RN002, RN003 e RN011 (disponibilidade por quantidade permanece pendente); RN010 e RN013 (calendário definido; limites e adjacência pendentes); RN014 (confirmação parcial definida, apresentação/consentimento pendentes).

**Prioridade:** Alta — proposta para validação (RF005, P1).

## HU006 — Evitar dupla reserva simultânea

**ID e título:** HU006 — Evitar dupla reserva simultânea

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Solicitante, Responsável e Administrador podem criar reservas. Sistema mantém a consistência e registra os resultados.

**Descrição:** Como Solicitante, Responsável ou Administrador, quero que solicitações simultâneas pelo mesmo recurso sejam tratadas sem duplicidade, para que o resultado confirmado represente a disponibilidade real.

**Critérios de aceitação:**
1. Em um ensaio com duas solicitações simultâneas para períodos conflitantes do mesmo recurso, no máximo uma resulta em reserva confirmada.
2. Após as tentativas, os dados apresentados não indicam duas reservas confirmadas para o mesmo conflito.
3. O resultado de cada tentativa pode ser verificado por registro; não se prescreve mecanismo técnico.
4. A consistência é verificada para salas, professores e materiais/equipamentos; disponibilidade e contagem por tipo/quantidade permanecem pendentes.
5. O calendário de operação é de segunda a sexta-feira, das 08:00 às 23:00, GMT−3. A determinação de conflito usa horários inicial e final; limites e adjacência continuam pendentes conforme RN013.

**RF relacionados:** RF006 (principal).

**RN relacionados:** RN001–RN003 e RN011 (disponibilidade/quantidade pendentes); RN010 e RN013 (calendário definido; limites e adjacência pendentes); RN014–RN015 conforme impacto em reservas parciais e solicitações pendentes.

**Prioridade:** Alta — proposta para validação (RF006, P1).

## HU007 — Avaliar solicitações de recursos restritos

**ID e título:** HU007 — Avaliar solicitações de recursos restritos

**Fatia de MVP:** Pós-MVP/a priorizar.

**Perfil:** Responsável (incluindo diretores nesse perfil) e Administrador aprovam reservas especiais. Administrador classifica recursos restritos. Os três perfis podem criar reservas.

**Descrição:** Como Responsável ou Administrador, quero aprovar reservas especiais de recursos restritos, para que sua confirmação dependa da decisão autorizada.

**Critérios de aceitação:**
1. Uma reserva especial para recurso restrito não é confirmada antes de aprovação por Responsável ou Administrador.
2. Responsável ou Administrador pode aprovar a reserva especial. Ao reprovar uma solicitação, deve informar justificativa; a reprovação não é concluída sem esse preenchimento.
3. O registro permite verificar a decisão, o decisor e a data.
4. O Administrador classifica equipamentos de alto custo e auditórios como recursos restritos; critério objetivo de alto custo permanece pendente.
5. Solicitação pendente bloqueia recurso e quantidade por até 24 horas e expira se não aprovada nesse prazo.
6. Estado/registro da expiração, momento exato da liberação, definição de outras reservas especiais e demais critérios residuais permanecem pendentes.

**RF relacionados:** RF007 (principal).

**RN relacionados:** RN007 (aprovação definida); RN015 (bloqueio/expiração definidos, estado e momento exato de liberação pendentes); RN018 (categorias e autoridade definidas, limiar de alto custo pendente).

**Prioridade:** Alta — proposta para validação (RF007, P1).

## HU008 — Registrar bloqueios e manutenção

**ID e título:** HU008 — Registrar bloqueios e manutenção

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Administrador gerencia bloqueios e manutenção. Sistema considera a indisponibilidade e trata reservas futuras afetadas conforme RN017.

**Descrição:** Como Administrador, quero gerenciar bloqueios e manutenção de salas e materiais/equipamentos, para impedir solicitações durante períodos indisponíveis.

**Critérios de aceitação:**
1. O Administrador pode gerenciar bloqueios de salas e materiais/equipamentos, incluindo período, motivo e responsável pelo bloqueio.
2. Recursos bloqueados ou em manutenção não estão disponíveis para consulta/reserva durante o período correspondente.
3. Se manutenção afetar reserva futura, redirecionar para outra sala disponível e informar o solicitante; o que ocorre sem sala alternativa, a necessidade de confirmação do solicitante e os efeitos em professor/materiais permanecem pendentes.

**RF relacionados:** RF008 (principal).

**RN relacionados:** RN006; RN017 (redirecionamento e aviso definidos; contingências e efeitos residuais pendentes).

**Prioridade:** Alta — proposta para validação (RF008, P1).

## HU009 — Registrar movimentação e ocorrências de materiais

**ID e título:** HU009 — Registrar movimentação e ocorrências de materiais

**Fatia de MVP:** Pós-MVP/a priorizar.

**Perfil:** Responsável e Administrador podem registrar retirada e devolução. Elegibilidade limita-se a reserva confirmada e aprovada.

**Descrição:** Como Responsável ou Administrador, quero registrar retirada e devolução de materiais/equipamentos vinculadas a reserva confirmada e aprovada, para acompanhar as movimentações.

**Critérios de aceitação:**
1. Responsável ou Administrador pode registrar retirada e devolução vinculadas à reserva elegível.
2. Uma retirada sem devolução registrada pode ser identificada como pendência.
3. A reserva só é elegível para movimentação quando confirmada e aprovada; ocorrência de utilização e seus perfis autorizados permanecem pendentes.
4. Movimentações são vinculadas à reserva elegível; não se permite registrar retirada/devolução para reserva não confirmada ou não aprovada.
5. Período/janela de movimentação, tratamento de atraso e devolução parcial permanecem pendentes.

**RF relacionados:** RF009 (principal).

**RN relacionados:** RN012; RN019 (elegibilidade definida; janela, atraso e devolução parcial pendentes).

**Prioridade:** Média — proposta para validação (RF009, P2).

## HU010 — Consultar histórico e auditoria

**ID e título:** HU010 — Consultar histórico e auditoria

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Sistema registra e preserva eventos; Responsável e Administrador consultam auditoria. Política de retenção permanece pendente.

**Descrição:** Como Responsável ou Administrador, quero consultar auditoria das operações relevantes, para rastrear alterações e decisões relacionadas às reservas e aos recursos.

**Critérios de aceitação:**
1. Criação, alteração e cancelamento de reservas, alterações cadastrais relevantes e aprovações/reprovações geram registros que identificam usuário, data/hora e operação.
2. Responsável e Administrador conseguem consultar auditoria; retenção e detalhes dos eventos permanecem pendentes.
3. O histórico de reservas canceladas é tratado conforme RN008, sem inventar detalhamento além da regra correlata.
4. Preservar o histórico relativo à liberação após cancelamento e a reservas futuras afetadas conforme RN016/RN017; detalhes permanecem sujeitos às regras correspondentes.
5. Matrícula/número de registro do professor é dado identificado; finalidade e retenção permanecem pendentes. Não foi informada obrigação legal, sem concluir que nenhuma se aplica.

**RF relacionados:** RF010 (principal).

**RN relacionados:** RN008 (permanência de reservas canceladas ainda sujeita à validação); RN016 e RN017 (decisões registradas e pendências residuais); RN018 (classificação definida, escopo de auditoria de alterações não ampliado por inferência).

**Prioridade:** Alta — proposta para validação (RF010, P1).

## HU011 — Receber notificações de eventos

**ID e título:** HU011 — Receber notificações de eventos

**Fatia de MVP:** Pós-MVP/a priorizar.

**Perfil:** Sistema gera notificações; destinatários, canal, mecanismo, eventos e momento de entrega permanecem pendentes.

**Descrição:** Como usuário destinatário a definir, quero receber notificações sobre eventos e pendências que venham a ser incluídos no escopo, para acompanhar mudanças relevantes nas reservas.

**Critérios de aceitação:**
1. Para cada evento que venha a ser definido no escopo, é possível verificar a geração da notificação correspondente; eventos e destinatários permanecem pendentes.
2. A notificação identifica o evento e o status ou a pendência relacionada, conforme conteúdo que vier a ser definido.
3. Eventos associados a aprovação pendente, cancelamento ou manutenção futura só são incluídos conforme decisão explícita de escopo.
4. Não se presume envio ou evento para bloqueio/expiração de solicitação, liberação após cancelamento ou redirecionamento de manutenção.
5. Destinatários, preferências e momento de entrega permanecem pendentes.
6. Canal e mecanismo de notificação permanecem pendentes; não há API nem envio simulado definido.

**RF relacionados:** RF011 (principal; funcionalidade futura/depriorizada no MVP).

**RN relacionados:** RN015, RN016 e RN017 somente se eventos correspondentes forem definidos no escopo de notificações.

**Prioridade:** Média — proposta para validação (RF011, P2).

## HU012 — Consultar relatórios e indicadores

**ID e título:** HU012 — Consultar relatórios e indicadores

**Fatia de MVP:** Pós-MVP/a priorizar.

**Perfil:** Responsável e Administrador consultam relatórios gerais. Conteúdo e dados apresentados permanecem pendentes.

**Descrição:** Como Responsável ou Administrador, quero consultar relatórios gerais, para acompanhar dados operacionais dos recursos.

**Critérios de aceitação:**
1. Responsável e Administrador podem consultar relatórios gerais.
2. Conteúdo, indicadores, período, filtros, fórmulas e critérios de validação dos relatórios permanecem pendentes; não se presume detalhamento.
3. Resultados poderão ser verificados com dados de referência após definição do escopo e dos critérios dos relatórios.

**RF relacionados:** RF012 (principal).

**RN relacionados:** Nenhuma RN direta identificada no PRD.

**Prioridade:** Média — proposta para validação (RF012, P2).

## HU013 — Usar interface responsiva e compreensível

**ID e título:** HU013 — Usar interface responsiva e compreensível

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Solicitante, Responsável e Administrador. Funções são diferenciadas conforme as permissões confirmadas e cumulativas; validação de interface e acessibilidade permanece aberta.

**Descrição:** Como usuário de um ou mais perfis, quero consultar disponibilidade e identificar status e erros em uma interface adaptável, para concluir os fluxos autorizados aos perfis que acumulo.

**Critérios de aceitação:**
1. A interface se adapta a desktop, tablet e celular; metas e matriz de suporte permanecem sujeitas a validação.
2. Estados de reserva são identificáveis visualmente e mensagens de erro permitem compreender que a operação não foi concluída e qual situação ocorreu.
3. As funções apresentadas refletem as permissões confirmadas para cada perfil e sua acumulação; a matriz formal de autorização permanece pendente.
4. Disponibilidade e status exibidos refletem as regras pertinentes de sala, professor, material, bloqueio e calendário, incluindo limites/adjacência ainda pendentes.
5. Estados de aprovação pendente e recurso restrito refletem as decisões de bloqueio/expiração e classificação; estado de expiração e momento de liberação permanecem pendentes.
6. Conclusão dos fluxos, compreensão das mensagens e acessibilidade permanecem sujeitos a validação; os alvos quantitativos dos RNF foram aceitos para validação empírica, sem resultados medidos ou alegação de atingimento.

**RF relacionados:** RF013 (principal); RF001, RF003, RF004, RF005 e RF007 apenas como comportamentos apresentados na interface.

**RN relacionados:** RN001–RN007 e RN010–RN011 conforme aplicabilidade; RN013 (calendário definido, limites/adjacência pendentes); RN014–RN015 e RN018 (decisões registradas, com pendências residuais pertinentes à interface).

**Prioridade:** Alta — proposta para validação (RF013, P1).

## HU014 — Disponibilizar documentação dos fluxos e contratos

**ID e título:** HU014 — Disponibilizar documentação dos fluxos e contratos

**Fatia de MVP:** Núcleo obrigatório.

**Perfil:** Responsável pela documentação e usuários da documentação permanecem pendentes; não se atribui essa responsabilidade a um perfil sem validação.

**Descrição:** Como usuário da documentação a definir, quero consultar os fluxos principais e as regras de negócio documentados, para compreender os comportamentos aplicáveis.

**Critérios de aceitação:**
1. Fluxos principais, regras de negócio e permissões confirmadas são documentados, distinguindo decisões registradas de questões residuais pendentes.
2. A documentação de API inclui endpoints, parâmetros, respostas e códigos de erro somente se uma API vier a ser definida.
3. A existência de API e o escopo de contratos públicos permanecem pendentes; não se presume API.
4. As RN001–RN019 são documentadas conforme aplicabilidade e estado no PRD, sem apresentar propostas ou pendências como decisões aprovadas.
5. Titularidade, audiência e formato da documentação permanecem pendentes.

**RF relacionados:** RF014 (principal).

**RN relacionados:** RN001–RN019, somente para documentar as regras pertinentes e seus estados de validação, sem convertê-las em decisões aprovadas.

**Prioridade:** Média — proposta para validação (RF014, P2).

---

Este catálogo alinha-se às decisões registradas no PRD v1.2, mas permanece em rascunho, aguardando o sign-off explícito e documentado de Renato dos Santos e a declaração do estado da baseline. A autoridade final está confirmada; a baseline continua bloqueada. A prioridade de feature Alta/Média é distinta da fatia de MVP de cada HU.