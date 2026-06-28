# ProjetoControl® — Landing Page

Site de vendas do **ProjetoControl®**, software de gestão de projetos industriais.

🌐 **Site:** [www.projetocontrol.com.br](https://www.projetocontrol.com.br)

---

## Estrutura

```
landing-page/
├── index.html   # Página única (HTML + CSS + JS inline)
├── CNAME        # Domínio customizado para GitHub Pages
└── README.md    # Este arquivo
```

## Tecnologia

- HTML5 + CSS3 + JS vanilla — sem dependências externas
- Bilíngue PT-BR / EN com toggle na navbar
- Responsivo: desktop, tablet e mobile (hamburger menu)
- Hospedagem: GitHub Pages com domínio customizado

## Como atualizar o site

1. Edite o `index.html`
2. No repositório do GitHub, abra o arquivo → clique no ✏️ (lápis)
3. Cole o conteúdo atualizado → **Commit changes**
4. O site atualiza automaticamente em ~1 minuto

## Configuração de DNS (Registro.br)

Para apontar `www.projetocontrol.com.br` para o GitHub Pages, adicione no Registro.br:

| Tipo  | Nome | Valor                        |
|-------|------|------------------------------|
| CNAME | www  | `seuusuario.github.io`       |

> Substitua `seuusuario` pelo seu usuário do GitHub.

Para o domínio raiz (`projetocontrol.com.br` sem www), adicione também:

| Tipo | Nome | Valor           |
|------|------|-----------------|
| A    | @    | 185.199.108.153 |
| A    | @    | 185.199.109.153 |
| A    | @    | 185.199.110.153 |
| A    | @    | 185.199.111.153 |

O certificado HTTPS é gerado automaticamente pelo GitHub após ~24h.

## Planos / Preços

| Plano        | Preço        | Projetos    |
|--------------|--------------|-------------|
| Free         | R$ 0         | 1 projeto   |
| Professional | R$ 497 único | Ilimitados  |
| Enterprise   | R$ 997 único | Ilimitados  |

## Contato

📧 contato@projetocontrol.com.br
