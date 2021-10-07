# -outstaffing-land

## Установить зависимостей (в корне проекта)
```
npm install
```

### Запустить
```
npm run serve
```

### Если кидает ошибку, то, возможно, что это из-за scss. Нужно установить node.js 14+
```
curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -
sudo apt -y install nodejs
```
### Проверяем версию
```
node  -v
```
### Если 14+, то все ок. 
### И сделать привязку к текущей версии:
```
npm rebuild node-sass --force
```
