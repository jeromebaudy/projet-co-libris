
## Dévelopement

### Dépendance

- nodejs
- npm
- mongodb

### Utilisation

#### Linux

```
$ cd co-libris
$ npm install
$ mongod --dbpath "/path/to/bdd_mongodb_colibris"
$ npm start
```

Puis aller dans le navigateur à l'adresse `http://localhost:8080`

#### Windows

```
$ cd co-libris
$ npm install
```

Lancé le `.bat` et coriger les liens vers l'executable `mongod.exe` et le chemin de la base de donnée 

```
$ npm start
```

Puis aller dans le navigateur à l'adresse `http://localhost:8080`

