
# vim-operator-autopep8


## Installation

with NeoBundle

```vim
NeoBundle 'hachibeeDI/vim-operator-autopep8', {
\   'depends': ['kana/vim-operator-user', 'andviro/flake8-vim'],
\ }
```

## Usage

```vim
" in .vimrc

map ,p <Plug>(operator-autopep8)
```

## Requirements

- [https://github.com/kana/vim-operator-user](kana/vim-operator-user)
- [https://github.com/andviro/flake8-vim](andviro/flake8-vim)

## Other recommended plugins

- [https://github.com/bps/vim-textobj-python](bps/vim-textobj-python)
