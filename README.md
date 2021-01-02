# first-gitbook

Este Gitbook conten algunhas notas sobre como crean un Gitbook.

Un tutorial de cómo aloxar este gitbook en paxinas de github está escrito aquí .

## Cómo servir este repositorio localmente

1. Abrir o terminal e executar
```git clone https://github.com/nunhes/first-gitbook```
2. Instalar as dependencias (asumindo que xa tes npm e yarn instalados)
```npm install -g gitbook-cli```
```yarn add gulp gulp-gh-pages gulp-load-plugins --save-dev```
```gitbook install```
3. Na carpeta raíz deste repositorio ( cd first-gitbook) executar
```gitbook serve```
4. Para implementar cambios en github, executar
```gulp publish```