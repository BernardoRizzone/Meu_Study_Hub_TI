# 04 · Implantação do PortfolioHUB + IA Gemini

Documentação da implantação do **PortfolioHUB**: plataforma centralizada para exibir e gerenciar meus projetos e portfólios digitais, usando **Git/GitHub** para versionamento e controle de acesso e o **Google Gemini** como apoio durante todo o processo.

🌐 Site: https://bernardorizzone.github.io/Meu_Study_Hub_TI/
📦 Repositório: https://github.com/BernardoRizzone/Meu_Study_Hub_TI

## Índice

| # | Documento | Conteúdo |
|---|-----------|----------|
| 1 | [Plano de Implantação](01_Plano_de_Implantacao.md) | Objetivo, escopo, cronograma e papel do Gemini |
| 2 | [Gestão de Usuários e Segurança](02_Gestao_de_Usuarios_e_Seguranca.md) | Contas, permissões, 2FA, proteção de branch e checklist |
| 3 | [Colaboração e Controle de Acesso](03_Colaboracao_e_Controle_de_Acesso.md) | Fluxo de trabalho, PRs, issues e versionamento |
| 4 | [Testes e Lançamento](04_Testes_e_Lancamento.md) | Checklist de testes e preparo para produção |
| 5 | [Uso do Gemini](05_Uso_do_Gemini.md) | Prompts usados, respostas e o que foi aplicado |
| 6 | [Desafios e Soluções](06_Desafios_e_Solucoes.md) | Problemas encontrados e como foram resolvidos |

## Arquitetura

```text
Gemini (guia/consultoria)
        │ orienta
        ▼
Git local ──push──▶ GitHub (repositório + controle de acesso) ──deploy──▶ GitHub Pages (PortfolioHUB no ar)
        ▲                          │
        └────────pull──────────────┘          LinkedIn aponta para o site e o repositório
```

## Versionamento

- **v1.0** — Study Hub e página web inicial (entrega intermediária)
- **v2.0** — Implantação do PortfolioHUB com segurança e colaboração (entrega final)
