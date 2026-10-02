# Projeto Distribuição de Vagas por Curso — Conformidade MEC e Alocação Dinâmica

## 🎯 Objetivo

Implementar sistema automatizado de distribuição de vagas entre polos e sincronização com sistema e-MEC, permitindo conformidade regulatória com o indicador de qualidade MEC 1.1 (distribuição proporcional de vagas) e reduzindo overhead de gestão manual.

## 📋 Descrição do Projeto

**Período:** Janeiro – Junho 2022  
**Patrocinador:** Paulo Siqueira (Diretoria Acadêmica)  
**PM Responsável:** Claudiomir Paveukieviz  
**Status:** ✅ Concluído

### Contexto Estratégico

A Uniasselvi ofertava cursos através de vários polos, mas enfrentava desafios na distribuição proporcional de vagas conforme regulamentações MEC. O sistema anterior era:

- **Gestão Manual:** Alocação de vagas feita por spreadsheets e comunicações ad-hoc
- **Falta de Conformidade:** Dificuldade em demonstrar proporção regulamentária de vagas ao MEC
- **Ineficiência Operacional:** Processamento lento de atualizações, resultando em gaps entre sistema e-MEC
- **Falta de Rastreabilidade:** Sem auditoria clara de decisões de alocação

**Desafio:** Criar sistema que permitisse:
- Distribuição automática e proporcional de vagas entre polos
- Sincronização em tempo real com e-MEC
- Auditoria completa de todas as decisões de alocação
- Conformidade demonstrável com indicador MEC 1.1

### Solução Implementada

Desenvolvemos sistema integrado de gestão de vagas com três componentes principais:

✅ **Módulo de Cálculo Proporcional** — Algoritmo de distribuição baseado em capacidade registral, demanda histórica e objetivos estratégicos  
✅ **Integração e-MEC** — Sincronização bidirecional com sistema federal, validação de conformidade em tempo real  
✅ **Painel Administrativo** — Dashboard para visualizar alocação, histórico de mudanças, alertas de conformidade  
✅ **Auditoria e Rastreabilidade** — Log completo de todas as operações de distribuição  

### Escopo do Projeto

**Fazer:**
- FORM 0107: Implementar algoritmo de distribuição proporcional
- FORM 0107: Integrar com APIs do sistema e-MEC
- FORM 0107: Criar painel de gestão e monitoramento
- Relatórios de conformidade MEC
- Processamento em lote e validação de dados

**Não fazer:**
- Modificação de políticas de admissão dos polos
- Integração com CRM Salesforce (escopo futuro)

## 🛠️ Tecnologias Utilizadas

| Camada | Tecnologia |
|--------|-----------|
| **Frontend** | Portal Acadêmico Institucional (Interface Web) |
| **Backend** | Plataforma de Gestão Acadêmica Corporativa |
| **Integração e-MEC** | API REST e-MEC (protocolos MEC) |
| **Banco de Dados** | Sistema relacional corporativo com replicação |
| **Infraestrutura** | Servidores institucionais com suporte de Bruno Santa Maria |
| **Segurança** | Certificação de Marcos Aurelio Amarante (Seg. da Informação) |

## 📊 Resultados & Impacto

### Cronograma Executado

| Fase | Descrição | Início | Término | Status |
|------|-----------|--------|---------|--------|
| **Iniciação** | Planejamento e análise de conformidade | 18/01/2022 | 28/02/2022 | ✅ |
| **Desenvolvimento Módulo 1** | Algoritmo de distribuição | 01/03/2022 | 25/03/2022 | ✅ |
| **Homologação Módulo 1** | Testes de conformidade MEC | 28/03/2022 | 15/04/2022 | ✅ |
| **Desenvolvimento Módulo 2** | Integração e-MEC | 18/04/2022 | 06/05/2022 | ✅ |
| **Homologação Integrada** | Testes ponta-a-ponta | 09/05/2022 | 20/05/2022 | ✅ |
| **Implantação** | Deploy em produção | 23/05/2022 | 27/05/2022 | ✅ |
| **Operação Assistida** | Suporte pós-lançamento | 30/05/2022 | 30/06/2022 | ✅ |

### Resultados Alcançados

✅ **Conformidade Regulatória** — Sistema atende indicador MEC 1.1 com distribuição proporcional documentada  
✅ **Automação Completa** — Redução de 95% do trabalho manual em alocação de vagas  
✅ **Sincronização Real-Time** — e-MEC sempre reflete estado atual de vagas por polo  
✅ **Auditoria Integral** — Rastreamento completo de quem, o quê e quando nas decisões  
✅ **Escalabilidade** — Preparado para crescimento: 50+ polos, 200+ cursos  

### Impacto Organizacional

- **Conformidade Regulatória:** Redução de riscos em auditorias MEC
- **Eficiência Operacional:** Processamento automático de atualizações em segundos
- **Visibilidade Estratégica:** Direção tem dados em tempo real sobre oferta por polo
- **Escalabilidade:** Sistema preparado para crescimento futuro

## 💡 Competências Demonstradas

| Competência | Como Evidenciado |
|------------|-----------------|
| **Conformidade Regulatória** | Implementação de requisitos MEC (indicador 1.1) em arquitetura de sistema |
| **Integração Sistêmica** | Conexão bidirecional com APIs federais (e-MEC) sob constraints regulatórios |
| **Gestão de Projetos** | Execução de 6 meses com entregas faseadas (2 GMUD separados) |
| **Algoritmos & Data** | Design de algoritmo de distribuição proporcional com validação |
| **Liderança Técnica** | Coordenação entre Desenvolvimento, Acadêmico e Conformidade |
| **Comunicação Regulatória** | Alinhamento com stakeholders MEC durante integração |

## 📞 Referências

**Documentação Disponível sob Solicitação:**
- FORM 0015 — Termo de Abertura do Projeto
- FORM 0019 — Status Reports (versões 1–5)
- Especificações técnicas de integração e-MEC
- Documentação de conformidade MEC (indicador 1.1)
- Planos de contingência e suporte pós-lançamento

---

**Gerente de Projeto:** Claudiomir Paveukieviz  
**Período:** Janeiro–Junho 2022  
**Resultado Final:** ✅ Sucesso — Sistema em operação, conformidade MEC certificada
