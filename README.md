This template should help get you started developing with Vue 3 in Vite.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

npm run build
rsync -aP  dist root@161.97.105.143:~/home/resad/site
ssh root@161.97.105.143
nohup serve -p 8080  > serve.log 2>&1 &
sudo npm install -g pm2
pm2 start "serve -p 8087" --name my-site
pm2 logs my-app
# Stop the app
pm2 stop my-site






# Restart the app
pm2 restart my-app

# Delete the app from pm2
pm2 delete my-app# ruzi-site
