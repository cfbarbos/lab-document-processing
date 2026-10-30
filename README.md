# Lab 3 — Classificar documentos e extrair dados com um Agentic Workflow

Guia passo a passo para os alunos criarem, no IBM watsonx Orchestrate, um agente que chama um
agentic workflow para classificar documentos (contrato ou fatura) e extrair seus campos principais.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie todos os arquivos desta pasta para a branch `main`.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Source: Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em 1 a 2 minutos o site fica disponível em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.

## Estrutura

```
index.html      # o Lab completo (uma página)
images/         # 46 capturas de tela usadas nos passos
files/          # documentos de teste para upload no lab (dados fictícios)
  Contract.pdf  # contrato de demonstração
  Invoice.pdf   # fatura de demonstração
.nojekyll       # publica os arquivos como estão, sem processamento Jekyll
```

> Os documentos em `files/` são **fictícios**, criados exclusivamente para fins de demonstração.
> Nunca substitua por contratos ou faturas reais neste repositório público.
