# CerealesPP
Aplicación web sobre una tienda de Cereales que vende al por mayor. Es el primer proyecto con Spring Boot de 1ºDAM.

## Índice
1. [Introducción](#INTRO)
2. [Tecnologías](#TEC)
3. [Arrancar el proyecto en local](#LOCAL)
4. [Url de la web](#URL)

## Introducción<a name ="INTRO"></a>
Este proyecto es una app web de una tienda de cereales que vende al por mayor a otras empresas.

Los usuarios anónimos podrán navegar por las páginas públicas pero no podrán añadir productos a la cesta, puesto que para comprar deben estar registrados.

Los usuarios registrados podrán realizar compra, administrar su perfil y ver el historial de pedidos.

El administrador podrá gestionar los productos y pedidos. Podrá visualizar a los clientes.

Las cantidades de compra son un poco diferente a lo normal. En ese tipo de empresa se compra por camiones. Un camión son 26 toneladas. Por tanto, la aplicación exigirá una compra mínima de 26t y una compra máxima de 208 toneladas por cereal. El transporte se cobrará por camiones.

### Tecnologías<a name ="TEC"></a>
1. Java
2. Hibernate
3. JPA
4. Thymeleaf
5. Spring Security


## Arrancar el proyecto en local<a name ="LOCAL"></a>

Haga un Maven install, y después ejecute el siguiente comando en la carpeta \target del proyecto:
```
 java -jar cerealespp-0.0.1-SNAPSHOT.jar
```

Finalmente, la web se visualizará en: localhost:9000.

Además, el proyecto contiene un archivo de texto con una pequeña base de datos para poder probar la app.

## ¿Puedo probar el proyecto sin desplegarlo?<a name ="URL"></a>
Sí. Actualmente, está desplegado en los servidores de Heroku y puedes acceder a la app web a través del siguiente [link](https://cereales-pp.herokuapp.com/).

