# Sistema Dinho Autopeças

Site de apresentação e demonstração interativa de um sistema de gestão (ERP) para lojas de autopeças. A página mostra como o sistema organiza o dia a dia da loja, do balcão ao financeiro, e inclui uma demo navegável com dados fictícios.

![Tela de produtos e estoque](public/images/estoque-demo.png)

## O que o sistema cobre

- **Produtos e estoque:** busca por referência, aplicação e prateleira, com saldo e preço no mesmo lugar
- **Vendas:** a venda confirmada movimenta o estoque e alimenta o financeiro automaticamente
- **Frente de caixa:** controle de abertura de caixa e recebimentos
- **Financeiro:** contas a pagar e a receber e visão geral da operação
- **Perfis de acesso:** telas específicas para gestão, vendas, caixa e cadastro

![Tela do financeiro](public/images/financeiro-demo.png)

## Tecnologias

- React 19 e TypeScript
- Tailwind CSS e componentes shadcn/ui
- Vite com deploy em Cloudflare Workers
- Demo estática em HTML, CSS e JavaScript (`public/demo`)

## Como executar

Requisitos: Node.js 22.13 ou superior e pnpm.

```bash
git clone https://github.com/oLucas-Passos/sistema-dinho-autopecas.git
cd sistema-dinho-autopecas
pnpm install
pnpm dev
```

## Estrutura

```
app/            página principal e layout
components/ui/  componentes de interface reutilizáveis
public/demo/    demonstração interativa do sistema
public/images/  capturas de tela usadas no site
```

## Autor

Lucas Passos · [GitHub](https://github.com/oLucas-Passos)
