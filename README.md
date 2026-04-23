# 🔧 ServiMatch - El servicio ideal, con la confianza que necesitás

### Codigo Maestro -  Proyecto Integrador II - Primer Cuatrimestre - 2026

## ⚠️ Situación Problemática

En la vida cotidiana, es frecuente que las personas necesiten resolver problemas domésticos o realizar mejoras en sus hogares, como arreglos eléctricos, trabajos de carpintería  o tareas de pintura. Estas situaciones suelen surgir de manera imprevista por ejemplo, un corte eléctrico, una pérdida o una reparación urgente lo que obliga a tomar decisiones rápidas para encontrar un profesional que pueda solucionar el problema.

En este contexto, la búsqueda de trabajadores de oficio se da, en la mayoría de los casos, a través de medios informales. Las personas consultan a familiares, amigos o conocidos, revisan publicaciones en redes sociales o grupos de compra y venta, e incluso recurren a anuncios pegados en la vía pública. Durante este proceso, los usuarios suelen evaluar opciones con información limitada, basándose en comentarios subjetivos, recomendaciones poco verificables o simplemente en la disponibilidad inmediata del trabajador.

Esta forma de búsqueda genera una experiencia cargada de incertidumbre. Los usuarios no tienen garantías sobre la calidad del servicio, la experiencia del profesional ni su confiabilidad. Como consecuencia, pueden surgir situaciones problemáticas como incumplimiento de horarios, trabajos mal realizados, sobreprecios o incluso riesgos relacionados con la seguridad del hogar. Esta desconfianza no solo afecta la decisión inicial de contratación, sino también la tranquilidad del usuario durante todo el proceso.

Por otro lado, los trabajadores de oficio que sí son responsables y brindan un buen servicio también se ven perjudicados. Al no existir un sistema formal que respalde su trayectoria, calificaciones o experiencia, dependen exclusivamente del “boca en boca” para conseguir nuevos clientes, lo que limita su crecimiento y visibilidad frente a otros profesionales.

Esta problemática se desarrolla en un contexto donde la tecnología y la digitalización han avanzado significativamente en otros ámbitos, pero aún presentan una falta de soluciones organizadas y confiables en el sector de servicios de oficios.

La identificación de este problema surge a partir de la observación de situaciones concretas en el entorno cotidiano, donde se repite el mismo patrón: personas que necesitan resolver un problema, recurren a medios informales y experimentan dudas o resultados insatisfactorios. Estos pain points permitieron reconocer la necesidad de una solución que reduzca la incertidumbre, mejore la confianza y facilite la conexión entre clientes y profesionales.

En este marco, nace la propuesta de ServiMatch, una aplicación web orientada a organizar y transparentar el proceso de búsqueda y contratación de servicios de oficios, brindando herramientas como verificación de identidad, calificaciones reales, historial de trabajos y comunicación directa entre las partes.


## 📋 Listado de Requerimientos

### ✅ Requerimientos Funcionales

- **RF1:** El usuario podrá registrarse en la plataforma mediante un formulario con sus datos personales.  
- **RF2:** El usuario podrá iniciar sesión utilizando su correo electrónico y contraseña.  
- **RF3:** El usuario podrá buscar profesionales filtrando por tipo de oficio y ubicación.  
- **RF4:** El usuario podrá visualizar un listado de profesionales disponibles según los criterios de búsqueda.  
- **RF5:** El usuario podrá acceder al perfil detallado de cada profesional, incluyendo datos personales, experiencia, calificaciones y trabajos realizados.  
- **RF6:** El profesional podrá editar su información, experiencia y datos de contacto.  
- **RF7:** El administrador podrá validar la identidad de los profesionales antes de que sean visibles en la plataforma.  
- **RF8:** El administrador podrá gestionar los usuarios registrados (alta, baja o modificación).  
- **RF9:** El sistema permitirá almacenar y mostrar calificaciones y opiniones de los usuarios sobre los profesionales.

##  Requerimientos No Funcionales

- **RNF1:** Diseño Responsivo
La interfaz debe adaptarse correctamente a dispositivos móviles, tablets y computadoras utilizando diseño responsive (por ejemplo, Bootstrap).
- **RNF2:** Usabilidad
La aplicación debe ser intuitiva y fácil de usar, permitiendo que un usuario pueda buscar y contactar un profesional en pocos pasos.
- **RNF3:** Seguridad
El sistema debe proteger los datos personales de los usuarios mediante autenticación segura y almacenamiento cifrado de contraseñas.
- **RNF4:** Validación de Datos
 El sistema no debe permitir el envío de formularios con campos vacíos o datos inválidos (como correos electrónicos incorrectos).
- **RNF5:** Rendimiento
El sistema debe responder a las búsquedas y acciones del usuario en un tiempo adecuado.
- **RNF6:** Integridad de Datos (Persistencia)
El sistema debe garantizar que los datos almacenados en la base de datos MySQL no se pierdan ni se corrompan ante fallos del sistema.
