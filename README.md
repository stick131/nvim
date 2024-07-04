# Установка
1. Копируем репозиторий в папку .config
```git clone https://github.com/stick131/my-vim.git```
2. Пермеменовываем папку в nvim
   ```mv my-vim nvim```
3. Качаем vim-plub
   ```sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'```
4. Заходи в init.vim и пишем в командном режиме `:PlugInstall`
5. Устанавливаем nodejs, npm, exuberant-ctags, pytthon3
   ```sudo pat install nodejs
      sudo apt install exuberant-ctags
      sudo apt install pytthon3
      sudo apt install yarn
      sudo apt install python3-pip
      
   ```
6. Устанавливаем автоподсказки
   ```:CocInstall coc-emmet
   :CocInstall coc-css
   :CocInstall coc-cssmodules
   :CocInstall coc-json coc-tsserver
   :CocInstall coc-snippets
   :CocInstall coc-html-css-support
   :CocInstall coc-stylelint
   :CocInstall coc-svg
   :CocInstall coc-prettier
   ```


