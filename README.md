# vimrc for Python development

## Usage

1. run the command
```bash
$ mkdir -p ~/.vim ~/.vim/autoload ~/.vim/backup ~/.vim/colors ~/.vim/plugged
```

2. run the command
```bash
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

3. download the `.vimrc` file and put it under `~` directory.

4. install `nodejs` (required by [coc.nvim](https://github.com/neoclide/coc.nvim))

5. run the command
```bash
$ vim
```

6. run the command in the vim
```vim
:PlugInstall
```
7. quit vim and re-enter

8. run the command in the vim
```vim
:CocInstall coc-pyright
```

## Plugins (check the plugins for keyboard bindings)

- [NerdCommenter](https://github.com/preservim/nerdcommenter): 🌟🌟🌟🌟🌟 easy comment
- [NeoFormat](https://github.com/sbdchd/neoformat): 🌟🌟🌟 not required
- [ALE](https://github.com/dense-analysis/ale): 🌟🌟🌟🌟🌟 real time linters
- [vim-airline](https://github.com/vim-airline/vim-airline) & [vim-airline-themes](https://github.com/vim-airline/vim-airline-themes): 🌟🌟🌟🌟🌟 status line prettify
- [NerdTree](https://github.com/preservim/nerdtree): 🌟🌟🌟🌟🌟 file system visulization and operation
- [auto-pairs](https://github.com/jiangmiao/auto-pairs): 🌟🌟🌟🌟 auto pair the brackets
- [indentLine](https://github.com/Yggdroot/indentLine): 🌟🌟🌟 not required
- [vim-startify](https://github.com/mhinz/vim-startify): 🌟🌟🌟🌟 very cute plugin, prettify start page of command `vim`
- [jedi-vim](https://github.com/davidhalter/jedi-vim): 🌟🌟🌟🌟🌟 auto completion (disabled in .vimrc) and goto definition
- [requirements.txt.vim](https://github.com/raimon49/requirements.txt.vim): 🌟🌟🌟🌟 requirements.txt prettify
- [ayu-vim](https://github.com/ayu-theme/ayu-vim): 🌟🌟🌟🌟🌟 color scheme
- [coc.nvim](https://github.com/neoclide/coc.nvim): 🌟🌟🌟🌟🌟 auto completion
