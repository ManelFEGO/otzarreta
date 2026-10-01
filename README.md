# Correcciones web Endermar

Documento de correcciones del entorno de pruebas `endermar.digitalotzarreta.com`, preparado para enviar a Otzarreta.
Una pantalla por corrección, con capturas, URL y criterio de comprobación.

Revisión del entorno: **30 de septiembre de 2026**.

## Contenido de la carpeta

```
correcciones-endermar/
├── index.html      ← el documento completo
├── img/            ← las capturas (no cambiar los nombres)
└── README.md       ← este archivo
```

## Cómo publicarlo en GitHub Pages

Sigue estos pasos en este orden. Tardas cinco minutos.

1. Entra en **github.com** con tu cuenta y pulsa el botón verde **New** (o el signo **+** de arriba a la derecha, **New repository**).
2. En **Repository name** escribe `correcciones-endermar`.
3. Deja la opción **Public** marcada. No marques «Add a README file».
4. Pulsa **Create repository**.
5. En la página que aparece, pulsa el enlace **uploading an existing file**.
6. Arrastra a la ventana el archivo `index.html` y **la carpeta `img` entera**. Espera a que terminen de subirse: verás la lista de archivos.
7. Abajo pulsa el botón verde **Commit changes**.
8. Arriba, pulsa la pestaña **Settings**.
9. En la columna de la izquierda, pulsa **Pages**.
10. En **Source** elige **Deploy from a branch**. En **Branch** elige **main** y la carpeta **/ (root)**. Pulsa **Save**.
11. Espera un minuto y recarga la página. Arriba aparecerá la dirección, con esta forma:
    `https://TUUSUARIO.github.io/correcciones-endermar/`
12. Abre esa dirección para comprobar que se ve bien, y pégala en el correo a Otzarreta.

## Cómo borrarlo cuando ya no haga falta

1. Entra en el repositorio, pestaña **Settings**.
2. Baja del todo hasta **Danger Zone** y pulsa **Delete this repository**.
3. Escribe el nombre del repositorio para confirmar.

Al borrar el repositorio desaparece también la página publicada.

## Notas

- El documento no necesita internet para nada externo salvo la tipografía; si no carga, se ve igual con la tipografía del sistema.
- Las casillas de «Hecho» se guardan en el navegador de quien las marca: no se comparten. Por eso está el botón **Copiar resumen para el correo**.
- El documento lleva `noindex`, así que los buscadores no deberían indexarlo. Aun así, contiene capturas del entorno de pruebas: bórralo cuando se apliquen las correcciones.
