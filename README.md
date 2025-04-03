#Tema: Sistema de Encriptación en Tiempo Real para E-Commerce  
**Nombre**: Jimmy Santiago Ayala Garrido  

## Resumen  
El proyecto busca implementar un sistema de encriptación en tiempo real para proteger datos sensibles (nombres, teléfonos, emails y métodos de pago) en un e-commerce **antes** de que sean almacenados en la base de datos.  

## Contexto  
- **Problema actual**: La encriptación suele realizarse *después* de recibir los datos, generando vulnerabilidades.  
- **Regulaciones**: El GDPR y otras normas exigen protección de datos desde el diseño.  
- **Desconocimiento**: Los usuarios no siempre comprenden cómo se protege su información.  

## Planteamiento del Problema  
1. **Exposición de datos**: Información sensible vulnerable durante el envío/almacenamiento.  
2. **Limitaciones económicas**: Pymes con recursos limitados no implementan soluciones robustas.  
3. **Desconfianza del cliente**: Resistencia a compartir datos personales por falta de transparencia.  

## Objetivos  
### General  
Desarrollar un sistema de encriptación en tiempo real desde el *front-end* hasta la base de datos.  

### Específicos  
- Implementar cifrado **AES-256 + RSA** antes del almacenamiento.  
- Notificar al usuario mediante la interfaz sobre el proceso de protección.  
- Cumplir con los estándares del **GDPR**.  

## Metodología  
### Tecnologías  
- **Front-end**: React.js + WebCrypto API (encriptación del lado del cliente).  
- **Back-end**: Node.js.  
- **Base de datos**: MongoDB.  

### Fases  
1. **Investigación**: Análisis de algoritmos criptográficos y requisitos legales.  
2. **Prototipo**: Demo interactivo de encriptación en el navegador.  
3. **Implementación**: Conexión Front-end y Back-end con flujo de encriptación.  
4. **Pruebas**: Simulación de ataques para evaluar robustez.  

## Conclusión  
El sistema propuesto:  
- Reduce riesgos de brechas de seguridad.  
- Garantiza cumplimiento legal (GDPR).  
- Aumenta la confianza del cliente mediante transparencia.  
