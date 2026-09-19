# Ygor Automações — Site

Site institucional de uma página (one-page) para a **Ygor Automações**, negócio de automação de atendimento no WhatsApp, bots, catálogos digitais, sistemas sob medida e criação de sites para comércios locais e prestadores de serviço em Contagem, Belo Horizonte e região.

🔗 **Site no ar:** _adicione aqui o link assim que publicar no GitHub Pages ou domínio próprio_

## Sobre o projeto

Site estático de uma página só, sem build step e sem dependências externas além de fontes do Google Fonts. Pensado para:

- Carregar rápido
- Ser fácil de editar (HTML + CSS puro, tudo em um arquivo)
- Já vir com SEO básico configurado (título, meta descrição, dados estruturados)

## Estrutura

```
.
├── index.html   # site completo (HTML + CSS + dados estruturados)
└── README.md
```

## Como editar

Todo o conteúdo está em `index.html`. Não precisa de nenhuma ferramenta especial — basta abrir em qualquer editor de texto (VS Code, Sublime, Notepad++, etc).

Principais pontos de edição:

| O que mudar | Onde procurar no arquivo |
|---|---|
| Textos e títulos | Dentro das tags `<h1>`, `<h2>`, `<p>` de cada seção |
| Número de WhatsApp | Buscar por `5538997284600` e substituir em todos os lugares |
| Serviços oferecidos | Seção `id="servicos"`, dentro de `<div class="grid">` |
| Perguntas frequentes | Seção `id="faq"`, dentro de `<div class="faq-list">` |
| Cores do site | Bloco `:root { ... }` no início do `<style>` |
| Título da aba e SEO | Tags `<title>` e `<meta name="description">` no `<head>` |

## Como testar localmente

Não precisa de servidor nem instalação. Basta abrir o arquivo `index.html` direto no navegador (duplo clique ou arrastar para o Chrome).

## Como publicar no GitHub Pages

1. Suba este repositório no GitHub (se ainda não estiver lá)
2. Vá em **Settings → Pages**
3. Em **Branch**, selecione `main` e a pasta `/ (root)`, depois clique em **Save**
4. Em alguns minutos o site estará disponível em:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO`

### Conectando um domínio próprio

Depois de registrar um domínio (ex: `ygorautomacoes.com.br`):

1. Em **Settings → Pages → Custom domain**, digite o domínio
2. No painel do seu provedor de domínio (ex: registro.br), configure os registros DNS conforme a [documentação oficial do GitHub Pages](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site)
3. Atualize o link do site no Perfil da Empresa do Google para o novo domínio

## SEO já incluído

- Título e meta descrição otimizados para as palavras-chave do negócio
- Dados estruturados (Schema.org `LocalBusiness`) no `<head>`, ajudando o Google a entender nome, telefone e área de atendimento
- Estrutura semântica com `<h1>`, `<h2>`, `<section>` bem definidos

Depois de publicar com domínio próprio, cadastre o site no [Google Search Console](https://search.google.com/search-console) para acelerar a indexação.

## Licença

Uso livre para fins do próprio negócio Ygor Automações.
