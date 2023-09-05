### Versiones

##1.0.0
Versión original primeng 11.4.0
Añadido soporte para fecha en formato ISO8601 en componente calendar


## Notas

Para generar libreria de componentes
Con Node 11
  npm run build-lib
o
  ng build primeng-library
  gulp build-assets

En dist:
 - modificar version de package.json
    - aumentar versión
    - cambiar nombre de paquete a @diaple/primeng
 - npm publish --registry https://npm.diaple.com:4873