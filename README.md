# Moodle Theme Base

Base de projeto para gerar um arquivo CSS de tema Moodle usando Stylus.

## Objetivo

- Gerar `dist/theme.css` a partir de um conjunto de arquivos `.styl`.
- Manter a paleta e estilo do projeto atual.
- Permitir que o conteúdo textual seja adicionado por outras pessoas separadamente.

## Uso

1. Instale dependências:
   ```bash
   npm install
   ```
2. Gere o CSS:
   ```bash
   npm run build
   ```
3. O arquivo compilado ficará em `dist/theme.css`.

## Suporte Astro

Astro dá suporte a Stylus quando o pacote `stylus` está instalado. Você pode usar arquivos `.styl` diretamente em componentes Astro ou com o plugin apropriado do Vite.
