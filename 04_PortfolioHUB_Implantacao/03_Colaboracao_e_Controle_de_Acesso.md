# 3 · Colaboração e Controle de Acesso

## Fluxo de trabalho

```text
main (protegida, sempre estável)
  └── feature/nome-da-alteracao  →  commit  →  push  →  Pull Request  →  revisão  →  merge em main  →  deploy no Pages
```

1. Criar uma branch para cada alteração (`feature/`, `fix/`, `docs/`).
2. Fazer commits pequenos com mensagens claras.
3. Abrir um **Pull Request** descrevendo a mudança.
4. Revisar (por mim ou por um colaborador) e fazer o merge na `main`.
5. O GitHub Pages publica a nova versão automaticamente.

## Padrão de commits

| Prefixo | Uso |
|---------|-----|
| `feat:` | Nova funcionalidade ou conteúdo |
| `fix:` | Correção |
| `docs:` | Documentação |
| `style:` | Ajuste visual sem mudar a lógica |
| `chore:` | Tarefas de manutenção |

## Ferramentas colaborativas usadas

- **Issues:** registro de tarefas e melhorias
- **Pull Requests:** revisão e histórico de decisões
- **Projects (quadro Kanban):** acompanhamento das fases da implantação
- **Releases e tags:** marcação das versões (v1.0, v2.0)
- **Google Docs / Drive:** documentos de apoio e entregas anteriores

## Controle de acesso

| Recurso | Quem acessa | Como é controlado |
|---------|-------------|-------------------|
| Leitura do repositório e do site | Público | Repositório público |
| Escrita direta na `main` | Ninguém | Proteção de branch |
| Alterações | Proprietário e colaboradores | Pull Request |
| Configurações do repositório | Somente o proprietário | Permissão Admin |

## Como colaborar

Veja o [CONTRIBUTING.md](../CONTRIBUTING.md) na raiz do repositório.
