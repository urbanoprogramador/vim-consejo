Para configurar Vim de modo que se muestre una ventana con el tipado de la función, podemos emplear la función `CocAction('doHover')`. Para hacerlo, es necesario agregar el siguiente código a nuestro archivo `~/.vimrc` o al archivo donde se configuren nuestros atajos:

```bash
nmap <leader>h <Plug>(coc-hover)
```
Esta línea nos permitirá invocar una ventana con información sobre el tipado de la función pulsando `<leader> + h`.

Asimismo, para configurar la tecla líder, podemos asignarle un mapeo en nuestro archivo de configuración de variables de Vim, ya sea `~/.vimrc` u otro:

```bash
let mapleader = " "
```

Con estos ajustes, podremos usar Vim de una manera más efectiva y personalizada según nuestras necesidades.