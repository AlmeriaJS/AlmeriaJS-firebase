# Proyecto Firebase para la web de Almería JS

## Instrucciones para publicar una nueva build

Actualizar el submódulo con el repo de la wweb

```
cd public/AlmeriaJS
git submodule init
git submodule update
```

Generar una nueva build:

```
npm run prerender
```

Publicar la build:

```
firebase login
firebase deploy --only hosting
```
