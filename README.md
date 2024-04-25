**TABLA DE CONTENIDO**

[TOCM]

[TOC]

### Descripción del Proyecto
- Proyecto frontend, desarrollado exclusivamente con PrimeReact, es un sistema CRUD diseñado para la gestión de programadores dentro de un equipo de trabajo. Ofrece funcionalidades completas para listar, crear, actualizar y eliminar perfiles de programadores, sin necesidad de un backend. Con una interfaz intuitiva y componentes dinámicos de PrimeReact, proporciona una experiencia de usuario fluida y eficiente en la administración de recursos humanos en el ámbito de desarrollo de software. Además, permite la descarga de archivos CSV y PDF de la lista de programadores para facilitar el análisis y la presentación de datos.

### Caracteristicas
![](https://www.primefaces.org/primereact-v5/showcase/images/primereact-logo-dark.png)
- Prime React ( primeflex, primeicons): Es una biblioteca de componentes de interfaz de usuario de React de primera calidad. Proporciona una amplia gama de componentes listos para usar que facilitan la creación de interfaces de usuario atractivas y funcionales. 
- React-router-dom: Es una librería de enrutamiento para React que permite gestionar la navegación en una aplicación de una sola página. Permite definir rutas y renderizar componentes específicos según la URL actual.
- jspdf: Es una biblioteca JavaScript que permite generar archivos PDF en el navegador. Proporciona una API para crear documentos PDF dinámicamente a partir de datos generados por la aplicación. En este caso, se utiliza para generar archivos PDF a partir de los datos de la lista de programadores (incluye jspdf-autotable).


### Funciones del Proyecto
- Crear perfiles desarrolladores
- Listar desarrolladores
- Actualizar perfiles desarrolladores
- Eliminar desarrolladores (Individual o grupal)
- Descargar CSV de la tabla desarrolladores
- Descargar PDF de la tabla desarrolladores

# Framework
- React: Es una biblioteca de JavaScript para construir interfaces de usuario, especialmente para aplicaciones de una sola página. Permite la creación de componentes reutilizables que gestionan su propio estado.
![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/React.svg/300
px-React.svg.png)


# Instalación
- Descarga y clonacion de proyecto
`git Clone https://github.com/FitzroyGarcia/Reto-PrimeReactApp.git`

- Instalacion de paquetes: acceder a la ruta del projecto y abrir CMD para ejecutar
```shell
npm install
```
- Ejecucion de proyecto
```shell
npm start
```

# Configuración
- Entrar al archivo, crea la carpeta images y copia los avatar inciales(Imagenes) de tu equipo
`src\components\data\images`

- Entrar a la direccion, crea el archivo 'desarrolladoresData' y copia el codigo o genera tu grupo de datos
`src\components\data`
    import imagen1 from './images/imagen1.jpg';
    import imagen2 from './images/imagen2.jpg';
    
    export const proveedorDesarrolladores = {
        getDesarrolladores: () => {
          const desarrolladores = [
            {
                id: 1,
                nombre: 'JUAN',
                avatar: imagen1,
                edad: 25,
                ciudad: 'URUBAMBA',
                experiencia: 'FRONTEND DEVELOPER',
            },
            {
                id: 2,
                nombre: 'PEDRO',
                avatar: imagen2,
                edad: 26,
                ciudad: 'CUSCO',
                experiencia: 'BACKEND DEVELOPER',
            },
          ];
          return Promise.resolve(desarrolladores);
        }
      };


