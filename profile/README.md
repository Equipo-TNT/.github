## 🌿 **Nombre tentativo**: *“Habita”*

**Tu espacio digital de bienestar emocional y productividad personal** 🌱

------

### 🎯 **Pitch resumido**

**Habita** es una app móvil que combina voz e inteligencia artificial para ayudarte a gestionar tus emociones, cultivar hábitos de autocuidado y mantenerte motivado cada día. No es terapia. Es una herramienta de bienestar diseñada para acompañarte, escucharte y ayudarte a conectar contigo mismo.

------

### 🧱 **Estructura de la App**

#### 0. **Verificación de red de soporte cercana** 📱

- Al primer ingreso, el usuario confirma que cuenta con al menos una persona de apoyo (familiar o amigo) listada en sus contactos de emergencia.
- Se solicita añadir o validar un contacto de emergencia durante el onboarding.
- Este contacto recibe notificación en caso de alertas graves o falta de interacción prolongada.

#### 1. **Inicio del día – Conversación de bienvenida personalizada** 🌞

- Tavus gestiona la bienvenida matutina mediante un avatar IA que interactúa con el usuario por voz o texto. (De momento no consumimos minutos de generación de video).
- El guion de la conversación se adapta al patrón emocional de los últimos días.
- Tono amigable y empático (como un coach, no como un terapeuta).
- Ejemplo de saludo: “Hoy puedes comenzar de nuevo. Respira. Eres suficiente.”

#### 2. **Check-in emocional por voz (ElevenLabs)** 🎤

- El usuario habla con su "compañero emocional" sobre cómo se siente.
- La IA **no interpreta ni aconseja**: solo **ayuda a nombrar emociones**.
- Genera una “bitácora de emociones” personal.
- Alternativa de entrada por texto.

#### 3. **Mini prácticas de autocuidado diario** 💆‍♀️

- Rutinas simples, tipo “elige una para hoy”: respiración 4x4; escribir 3 agradecimientos; caminar sin el celular por 5 minutos; escuchar un audio relajante.
- Todo guiado por voz, sin lenguaje clínico.

#### 4. **Seguimiento de hábitos saludables** 📊

- Registro visual de hábitos: sueño, alimentación, tiempo al aire libre, tiempo en pantalla, contacto social.
- Gráficas semanales de bienestar.
- Alertas automáticas si detecta patrones preocupantes (p. ej., más de 3 días sin registro de ánimo).

#### 5. **Generación de alertas y recomendaciones** 🔔

- Análisis de la bitácora emocional para alertar al usuario cuando se detecten tendencias negativas.
- Notificaciones push: “Hemos notado que en los últimos días te has sentido bajo de ánimo. ¿Quieres hablar con alguien?”

#### 6. **Red de apoyo y alianzas** 🤝

- Sección de **Red de Apoyo** que conecta al usuario con grupos de pares (foros temáticos, chats grupales).
- **Alianzas con entidades y profesionales**: ONGs, fundaciones y coaches certificados que ofrecen recursos gratuitos o descuentos.
- Recomendación de especialistas: psicólogos, coaches de vida y terapeutas vocacionales según la ubicación y necesidades.

#### 7. **Historias reales de bienestar** 📖

- Comunidad optativa donde los usuarios comparten relatos de mejora personal.
- Los relatos más valorados se convierten en videos motivacionales con Tavus.

#### 8. **Modo premium (con RevenueCat)** 💎

- Acceso a rutinas ampliadas de bienestar.
- Audio-cápsulas sobre gestión del tiempo, enfoque y autoaceptación.
- Módulo de “retos personales” guiados: “21 días para levantarme con energía”.

------

### 🧩 **Integraciones del bootcamp** 🏆

| Requisito Bootcamp                     | Implementación en *Habita*                                   |
| -------------------------------------- | ------------------------------------------------------------ |
| **Voice AI Challenge**                 | Check-in emocional y ejercicios guiados por voz con ElevenLabs |
| **Conversational AI Video Challenge**  | Conversaciones en tiempo real con avatar IA de Tavus (solo voz y texto; video deshabilitado por falta de minutos) |
| **Deploy Challenge**                   | Despliegue en Netlify con dominio IONOS vía Entri            |
| **Make More Money Challenge**          | Monetización por suscripción con RevenueCat                  |
| **Bonus: Inspirational Story**         | Comunidad de relatos de bienestar (modo seguro y positivo)   |
| **Custom Domain Challenge**            | Uso de Entri para conectar dominio personalizado con Habita  |
| **Blockchain Challenge**               | Registro de interacciones emocionales como tokens privados (Algorand) |
| **Bonus: Creative Use of AI**          | Uso combinado de Tavus + ElevenLabs para seguimiento emocional |
| **Bonus: Most Beautiful UI**           | Interfaz simple, cálida y accesible pensada para bienestar   |
| **Bonus: Top Build-in-Public Journey** | Registro público de avances semanales durante el bootcamp    |
| **Bonus: Uniquely Useful Tool**        | Herramienta accesible con IA centrada en bienestar y utilidad diaria |
| **Bonus: Most Viral Project**          | Potencial viral gracias a historias reales compartidas por la comunidad |
| **Bonus: Future Unicorn**              | Escalabilidad global en bienestar emocional no clínico con modelo freemium |
| **Bonus: Sharpest Problem Fit**        | Enfoque en un problema real: usuarios que necesitan herramientas no clínicas para autocuidado diario |
| **We Didn’t Know We Needed This**      | Interacción emocional diaria simplificada, con IA, sin barreras clínicas |
| **Most Likely to Get Funded**          | Propuesta clara, viable, con monetización y enfoque ético    |



------

### 🛠️ **Tecnologías utilizadas** 🔧

#### **Backend:**

- **Lenguaje:** C# 💻
- **Base de datos:** PostgreSQL 🗃️
- **Backend-as-a-Service:** Supabase (para gestión de bases de datos y autenticación) 🔒
- **API:** RESTful API para comunicación entre el backend y el frontend 🌐

#### **Frontend:**

- **Web:** React 🌍
- **Móvil:** Flutter (para Android e iOS) 📱

#### **Otras tecnologías y herramientas:**

- **IA Conversacional:** Tavus (para las interacciones en voz y texto) 🗣️
- **Voice AI:** ElevenLabs (para check-in emocional por voz) 🎙️
- **Notificaciones Push:** Firebase 🔥
- **Monetización:** RevenueCat (gestión de suscripciones) 💳
- **Blockchain:** Algorand (para registrar interacciones emocionales como tokens privados) 🔗

------

### 📁 **Organización en GitHub** 👨‍💻

- El proyecto está organizado en un repositorio público de GitHub.
- Utilizamos **GitHub Projects** para gestionar tareas y asignar responsabilidades.
- Cada funcionalidad o componente tiene su propio **branch** en GitHub, siguiendo la metodología de Git Flow.
- **Issues:** Para el seguimiento de bugs, mejoras y tareas.

### **Desarrolladores involucrados en el proyecto:** 👨‍💻

- **[Santiago Arenas](https://github.com/Arenas07)** - *Arenas07* 🎩
- **[Jose David Florez Navarrete](https://github.com/JoseDFN)** - *JoseDFN* 💼
- **[Juan Carlos Flórez](https://github.com/juancarlosfc5)** - *juancarlosfc5* 👔
- **[Juan David](https://github.com/Juanfrxz)** - *Juanfrxz* 🧑‍💻
- **[Julián Camilo Villamizar Montañez](https://github.com/JulianCVM)** - *JulianCVM* 🧑‍🎓
- **[Kevin Angarita](https://github.com/kevincito0987)** - *kevincito0987* 👓
- **[addsdev-campuslands](https://github.com/addsdev-campuslands)** - *addsdev-campuslands* 🚀

------

### 📜 **Mensajes legales y disclaimers** ⚖️

En el onboarding, incluir:

> **“Habita no es una herramienta médica ni reemplaza la atención profesional en salud mental. Si necesitas ayuda clínica, consulta con un psicólogo certificado.”**

Y también en la App Store:

> Categoría: Bienestar, Autocuidado, Estilo de vida.
>  Evitar términos: salud mental, terapia, diagnóstico, ansiedad, depresión.

------

### 🎯 **Valor diferencial** 🌟

- Usa IA legalmente segura 🔐.
- Impacto emocional sin ser invasivo ni clínico 💖.
- Conecta a personas con apoyo real y comunidades 🤗.
- Ofrece alertas proactivas y recomendaciones de especialistas 🧑‍⚕️.
- Monetiza sin barreras regulatorias 💵.

------

### 💬 **Frase inspiradora** ✨

*"Hoy es un buen día para empezar de nuevo. No estás solo/a, y siempre hay espacio para crecer y ser mejor."* 🌱
