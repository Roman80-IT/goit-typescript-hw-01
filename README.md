# goit-typescript-hw-01

```
npm install -g typescript

tsc -v

tsc --init // tsconfig.json

tsc

npm init -y  // package.json

npm i --save-dev @web/dev-server
```

Перейдемо до файлу **package.json**, де нам потрібно додати команду `start`:

```
"scripts": {
    "start": "web-dev-server --node-resolve --open --watch"
  },
```

А тепер просто запускаємо:

```
npm start
```
