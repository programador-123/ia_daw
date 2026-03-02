# IA_a
## **Autor**: *Miguel Angel Perez Gonzalez*

1) Describe el proceso “ANTES” (sin IA)
¿Quién lo hace? (rol/equipo)
**Hacker:** Es el principal responsable de las brechas de seguridad. Y se ayuda en sus scripts, archivos.txt "Fuerza Bruta", etc.
¿Qué pasos tiene? (5–7 pasos)
1. Busca a la victima o espera a que alguien caiga
2. Busca informacion de el/ella en paginas, redes o en la vida real
3. Crea un archivo con algunas palabras que puedan ser posibles contraseñas para acceder a su usuario
4. Si no lo consigue a la fuerza bruta creara scripts para intentar descifrar la contraseña, o lo hara con programas de terceros.
5. Una vez dentro puede hacer muchas cosas pero digamos que empieza a buscar una de las que mas se utilizan es la extorsion, ya sea por contenidos intimos, datos sensibles, etc
6. Y una vez pague, intenta borrar todos sus pasos para que no lo detecten.
¿Cuánto tarda? (estimación)
- Puede durar minutos, horas, dias, semanas, meses pero para poner un ejemplo si estamos hablando por ejemplo de un banquero y de mientras que intenta recopilar informacion y prueba con las posibles contraseñas unos 4 o 5 dias no se lo quita nadie
¿Qué errores o cuellos de botella hay?
- La contraseña es el mayor problema ya que es la que mas tiempo consume una vezdentro solo depende de la victima


### ¿Qué pasos tiene? (5–7 pasos)

1. Identifica posibles objetivos vulnerables (personas o empresas).
2. Recopila información pública disponible (redes sociales, webs, filtraciones previas).
3. Intenta acceder a cuentas mediante técnicas automatizadas de prueba de credenciales.
4. Si detecta una debilidad, intenta explotarla para obtener acceso no autorizado.
5. Una vez consigue acceso, puede intentar obtener información sensible o beneficios económicos.
6. Finalmente, trata de ocultar su actividad para evitar ser detectado.

---

### ¿Cuánto tarda? (estimación)

El tiempo puede variar mucho:

- Ataques automatizados simples: minutos u horas.
- Ataques dirigidos contra perfiles específicos: varios días.

Por ejemplo, si el objetivo es una persona con un perfil profesional relevante, el proceso puede durar 4 o 5 días.

---

### ¿Qué errores o cuellos de botella hay?

- Contraseñas robustas dificultan el acceso.
- Sistemas con doble factor de autenticación bloquean el ataque.
- Sistemas de detección pueden identificar intentos repetidos.
- Falta de información útil sobre la víctima.

---

## 2) Propón la automatización con IA (DESPUÉS)

### ¿Qué parte automatiza la IA?

La IA puede automatizar principalmente:

- Clasificación: detectar intentos sospechosos de inicio de sesión (múltiples intentos fallidos, ubicaciones inusuales, horarios extraños).
- Predicción: anticipar comportamientos anómalos comparando con el patrón habitual del usuario.
- Extracción: analizar grandes volúmenes de logs automáticamente.
- Detección de anomalías: identificar patrones típicos de ataques automatizados.
- Generación automática: crear alertas e informes de seguridad en tiempo real.

---

### ¿Qué queda para humanos?

- Validar alertas críticas.
- Tomar decisiones importantes (bloqueo de cuentas, comunicación con usuarios).
- Ajustar políticas de seguridad.
- Supervisar y mejorar el sistema de IA.

---

### ¿Qué datos necesitaría la IA? (sin datos sensibles)

- Logs de acceso (fecha, hora, IP, número de intentos).
- Historial de intentos fallidos.
- Ubicación aproximada por IP.
- Tipo de dispositivo o navegador.
- Registros de actividad del sistema.
- Historial de incidentes previos.

---

## 3) Explica la OPTIMIZACIÓN (mejora medible)

### Métrica 1: Tiempo

ANTES: 
La detección de actividad sospechosa podía tardar horas o días si dependía de revisión manual.

DESPUÉS (con IA): 
La detección se realiza en segundos o minutos.

Mejora estimada: 
De 4–5 horas → 5–10 minutos por incidente. 
Reducción aproximada del 80–90% en tiempo de detección.

---

### Métrica 2: Coste

ANTES: 
Muchas horas de trabajo manual revisando registros.

DESPUÉS: 
La IA filtra automáticamente eventos normales y destaca solo los sospechosos.

Mejora estimada: 
Reducción del 30–40% en horas dedicadas a análisis manual.

---

### Métrica 3: Calidad / Precisión

ANTES:
- Elevado número de falsas alarmas.
- Algunos ataques no detectados a tiempo.

DESPUÉS:
- Mejor priorización de riesgos.
- Mayor tasa de detección temprana.

Mejora estimada: 
Incremento del 50% en precisión y reducción significativa de falsos positivos.

---

## Conclusión

El uso de IA en ciberseguridad permite:

- Detectar amenazas en tiempo real.
- Reducir costes operativos.
- Mejorar la precisión en la identificación de riesgos.
- Proteger mejor a usuarios y organizaciones frente a accesos no autorizados.
