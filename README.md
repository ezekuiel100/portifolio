# Meus Sites 🚀

Página inicial (hub) que reúne links para todos os meus sites e projetos.

## Como editar

Abra o arquivo [`index.html`](index.html) e procure pela seção marcada com:

```html
<!-- EDITE AQUI: cada <a class="card"> é um site seu. -->
```

Cada site é um bloco como este:

```html
<a class="card" href="https://SEU-SITE.com" target="_blank" rel="noopener">
  <div class="icon">🌐</div>
  <h3>Nome do Site <span class="arrow">↗</span></h3>
  <p>Descrição curta do site.</p>
  <span class="tag">Categoria</span>
</a>
```

- **`href`** → o endereço do seu site
- **`icon`** → qualquer emoji
- **`h3`** → o nome (mantenha o `<span class="arrow">↗</span>`)
- **`p`** → descrição curta
- **`tag`** → categoria (Web, Jogo, App, Ferramenta...)

Copie um bloco para adicionar mais sites, ou apague os que não usar.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub. Para o site ficar em `https://SEU-USUARIO.github.io`, nomeie o repositório como **`SEU-USUARIO.github.io`**. (Qualquer outro nome também funciona — o endereço fica `https://SEU-USUARIO.github.io/nome-do-repo`.)

2. Envie os arquivos para o repositório:

   ```bash
   git init
   git add .
   git commit -m "Página inicial dos meus sites"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/SEU-REPO.git
   git push -u origin main
   ```

3. No GitHub, vá em **Settings → Pages**.
4. Em **Source**, selecione a branch **`main`** e a pasta **`/ (root)`**, depois clique em **Save**.
5. Aguarde 1–2 minutos. Seu site estará no ar no endereço mostrado nessa mesma página.

## Funcionalidades

- ✅ Design moderno e responsivo (funciona no celular)
- ✅ Botão de tema claro/escuro (lembra a sua preferência)
- ✅ Campo de busca para filtrar os sites
- ✅ Um único arquivo, sem dependências externas
