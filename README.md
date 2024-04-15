En el back-end lo primero que se hizo fue crear el modelo de la base de datos, el cual se encuentra en el archivo Employee.java en la carpeta model. En este archivo se definen los atributos de la tabla de la base de datos, así como los métodos get y set para cada uno de los atributos.

Posteriormente se creó el repositorio de la base de datos, el cual se encuentra en el archivo EmployeeRepository.java en la carpeta repository. En este archivo se definen los métodos que se utilizarán para interactuar con la base de datos, como por ejemplo, guardar un empleado, obtener un empleado por su id, obtener todos los empleados, etc.

Después se creó el controlador, el cual se encuentra en el archivo EmployeeController.java en la carpeta controller. En este archivo se definen los métodos que se utilizarán para manejar las peticiones HTTP que se hagan al back-end, como por ejemplo, guardar un empleado, obtener un empleado por su id, obtener todos los empleados, etc.

Finalmente se creó el servicio, el cual se encuentra en el archivo EmployeeService.java en la carpeta service. En este archivo se definen los métodos que se utilizarán para interactuar con el repositorio, como por ejemplo, guardar un empleado, obtener un empleado por su id, obtener todos los empleados, etc.

En el front-end lo primero que se hizo fue crear los componentes para listar los empleados, agregar un empleado y editar un empleado. Estos componentes se encuentran en las carpetas list-employees, add-employee y edit-employee respectivamente.

Posteriormente se creó el servicio para interactuar con el back-end, el cual se encuentra en el archivo employee.service.ts en la carpeta services. En este archivo se definen los métodos que se utilizarán para hacer las peticiones HTTP al back-end, como por ejemplo, guardar un empleado, obtener un empleado por su id, obtener todos los empleados, etc.

Finalmente se creó el módulo principal de la aplicación, el cual se encuentra en el archivo app.module.ts en la carpeta app. En este archivo se definen los componentes, servicios y módulos que se utilizarán en la aplicación.

En lo relacionado al CRUD de empleados, se crearon los métodos necesarios en el back-end y en el front-end para poder agregar, editar, eliminar y listar los empleados. Para agregar un empleado se debe hacer clic en el botón "Add Employee" y llenar el formulario que aparece en pantalla. Para editar un empleado se debe hacer clic en el botón "Update" que aparece al lado de cada empleado en la lista y llenar el formulario que aparece en pantalla. Para eliminar un empleado se debe hacer clic en el botón "Delete" que aparece al lado de cada empleado en la lista y confirmar dicha transaccion.

Los elementos de REACT usados en el front-end son:

- Componentes para listar los empleados, agregar un empleado y editar un empleado.