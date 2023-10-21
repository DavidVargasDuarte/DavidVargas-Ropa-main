

<!-- Descripcion -->
<p>La empresa safe clothing desea realizar un backend que le permita llevar el control, registro y seguimiento de la producción de prendas de seguridad industrial, la empresa cuenta con diferentes tipos de prendas entre las cuales están las prendas resistentes al fuego (Ignifugas), resistentes a altos voltajes (Arco eléctrico). La empresa lo contrata a usted como experto backend para que cumpla con los siguientes requerimientos de desarrollo</p>

<!-- Seccion 1 -->
##  Tecnologias 
<p align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br>

- **Back-End Development**: 
  ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=flat&logo=c-sharp&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=flat&logo=.net&logoColor=white) 


- **Frameworks, platforms & libraries**:
  ![JWT](https://img.shields.io/badge/JWT-black?style=flat&logo=JSON%20web%20tokens)

- **Softwares & Tools**: 
  ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=flat&logo=visual-studio-code&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=flat&logo=swagger&logoColor=white) ![Insomnia](https://img.shields.io/badge/Insomnia-black?style=flat&logo=insomnia&logoColor=5849BE) ![GIT](https://img.shields.io/badge/Git-fc6d26?style=flat&logo=git&logoColor=white)

- **Database**:
  ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=flat&logo=mysql&logoColor=white)
  
</p>
<
mg src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><br>

<!-- Seccion 2 -->
###  Requerimientos funcionales <br>
- Implementar restricción de peticiones haciendo uso de limitaciones de peticiones por IP. ❌ <br>
- Implementar protección a los endPoints haciendo uso de JWT y roles de usuario. ❌ <br>
- Implementar esquema de versionado de Api que facilite el proceso de implementación de nuevos endpoints sin afectar el funcionamiento de las aplicaciones externas que consumen los servicios del Api. ❌ <br>
- Se debe permitir realizar procesos de creacion, edicion, eliminacion y listado de informacion de cada una de las tablas. ❌ <br>
- Implementar endpoints que permitan realizar el proceso de CRUD en cada uno de los controladores del backend. ❌ <br>
- Debido al gran volumen de información que la empresa procesa diariamente se requiere que los endpoints encargados de consultar el contenido de las tablas implementen sistema de paginación. ❌ <br>

<!-- Seccion 3 -->
### Realizar las siguientes consultas: 
<h4>Grupo B:</h4>
- Listar las prendas de una orden de producción cuyo estado sea en producción. El usuario debe ingresar el número de orden de producción. ❌ <br>
-Listar las prendas agrupadas por el tipo de protección. ❌ <br>
- Listar las ordenes de producción que pertenecen a un cliente especifico. El usuario debe ingresar el IdCliente y debe obtener la siguiente información:

1. IdCliente, Nombre, Municipio donde se encuentra ubicado.
2. Nro de orden de producción, fecha y el estado de la orden de producción (Se debe mostrar la descripción del estado, código del estado, valor total de la orden de producción.
3. Detalle de orden: Nombre de la prenda, Código de la prenda, Cantidad, Valor total en pesos y en dólares. ❌ <br>
- Listar los insumos de una prenda y calcular cuanto cuesta producir una prenda especifica. El costo de la prenda dependerá de la cantidad de insumos que sean necesarios para la producción de la misma. El usuario debe ingresar en Id de la prenda. ❌ <br>
- Listar los insumos que son vendidos por un determinado proveedor. El usuario debe ingresar el Nit de proveedor. ❌<br>
- Listar las ventas realizadas por un empleado especifico. El usuario debe ingresar el Id del empleado y mostrar la siguiente información.

1. Id Empleado
2. Nombre del empleado
3. Fecturas : Nro Factura, fecha y total de la factura. ❌ <br>

<!-- Seccion 4 -->
###  Dependencias o paquetes Nuget utilizados 
<h4>API</h4>
- Serilog.AspNetCore - v7.0.0 <br>
- AspNetCoreRateLimit - v5.0.0 <br>
- System.IdentityModel.Tokens.Jwt - v7.0.2 <br>
- Microsoft.AspNetCore.Mvc.Versioning - v5.1.0 <br>
- Microsoft.EntityFrameworkCore.Design - v7.0.12 <br>
- Microsoft.AspNetCore.Authentication.JwtBearer - v7.0.12 <br>
- AutoMapper.Extensions.Microsoft.DependencyInjection - v12.0.1 <br>

<h4>Domain</h4>
- itext7.pdfhtml - v5.0.1 <br>
- FluentValidation.AspNetCore - v11.3.0 <br>
- Microsoft.EntityFrameworkCore - v7.0.12 <br>

<h4>Persistence</h4>
- CsvHelper - v30.0.1 <br>
- Microsoft.EntityFrameworkCore - v7.0.12 <br>
- Pomelo.EntityFrameworkCore.Mysql - v7.0.11 <br>
