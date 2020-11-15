# Tutorial Felipe Deschamps 


[Como Eu Programo e Hospedo Sites da Forma Mais Moderna que Existe [GUIA DEFINITIVO]](https://www.youtube.com/watch?v=EW7m2WIvFgQ)


## Libraries and setup

```
npm install next react react-dom
```

In package.json 

```
  "scripts": {
    "dev": "next dev"
  },
```

### File system routing

* /pages/index.js  > site.com
* /pages/contato.js  > site.com/contato
* /pages/blog/index.js  > site.com/blog
* /pages/sobre/filipe.js  > site.com/sobre/filipe


### Running it

```
npm run dev
```

### Deploy

Enter in https://vercel.com/, log using Github account 

https://deploy-deshamps-tutorial.vercel.app/


## New branch

```
git checkout -b teste
git commit -m 'nova pagina'
git push origin teste
```

### Useful links

