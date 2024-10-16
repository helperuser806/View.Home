## View.Home

- Pagina web para la gestion y visualizacion de propiedades en arriendo

## Tabla de Contenidos
[TOC]
#Proposito del proyecto
- El proyecto view.home consiste en desarrollar una página web para la gestión y visualización de propiedades en arriendo. Su objetivo es facilitar la interacción entre propietarios y arrendatarios, proporcionando una plataforma digital eficiente para la búsqueda, consulta, y administración de propiedades arrendadas.

- **Objetivos generales:**
1. - Optimizar la búsqueda de propiedades mediante un sistema de filtros que permita a los arrendatarios encontrar rápidamente inmuebles que se ajusten a sus necesidades.
2. - Facilitar la gestión de propiedades para los propietarios, permitiéndoles publicar, modificar, o eliminar propiedades de forma sencilla.
3. - Promover una comunicación directa y segura entre arrendatarios y propietarios para la resolución rápida de consultas o la negociación de condiciones de arriendo.
4. - Proveer una experiencia de usuario amigable a través de una interfaz moderna y responsiva que funcione en diferentes dispositivos.

#Contexto del proyecto
- El proyecto está diseñado para un mercado en crecimiento de arrendamientos de propiedades, donde tanto propietarios como arrendatarios requieren una solución fácil de usar para gestionar el proceso de alquiler de inmuebles. La plataforma deberá ser intuitiva, responsiva y accesible desde dispositivos móviles.

- Todo esto se desarrolla en un contexto de creciente demanda de soluciones digitales en el mercado inmobiliario. La digitalización del sector inmobiliario ha permitido una mayor accesibilidad a la información de propiedades y una mejor comunicación entre interesados, lo cual es una ventaja competitiva importante en un mercado tan dinámico. La plataforma está dirigida tanto a personas que buscan propiedades residenciales como comerciales.

#Identificacion de SkateHolders
**1. Propietarios de inmuebles**
- **Rol:** Publicar y gestionar las propiedades disponibles para arrendar.
- **Intereses:** Maximizar la visibilidad de sus propiedades en la plataforma, atraer a potenciales arrendatarios y asegurar contratos de arrendamiento a largo plazo.
- **Necesidades:**
- Un panel de control intuitivo para publicar, editar y eliminar propiedades.
- Estadísticas sobre las visualizaciones de sus propiedades y contacto rápido con los arrendatarios interesados.
- Seguridad y confianza en el sistema para la gestión de sus datos e inmuebles.

------------


**2. Arrendatarios (Usuarios en búsqueda de propiedades)**
- **Rol:** Buscar propiedades que se ajusten a sus necesidades (residenciales o comerciales) y contactar a los propietarios para realizar el proceso de arrendamiento.
- **Intereses:** Encontrar una propiedad que cumpla con su presupuesto y requerimientos en el menor tiempo posible.
- **Necesidades:**
- Herramientas de búsqueda y filtrado avanzadas (precio, ubicación, características del inmueble).
- Acceso a información clara y detallada de las propiedades (fotos, precios, descripción, y ubicación).
- Sistema de comunicación eficiente para contactar a los propietarios directamente desde la plataforma.

------------
**3. Administradores del sistema**
- **Rol:** Monitorear y gestionar el buen funcionamiento de la plataforma, asegurarse de que el contenido publicado sea adecuado, y resolver problemas técnicos.
- **Intereses: **Garantizar el correcto funcionamiento de la plataforma, que los usuarios tengan una experiencia fluida y que los datos de usuarios estén protegidos.
- **Necesidades:**
- Acceso a herramientas para moderar contenido, administrar usuarios y revisar estadísticas de uso.
- Panel de administración con funciones para eliminar contenido inapropiado o corregir errores técnicos.
- Sistemas de seguridad robustos para proteger la información de los usuarios y propiedades.

------------

**4. Desarrolladores del sistema**
- **Rol:** Desarrollar y mantener la plataforma, implementar nuevas funcionalidades y solucionar errores técnicos.
- **Intereses: **Entregar una plataforma funcional, escalable y libre de errores que se ajuste a las expectativas de los stakeholders principales.
- **Necesidades:**
- Requerimientos funcionales claros y precisos para el desarrollo de funcionalidades.
- Acceso a herramientas y tecnologías para el mantenimiento continuo de la plataforma.
- Feedback constante de los usuarios finales para mejorar la experiencia y corregir problemas técnicos.

------------

**5. Entidad de Seguridad y Regulación**
- **Rol:** Asegurar que la plataforma cumpla con las normativas locales sobre protección de datos y contratos de arrendamiento.
- **Intereses:** Que la plataforma respete las leyes y regulaciones de protección de datos y contratos de arrendamiento.
- **Necesidades:**
- Implementación de políticas de seguridad que cumplan con la normativa local.
- Acceso para la revisión de las políticas de privacidad y términos de uso de la plataforma.

------------





#Requerimientos
##Funcionales
**1. Registro y autenticación de usuarios:**
- El sistema debe permitir que los propietarios y arrendatarios se registren y autentiquen a través de un formulario de registro con validación de datos.
- Los usuarios deben poder iniciar sesión y recuperar su contraseña en caso de olvido.

**2. Gestión de propiedades (para propietarios):**
- Los propietarios deben poder agregar nuevas propiedades a la plataforma, proporcionando detalles como título, descripción, precio, ubicación, tipo de propiedad, número de habitaciones, fotos, y otras características.
- Los propietarios deben poder editar o eliminar propiedades previamente publicadas.

**3. Búsqueda y filtrado de propiedades (para arrendatarios):**
- El sistema debe permitir a los arrendatarios buscar propiedades por ubicación, rango de precios, número de habitaciones, tipo de propiedad (residencial/comercial), y otros filtros relevantes.
- Los resultados de búsqueda deben mostrarse en forma de lista o cuadrícula, con la opción de visualizar detalles de cada propiedad.

**4. Visualización detallada de propiedades:**

- Los arrendatarios deben poder hacer clic en una propiedad para ver una página con los detalles completos, incluyendo fotos, descripción, precio, ubicación en un mapa, y la información del propietario.

**5. Sistema de contacto entre arrendatarios y propietarios:**
- Los arrendatarios deben poder enviar mensajes a los propietarios directamente desde la plataforma para hacer consultas sobre una propiedad.
- El propietario debe recibir una notificación cuando un arrendatario haya enviado un mensaje o mostrado interés en una propiedad.

##No funcionales
**1. Seguridad:**
- El sistema debe implementar medidas de seguridad como cifrado de contraseñas y datos personales, para proteger la información de los usuarios.
- Los datos sensibles de los usuarios deben estar protegidos contra accesos no autorizados, con autenticación segura y políticas de privacidad claras.

**2. Rendimiento:**
- La plataforma debe ser capaz de manejar múltiples usuarios simultáneamente, con tiempos de respuesta inferiores a 3 segundos para la mayoría de las operaciones.
- Las consultas de búsqueda deben ejecutarse de manera eficiente, incluso con un gran volumen de datos.

**3. Compatibilidad y accesibilidad:**
- El sistema debe ser completamente responsivo y accesible desde dispositivos móviles, tablets y computadoras de escritorio.
- La interfaz debe cumplir con las normas de accesibilidad (WCAG), para que personas con discapacidades puedan utilizar la plataforma.

**4. Escalabilidad:**
- La plataforma debe ser escalable para manejar el crecimiento en el número de usuarios y propiedades sin comprometer su rendimiento.
- El sistema debe permitir la adición de nuevas funcionalidades sin grandes cambios en la arquitectura existente.

**5. Disponibilidad:**
- La plataforma debe estar disponible el almenos el 99.9% del tiempo, con tiempos de inactividad mínimos y un sistema de backup para asegurar la continuidad del servicio.
- El sistema debe contar con soporte técnico disponible para resolver posibles problemas y mantener la plataforma en funcionamiento.

#Historias de usuario
