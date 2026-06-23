# CodeStudy Pro Desktop PC

Versão limpa apenas para PC.

## O que foi removido

- Arquivos de Android/APK.
- Capacitor.
- Pasta `www`.
- Workflow de APK.
- README antigo de celular.
- Duplicatas mobile.

## O que ficou

- `app/index.html` — app desktop.
- `index-pc-browser.html` — versão para abrir no navegador.
- `main.js` — inicialização Electron.
- `package.json` — dependências e scripts Electron.
- `.github/workflows/build-windows.yml` — gera `.exe` no GitHub Actions.
- `README-PC.md` — instruções da versão PC.

## O que foi mantido no app

- 71 aulas.
- Java, HTML, CSS, JavaScript, Apex e Backend.
- IA contextual por aula.
- Tirar dúvidas.
- Explicar aula.
- Gerar desafios personalizados.
- Corrigir código.
- XP.
- Níveis.
- Metas.
- Revisão espaçada.
- Projetos guiados.
- Exercícios.
- Progresso salvo localmente.

## Como testar sem instalar

Abra:

```txt
index-pc-browser.html
```

## Como rodar como app no PC

Instale Node.js e rode:

```bash
npm install
npm start
```

## Como gerar EXE no GitHub

1. Crie um repositório novo.
2. Envie os arquivos extraídos.
3. Vá em Actions.
4. Rode `Build Windows EXE`.
5. Baixe o `.exe` em Artifacts.

## Observação sobre IA

A IA depende da API Key NVIDIA, internet e modelo disponível.
