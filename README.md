<p align="center">
<img src="https://github.com/wolandark/wim/blob/main/img/wim-logo-transp.png" width=60%>
</p>

# Wim

This is a Vim configuration that gets you a similar experience as a full-featured IDE. Its made from the ground up from the vanilla Vim with the help of plugins and .vimrc configurations. You will never have to wait for an IDE to launch
# Dependencies
- Vim 8+ up to latest (Tested and also works on vim 7)
- [vimplug](https://github.com/junegunn/vim-plug) (Will be installed automatically as of version 2. Unix and Linux Only! for windows you must use the windows curl command of vimplug)
- nodejs and npm (For coc completion. Unneeded if you want another completion engine like YCM)
- xsel (An xorg utility that is ESSENTIAL for shared clipboard)
- FZF 
- Figlet (For the start menu ascii art, unneeded if you dont care for the ascii art)
- A Nerd Font (ESSENTIAL for icons in the nerdtree)

<h1> Some of the features</h1>

- Out of the box plugin installation <br>
- Tab Completion and snippets for fast coding <br>
- Fixed shared clipboard with desktop and other other apps<br>
- Easy tab and split navigation <br>
- Complete Markdown and HTML-CSS-JS support with live servers for both of them <br>
- Start Screen with bookmarks and file history <br>
- Beautiful built in colorschemes
- Easy syntax and alignment with Beautify option  <br>
- Nerdtree-like configuration of Netrw <br>
- Three options for statusline.Vim's customized statusline, Lighline and hackline. The choice is yours! <br>
  - Choices! It is all about choices <br>
- Customizability! It is lightweight and extensible without having to learn a whole new software or language  <br>

<h1>Usage / Installation </h1>

Windows users must delete the statement that auto installs vimplug at the beggining of the vimrc and proceed with the manual installation of vimplug, then launch vim with the new vimrc so that the plugins can be installed. Naturally you must use another editor to alter the vimrc. <br>

Watch how its installed on [Vimeo](https://vimeo.com/726201897) or [Youtube](https://www.youtube.com/watch?v=iZREwWViH6o) <br>
Watch me go through every feature and the entire .vimrc file [here](https://www.youtube.com/watch?v=-8TTb4tf8uE)
- As of version 2, once you start vim with my .vimrc. vimplug and plugins will be installed automatically. Don't panic and let it work <br>
- Refer to the release page for easy download. Remember to rename the file to .vimrc<br>
- Place the .vimrc file in your home directory<br>
- You can rename your already existing .vimrc or move it to another directory. this way; you can always bring it back if you dont like Wim<br>
- Place the provided nerd fonts in your fonts folder and run fc-cache<br>
- Select the nerd font in your terminals font settings (only for icons if you want to use Netrw you can skip this) <br>

- Refer to the [list](https://github.com/neoclide/coc.nvim/wiki/Language-servers) of autocompletion languages and add the ones you'd like with 

- <code> :CocInstall </code><br>
  	- Example: <code>:CocInstall coc-css</code> <br>
  
- Once the downloads are finished you can start using Vim normally<br>
- Leader key is naturally space<br>
- Press space h to view a list of leader key bindings<br>
<h4>Optional Dependencies </h4>

- Ranger. See [mine](https://github.com/wolandark/ranger) <br>
- Vifm<br>

<h4> Notice </h4>

- It was tested on multiple devices and distros with Vim from the terminal on linux and Gvim on Arch and Windows and it works perfectly. If anyone happens to use this on OSX please provide me with your feedback.<br>
- Please keep in mind that in case your terminal emulator takes charge of some of your keys, its up to you to figure it out. Some terminals do hold unto your Ctrl or Alt or shift key for their own functions
- You can review the list of plugins and comment out or delete the lines about the ones you dont want. This must be done before running <code>:PlugInstall</code>
  - If you want to delete any plugins later, delete the lines about them and run: <code>:PlugClean</code>

# Keymappings (Always up to date)

<h4>leader is space</h4>

|Keys              |Function               |
| --               | --                    |
| leader n         | NERDTree              |
| leader v         | Vifm Floating         |
| leader r         | Ranger Floating       |
| leader e         | Netrw On The Left Side |
| leader t         | Terminal              |
| leader i          |  Pop Start Menu   |
| leader T         | NewTab                |
| leader d         | Duplicate Cleaner     |
| leader m         | File History          |
| leader cc        | Comment Out           |
| leader 1-9       | Go To Tab             |
| leader tm        | Move Tab              |
| leader x         | Close Tab             |
| leader c         | Fuzzy Colorschemes    |
| leader b         | Fuzzy Buffers         |
| leader s         | Fuzzy File Search     |
| leader W         | Fuzzy Windows         |
| leader H         | Fuzzy History         |
| leader M         | Fuzzy Mappings        |
| leader w         | Quick Save w!         |
| leader op        | Source Current File   |
| leader z          | Fix Spelling For 1 word |
| leader l          | Fix Spelling On 1 Line |
| Alt Arrows       | Go Tabs Right Or Left |
| Shift Arrows     | Resize Splits         |
| Ctrl hjkl/Arrows | Focus Between Splits  |
| F2               | Start Live Webserver  |
| F3               | Reload Live Webserver |
| F4               | Stop Live Webserver   |
| F6               | SpellCheck            |
| F8               | Markdown Live Server  |
| END              | Trigger Snippets       |
|Ctrl j k          | Move Within Triggered Snippet |
|Ctrl PGDNN        | List Available Snippets  |
|V mode c-p | Copies To Shared Clipboard |
|V mode c-v | Pastes From Shared Clipboard | 

Start menu and auto NERDTree with Icons 
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/wim%20start.png">
Customized Nerdtree-like Netrw
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/wimnetrw.png">
Great Completion Support
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/comp.png">
Keymappings Help Menu
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/helpmenu.png">
Fuzzy File History Floating Menu
<img src="https://github.com/wolandark/wim/blob/main/img/vim5.png">
Default Gruvbox Theme
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/default.png">
Dracula Theme
<img src="https://github.com/wolandark/wim/blob/main/img/wim3.png">
Oceanic Theme
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/wimocean.png">
Nord Theme
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/wimnord.png">
Command History Floating Menu
<img src="https://github.com/wolandark/wim/blob/main/img/wim6.png">
Floating Filemanagment with Vifm
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/wimvifm.png">
Floating Terminal
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/floterm.png">
Great Support For Gvim on Windows
<img src="https://github.com/wolandark/wim/blob/main/img/Ver2/Screenshot%20(1).png">

<h1>FAQ</h1>

<h5> Whats with the name?</h5>
Woland's Vim = Wim. Get it?

<h5>leader h works but colors are odd</h5>
Delete lines 827-829 of vimrc to make whichkey follow your colorscheme <br>
<h5> What features does Wim offer? </h5>

- Fixed shared clipboard with desktop and other other apps<br>
- Customizability! It is lightweight and extensible without having to learn a whole new software  <br>
- Easy tab and split navigation <br>
- Complete Markdown and HTML-CSS-JS with live servers for both of them <br>
- Start Screen with bookmarks and file history <br>
- Beautiful built in colorschemes
- Easy syntax check and debugging <br>
- Three options for status bar. Lighline, Vim statusline and hackline. The choice is yours! <br>
  - Choices! It is all about choices <br>

<h5> Can I expect support? </h5>
Yes! Just ask and I will answer. When asking however, provide proper information so that I can help you <br>

<h5> Why didn't you use Neovim like everyone else? </h5>
Because Vim is the one I use and frankly Vim is fine.

<h5> Will you make custom vimrc configuratons? </h5>

[Contact me](https://t.me/inlovewithapenguin)

<h5> Are you open to collaborations? </h5>

[Contact me](https://t.me/inlovewithapenguin)

<h5>But vimplug is installed with curl!</h5>

Yes! and it does only one thing, adding an easier integration for installing plugins. <br>

