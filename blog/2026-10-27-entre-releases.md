---
title: "Entre releases — 27/10/2026"
authors: [explorador-mds]
tags: [entre-releases]
date: 2026-10-27
---

## 1. Olhando para a release que acabou de ser entregue, o que você diria que funcionou bem e o que não funcionou na sua equipe?

O grande trunfo da nossa Release 1 foi a robustez da base técnica e da camada de dados. 

Conseguimos integrar e consumir os dados do SIGAA Turmas de forma consistente, permitindo realizar buscas e filtragens sem inconsistências.

O banco de dados PostgreSQL e a API em FastAPI funcionaram perfeitamente juntos desde o primeiro teste integrado, 
garantindo que a lógica principal do sistema estivesse de pé.

Em contrapartida, o que claramente falhou foi a gestão de tempo em relação à experiência do usuário e ao design.
Entregamos um front-end cru, visualmente descuidado e sem um protótipo consolidado para sustentar as decisões de interface. 

Essa discrepância expôs uma falha clássica de planejamento: nos aprofundamos tanto na viabilidade dos dados e na estabilidade
do back-end que acabamos negligenciando a camada com a qual o usuário e a banca interagem diretamente. 

Por baixo dos panos o software funcionava muito bem, mas a primeira impressão visual não transmitia a mesma segurança técnica.

## 2. Como o feedback recebido (de colegas, professora, monitoria) tem influenciado o que vocês estão fazendo agora?

Durante a apresentação da R1, os apontamentos da professora e da monitoria foram diretos: precisávamos reformular o front-end,
entregar um protótipo de alta fidelidade e recalibrar os requisitos funcionais (
alguns estavam genéricos demais e outros excessivamente específicos). 

A reação do nosso grupo a essas críticas foi muito madura: ninguém se desestabilizou ou tentou apontar culpados. 

Saímos da apresentação genuinamente orgulhosos da funcionalidade que colocamos no ar, 
mas acolhendo com humildade cada ponto de melhoria destacado pela banca.

Esse retorno tornou-se o nosso plano de ação imediato para a transição rumo à R2. 
A etapa de requisitos já foi superada — revisamos e afinamos todo o escopo em equipe. 

No momento, nosso gargalo e prioridade estão no protótipo: já temos algumas versões de telas em discussão no Figma e
estamos trabalhando para bater o martelo na versão definitiva. 

Ter levado esse puxão de orelha cedo foi fundamental para não empurrarmos esse débito visual até o final da disciplina.

## 3. O que mudou, para você, entre o início da disciplina e este momento — tecnicamente e no seu jeito de trabalhar em equipe?

O contraste entre a minha postura de hoje e a do início do semestre é notável. 

Aquele medo paralisante da carga horária e da complexidade de MDS praticamente sumiu. 

A dinâmica de abrir o repositório, puxar uma issue, discutir no grupo e subir commits tornou-se uma rotina fluida e natural.

Na parte técnica, a responsabilidade de gerenciar o banco de dados fluiu muito melhor 
graças à sinergia direta com a matéria de Banco de Dados 1 (BD1), que estou cursando neste mesmo semestre.

Em vez de simplesmente gerar tabelas às cegas ou delegar a arquitetura inteira para uma Inteligência Artificial,
fiz questão de aplicar as aulas de modelagem conceitual e lógica para desenhar os relacionamentos à mão primeiro, 
garantindo que eu realmente compreendesse a estrutura dos dados. 

Apenas depois desse entendimento sólido é que utilizei a IA como ferramenta de suporte para revisar e validar a implementação no PostgreSQL.

Essa abordagem me deu uma segurança enorme, permitindo que eu evoluísse de alguém inseguro com a stack 
para um membro que atua com autonomia na espinha dorsal do projeto.
