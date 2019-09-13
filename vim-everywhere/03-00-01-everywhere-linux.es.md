
# 3. ¡Donde sea!

## Linux

### Desde el código fuente

```shell-session
# apt-get purge -fy "vim-*"
# apt-get install gcc libncurses-dev libx11-dev \
                  libxpm-dev libxt-dev libxtst-dev make

$ wget 'ftp://ftp.vim.org/pub/vim/unix/vim-8.1.tar.bz2'
$ tar -xf vim-8.1.tar.bz2
$ cd vim81
$ ./configure --with-features=huge
# make all install
$ rm -rf vim81
```

