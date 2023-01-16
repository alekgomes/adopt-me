# Prettier

Utilizado para formatação consistente de código

```js
  "format": "prettier \"src/**/*.{js,html}\" --write"
```

Acima, estamos chamando o comando prettier em todos os arquivos .js ou .html dentro da pasta src.
O prettier tbm pode ser usado como extensão no VSCode. É preciso habilitar duas coisas no vscode para o bom funcionamento da extensão:

  
    1 - format on save
    2 - require config 
         |_--> Uma vez que essa opção foi marcada, é preciso criar
         arquivo de config para o prettier: .prettierrc.
         Esse arquivo pode ser vazio
      

# Eslint
Eslint pode ser usado juntamente com o Eslint-config-prettier
```js
  npm i -D eslint eslint-config-prettier
```

O eslint tbm precisa de um arquivo de configuração, o *.eslintrc.{json, yml, js}*.

É nesse arquivo que se concentra as regras que o eslint vai usar para validar o código.

# Babel
Babel é um compilador de javascript e tem como função transformar o js que escrevemos (moderno e atualizado) em js compreendido pelos navegadores (antigos e desatualizados). Mais infos podem na [site do babel](https://babeljs.io/)


