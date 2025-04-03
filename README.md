# Tema: Encriptación en tiempo real para un e-commerce
**Nombre**: Jimmy Santiago Ayala Garrido

## Resumen 
Su busca alcanzar un sistema de encriptación en tiempo real para gestionar los datos sensibles de un e-commerce, tales como, nombres, teléfonos, emails y métodos de pagos antes de que estos mismos sean guardados o almacenados dentro de la base de datos.

## Contexto
Muchos negocios realizan los procesos de encriptación después de recibir los datos, cuál deja un espacio para que ocurran brechas de seguridad. Además, hay regulaciones como el Reglamento General de Protección de Datos (GDPR) que exigen en un marco legal implementar la protección de datos. Más aún, existe un gran desconocimiento de parte de los usuarios al proteger su información.

## Planteamiento del problema 
1. Los datos sensibles están expuestos a vulnerabilidades al enviar o almacenar sin encriptarlos.
2. Tiendas en línea que tienen una pequeña escalabilidad de negocio no cuentan con el capital suficiente para implementar modelos seguros.
3. Los clientes tienden a desconfiar del momento de compartir su información personal.

## Objetivo 
### General
Desarrollar un sistema de encriptación en tiempo real para la gestión de datos sensibles desde el front-end hasta almacenar en la base de datos.

### Específicos
- Usar el cifrado AES-256 + RSA antes de guardar los datos sensibles en la base de datos
- Informar al usuario o cliente por medio de la interfaz de usuario
- Garantizar los estándares del GDPR

## Metodología

### Tecnologías:
-React.js (Front-end)
- Node.js (Back-end)
- MongoDB (Base de datos)
- WebCrypto API (Encriptación de parte del cliente)

### Fases
1. **Investigación**: Evaluar algoritmos de criptografía y sus requerimientos
2. **Prototipo**: Un demo interactivo sobre la encriptación mediante el navegador
3. **Implementación:** Conectar entre Front-end y el Back-end
4. **Pruebas**: Simulación ante un ataque malicioso

## Conclusión 
Con este sistema se busca solventar la protección de datos sensibles que nos permite reducir riesgos, seguir las normas legales y mostrar transparencia al cliente con sus datos de manera que sea más fiable. 
