# 2 Anos de Nós 💙

Site em um único arquivo (`index.html`): quiz, jogo da memória, jogo de plataforma, caça-palavras, raspadinha e livro virtual. Sem dependências e sem build.

## Subir no GitHub
1. Crie um repositório novo em github.com/new (pode ser privado).
2. Clique em **uploading an existing file** e envie `index.html`, `vercel.json` e `README.md`.
3. Clique em **Commit changes**.

Pelo terminal:
```bash
git init && git add . && git commit -m "primeira versão"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
git push -u origin main
```

## Publicar na Vercel
1. Entre em vercel.com/new e escolha **Import** no repositório.
2. Em **Framework Preset** deixe **Other**. Não precisa de build command.
3. Clique em **Deploy**. Cada novo commit publica de novo automaticamente.

Observação: a página tem `noindex`, então o Google não lista o site.
