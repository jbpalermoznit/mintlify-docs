# ZNIT Simulador de Carbono — Documentação de Usuário

Documentação técnica do simulador, publicada via [Mintlify](https://mintlify.com).

App de produção: <https://simulador.znit.ai>

## Estrutura

```
.
├── docs.json              # config (cores, nav, branding)
├── logo.png               # logo no topbar
├── favicon.png            # favicon
├── introducao/
│   ├── bem-vindo.mdx
│   └── primeiros-passos.mdx
├── fluxo/
│   ├── importar-curva-abc.mdx
│   ├── entendendo-itens.mdx
│   ├── editar-fator.mdx
│   └── cenarios.mdx
├── analise/
│   └── visao-geral.mdx
└── referencia/
    └── glossario.mdx
```

## Desenvolvimento local

```bash
npm install -g mintlify
mintlify dev
# abre em http://localhost:3000
```

Hot-reload automático nos `.mdx`.

## Deploy

O Mintlify reconstrói a cada push neste repositório. Para a configuração inicial:

1. Acesse <https://dashboard.mintlify.com>
2. **Add deployment** → conecte este repositório
3. Defina **Production Branch**: `main`
4. (Opcional) Custom domain `docs.simulador.znit.ai` em **Settings → Domain**

## Convenções

- **PT-BR neutro profissional.** Você, sua. Sem gírias.
- Componentes Mintlify para realçar fluxo: `<Steps>`, `<Tabs>`, `<Cards>`,
  `<Note>`, `<Tip>`, `<Warning>`, `<Accordion>`.
- Imagens em `images/` (PNG, ideal ≤ 1 MB).
- Para detalhes técnicos do código-fonte da aplicação, ver o repo
  [`jbpalermoznit/ZNIT-SIMULADOR-CARBONO`](https://github.com/jbpalermoznit/ZNIT-SIMULADOR-CARBONO).

## Pendências

- [ ] Screenshots reais (substituir referências textuais)
- [ ] Página de Relatórios/Exportações quando o PDF do memorando estiver pronto
- [ ] Vídeo demo curto (1-2 min)
- [ ] Versão em inglês para clientes fora do Brasil
