# Projeto Comercialização de Cursos Livres — Monetização de Conteúdo

## 🎯 Objetivo

Capacitar a Uniasselvi a comercializar cursos livres para o mercado externo e interno, desenvolvendo infraestrutura de inscrição parametrizável, relatórios de acompanhamento financeiro, e integração de múltiplos canais de pagamento (PIX, Boleto, Cartão de Crédito).

## 📋 Descrição do Projeto

**Período:** Março – Setembro 2022  
**Patrocinador:** Carlos Fistarol / Ilana Gerber (Educação Continuada)  
**PM Responsável:** Claudiomir Paveukieviz  
**Líder de Projeto:** Caroline Martins  
**Status:** ✅ Concluído

### Contexto Estratégico

A Uniasselvi ofertava cursos livres aos alunos para preenchimento de horas de extensão, mas não possuía infraestrutura para comercializá-los junto à comunidade externa. Isso representava:

- **Perda de Receita:** Não havia fluxo de comercialização para público externo
- **Falta de Controle:** Gestão manual de inscrições e finanças
- **Baixa Escala:** Sistema de inscrição não padronizado em relação à identidade visual institucional

**Desafio:** Criar ecossistema completo de e-learning para cursos livres com:
- Inscrição padronizada e intuitiva
- Múltiplas formas de pagamento
- Relatórios administrativos e de repasses aos polos
- Integração com bases de dados de clientes

### Solução Implementada

Desenvolvemos plataforma modular com três fases principais:

✅ **Fase 1 — Inscrição Parametrizável**
- Tela de inscrição alinhada ao padrão visual da instituição
- Parametrização dinâmica de campos obrigatórios/opcionais
- Validação de dados em tempo real

✅ **Fase 2 — Pagamento Integrado**
- Suporte a PIX (transferência imediata)
- Suporte a Boleto Bancário (liquidação para crédito do polo)
- Suporte a Cartão de Crédito (processamento seguro)
- Gestão de transações com auditoria completa

✅ **Fase 3 — Relatórios & Repasses**
- Relatório de acompanhamento por polo (alunos inscritos)
- Relatório financeiro (receitas e repasses)
- Configuração de regras de repasse por polo
- Exportação para sistemas contábeis

### Escopo do Projeto

**Fazer:**
- FORM 0107: Parametrizar tela de inscrição
- FORM 0107: Implementar repasse e acompanhamento
- FORM 0107: Integrar múltiplos canais de pagamento
- Relatórios administrativos e financeiros
- Atualização de dados de alunos e financeiros

**Não fazer:**
- Criação de novos cursos ou conteúdo de cursos
- Integração com CRM Salesforce (escopo futuro)

## 🛠️ Tecnologias Utilizadas

| Camada | Tecnologia |
|--------|-----------|
| **Frontend** | Portal Educacional Institucional (Interface Responsiva) |
| **Backend** | Plataforma de E-Learning Corporativa |
| **Pagamentos** | Gateways de PIX, Boleto, Processador PCI-DSS para Cartão |
| **Relatórios** | Business Intelligence / Data Warehouse Institucional |
| **Infraestrutura** | Servidores de produção com redundância (Bruno Santa Maria) |
| **Segurança** | PCI-DSS, Criptografia de dados sensíveis (Marcos Aurelio Amarante) |
| **Banco de Dados** | Sistema relacional corporativo com replicação |

## 📊 Resultados & Impacto

### Cronograma Executado

| Fase | Descrição | Início | Término | Status |
|------|-----------|--------|---------|--------|
| **Iniciação** | Planejamento e estruturação | 23/03/2022 | 08/07/2022 | ✅ |
| **Desenvolvimento Fase 1** | Tela de inscrição | 11/07/2022 | 29/07/2022 | ✅ |
| **Homologação Fase 1** | Testes e validação inscrição | 01/08/2022 | 17/08/2022 | ✅ |
| **Desenvolvimento Fase 2** | Relatórios e pagamento | 18/07/2022 | 01/08/2022 | ✅ |
| **Homologação Fase 2** | Testes de pagamento e relatórios | 08/08/2022 | 24/08/2022 | ✅ |
| **GMUD** | Implantação em produção | 18/08/2022 + 25/08/2022 | Concluído | ✅ |
| **Operação Assistida** | Suporte pós-lançamento | 26/08/2022 | 21/09/2022 | ✅ |
| **Encerramento** | TEP e documentação | 22/09/2022 | 22/09/2022 | ✅ |

### Resultados Alcançados

✅ **Monetização Ativa** — Plataforma pronta para comercializar cursos livres  
✅ **Múltiplos Canais** — 3 opções de pagamento para maior conversão  
✅ **Controle Financeiro** — Rastreabilidade completa de transações e repasses  
✅ **Escalabilidade** — Infraestrutura parametrizável para novos cursos/promoções  
✅ **Entrega Robusta** — 72% de progresso físico em operação, zero incidentes críticos  

### Impacto Financeiro & Operacional

- **Nova Receita Stream:** Criação de canal de comercialização para cursos livres
- **Eficiência Operacional:** Redução de overhead manual em inscrições e repasses
- **Experiência do Cliente:** Inscrição simplificada com múltiplas opções de pagamento
- **Visibilidade Financeira:** Relatórios consolidados para gestão por polo

## 💡 Competências Demonstradas

| Competência | Como Evidenciado |
|------------|-----------------|
| **Transformação Digital** | Migração de processo manual para plataforma automatizada |
| **Gestão de Mudança** | Alinhamento de 13 stakeholders (Sponsor, Dev, Infra, Seg., Usuários) |
| **Gestão Ágil** | Execução em fases com 2 GMUD separados, reprogramação ágil conforme requisitos evoluíram |
| **Gestão de Riscos** | Identificação e mitigação: indisponibilidade de equipe, scope creep, requisitos incompletos |
| **Integração Sistêmica** | Conexão com Portal Educacional, gateways de pagamento, sistemas financeiros |
| **Liderança Técnica** | Coordenação de 2 coordenadores de desenvolvimento (Emmerson, Douglas) |
| **Comunicação** | 3 change requests gerenciados e aprovados durante execução |
| **Gestão de Stakeholders** | Coordenação entre Educação Continuada, TI, Finanças e Comercial |

## 📈 Lições Aprendidas

- **Importância de Requisitos Detalhados:** Projeto enfrentou 2 mudanças de escopo (mudanças aprovadas)
- **Equipes Distribuídas:** Sucesso dependeu de coordenação clara entre Desenvolvimento (2 coords), Infra e Seg. Informação
- **Flexibilidade Estratégica:** Priorização dinâmica (pausa para Hub Enfermagem, retomada com novos requisitos)
- **Governança de Pagamentos:** Rigor em PCI-DSS foi crítico para aprovação de cartão de crédito

## 📞 Referências

**Documentação Disponível sob Solicitação:**
- FORM 0015 — Termo de Abertura do Projeto
- FORM 0019 — Status Reports (versões 1–4)
- FORM 0021 — Change Requests (2 aprovadas)
- FORM 0022 — Termo de Encerramento
- Especificações técnicas de integração de pagamento (PCI-DSS)
- Planos de contingência e suporte pós-lançamento

---

**Gerente de Projeto:** Claudiomir Paveukieviz  
**Período:** Março–Setembro 2022  
**Resultado Final:** ✅ Sucesso — Plataforma operacional, todas as fases entregues com controles de mudança formal
