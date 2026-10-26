# 2 · Gestão de Usuários e Segurança

## Estrutura de usuários

| Usuário | Papel | Permissão | Justificativa |
|---------|-------|-----------|---------------|
| BernardoRizzone | Proprietário (Owner) | Admin | Responsável pelo PortfolioHUB |
| _[colega/professor convidado]_ | Colaborador | Write ou Read | Revisão e colaboração |

Princípio aplicado: **menor privilégio**, dando a cada pessoa só o acesso necessário.

## Políticas de segurança implementadas

Marque ✅ conforme for aplicando e anexe o print no PDF.

### Conta
- [ ] Autenticação em dois fatores (2FA) ativada
- [ ] Códigos de recuperação salvos fora do computador
- [ ] E-mail pessoal verificado e e-mail privado configurado nos commits
- [ ] Sessões e dispositivos revisados (Settings → Sessions)

### Repositório
- [ ] Visibilidade definida (público, por ser portfólio)
- [ ] Branch `main` protegida (Settings → Branches / Rules → exigir Pull Request)
- [ ] `SECURITY.md` criado com canal de reporte de vulnerabilidades
- [ ] `.gitignore` impedindo arquivos sensíveis
- [ ] Secret scanning e push protection ativos (Settings → Code security)
- [ ] Dependabot alerts ativo (Settings → Code security)
- [ ] `CODEOWNERS` definindo quem revisa

### Conteúdo
- [ ] Nenhum dado pessoal sensível (CPF, endereço, telefone) nos arquivos
- [ ] Nenhuma senha, token ou chave no histórico de commits
- [ ] Links externos revisados

## Verificação com o Gemini

Pedi ao Gemini que revisasse este checklist e apontasse lacunas. O resultado e os ajustes feitos estão em [05_Uso_do_Gemini.md](05_Uso_do_Gemini.md).

## Boas práticas adotadas

1. Commits pequenos e com mensagem descritiva.
2. Nunca versionar segredos; se acontecer, revogar o segredo imediatamente.
3. Revisar as permissões dos colaboradores periodicamente.
4. Manter o repositório documentado para facilitar auditoria.
