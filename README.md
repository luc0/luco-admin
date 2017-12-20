## Admin on rest usando api ([ver proyecto](https://github.com/luc0/luco-admin-api))

#### Admin
```
Yarn start
```
#### Api ([ver proyecto](https://github.com/luc0/luco-admin-api))
Lo levanto con laradock.
```
docker compose up -d postgres nginx
```

#### Aviso
No esta funcionando el method OPTIONS. Por alguna razon esta mal configurado los métodos que acepta nginx, eso hay que cambiarlo en su archivo de configuracin y ver si necesita algo mas.
