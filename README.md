# Extensões do Visual Studio Code (VSCode)

Este documento lista as extensões essenciais instaladas no VSCode, organizadas por categoria, e fornece instruções para exportar e importar essas extensões.

---

## **Extensões Instaladas**

### **Estilo e Temas**
- **Catppuccin for VSCode** (`catppuccin.catppuccin-vsc`): Tema de cores moderno e agradável visualmente.
- **Material Icon Theme** (`pkief.material-icon-theme`): Ícones temáticos para o explorador de arquivos.

### **Formatação e Linting**
- **Prettier** (`esbenp.prettier-vscode`): Formatador de código para JavaScript, TypeScript, HTML, CSS e outros.
- **ESLint** (`dbaeumer.vscode-eslint`): Linting para JavaScript e TypeScript.
- **Black Formatter** (`ms-python.black-formatter`): Formatador opinativo para Python.
- **isort** (`ms-python.isort`): Organiza imports em Python.

### **Produtividade**
- **Todo Tree** (`gruntfuggly.todo-tree`): Gerencia TODOs, FIXMEs e outros comentários no código.
- **Auto Import** (`steoates.autoimport`): Importação automática de módulos em JavaScript/TypeScript.
- **Codeium** (`codeium.codeium`): Ferramenta de autocompletar baseada em IA.
- **JavaScript (ES6) Code Snippets** (`xabikos.javascriptsnippets`): Snippets para JavaScript.
- **indent-rainbow** (`oderwat.indent-rainbow`): Coloriza indentações para melhorar a legibilidade.

### **Markdown**
- **Markdown All in One** (`yzhang.markdown-all-in-one`): Ferramentas para edição de Markdown.
- **Markdown Preview Enhanced** (`shd101wyy.markdown-preview-enhanced`): Visualização avançada de Markdown.

### **Python**
- **Python** (`ms-python.python`): Suporte à linguagem Python.
- **Pylance** (`ms-python.vscode-pylance`): Análise estática e autocompletar inteligente para Python.
- **debugpy** (`ms-python.debugpy`): Ferramenta de debugging para Python.
- **autoDocstring** (`njpwerner.autodocstring`): Gera docstrings automaticamente para Python.

### **Front-end (HTML/CSS/JavaScript)**
- **HTML CSS Support** (`ecmel.vscode-html-css`): Autocompletar para classes e IDs de CSS em arquivos HTML.
- **Live Server** (`ms-vscode.live-server`): Servidor local com recarga automática para desenvolvimento web.

### **Verificação Ortográfica**
- **Code Spell Checker** (`streetsidesoftware.code-spell-checker`): Verificação ortográfica no código.
- **Code Spell Checker (Português)** (`streetsidesoftware.code-spell-checker-portuguese-brazilian`): Dicionário em português.

### **Tailwind CSS**
- **Tailwind CSS IntelliSense** (`bradlc.vscode-tailwindcss`): Autocompletar para classes do Tailwind CSS.

---

## **Como Exportar e Importar Extensões**

### **Exportar Extensões**
Para exportar a lista de extensões instaladas, siga os passos abaixo:

1. Abra o terminal no VSCode (Ctrl + `).
2. Execute o seguinte comando:
   ```bash
   code --list-extensions > extensions.txt
   ```


settings:
```json
// Extensoes Requeridas
//
// Estilo e Temas
//    Catppuccin for VSCode - Tema de cores moderno
//    Material Icon Theme - Ícones temáticos para o explorador de arquivos
//
// Formatação e Linting
//    Prettier - Formatador de código para JavaScript, TypeScript, HTML, CSS
//    ESLint - Linting para JavaScript e TypeScript
//    Black Formatter - Formatador opinativo para Python
//    isort - Organiza imports em Python
//
// Produtividade
//    Todo Tree - Gerencia TODOs, FIXMEs e outros comentários
//    Auto Import - Importação automática de módulos em JavaScript/TypeScript
//    Codeium - Ferramenta de autocompletar baseada em IA
//    JavaScript (ES6) Code Snippets - Snippets para JavaScript
//    indent-rainbow - Coloriza indentações para melhorar a legibilidade
//
// Markdown
//    Markdown All in One - Ferramentas para edição de Markdown
//    Markdown Preview Enhanced - Visualização avançada de Markdown
//
// Python
//    Python - Suporte à linguagem Python
//    Pylance - Análise estática e autocompletar inteligente para Python
//    debugpy - Ferramenta de debugging para Python
//    autoDocstring - Gera docstrings automaticamente para Python
//
// Front-end (HTML/CSS/JavaScript)
//    HTML CSS Support - Autocompletar para classes e IDs de CSS em arquivos HTML
//    Live Server - Servidor local com recarga automática para desenvolvimento web
//    VS Code JavaScript (ES6) snippets - Snippets para JavaScript
//
// Verificação Ortográfica
//    Code Spell Checker - Verificação ortográfica no código
//    Code Spell Checker (Português) - Dicionário em português
//
// Tailwind CSS
//    Tailwind CSS IntelliSense - Autocompletar para classes do Tailwind CSS
//
// Configurações do editor abaixo...
{
  // General
  "json.schemaDownload.enable": true, // true -> habilita o download de schemas de json
  "update.mode": "manual", // manual -> desabilita as atualizações automáticas
  "update.showReleaseNotes": false, // false -> não mostra as notas de lançamento das atualizações
  "window.titleBarStyle": "native", // native -> usa a barra de título do sistema
  "window.commandCenter": false, // false -> desabilita o Command Palette
  "window.menuBarVisibility": "hidden", // hidden -> esconde a barra de menu
  "window.restoreWindows": "all", // all -> restaura todas as janelas
  "window.zoomLevel": 2, // 2 -> zoom do editor
  // Workbench
  "workbench.startupEditor": "newUntitledFile", // newUntitledFile -> abre um novo arquivo ao iniciar
  "workbench.list.smoothScrolling": true, // true -> ativa a rolagem suave
  "workbench.iconTheme": "material-icon-theme", // symbols -> usa o tema de ícones Symbols
  "workbench.editor.labelFormat": "short", // short -> usa o formato de rótulo curto
  "workbench.editor.empty.hint": "hidden", // hidden -> esconde a dica de arquivo vazio
  "workbench.editor.editorActionsLocation": "hidden", // default -> coloca as ações do editor no local padrão
  "workbench.activityBar.location": "hidden", // hidden -> esconde a barra de atividades
  "workbench.statusBar.visible": false, // false -> esconde a barra de status
  "workbench.layoutControl.enabled": false, // false -> desabilita o controle de layout
  "workbench.colorTheme": "Catppuccin Mocha",
  "workbench.sideBar.location": "right", // right -> coloca a barra lateral na direita
  // Editor
  "editor.lineNumbers": "on", // on -> exibe os números de linha
  "editor.fontSize": 14, // 14 -> tamanho da fonte do editor
  "editor.lineHeight": 1.8, // 1.8 -> altura da linha
  "editor.rulers": [
    80,
    120
  ], // 80, 120 -> exibe as réguas em 80 e 120 caracteres
  "editor.tabSize": 2, // 2 -> tamanho da tabulação
  "editor.wordWrap": "on", // on -> ativa a quebra de linha
  "editor.wordWrapColumn": 120, // 120 -> coluna de quebra de linha
  "editor.suggestSelection": "first", // first -> seleciona a primeira sugestão
  "editor.cursorSmoothCaretAnimation": "on", // on -> ativa a animação suave do cursor
  "editor.smoothScrolling": true, // true -> ativa a rolagem suave
  "editor.parameterHints.enabled": true, // true -> ativa as dicas de parâmetro
  "editor.fontFamily": "JetBrains Mono", // JetBrains Mono -> família da fonte
  "editor.fontLigatures": true, // true -> ativa as ligaduras de fonte
  "editor.acceptSuggestionOnCommitCharacter": true, // true -> aceita a sugestão ao digitar um caractere de confirmação
  "editor.accessibilitySupport": "off", // off -> desabilita o suporte à acessibilidade
  "editor.semanticHighlighting.enabled": true, // true -> ativa o destaque semântico
  "editor.inlineSuggest.enabled": true, // true -> ativa as sugestões inline
  "editor.hideCursorInOverviewRuler": false, // false -> exibe o cursor no resumo da régua
  "editor.minimap.enabled": false, // false -> desabilita o minimapa
  "editor.scrollbar.vertical": "auto", // auto -> exibe a barra de rolagem vertical automaticamente
  "editor.renderLineHighlight": "all", // all -> destaca a linha inteira
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  },
  "editor.quickSuggestions": { // configurações de sugestões rápidas
    "strings": "on"
  },
  "editor.codeActionsOnSave": { // ações de código ao salvar
    "source.fixAll.eslint": "explicit"
  },
  "editor.cursorSurroundingLines": 5,
  "editor.cursorSurroundingLinesStyle": "all",
  //"vsintellicode.modify.editor.suggestSelection": "choseToUpdateConfiguration", // choseToUpdateConfiguration -> escolhe atualizar a configuração
  //"github.copilot.editor.enableAutoCompletions": true,
  // Explorer
  "explorer.compactFolders": false, // false -> desabilita as pastas compactas
  "explorer.confirmDelete": false, // false -> desabilita a confirmação de exclusão
  "explorer.confirmDragAndDrop": false, // false -> desabilita a confirmação de arrastar e soltar
  "explorer.sortOrder": "foldersNestsFiles", // foldersNestsFiles -> ordena as pastas primeiro
  "explorer.fileNesting.enabled": true, // true -> ativa o aninhamento de arquivos
  "explorer.fileNesting.patterns": { // padrões de aninhamento de arquivos
    "package.json": ".eslint*, .prettier*, tsconfig*, vite*, pnpm-lock*, bun.lockb, nest*, .yarn*, yarn.lock",
    "tailwind.config.js": "tailwind.config*, postcss.config*",
    "next.config.js": "next*",
    ".env.local": ".env*",
    ".env": ".env*"
  },
  // Terminal
  "terminal.integrated.fontSize": 14, // 14 -> tamanho da fonte do terminal
  "terminal.integrated.fontFamily": "MesloLGS NF", // JetBrainsMono Nerd Font -> família da fonte do terminal
  "terminal.integrated.defaultProfile.windows": "Git Bash", // Git Bash -> perfil padrão do terminal
  "terminal.integrated.showExitAlert": false, // false -> desabilita o alerta de saída
  "terminal.integrated.cursorStyle": "block", // block -> estilo do cursor
  "terminal.integrated.cursorBlinking": true, // true -> ativa o piscar do cursor
  // Terminal configuration: tema de cores do terminal
  // Link com os temas: https://glitchbone.github.io/vscode-base16-term/#/paraiso
  "workbench.colorCustomizations": {
    "terminal.background": "#0B1C2C",
    "terminal.foreground": "#CBD6E2",
    "terminalCursor.background": "#CBD6E2",
    "terminalCursor.foreground": "#CBD6E2",
    "terminal.ansiBlack": "#0B1C2C",
    "terminal.ansiBlue": "#8B56BF",
    "terminal.ansiBrightBlack": "#627E99",
    "terminal.ansiBrightBlue": "#8B56BF",
    "terminal.ansiBrightCyan": "#568BBF",
    "terminal.ansiBrightGreen": "#56BF8B",
    "terminal.ansiBrightMagenta": "#BF568B",
    "terminal.ansiBrightRed": "#BF8B56",
    "terminal.ansiBrightWhite": "#F7F9FB",
    "terminal.ansiBrightYellow": "#8BBF56",
    "terminal.ansiCyan": "#568BBF",
    "terminal.ansiGreen": "#56BF8B",
    "terminal.ansiMagenta": "#BF568B",
    "terminal.ansiRed": "#BF8B56",
    "terminal.ansiWhite": "#CBD6E2",
    "terminal.ansiYellow": "#8BBF56"
  },
  // Security
  "security.promptForLocalFileProtocolHandling": false, // false -> desabilita a solicitação de manipulação de protocolo de arquivo local
  "security.workspace.trust.untrustedFiles": "newWindow", // newWindow -> abre arquivos não confiáveis em uma nova janela
  "security.workspace.trust.banner": "never", // never -> nunca exibe o banner de confiança do espaço de trabalho
  "security.workspace.trust.startupPrompt": "never", // never -> nunca exibe a solicitação de confiança do espaço de trabalho
  "security.workspace.trust.enabled": false, // false -> desabilita a confiança do espaço de trabalho
  // Files
  "files.insertFinalNewline": true, // true -> insere uma nova linha no final do arquivo
  "files.trimTrailingWhitespace": true, // true -> remove espaços em branco à direita
  "files.exclude": { // exclusões de arquivos
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/Thumbs.db": true,
    "**/.vscode": true,
    //"**/node_modules": true,
  },
  "files.associations": { // associações de arquivos
    ".env.*": "dotenv",
    ".prettierrc": "json",
    "*.css": "css",
    "*.scss": "scss",
    "*.sass": "sass",
    "*.html": "html",
    "*.md": "markdown",
    "*.yml": "yaml",
    "*.yaml": "yaml",
    "*.ts": "typescript",
    "*.tsx": "typescriptreact",
    "*.js": "javascript",
    "*.jsx": "javascriptreact",
    "*.json": "json",
    "*.py": "python",
    "*.sh": "shellscript",
    "*.bat": "bat",
    "*.ps1": "powershell"
  },
  "files.autoSave": "onFocusChange", // onFocusChange -> salva automaticamente ao perder o foco
  // Extensions settings
  //
  // Markdown
  "markdown-preview-enhanced.automaticallyShowPreviewOfMarkdownBeingEdited": true,
  "markdown-preview-enhanced.codeBlockTheme": "github-dark.css",
  "markdown-preview-enhanced.previewTheme": "github-dark.css",
  // AutoImport
  "autoimport.showNotifications": true, // true -> exibe notificações
  "autoimport.filesToScan": "**/*.{ts,tsx,js,jsx,py}", // arquivos para escanear
  "autoimport.autoComplete": true,
  // Git
  "git.autofetch": true, // true -> habilita o autofetch
  "git.confirmSync": false, // false -> desabilita a confirmação de sincronização
  "git.suggestSmartCommit": false, // false -> desabilita a sugestão de commit inteligente
  //Todo Tree
  "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^\\s*(-|\\d+.))\\s*($TAGS)",
  "todo-tree.highlights.customHighlight": {
    "TODO": {
      "icon": "check",
      "type": "line",
      "iconColour": "#ffe100b5",
      "foreground": "#fc0404",
      "background": "#ffe100"
    },
    "FIXME": {
      "icon": "beaker",
      "iconColour": "#fc0404",
      "foreground": "#ffffff",
      "background": "#fc0404"
    },
    "BUG": {
      "icon": "bug",
      "type": "line",
      "iconColour": "#fc0404",
      "foreground": "#ffffff",
      "background": "#fc0404"
    },
    "INFO": {
      "icon": "info",
      "iconColour": "#ffffff",
      "foreground": "#ffffff",
      "background": "#000000"
    },
    "NOTE": {
      "icon": "note",
      "iconColour": "#00ff00",
      "foreground": "#000000",
      "background": "#00ff00"
    },
    "HACK": {
      "foreground": "#ffffff",
      "background": "#ff00ff"
    },
    "REVIEW": {
      "icon": "eye",
      "iconColour": "#0000ff",
      "foreground": "#ffffff",
      "background": "#0000ff"
    },
    "[]": {
      "icon": "circle",
      "type": "line",
      "iconColour": "#ff0000", // Vermelho para tarefas pendentes
      "foreground": "#ff0000",
      "background": "#0000007b"
    },
    "[x]": {
      "icon": "check-circle",
      "type": "line",
      "iconColour": "#00ff00", // Verde para tarefas concluídas
      "foreground": "#00ff00",
      "background": "#0000007b"
    }
  },
  "todo-tree.general.tags": [
    "TODO",
    "FIXME",
    "BUG",
    "INFO",
    "NOTE",
    "HACK",
    "REVIEW",
    "[]",
    "[x]"
  ],
  // Prettier
  "editor.defaultFormatter": "esbenp.prettier-vscode", // esbenp.prettier-vscode -> formatador padrão
  "prettier.trailingComma": "all", // all -> adiciona vírgula no final
  "prettier.singleQuote": false, // false -> usa aspas duplas
  "prettier.jsxSingleQuote": false, // false -> usa aspas duplas no JSX
  "prettier.arrowParens": "always", // always -> adiciona parênteses em funções de seta
  "prettier.bracketSpacing": true, // true -> coloca espaçamento nas chaves
  "prettier.useTabs": false, // false -> usa espaços em vez de tabs
  // Language specific settings
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "graphql",
  ],
  "emmet.syntaxProfiles": {
    "javascript": "jsx",
    "typescript": "tsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.suggest.autoImports": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features",
    "editor.formatOnSave": true,
    "editor.tabSize": 2
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features",
    "editor.formatOnSave": true,
    "editor.tabSize": 2
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "editor.tabSize": 2,
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "editor.tabSize": 2,
  },
  "[markdown]": {
    "editor.defaultFormatter": "vscode.markdown-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "editor.tabSize": 2,
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features",
    "editor.formatOnSave": true,
    "editor.tabSize": 2
  },
  "[jinja]": {
    "editor.defaultFormatter": "vscode.html-language-features",
    "editor.formatOnSave": true,
    "editor.tabSize": 2
  },
  "[python]": {
    "diffEditor.ignoreTrimWhitespace": false,
    "editor.formatOnType": true,
    "editor.wordBasedSuggestions": "off",
    "editor.tabSize": 4,
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "ms-python.black-formatter",
    "editor.codeActionsOnSave": {
      "source.organizeImports": "explicit"
    }
  },
  // Vim settings
  // cspell checker
  "cSpell.language": "pt_BR, en-US",
  "cSpell.spellCheckOnlyWorkspaceFiles": true, // true -> verifica apenas os arquivos do espaço de trabalho
  "cSpell.enabledFileTypes": {
    "*": true,
    "markdown": false,
    "json": false,
    "yaml": false,
  },
  "cSpell.userWords": [
    "AGREGACAO",
    "Atualizacao",
    "autofetch",
    "autoimport",
    "BASEPATH",
    "basicos",
    "bmewburn",
    "bootcamp",
    "calendario",
    "Cascadia",
    "Catppuccin",
    "chakra",
    "checkin",
    "checkins",
    "clsx",
    "Codegen",
    "codigo",
    "combustivel",
    "conteudo",
    "criterio",
    "datadog",
    "Datetime",
    "dayjs",
    "desativacao",
    "descricao",
    "devolucao",
    "Devolucao",
    "Dexie",
    "disponivel",
    "Dotenv",
    "esbenp",
    "esbuild",
    "fastify",
    "Fastify",
    "feedbackwidget",
    "ffprobe",
    "fipe",
    "funcoes",
    "grafico",
    "graficos",
    "historico",
    "Hono",
    "intelephense",
    "IUGU",
    "jamjuree",
    "jdbc",
    "jupiter",
    "jupyter",
    "lclz",
    "liveblocks",
    "LIVEBLOCKS",
    "liveshare",
    "lockb",
    "manutencao",
    "middlewares",
    "mixpanel",
    "monaco",
    "movimentacao",
    "nestjs",
    "odometro",
    "omni",
    "Omni",
    "Onboarded",
    "pallas",
    "parametros",
    "permissao",
    "postgres",
    "postgresql",
    "prefetch",
    "preparacao",
    "previsao",
    "programfiles",
    "proximas",
    "reactflow",
    "reativacao",
    "rgba",
    "roboto",
    "rocketseat",
    "rotion",
    "rsxp",
    "Sandpack",
    "selecao",
    "Selecao",
    "sequelizerc",
    "shiki",
    "situacao",
    "situacoes",
    "skylab",
    "sqlite",
    "stylelintrc",
    "stylesheet",
    "supergraph",
    "svgr",
    "sympla",
    "Sysnative",
    "textblock",
    "tiptap",
    "trpc",
    "TRPC",
    "tsup",
    "unfollow",
    "Unfollow",
    "unform",
    "Unform",
    "unmark",
    "upsert",
    "usuario",
    "Usuario",
    "usuarios",
    "utilitarias",
    "utilizacao",
    "veiculos",
    "WEBPUSH",
    "windir"
  ],
  "markdown-preview-enhanced.revealjsTheme": "black.css",
}

```







