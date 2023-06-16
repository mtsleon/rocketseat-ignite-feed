
# Instalação de versões do Nodejs de forma customizada
```
npm install -g n    

n install lts (versao do node LTS)

n install 18 (versao do node 18)

```


# Criando e executando um projeto no ReactJs com Vite
```
npm create vite@latest

npm install / npm i

npm run dev

```

# Customizando a porta onde o Vite irá disponibiliar a app 
Acessar o arquivo "vite.config.js"
```
export default defineConfig({
..
    server: {port: 3001,}
})
```