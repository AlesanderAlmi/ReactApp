[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/I4C_7ZVc)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15304874)
# React Firebase Chat: Ejercicio día 3

## Enunciado

Escribir una regla en Firestore la cual solo permite escribir y borrar el mensaje a quien lo ha creado.

---

## Ejecutar la aplicación

Para arrancar el proyecto ejecuta

`npm install`

Y posteriormente:

`npm start`

## Solucionar errores

Es posible que antes de arrancar de un error de que no reconoce algunos paquetes, para esolver ese problema debemos ejecutar.

`export NODE_OPTIONS=--openssl-legacy-provider`

---

Si nos encontramos en **Codespaces** e indica el error **Error: Cannot find modul** con **code: 'MODULE_NOT_FOUND'**, entonces debemos ejecutar:

`rm -rf node_modules`

`rm -f package-lock.json`

`npm cache clean --force`

`npm install`
