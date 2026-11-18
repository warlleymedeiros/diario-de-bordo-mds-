---
title: "Pré-release 2 — 18/11/2026"
authors: [explorador-mds]
tags: [pre-release-2]
date: 2026-11-18
---

## 1. Compare como você está se sentindo na preparação desta segunda entrega com a forma como se sentiu na primeira.

Em comparação com a primeira entrega, a sensação predominante nesta reta final para a Release 2 é de muito mais tranquilidade e controle, embora o final de semestre continue bastante puxado com as demandas acumuladas de outras disciplinas. Na R1, a equipe viveu uma oscilação prejudicial: começamos muito lentos e fomos obrigados a virar noites e correr contra o tempo nas últimas duas semanas para colocar o software de pé. Desta vez, nossa dinâmica foi completamente diferente.

Um exemplo prático dessa evolução foi o fechamento da nossa Sprint 12, que concentrou os esforços em documentação, melhorias de UI/UX e consolidação do front-end. Conseguimos nos planejar de forma cadenciada ao longo dos dias, distribuindo as tarefas para não acumular trabalho na véspera. Ver a sprint ser concluída e integrada com antecedência, sem o desespero e o estresse que marcaram a primeira entrega, foi a evidência mais clara de que nosso fluxo de trabalho amadureceu.

Essa situação me mostrou que a maturidade da equipe não está apenas em saber codificar melhor, mas na capacidade de prever gargalos e manter um ritmo sustentável. O susto e os débitos que tivemos na R1 serviram de lição prática sobre o custo do retrabalho e da procrastinação. Para as próximas etapas e a entrega final, meu objetivo é manter rigorosamente essa disciplina de fatiar as entregas e fechar as tarefas com folga, provando que é possível entregar com qualidade sem recorrer a correrias de última hora.

## 2. Descreva como as decisões técnicas estão sendo tomadas na sua equipe nesta fase — quem decide, como se chega a um consenso.

Nesta fase do projeto, as decisões técnicas deixaram de ser suposições individuais e passaram a ser centralizadas em reuniões síncronas de alinhamento com toda a equipe. Nossa dinâmica de consenso funciona de forma bastante colaborativa: quando algum membro sugere o uso de uma ferramenta, biblioteca ou abordagem, pedimos para a pessoa explicar a proposta ou nós mesmos tiramos um tempo para pesquisar e entender como ela funciona na prática. Caso não haja sugestão inicial, pesquisamos juntos as alternativas disponíveis até encontrarmos a opção mais viável.

O momento mais emblemático dessa tomada de decisão aconteceu quando debatemos o escopo desta entrega. Havia uma vontade genuína do grupo de implementar mais funcionalidades de impacto, principalmente a opção de visualizar o fluxo do curso (a grade curricular com seus pré-requisitos) e disponibilizar antecipadamente as avaliações dos professores vinculados às matérias. No entanto, ao analisarmos com sinceridade o cronograma restante e a carga de trabalho de final de semestre, percebemos que tentar abraçar tudo comprometeria a qualidade do que já estava funcionando e a correção do front-end cobrada na R1. Em consenso, decidimos enxugar as mudanças e priorizar a estabilidade.

Esse debate me ensinou que consenso em engenharia de software tem muito mais a ver com saber o que **não** fazer do que simplesmente acumular código. Cortar funcionalidades que gostaríamos de ver no ar foi difícil, mas mostrou responsabilidade com o produto. O que vou manter para os próximos passos é essa cultura de debate transparente e fundamentado no tempo real da equipe, guardando as ideias não priorizadas como backlog futuro em vez de inflar o escopo de forma irrealista.

## 3. Que lacunas técnicas ainda te incomodam, e o que você tem feito, ou pretende fazer, a respeito?

A principal lacuna que ainda me gera inquietação não é estritamente de infraestrutura ou de banco de dados — camadas nas quais me sinto consideravelmente mais seguro hoje —, mas sim a percepção sobre o conjunto de features do site. Sinto que o sistema ainda precisa de um diferencial mais marcante e atrativo para o usuário final, algo que vá além da consulta básica de dados e gere um impacto real na experiência acadêmica.

A funcionalidade de visualização interativa do fluxo do curso, conectando as disciplinas aos professores e às suas turmas, é exatamente o tipo de valor agregado que eu gostaria de ver consolidado no sistema. A lacuna técnica que me incomoda é justamente o desafio de como estruturar, renderizar e integrar essa teia de dependências (matérias, pré-requisitos e professores) de forma fluida na interface e com consultas otimizadas, sem tornar a aplicação pesada ou confusa para quem navega.

Para lidar com essa sensação, tenho compreendido que o desenvolvimento de software precisa respeitar etapas: primeiro garantimos uma base sólida, estável e bem documentada (o foco principal da R2), para só então construir diferenciais mais complexos. Pretendo aproveitar o período logo após o fechamento da entrega da R2 para estudar mais sobre modelagem e componentes visuais de grafos/fluxogramas, amadurecendo a ideia para que possamos avaliar tecnicamente a viabilidade de trazer esse recurso na evolução final do projeto.
