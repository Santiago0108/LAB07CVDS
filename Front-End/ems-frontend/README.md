# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

En el front end se utilizó React con Vite, para poder hacer uso de la librería de React y poder hacer uso de las funcionalidades de la librería de React, como por ejemplo, crear componentes, manejar el estado de la aplicación, hacer peticiones HTTP al back-end, etc.

Para poder hacer uso de React en Vite, se creó un proyecto de Vite con la plantilla de React, la cual se puede encontrar en la documentación oficial de Vite. En esta plantilla se crean los archivos y carpetas necesarios para poder empezar a trabajar con React en Vite, como por ejemplo, el archivo index.html, el archivo index.tsx, la carpeta public, la carpeta src, etc.

En el archivo index.html se define la estructura básica de la página web, como por ejemplo, el título de la página, la hoja de estilos, los scripts, etc. En el archivo index.tsx se define el componente principal de la aplicación, el cual se encarga de renderizar los demás componentes de la aplicación. En la carpeta public se encuentran los archivos estáticos de la aplicación, como por ejemplo, las imágenes, los estilos, los scripts, etc. En la carpeta src se encuentran los archivos de código fuente de la aplicación, como por ejemplo, los componentes, los estilos, los scripts, etc.

En la carpeta components se encuentran los componentes de la aplicación, como por ejemplo, el componente de la lista de empleados, el componente de agregar un empleado, el componente de editar un empleado, etc. En la carpeta services se encuentran los servicios de la aplicación, como por ejemplo, el servicio de empleados, el servicio de departamentos, el servicio de cargos, etc. En la carpeta utils se encuentran las utilidades de la aplicación, como por ejemplo, las funciones de validación, las funciones de formateo, las funciones de conversión, etc.

En lo relacionado al CRUD de empleados, se crearon los métodos necesarios en el front-end y en el back-end para poder agregar, editar, eliminar y listar los empleados. Para agregar un empleado se debe hacer clic en el botón "Add Employee" y llenar el formulario que aparece en pantalla. Para editar un empleado se debe hacer clic en el botón "Update" que aparece al lado de cada empleado en la lista y llenar el formulario que aparece en pantalla. Para eliminar un empleado se debe hacer clic en el botón "Delete" que aparece al lado de cada empleado en la lista

En EmployeeServices se crearon los métodos necesarios para poder hacer las peticiones HTTP al back-end, como por ejemplo, guardar un empleado, obtener un empleado por su id, obtener todos los empleados, etc. En EmployeeList se crearon los métodos necesarios para poder listar los empleados, como por ejemplo, obtener todos los empleados, eliminar un empleado, etc. En AddEmployee se crearon los métodos necesarios para poder agregar un empleado, como por ejemplo, guardar un empleado, obtener todos los departamentos, obtener todos los cargos, etc. En EditEmployee se crearon los métodos necesarios para poder editar un empleado, como por ejemplo, obtener un empleado por su id, guardar un empleado, obtener todos los departamentos, obtener todos los cargos, etc.

En ListEMployeeComponent se crearon los métodos necesarios para poder listar los empleados, como por ejemplo, obtener todos los empleados, eliminar un empleado, etc. 

En EmployeeComponent se implementaros los componentes necesarios para el CRUD de empleados, como por ejemplo, el componente de agregar un empleado, el componente de editar un empleado, etc.