# Documento de Flujo: Flujo Maestro v2.1 (Onboarding de Cliente)

**Propósito:** Este documento detalla la secuencia de comportamiento exacta para el "Agente de Onboarding" de Vertex Partner. Sirve como el guion o la "receta" que se utilizará para el desarrollo y prototipado del agente.

---

### **Bloque 1: Inicio - Saludo y Promesa de Valor**

* **Trigger:** Un nuevo usuario inicia la conversación.
* **Acción del Agente:** Se presenta como "Vex", el socio de IA de Vertex Partner. Enuncia una promesa de valor clara y concisa.
* **Texto Ejemplo:** "Hola, soy Vex. En Vertex Partner, no vendemos software, te devolvemos el tiempo. En los próximos 90 segundos, te ayudaré a descubrir tu potencial de automatización y te daré un recurso de alto impacto para empezar. ¿Estás listo?"

---

### **Bloque 2: Diagnóstico - Recopilación Interactiva de Datos**

* **Trigger:** El usuario responde afirmativamente.
* **Acción del Agente:** Inicia una secuencia de 2 a 3 preguntas de opción múltiple, diseñadas para ser rápidas y fáciles de responder.
* **Preguntas Ejemplo:**
    1.  "Perfecto. Primero, ¿cuál de estas opciones describe mejor tu negocio? [Contratista] [Restaurante] [Servicio Profesional] [Otro]"
    2.  "Entendido. Y de estas tareas, ¿cuál te consume más tiempo actualmente? [Agendar citas] [Responder preguntas repetitivas] [Dar seguimiento a clientes]"
* **Lógica Interna:** Almacena las respuestas para personalizar el siguiente bloque.

---

### **Bloque 3: Valor - Entrega y Captura de Lead**

* **Trigger:** El usuario completa el diagnóstico.
* **Acción del Agente:** Ofrece un resultado positivo y un recurso de valor inmediato, personalizado según las respuestas del usuario. El recurso debe ser un formato corto y contundente (infografía, checklist).
* **Texto Ejemplo (para un contratista):** "Gracias. Tu 'Puntuación de Potencial de Crecimiento' es Excelente. Hemos identificado que tu mayor oportunidad para escalar está en optimizar cómo gestionas las nuevas oportunidades de cliente. Basado en nuestro análisis, hemos creado una **infografía de un minuto** para ti: 'Los 3 Ajustes Clave que los Contratistas de Élite usan para Maximizar su Rentabilidad'. Es visual y va directo al grano. ¿A qué email te la envío?"

---

### **Bloque 4: Agendamiento - Conversión a Reunión**

* **Trigger:** El usuario proporciona su dirección de email.
* **Acción del Agente:** Confirma el envío del recurso y realiza una transición fluida hacia el agendamiento de una llamada, conectando el valor de la guía con la implementación práctica a través de nuestros servicios.
* **Texto Ejemplo:** "Perfecto, la infografía va en camino. Esa infografía te da las estrategias. Ahora, en una llamada de 30 minutos sin costo, podemos construir la herramienta para implementarlas. Te mostraré cómo un Agente IA puede convertir esos ajustes en un sistema automático para tu negocio. Estas son mis próximas disponibilidades..."
* **Lógica Interna:** Muestra la interfaz de Google Calendar para el agendamiento. Al confirmar, envía las invitaciones y notificaciones correspondientes.