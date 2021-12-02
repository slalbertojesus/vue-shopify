# Shopify-Vue 
# Creación de tema de vue por medio de themekit

[![N|Solid](https://i.imgur.com/oyeAKhj.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Themekit es una de las opciones para crear un tema de shopify
se puede utilizar una StoreFront API (Para conectar desde otro stack de tecnología), el themekitSDK y el conjunto de SDK´s externos para otros dispositivos/plataformas. 

Antes de empezar, es importante recordar que debes tener una cuenta de shopify y una tienda creada, la tienda creada debe tener **añadir** la aplicación "Theme Kit Access"

![N|Solid](https://i.ibb.co/2gmhLJ9/Screenshot-2.png)

Lo anterior, se realiza para obtener permiso y acceso hacia el tema (hay que recordar, que no existe un "staging" para el desarrollo de temas de shopify, si no un solo instance en vivo, que no se libera hasta que el desarrollador lo decide).

Para la creación de los temas a desarrollar se ha especificado utilizar Vue/Vuetify
Los pasos para crear el ambiente de desarrollo son los siguientes

- Descargar e instalar themekit [descarga](https://shopify.dev/themes/tools/theme-kit/getting-started#windows).
- Crear contraseña para themekit

	![N|Solid](https://i.ibb.co/q0v1s4r/Screenshot-3.png)

- Agregar información de contacto de desarrollador  

	![N|Solid](https://i.ibb.co/Fmk24mB/Screenshot-4.png)

- Mandar password a desarollador

# Desarrollador

- Revisar correo de invitación a proyecto. 

	![N|Solid](https://i.ibb.co/gVZTk5W/Screenshot-5.png)

- Copiar contraseña para editar tema

	![N|Solid](https://i.ibb.co/LQL1mGz/pass.png)

# Conectar a un tema existente
- Dentro de la carpeta de trabajo asignada, ingresar el siguiente comando
`theme get --list --password=[your-password] --store="[your-store.myshopify.com]"`
- Si hubo conección, crea un nuevo tema
`theme new --password=shptka_73askjdhasjdhask1232137d09ba91a4f --store=storevue.myshopify.com --name=pruebaVue`
- Si hubo conección, empieza a ver tu tema en tiempo real
` theme watch 
`
# TODO
## Reparar estilos de imágenes (centrar)
## Revisar ortografía 
## Agregar Vue/vuetify a tema. 
## Agregar Manejo de props?. 
