# List of Things That I Always Forget

This is a list of tweaks that I most likely already forgot, or are hard for me to remember. (╯°□°)╯︵ ┻━┻

---

## NERDTree (Vim)

<C-n> - toggle NERDTree in normal mode

```vim
nmap <C-n> :NERDTreeToggle<CR>
```

### Most Helpful Shortcuts

```
i........Open selected file in a split window
gi.......Same as i, but leave the cursor on the NERDTree
s........Open selected file in a new vsplit
gs.......Same as s, but leave the cursor on the NERDTree
x........Close the current nodes parent
m........Display the NERDTree menu (move, delete, add childnode, etc.)
```

### Kinda Helpful

```
P........Jump to the root node
p........Jump to current nodes parent
I........Toggle whether hidden files displayed
?........Toggle the display of the quick help
```

---

## EasyMotion (Vim)

Always forgetting to use it, but it's very powerful.

```
<space>f{char}      Find {char} to the right. See |f|.
<space>F{char}      Find {char} to the left. See |F|.
<space>t{char}      Till before the {char} to the right. See |t|.
<space>T{char}      Till after the {char} to the left. See |T|.
<space>w            Beginning of word forward. See |w|.
<space>W            Beginning of WORD forward. See |W|.
<space>b            Beginning of word backward. See |b|.
<space>B            Beginning of WORD backward. See |B|.
<space>e            End of word forward. See |e|.
<space>E            End of WORD forward. See |E|.
<space>ge           End of word backward. See |ge|.
<space>gE           End of WORD backward. See |gE|.
<space>j            Line downward. See |j|.
<space>k            Line upward. See |k|.
<space>n            Jump to latest "/" or "?" forward. See |n|.
<space>N            Jump to latest "/" or "?" backward. See |N|.
<space>s            Find(Search) {char} forward and backward.
```

---

## Leader Mappings (Vim)

```vim
nnoremap <leader>ll :ls<CR>
nnoremap <leader>b :bp<CR>
nnoremap <leader>f :bn<CR>
nnoremap <leader>g :e#<CR>
nnoremap <leader>1 :1b<CR>
nnoremap <leader>2 :2b<CR>
nnoremap <leader>3 :3b<CR>
nnoremap <leader>4 :4b<CR>
nnoremap <leader>5 :5b<CR>
nnoremap <leader>6 :6b<CR>
nnoremap <leader>7 :7b<CR>
nnoremap <leader>8 :8b<CR>
nnoremap <leader>9 :9b<CR>
nnoremap <leader>0 :10b<CR>

nnoremap <leader>h :noh<CR>
```
