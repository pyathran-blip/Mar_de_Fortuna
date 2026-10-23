# Mar de Fortuna

**Mar de Fortuna v4** é um jogo HTML5 de pesca. O jogo pode ser executado no navegador e está sendo preparado também como aplicativo Android (APK).

## 🎮 Jogar online

https://pyathran-blip.github.io/Mar_de_Fortuna/

## ▶️ Jogar no computador

1. Baixe o repositório pelo botão **Code → Download ZIP**.
2. Extraia o ZIP.
3. Abra o arquivo `index.html` em um navegador moderno.

## 📱 APK para Android

O projeto inclui uma estrutura Android baseada em WebView para executar o jogo localmente.

- **Estado do APK:** a compilação automática está em andamento/validação. Não há ainda um APK publicado como versão oficial nesta página.
- **Acompanhar a compilação:** https://github.com/pyathran-blip/Mar_de_Fortuna/actions
- Quando uma compilação terminar com sucesso, abra a execução mais recente, desça até **Artifacts** e baixe `Mar-de-Fortuna-APK`.
- O artefato de teste do GitHub Actions fica disponível por tempo limitado; uma versão permanente será publicada em **Releases** após a validação.

## 📁 Arquivos principais

- `index.html` — jogo HTML5 (HTML, CSS e JavaScript).
- `app/` — projeto Android que carrega o jogo em uma WebView.
- `.github/workflows/main.yml` — automação de compilação do APK.

## 🛠️ Compilação automática

O GitHub Actions tenta compilar uma versão Android de teste quando há alterações na branch `main). O APK só deve ser considerado disponível quando a execução estiver verde e o artefato aparecer na execução.

## 🔗 Repositório

https://github.com/pyathran-blip/Mar_de_Fortuna
