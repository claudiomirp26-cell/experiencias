# Projeto Repositório de TG/TCC — Acervo Digital Acadêmico

## 🎯 Objetivo

Implementar repositório centralizado e searchable de Trabalhos de Graduação (TG) e Trabalhos de Conclusão de Curso (TCC) da Uniasselvi, permitindo conformidade com indicador de qualidade MEC 1.11 (documentação de trabalhos) e habilitando acesso à comunidade acadêmica.

## 📋 Descrição do Projeto

**Período:** Maio 2022 – Dezembro 2022  
**Patrocinador:** Gioconda Marques (Diretoria Acadêmica)  
**PM Responsável:** Claudiomir Paveukieviz  
**Líder de Projeto:** Stefania Müller  
**Status:** ✅ Concluído

### Contexto Estratégico

A Uniasselvi produzia centenas de trabalhos acadêmicos (TG/TCC) anualmente, mas não possuía:

- **Repositório Centralizado:** Trabalhos armazenados em pastas locais, desorganizados
- **Conformidade MEC:** Indicador 1.11 exigia documentação e acesso a trabalhos concluídos
- **Acesso Inadequado:** Estudantes e pesquisadores não conseguiam localizar trabalhos relevantes
- **Falta de Preservação:** Sem backup estruturado ou preservação de acervo acadêmico
- **Ausência de Metadados:** Sem catalogação por autor, título, tema, data

**Desafio:** Criar acervo digital que permitisse:
- Upload e catalogação automática de PDFs de TG/TCC
- Busca por título, autor, resumo, disciplina
- Integração com sistema Gioconda (gestão acadêmica)
- Conformidade com indicador MEC 1.11
- Escalabilidade para 5000+ trabalhos

### Solução Implementada

Desenvolvemos plataforma de acervo digital com componentes de armazenamento, busca e conformidade:

✅ **Módulo de Upload Gioconda** — Integração automática: TCC aprovado em Gioconda → PDF para repositório  
✅ **Armazenamento Estruturado** — Sistema de pastas por ano/curso/polo com metadados completos  
✅ **Motor de Busca Full-Text** — Indexação de título, resumo, palavras-chave e texto integral (PDFs)  
✅ **Interface de Pesquisa** — Dashboard permitindo buscar por título, autor, curso, data, palavras-chave  
✅ **Conformidade MEC** — Documentação automática de trabalhos concluídos conforme indicador 1.11  
✅ **Relatórios Analíticos** — Estatísticas de trabalhos por curso, polo, período  

### Escopo do Projeto

**Fazer:**
- FORM 0107: Integração com Gioconda para captura de TCC aprovados
- FORM 0107: Sistema de armazenamento e indexação de PDFs
- FORM 0107: Interface web de busca com múltiplos critérios
- FORM 0107: Geração de relatórios de conformidade MEC 1.11
- Migração de acervo existente (1500+ trabalhos)
- Documentação de metadados acadêmicos

**Não fazer:**
- Publicação aberta para internet (repositório restrito à comunidade)
- Integração com repositórios federais (escopo futuro)

## 🛠️ Tecnologias Utilizadas

| Camada | Tecnologia |
|--------|-----------|
| **Frontend** | Portal Acadêmico Institucional (Interface Web Responsiva) |
| **Integração Gioconda** | APIs Gioconda para captura de trabalhos aprovados |
| **Armazenamento** | Servidores NAS com replicação e backup (Bruno Santa Maria) |
| **Busca Full-Text** | Elasticsearch ou engine de indexação corporativo |
| **Processamento PDF** | Extração de texto de PDFs para indexação |
| **Banco de Dados** | Sistema relacional corporativo (metadados) |
| **Infraestrutura** | Servidores institucionais com CDN para download de PDFs |
| **Segurança** | Autenticação via SSO, certificação de Marcos Aurelio Amarante |

## 📊 Resultados & Impacto

### Cronograma Executado

| Fase | Descrição | Início | Término | Status |
|------|-----------|--------|---------|--------|
| **Iniciação** | Planejamento e análise de requisitos MEC | 02/05/2022 | 20/05/2022 | ✅ |
| **Desenvolvimento Módulo 1** | Integração Gioconda e armazenamento | 23/05/2022 | 17/06/2022 | ✅ |
| **Desenvolvimento Módulo 2** | Motor de busca e indexação | 20/06/2022 | 08/07/2022 | ✅ |
| **Homologação** | Testes com acervo existente (1500+ trabalhos) | 11/07/2022 | 29/07/2022 | ✅ |
| **Migração de Dados** | Importação e indexação de acervo legado | 01/08/2022 | 19/08/2022 | ✅ |
| **Implantação** | Deploy em produção | 22/08/2022 | 26/08/2022 | ✅ |
| **Operação Assistida** | Suporte e otimização pós-lançamento | 29/08/2022 | 30/09/2022 | ✅ |
| **Encerramento** | Documentação final e treinamento | 01/10/2022 | 07/10/2022 | ✅ |

### Resultados Alcançados

✅ **Conformidade MEC 1.11** — Indicador de qualidade alcançado com documentação integral de trabalhos  
✅ **Acervo Operacional** — 1.500+ trabalhos migrados e indexados em 3 semanas  
✅ **Busca Eficiente** — Resultados de busca em <500ms para 5.000+ documentos  
✅ **Integração Gioconda** — Novos TCC automaticamente enviados ao repositório após aprovação  
✅ **Escalabilidade** — Arquitetura preparada para 10.000+ trabalhos  
✅ **Adoção de Usuários** — 85%+ da comunidade acadêmica usando repositório mensalmente  

### Impacto Acadêmico

- **Preservação de Acervo:** Proteção de 1.500+ trabalhos com backup redundante
- **Acesso Acadêmico:** Pesquisadores e estudantes encontram trabalhos relacionados em segundos
- **Conformidade Regulatória:** Evidência clara de cumprimento MEC 1.11 em auditorias
- **Produtividade:** Redução de requisições manuais de trabalhos ao Acadêmico (antes: 10-15/semana)
- **Visibilidade:** Base para futuro repositório aberto e contribuição ao acervo brasileiro

## 💡 Competências Demonstradas

| Competência | Como Evidenciado |
|------------|-----------------|
| **Conformidade Regulatória** | Implementação de requisito MEC 1.11 em arquitetura de sistema |
| **Integração com Sistemas Corporativos** | Captura automática de TCC em Gioconda, sincronização bidirecional |
| **Busca e Indexação** | Design de engine full-text para 5.000+ documentos com latência <500ms |
| **Migração de Dados** — Transferência de 1.500+ trabalhos com validação de integridade |
| **Gestão de Projeto** | Execução de 8 meses (maio-dezembro 2022) com 3 change requests aprovados |
| **Liderança Técnica** | Coordenação entre Acadêmico, TI, Gioconda e equipe de Desenvolvimento (Stefania Müller) |
| **Comunicação Stakeholder** | Alinhamento com Diretoria Acadêmica e Gioconda para garantir conformidade |

## 📞 Referências

**Documentação Disponível sob Solicitação:**
- FORM 0015 — Termo de Abertura do Projeto
- FORM 0019 — Status Reports (versões 1–6)
- FORM 0021 — Change Requests (3 aprovadas)
- FORM 0022 — Termo de Encerramento do Projeto
- Especificações técnicas de integração Gioconda
- Documentação de metadados e conformidade MEC 1.11
- Planos de contingência e backup

---

**Gerente de Projeto:** Claudiomir Paveukieviz  
**Líder de Projeto:** Stefania Müller  
**Período:** Maio–Dezembro 2022  
**Resultado Final:** ✅ Sucesso — Repositório operacional com 1.500+ trabalhos, conformidade MEC 1.11 certificada, adoção de 85%+ da comunidade acadêmica
