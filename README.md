# Proffy - Next Level Week 2, Rocketseat

## WEB
### Configuração Inicial do Typescript
- yarn add typescript -D

- yarn tsc --init
    - tsconfig.json
        >> "target": "es2017",

- yarn add ts-node-dev -D
    - package.json
        >> "scripts": {
            "start": "tsnd --transpile-only --ignore-watch node_modules --respawn src/server.ts"
        },

## SERVER
### Express
- yarn add express
- yarn add @types/express -D

### Database
- yarn add knex sqlite3

### Knex
- package.json
    >> "scripts": {
       "knex:migrate": "knex --knexfile knexfile.ts migrate:latest",
       "knex:migrate:rollback": "knex --knexfile knexfile.ts migrate:rollback"
    }

- Instalar Extensão: SQLite

### Cors
- yarn add cors
- yarn add @types/cors -D

## MOBILE
### Expo
- yarn global add expo-cli
- expo init mobile
- yarn start

### Fontes Utilizadas
- expo install expo-font @expo-google-fonts/archivo @expo-google-fonts/poppins

### React Navigation
- yarn add @react-navigation/native
- expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
- yarn add @react-navigation/stack
- npm install @react-navigation/bottom-tabs
