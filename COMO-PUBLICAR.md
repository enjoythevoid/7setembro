# Como publicar — Itanhaém

Repositório já criado: **enjoythevoid/7setembro** ✓
O `editar.html` já vem configurado com esse nome — não precisa editar mais nada nele.

## 1. Subir os arquivos
1. Extrai o zip no computador (vai virar uma pasta `site`).
2. No repositório no GitHub (**github.com/enjoythevoid/7setembro**), clica em **Add file → Upload files**.
3. Abre a pasta `site` extraída e arrasta **o conteúdo de dentro dela** pra tela do GitHub — ou seja, `index.html`, `editar.html`, `style.css`, a pasta `data`, a pasta `assets` e `COMO-PUBLICAR.md` soltos, **não a pasta `site` inteira**. Eles precisam ficar na raiz do repositório, senão os links quebram.
4. Rola pra baixo e clica **Commit changes**.
5. O arquivo `.nojekyll` é oculto (começa com ponto) e pode não ir junto no arrastar-e-soltar. Depois do commit, confere se ele apareceu na lista de arquivos do repositório; se não apareceu, clica **Add file → Create new file**, digita `.nojekyll` como nome (deixa o conteúdo vazio) e commita.

## 2. Ativar o GitHub Pages
1. No repositório: **Settings → Pages**.
2. Em "Source", escolhe **Deploy from a branch**, branch **main**, pasta **/ (root)**.
3. Salva. Em 1–2 minutos o site fica em:
   **https://enjoythevoid.github.io/7setembro/**
   - Repositório público → qualquer um com o link acessa, sem precisar logar no GitHub.

## 3. Gerar o token pra sua namorada
1. Vai em **github.com/settings/tokens?type=beta**.
2. **Generate new token**.
3. Em "Repository access" → **Only select repositories** → escolhe `7setembro`.
4. Em "Permissions" → **Contents** → muda pra **Read and write**.
5. Gera e **copia o token** (só aparece uma vez).
6. Manda esse token pra ela por mensagem privada, junto com o link:
   **https://enjoythevoid.github.io/7setembro/editar.html**
7. Na primeira vez que ela abrir, vai pedir o token — ela cola uma vez e fica salvo só no celular dela.

## Link pra todo mundo ver
**https://enjoythevoid.github.io/7setembro/**

## Observações
- As fotos e os textos de Dados/Carro/Caminho/Gastos/Preferências são fixos no `index.html` — pra mudar algo ali, edita o HTML direto e sobe de novo (Add file → Upload files, substitui o arquivo).
- Só a **Lista de compras** é dinâmica (lida de `data/compras.json`), porque é a única parte que ela edita pelo celular.
