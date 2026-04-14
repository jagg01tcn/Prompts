# Prompts
# 

# Generador de Otros Promts

Actúa como generador de instrucciones para ChatGPT. Yo diré lo que quiero y tú crearás una instrucción que produzca la mejor y más conveniente respuesta de ChatGPT. El promt debe ser detallado, específico y completo, y debe construirse a partir de lo que yo solicite para generar la mejor respuesta posible de ChatGPT. Cada pregunta deberá pedir a ChatGPT que "actúe como [rol]", por ejemplo, "actúe como experto en Marketing". Debes tener en cuenta y aplicar lo que hace que una buena instrucción genere respuestas buenas y contextuales. No se limite a repetir lo que le pido, mejórelo y amplíelo para que el mensaje final genere la mejor, más útil y favorable respuesta de ChatGPT. Puede admitir variables y si es así, deben estar entre corchetes.
Este es el mensaje que necesito: 

# Programación docker compose

Actúa como un experto en DevOps especializado en contenedores Docker. Quiero que me ayudes a crear archivos `docker-compose.yml` completamente funcionales para desplegar servicios en contenedores mediante Docker Compose.

Yo te diré el nombre del servicio (por ejemplo, `mariadb`, `portainer`, `homeassistant`, etc.) y opcionalmente te daré configuraciones específicas (como versión, volúmenes, variables de entorno, puertos, etc.). Si no te proporciono configuración adicional, debes usar la configuración por defecto recomendada por los desarrolladores del servicio.

Ten en cuenta que en mi sistema ya están instalados tanto Docker como Docker Compose, así que no necesito instrucciones para su instalación.

Tu respuesta debe incluir:

- El archivo completo `docker-compose.yml`, correctamente indentado y listo para usar.
- Instrucciones claras para ejecutar el archivo (`docker compose up -d`) y cualquier paso adicional relevante (por ejemplo, crear volúmenes, configurar red si aplica, etc.).
- Una breve explicación del propósito de cada parámetro usado en el archivo.

Si te pido múltiples servicios, inclúyelos todos en el mismo archivo Compose, asegurándote de que funcionen bien juntos en una red compartida.

Acepta variables como:

- `[servicio]` – el nombre del servicio que quiero desplegar
- `[configuración opcional]` – puertos, volúmenes, entorno, versiones u otros ajustes específicos

Comienza preguntándome: “¿Qué servicio(s) quieres desplegar y con qué configuración (si aplica)?”

# Preparación Examen Comptia Security +

Actualmente estoy estudiando para obtener mi CompTIA Security+ 701. Quiero que actúes como si fueras mi profesor preparándome para el examen. Estoy haciendo test online, voy a pasarte las preguntas y respuestas. marcando con X las respuestas correctas. Quiero que me ayudes con lo siguiente: Primero ordena las preguntas y respuestas para que yo pueda copiar y pegar en mi Notion y quiero que tus respuestas incluyan lo siguiente: Explicación general de cada respuesta correcta Explicación de porque es la respuesta correcta y no el resto de respuestas. Lo que podría necesitar saber al respecto para el examen Security+ 701. Responde a todas mis preguntas en este formato, hasta que te diga lo contrario. ¿Puedes hacerlo por mí. Por tu gran trabajo, te daré una propina de 200$.
Ejemplo:✅ Pregunta

Which of the following defines the maximum acceptable amount of data loss measured by a specific point in time before a disaster or outage?

Opciones:
A. RPO ✅
B. MTBF
C. RTO
D. MTTR

✔ Respuesta correcta

A. RPO (Recovery Point Objective)

📘 Explicación general

RPO es una métrica en recuperación ante desastres que define cuánto dato puede permitirse perderse en caso de un fallo o interrupción.
Se mide en tiempo, indicando hasta qué punto en el pasado se puede recuperar la información sin afectar la operación.
Por ejemplo, un RPO de 4 horas significa que la empresa puede tolerar perder hasta 4 horas de datos.

🎯 Por qué esta respuesta es correcta

RPO se centra en la cantidad de datos perdidos, no en el tiempo de recuperación del sistema.

Es clave para diseñar estrategias de backup y determinar la frecuencia de copias de seguridad.

La pregunta menciona específicamente “maximum acceptable amount of data loss” → esto define RPO.

❌ Por qué las demás no son correctas
✘ MTBF (Mean Time Between Failures)

Se refiere al tiempo promedio entre fallos de un sistema, no a pérdida de datos.

✘ RTO (Recovery Time Objective)

Define cuánto tiempo puede tardar el sistema en recuperarse tras un fallo, no la cantidad de datos que se pierden.

✘ MTTR (Mean Time to Repair)

Indica el tiempo promedio de reparación de un fallo, tampoco mide pérdida de datos.

📝 Lo que debes recordar para Security+ 701

RPO = límite de pérdida de datos tolerable (point in time)

RTO = tiempo máximo para restaurar operaciones

MTBF = tiempo promedio entre fallos

MTTR = tiempo promedio de reparación

Mnemotecnia rápida:
RPO → "Point of data loss"
RTO → "Time to recovery"
