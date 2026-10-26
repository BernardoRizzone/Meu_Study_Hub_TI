# 4 · Testes e Lançamento

## Checklist de testes

| Teste | Como verificar | Resultado |
|-------|----------------|-----------|
| Site abre no link do Pages | Abrir em aba anônima | ☐ |
| Todos os links internos funcionam | Clicar em cada cartão do `index.html` | ☐ |
| Links externos (GitHub, LinkedIn, YouTube) | Clicar em cada um | ☐ |
| Layout no celular | Abrir no celular ou usar F12 → modo dispositivo | ☐ |
| READMEs renderizam corretamente | Abrir cada pasta no GitHub | ☐ |
| Nenhum texto de exemplo restante | Buscar `SEU-`, `[SEU` e `Escreva aqui` | ☐ |
| Sem dados sensíveis | Revisar arquivos e histórico | ☐ |
| Proteção de branch funcionando | Tentar push direto na `main` e ver o bloqueio | ☐ |
| Deploy concluído | Aba Actions com check verde | ☐ |

## Preparo para produção

- [ ] Todos os itens do checklist de segurança concluídos
- [ ] Todos os testes acima com resultado ✅
- [ ] Release **v2.0** criada em Releases com notas da versão
- [ ] Link do site divulgado no LinkedIn

## Lançamento

1. Merge final na `main`.
2. Criar a release: **Releases → Draft a new release → tag `v2.0`**.
3. Conferir o site em produção.
4. Atualizar o LinkedIn com o link.
