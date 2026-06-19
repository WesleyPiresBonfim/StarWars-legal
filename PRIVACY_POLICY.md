# Política de Privacidade do StarWars / StarWars Privacy Policy

Última atualização: 19 de junho de 2026

## Português (Brasil)

### 1. Visão geral

Esta Política de Privacidade explica como o app Discord **StarWars** (`1300865164954042398`) coleta, usa, armazena, compartilha e exclui dados. O StarWars é um jogo social para Discord com progressão por eras, economia, facções, territórios, modo solo, rankings, apostas configuráveis e integração opcional com DreamTeam.

O responsável operacional documentado para o app é **NegoAlbinoJr** (`249204720395223041`). Solicitações também podem ser abertas no servidor criador do projeto: [DreamStars](https://discord.gg/dreamstars-1152751704748601415).

### 2. Dados que coletamos

O StarWars coleta apenas dados necessários para operar o jogo, os comandos, as integrações e a segurança do serviço.

Dados de identificação do Discord:

- ID do usuário do Discord;
- ID do servidor, canal, thread, cargo e mensagem quando necessário para comandos, auditoria, notificações, threads de facção, confrontos e operações;
- nome de usuário, nome global, apelido no servidor, nome exibido e avatar podem ser consultados para exibição em embeds, rankings, contratos, notificações e perfis.

Dados de jogo:

- registro do jogador no servidor;
- saldo, StarCoins, recursos, inventário, itens, crafting, cooldowns e lembretes;
- reputação, lealdade, era, progresso, ranking e snapshots de temporada;
- facção, cargos de facção, membros, líder, vice-líder, contratos, salários, mercado, pesquisas e recursos coletivos;
- territórios, ataques, defesas, confirmações de presença, substituições, resultados, pontuações, W.O., penalidades e histórico de controle;
- apostas, palpites, jogos, resultados e pagamentos quando a funcionalidade estiver habilitada;
- registros de transações e extratos gerados por comando.

Dados de mensagens e conteúdo:

- comandos slash e componentes enviados ao bot;
- mensagens que começam com o prefixo administrativo configurado, processadas apenas para usuários GM autorizados;
- embeds ou mensagens do bot DreamTeam em canais ou threads esperados, quando usados para comparar times ou registrar resultados;
- payloads de webhook DreamTeam/StarWars contendo IDs de servidor, thread, usuários, placar, gols e metadados de partida;
- IDs de mensagem e thread para editar, limpar, auditar ou deduplicar resultados.

O StarWars não monitora conversas gerais para publicidade, perfilamento comercial ou treinamento de IA. O conteúdo de mensagem processado é limitado aos fluxos necessários para comando, resultado, comparação, auditoria ou integração.

Dados DreamTeam quando a integração estiver habilitada:

- vínculo entre ID Discord e ID DreamTeam;
- nome do time, imagens públicas do time, OVR médio, top OVR, elegibilidade, plano premium quando retornado pela API, forma recente e snapshots de força;
- fila de operação, pareamento, histórico de pares, placar, gols, recompensas internas do StarWars e ledger de recompensas DreamTeam.

Dados técnicos:

- eventos de domínio, outbox, métricas, erros, comandos executados, rejeições por regra de negócio, timestamps e dados mínimos para depuração;
- logs podem conter IDs do Discord, nomes públicos, nome do comando, resposta do bot e contexto operacional.

Dados que não coletamos:

- senhas de usuários do Discord;
- e-mail, telefone, documentos, endereço, dados de pagamento ou mensagens privadas do Discord;
- dados de presença, status online, atividades Rich Presence ou plataforma do usuário;
- conteúdo de mensagens para treinamento de modelos de IA.

### 3. Como usamos os dados

Usamos dados para:

- executar comandos e interações do Discord;
- manter perfis, progressão, economia, recursos, inventário e rankings;
- gerenciar facções, cargos, threads privadas, contratos, salários, mercado e lealdade;
- registrar, validar e apurar conflitos territoriais e operações DreamTeam;
- entregar notificações, lembretes, resultados e extratos;
- prevenir abuso, duplicidade de recompensa, fraude, spam, erros de integração e inconsistências;
- auditar ações administrativas e resolver suporte;
- melhorar balanceamento de jogo e estabilidade operacional.

### 4. Compartilhamento de dados

Dados podem ser compartilhados ou processados pelos seguintes serviços, conforme a configuração do ambiente:

- Discord, por meio da API e dos eventos necessários para operar o bot;
- provedores de hospedagem, banco PostgreSQL, Redis e infraestrutura operacional usada para executar o StarWars;
- DreamTeam, quando a integração estiver habilitada, para leitura de dados públicos/permitidos, pareamento, registro de resultados e entrega de recompensas;
- API-Football/API-Sports e The Odds API para dados de futebol, escudos, jogos e odds, sem envio de dados pessoais de usuários;
- administradores ou GMs do servidor, quando dados de jogo aparecem em comandos, rankings, embeds, extratos, auditorias ou painéis;
- autoridades ou terceiros quando exigido por lei ou necessário para proteger usuários, servidores, o operador do bot ou a integridade do serviço.

Não vendemos dados pessoais.

### 5. Retenção

Dados de jogo associados ao seu ID do Discord podem ser mantidos enquanto forem necessários para operar o StarWars no servidor, preservar rankings, auditoria, histórico de temporadas, integridade econômica, contratos, facções e prevenção de abuso.

Dados temporários, como lembretes, filas, locks, snapshots e eventos de integração, podem expirar ou ser limpos conforme a configuração do sistema. Logs e backups podem ser mantidos por período operacional razoável e removidos conforme rotação, manutenção ou solicitação aplicável.

Quando a retenção não for mais necessária, quando o bot deixar de operar, quando o Discord solicitar, quando a lei exigir ou quando o usuário solicitar exclusão válida, os dados aplicáveis devem ser excluídos ou anonimizados, salvo quando houver obrigação legítima de retenção.

### 6. Segurança

O StarWars usa controles técnicos e administrativos para proteger dados, incluindo:

- credenciais e tokens em variáveis de ambiente;
- segregação de configurações por ambiente;
- acesso restrito ao banco e à infraestrutura;
- logs com mascaramento de campos sensíveis quando suportado pelo logger;
- uso de IDs e dados mínimos necessários para cada fluxo;
- deduplicação e auditoria para reduzir fraude e repetição de eventos.

Nenhum sistema é 100% seguro. Incidentes relevantes serão avaliados e comunicados conforme exigido por lei e pelas políticas do Discord.

### 7. Seus controles e solicitações

Você pode solicitar:

- acesso geral aos dados de jogo associados ao seu ID;
- correção de dados incorretos quando tecnicamente possível;
- exclusão ou anonimização de dados pessoais associados ao seu ID;
- explicação sobre dados processados pelo bot.

Para solicitar exclusão ou suporte, contate **NegoAlbinoJr** no Discord (`249204720395223041`) ou abra um ticket no servidor [DreamStars](https://discord.gg/dreamstars-1152751704748601415).

A exclusão pode remover ou quebrar progresso de jogo, rankings, contratos, facções, recompensas, histórico de operações e recursos associados ao seu ID. Alguns registros podem ser mantidos de forma agregada, anonimizada ou pelo tempo necessário para segurança, auditoria, prevenção de fraude ou obrigação legal.

### 8. Crianças e menores

O StarWars é destinado a usuários que podem usar o Discord de acordo com as regras do Discord e a legislação aplicável. O bot não solicita intencionalmente dados de crianças fora do funcionamento normal do Discord.

### 9. Transferências internacionais

O StarWars pode ser hospedado e processado fora do seu país. Ao usar o bot, seus dados podem ser processados em regiões onde o operador, a infraestrutura, o Discord ou integrações externas operam, sempre conforme as regras aplicáveis do Discord e esta política.

### 10. Alterações desta política

Esta política pode ser atualizada para refletir mudanças no bot, nas integrações, na infraestrutura, nas regras do Discord ou na lei. A versão pública mais recente substitui versões anteriores.

## English

### 1. Overview

This Privacy Policy explains how the **StarWars** Discord app (`1300865164954042398`) collects, uses, stores, shares, and deletes data. StarWars is a social Discord game with era-based progression, economy, factions, territories, solo play, rankings, configurable betting features, and optional DreamTeam integration.

The documented operational owner for the app is **NegoAlbinoJr** (`249204720395223041`). Requests may also be opened in the project's main repository: [DreamStars](https://discord.gg/dreamstars-1152751704748601415).

### 2. Data we collect

StarWars collects only the data needed to operate the game, commands, integrations, and service security.

Discord identification data:

- Discord user ID;
- server, channel, thread, role, and message IDs when needed for commands, audit logs, notifications, faction threads, conflicts, and operations;
- username, global name, server nickname, display name, and avatar may be fetched to display embeds, rankings, contracts, notifications, and profiles.

Game data:

- player registration in a server;
- balance, StarCoins, resources, inventory, items, crafting, cooldowns, and reminders;
- reputation, loyalty, era, progress, rankings, and season snapshots;
- faction, faction roles, members, leader, vice leader, contracts, salaries, market, research, and collective resources;
- territories, attacks, defenses, presence confirmations, substitutions, results, scores, forfeits, penalties, and control history;
- bets, picks, games, results, and payouts when the feature is enabled;
- transaction records and command-generated statements.

Message and content data:

- slash commands and components sent to the bot;
- messages starting with the configured administrative prefix, processed only for authorized GM users;
- DreamTeam bot embeds or messages in expected channels or threads when used to compare teams or register results;
- DreamTeam/StarWars webhook payloads containing server IDs, thread IDs, user IDs, scores, goals, and match metadata;
- message and thread IDs used to edit, clean up, audit, or deduplicate results.

StarWars does not monitor general conversations for advertising, commercial profiling, or AI training. Message content processing is limited to command, result, comparison, audit, or integration flows required for the bot to work.

DreamTeam data when integration is enabled:

- link between Discord ID and DreamTeam ID;
- team name, public team images, average OVR, top OVR, eligibility, premium plan when returned by the API, recent form, and force snapshots;
- operation queue, matchmaking, pair history, scores, goals, internal StarWars rewards, and DreamTeam reward ledger.

Technical data:

- domain events, outbox events, metrics, errors, executed commands, business-rule rejections, timestamps, and minimal debugging context;
- logs may contain Discord IDs, public names, command name, bot response, and operational context.

Data we do not collect:

- Discord user passwords;
- email address, phone number, documents, address, payment data, or Discord private messages;
- presence data, online status, Rich Presence activities, or user platform data;
- message content for AI model training.

### 3. How we use data

We use data to:

- run Discord commands and interactions;
- maintain profiles, progression, economy, resources, inventory, and rankings;
- manage factions, roles, private threads, contracts, salaries, market, and loyalty;
- register, validate, and settle territory conflicts and DreamTeam operations;
- deliver notifications, reminders, results, and statements;
- prevent abuse, duplicate rewards, fraud, spam, integration errors, and inconsistencies;
- audit administrative actions and resolve support requests;
- improve game balance and operational stability.

### 4. Data sharing

Data may be shared with or processed by the following services depending on environment configuration:

- Discord, through the API and events required to operate the bot;
- hosting providers, PostgreSQL database, Redis, and operational infrastructure used to run StarWars;
- DreamTeam, when integration is enabled, for permitted/public data reads, matchmaking, result registration, and reward delivery;
- API-Football/API-Sports and The Odds API for football data, logos, games, and odds, without intentionally sending personal user data;
- server administrators or GMs when game data appears in commands, rankings, embeds, statements, audits, or dashboards;
- authorities or third parties when required by law or necessary to protect users, servers, the bot operator, or service integrity.

We do not sell personal data.

### 5. Retention

Game data associated with your Discord ID may be kept while it is needed to operate StarWars in a server, preserve rankings, audit trails, season history, economic integrity, contracts, factions, and abuse prevention.

Temporary data such as reminders, queues, locks, snapshots, and integration events may expire or be cleaned up according to system configuration. Logs and backups may be retained for a reasonable operational period and removed through rotation, maintenance, or applicable request.

When retention is no longer necessary, when the bot stops operating, when Discord requests deletion, when required by law, or when a user submits a valid deletion request, applicable data should be deleted or anonymized unless there is a legitimate obligation to retain it.

### 6. Security

StarWars uses technical and administrative controls to protect data, including:

- credentials and tokens in environment variables;
- environment-specific configuration separation;
- restricted database and infrastructure access;
- sensitive-field redaction in logs when supported by the logger;
- use of the minimum IDs and data needed for each flow;
- deduplication and audit trails to reduce fraud and repeated events.

No system is 100% secure. Relevant incidents will be evaluated and communicated as required by law and Discord policies.

### 7. Your controls and requests

You may request:

- general access to game data associated with your ID;
- correction of inaccurate data when technically possible;
- deletion or anonymization of personal data associated with your ID;
- removal of DreamTeam links, where applicable;
- an explanation of data processed by the bot.

To request deletion or support, contact **NegoAlbinoJr** on Discord (`249204720395223041`) or open a ticket on [DreamStars](https://discord.gg/dreamstars-1152751704748601415).

Deletion may remove or break game progression, rankings, contracts, factions, rewards, operation history, and resources associated with your ID. Some records may be retained in aggregate, anonymized form, or for as long as needed for security, audit, fraud prevention, or legal obligations.

### 8. Children and minors

StarWars is intended for users who may use Discord under Discord's rules and applicable law. The bot does not request children's data outside normal Discord functionality.

### 9. International transfers

StarWars may be hosted and processed outside your country. By using the bot, your data may be processed in regions where the operator, infrastructure, Discord, or external integrations operate, under Discord's applicable rules and this policy.

### 10. Changes to this policy

This policy may be updated to reflect changes to the bot, integrations, infrastructure, Discord rules, or the law. The latest public version replaces prior versions.