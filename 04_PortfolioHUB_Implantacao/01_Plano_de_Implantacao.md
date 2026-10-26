# 1 · Plano de Implantação

## Objetivo

Colocar o PortfolioHUB em produção como plataforma pública e segura para exibir meus projetos, com versionamento no GitHub, regras de acesso definidas e documentação completa.

## Escopo

**Inclui:** ambiente GitHub dedicado, repositório do PortfolioHUB, GitHub Pages, gestão de usuários, políticas de segurança, fluxo de colaboração, testes e lançamento.
**Não inclui:** domínio próprio pago, banco de dados e back-end (o site é estático).

## Fases e cronograma

| Fase | Atividade | Responsável | Prazo | Status |
|------|-----------|-------------|-------|--------|
| 1 | Planejamento e configuração do Gemini como guia | Bernardo | 21/10 | ☐ |
| 2 | Ambiente GitHub dedicado e integração do repositório | Bernardo | 22/10 | ☐ |
| 3 | Gestão de usuários e políticas de segurança | Bernardo + Gemini | 22/10 | ☐ |
| 4 | Compartilhamento, controle de acesso e colaboração | Bernardo | 23/10 | ☐ |
| 5 | Testes, ajustes e preparo para produção | Bernardo | 24/10 | ☐ |
| 6 | Vídeo de 5 min e PDF final | Bernardo | 25/10 | ☐ |

## Papel do Google Gemini

O Gemini foi configurado como **guia da trilha de implantação**, com este contexto inicial (colado no início da conversa):

> "Atue como um mentor de DevOps e segurança para um estudante de TI. Vou implantar o PortfolioHUB, um portfólio estático hospedado no GitHub Pages. Guie-me passo a passo, em português, uma etapa por vez, explicando o porquê de cada configuração e apontando riscos de segurança."

Os prompts e respostas de cada etapa estão em [05_Uso_do_Gemini.md](05_Uso_do_Gemini.md).

## Riscos e mitigação

| Risco | Mitigação |
|-------|-----------|
| Vazamento de dados pessoais ou credenciais | Nunca versionar tokens, senhas ou documentos pessoais; `.gitignore` e revisão antes do commit |
| Perda de acesso à conta | 2FA ativo com códigos de recuperação guardados |
| Alteração indevida do código | Proteção da branch `main` e revisão por Pull Request |
| Site fora do ar após alteração | Testar localmente e conferir o deploy na aba Actions |
