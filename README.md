# Proyecto: Mapeo de Información en Cartas

## Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar una aplicación web que acceda a un endpoint de API, obtenga la información y la mapee en tarjetas (cartas) sencillas. La aplicación debe ser fácil de entender y utilizar, enfocándose en la presentación clara y estructurada de los datos.

## Requisitos

### Tecnologías a Utilizar
- **Frontend:** HTML, CSS, JavaScript (opcionalmente pueden utilizar frameworks/librerías como React, Vue o Angular)
- **Herramientas de Desarrollo:** Git, cualquier IDE o editor de texto

### Funcionalidades Principales
1. **Acceso a el Endpoint:**
   - Deben acceder al endpoint de la PokeAPI para obtener todos los Pokémon.
   - Endpoint a utilizar: `https://pokeapi.co/api/v2/pokemon?limit=10`, donde `10` es el número de resultados por petición.
   - El endpoint devuelve una lista de Pokémon en formato JSON.

2. **Mapeo de Información en Cartas:**
   - Una vez obtenidos los datos, deben mapear esta información en tarjetas sencillas.
   - Cada tarjeta debe mostrar los datos de manera clara y organizada.
   - Las tarjetas deben tener un diseño coherente y atractivo.

### Pasos a Seguir

#### 1. Configuración Inicial
- Descargar en zip el proyecto y subirlo a su git personal en un repositorio público.
- Crear una rama main para empezar a trabajar.
- Configurar su entorno de desarrollo (instalar dependencias, configurar el servidor, etc.)

#### 2. Acceso a la API
- Implementar una función en el frontend que haga una solicitud HTTP GET al endpoint seleccionado.
- Asegurarse de manejar errores en caso de que la solicitud falle. 

#### 3. Procesamiento de Datos
- Recibir los datos obtenidos de la API y procesarlos para crear las tarjetas.

#### 4. Diseño de las Tarjetas
- Diseñar una tarjeta utilizando HTML y CSS.

#### 5. Mapeo de Datos a Tarjetas
- Iterar sobre los datos obtenidos de la API y crear una tarjeta para cada ítem de datos.

#### 6. Revisión y Pruebas
- Revisar el código para asegurarse de que esté limpio y bien documentado.
- Probar la aplicación para asegurarse de que funcione correctamente en diferentes navegadores.
- Corregir cualquier error encontrado durante las pruebas.

### Entrega
- Asegurarse de que el código pase todas las revisiones de código.
- Escribir un informe breve describiendo las decisiones de diseño tomadas y cualquier desafío encontrado durante el desarrollo.
- Subir la aplicación a un repositorio de GitHub público y compartir el link por el correo.
- Desplegar el proyecto en un servidor web (Github Pages, Vercel, Netlify, Firebase, etc) compartir este link también por el correo.

## Recursos Adicionales
- [Documentación de Fetch API](https://developer.mozilla.org/es/docs/Web/API/Fetch_API)
- [Introducción a React](https://es.reactjs.org/docs/getting-started.html)
- [Introducción a Vue](https://vuejs.org/v2/guide/)
- [Introducción a Angular](https://angular.io/start)

¡Buena suerte y feliz codificación!