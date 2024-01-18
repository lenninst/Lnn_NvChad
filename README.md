# Mi configuracion de nvchad 
Este repositorio contiene la configuración de nvchad para facilitar el desarrollo en Flutter (Mi configuracion personal). nvchad es una potente configuración de Neovim que proporciona una experiencia de programación eficiente y personalizable.

## Captura 

![nvchad para Flutter](capturas/democaptura.png)
![nvchad para Flutter](vimChad.png)
## Contenido adicional
- 👌 Configuración para Flutter
- 👍 Autoguardado
- 🍿 Autocompletado Github copilot
- 🤖 (opcional) Github CopilotChat 
- 🖥️ Tema tokyonight
- 😶‍🌫️ LunarVim color Schemes
- 🫡 LspSaga 
- 🤐 Pretty Folding
- 🙂 Varios atajos inspirados en LunarVim
-Entre otros... 🥲🥲
## Installacion para windows
Por ahora aun no he probado en otros sistemas mas que con Windows (en mi caso Windows 11) pero asumo que cualquier version de windows superior a 7 con 64bit no tendra problemas.. 🥲.
Opté por usar Chocolatey para instalar algunos complementeos externos ademas me parece la manera mas facil de instalar todo en fin.
Para ejecutar los siguiente comandos necesitas abrir un powershell en modo administrador + paciencia mucha paciencia.
1. Instala gestor de paquetes `Chocolatey`
```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
2. Instala NeoVim
```bash
choco install neovim --pre 
```
3. Instalar mingw
```bash
choco install mingw
```
4. Instala gnuwin32
```bash
choco install gnuwin32-coreutils.install
```
5. Instalacion Nvchad
En esta parte puedes optar por installar nvchad y luego copiar las configuraciones (recomendado)
```bash
git clone https://github.com/NvChad/NvChad $HOME\AppData\Local\nvim --depth 1 && nvim
```
O puedes clonar directamente mi configuracion personal
```bash
git clone https://github.com/lenninst/NvChad_Flutter $HOME\AppData\Local\nvim --depth 1 && nvim
```
7. Configura tu terminal recuerda usar nerd fonts "necesario"
   Si usas alacrity puedes copiar una configuracion personal mia aqui https://github.com/lenninst/Alacritty_myConfig.git.
9. Ejecuta el comando `nvim` en el terminal y espera o puedes tomar otra taza de cafe mientras tanto.
10. Has llegado el final

> [!NOTE]
> Estos pasos estan muy resumidos de modo que si encuentran problemas no duden en preguntar a nuestro amistoso asistente chatgpt o buscar en google 🫡, ademas asoy nuuevo en esto, cualquier correcion o sugerencia es bienvenido.

Ademas es necesario installar flutter y agregar la variable de entorno.
Puedes instalar siguiendo los pasos de instalacion proporcionada por Flutter en el siguiente enlace https://docs.flutter.dev/get-started/install/windows/desktop?tab=download
O Es posible usar el gestior de paquetes para instalarlo
```bash
choco install flutter
```
👌
## Agradecimientos
Para todo el grupo que esta detras de
- NvChad  💚 https://nvchad.com/
- LunarVim 💜 https://www.lunarvim.org/es/
- Neovim 🤎 https://neovim.io/
- Chocolatey 🩵 https://chocolatey.org/
  
Y los autores de los ingredientes 🧡
- https://nvimdev.github.io/lspsaga/
- https://github.com/codota/tabnine-nvim
- https://github.com/zbirenbaum/copilot.lua
- https://github.com/pocco81/auto-save.nvim
- entre otros que en este momento no recuerdo.🙏




