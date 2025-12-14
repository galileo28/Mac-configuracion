# ==========================================
# 🍺 BREWFILE MAESTRO - Configuración Mac
# ==========================================

tap "homebrew/services" # Permite correr bases de datos (MySQL) en segundo plano

# ------------------------------------------
# 🚀 HERRAMIENTAS MODERNAS (Superpoderes CLI)
# ------------------------------------------
brew "bat"          # Un 'cat' mejorado: con colores y números de línea
brew "eza"          # Un 'ls' moderno: con iconos, colores y mejor formato
brew "zoxide"       # Un 'cd' inteligente: aprende tus carpetas más usadas
brew "ripgrep"      # Buscador de texto ultrarrápido (reemplaza a grep)
brew "fd"           # Buscador de archivos rápido y amigable (reemplaza a find)
brew "lazygit"      # Interfaz gráfica increíble para Git dentro de la terminal
brew "thefuck"      # Corrige tus errores de comandos automáticamente
brew "btop"         # Monitor de sistema visual (CPU, RAM, Red)
brew "tldr"         # Manuales de comandos simplificados con ejemplos
brew "fastfetch"    # Muestra información del sistema y el logo (estético)
brew "fzf"          # Buscador difuso (Ctrl+R para historial)

# ------------------------------------------
# 🛠 HERRAMIENTAS ESENCIALES
# ------------------------------------------
brew "git"
brew "wget"         # Descargar archivos de internet
brew "tree"         # Ver estructura de carpetas en árbol
brew "vim"
brew "jq"           # Procesar y leer archivos JSON
brew "cmake"        # Compilador necesario para muchas herramientas
brew "mysql", restart_service: :changed

# ------------------------------------------
# 🐍 LENGUAJES DE PROGRAMACIÓN
# ------------------------------------------
brew "go"
brew "python@3.12"
brew "pipx"         # Para instalar aplicaciones Python aisladas

# ------------------------------------------
# 🖥 APLICACIONES DE ESCRITORIO (CASKS)
# ------------------------------------------
cask "visual-studio-code"
cask "discord"
cask "font-fira-code-nerd-font" # Fuente recomendada para ver los iconos en terminal

# ------------------------------------------
# 🆚 VS CODE EXTENSIONS (Limpias y Organizadas)
# ------------------------------------------

# >> Estética e Iconos
vscode "pkief.material-icon-theme"
vscode "zhuangtongfa.material-theme"
vscode "naumovs.color-highlight"
vscode "usernamehw.errorlens"  # Muestra el error en la misma línea de código

# >> Inteligencia Artificial
vscode "github.copilot"
vscode "github.copilot-chat"

# >> Web (HTML/CSS/JS/React)
vscode "esbenp.prettier-vscode"
vscode "dbaeumer.vscode-eslint"
vscode "dsznajder.es7-react-js-snippets"
vscode "bradlc.vscode-tailwindcss"
vscode "ritwickdey.liveserver"
vscode "formulahendry.auto-close-tag"
vscode "formulahendry.auto-rename-tag"

# >> Backend & Data
vscode "rangav.vscode-thunder-client"    # Cliente API (Tipo Postman)
vscode "cweijan.vscode-mysql-client2"    # El mejor cliente de Bases de Datos

# >> Python
vscode "ms-python.python"
vscode "ms-python.vscode-pylance"
vscode "ms-toolsai.jupyter"              # Notebooks

# >> Otros Lenguajes (.NET / Docker / C++)
vscode "ms-dotnettools.csharp"
vscode "ms-azuretools.vscode-docker"
vscode "ms-vscode.cpptools-extension-pack"

# >> Utilidades
vscode "ms-vscode-remote.vscode-remote-extensionpack" # SSH y WSL
vscode "formulahendry.code-runner"
vscode "streetsidesoftware.code-spell-checker"
vscode "streetsidesoftware.code-spell-checker-spanish"
vscode "ms-ceintl.vscode-language-pack-es"