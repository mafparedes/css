# Buscar todo las leyes ux t ui
## https://lawsofux.com/es/

# 🎨 Guía de Leyes UX/UI para Diseño Web

> [!TIP]
> **Regla de Oro:** La experiencia de usuario (`UX`) define **cómo funciona** la interfaz, mientras que la interfaz de usuario (`UI`) define **cómo se ve**.

---

## 🚀 1. Leyes de Heurística y Comportamiento
*Cómo interactúan, navegan y actúan los usuarios dentro de tu sitio web.*

* **Ley de Jakob** `[UX]`
  * **Concepto:** Los usuarios esperan que tu web funcione igual a las que ya conocen.
  * **Ejemplo Real:** El carrito de compras de Amazon siempre está arriba a la derecha.
  * **Ejemplo Práctico:** Al programar un e-commerce, mantén el carrito arriba a la derecha para no confundir al cliente.

* **Ley de Hick** `[UX + UI]`
  * **Concepto:** A mayor cantidad de opciones, más tiempo tarda el usuario en decidir.
  * **Ejemplo Real:** Netflix reduce la fatiga mental dividiendo las películas por categorías pequeñas.
  * **Ejemplo Práctico:** En lugar de un menú plano con 20 botones, usa un menú desplegable limpio con 5 secciones básicas.

* **Ley de Fitts** `[UX + UI]`
  * **Concepto:** Los botones importantes deben ser grandes y fáciles de alcanzar.
  * **Ejemplo Real:** El botón de "Play" en Spotify móvil es gigante y está al alcance del pulgar.
  * **Ejemplo Práctico:** Dale un buen tamaño y bastante margen (`padding: 15px;`) a tus botones de "Comprar".

* **Ley de Parkinson** `[UX]`
  * **Concepto:** El usuario tardará tanto tiempo como le permitas para terminar una tarea.
  * **Ejemplo Real:** Las páginas de conciertos te dan un límite de 10 minutos para pagar tus entradas.
  * **Ejemplo Práctico:** Incluye un temporizador visual en tus formularios de reserva para acelerar la conversión.

* **Umbral de Doherty** `[UX]`
  * **Concepto:** El sistema debe responder en menos de 400ms para mantener la atención del usuario.
  * **Ejemplo Real:** Las sugerencias instantáneas de Google Search mientras vas escribiendo.
  * **Ejemplo Práctico:** Implementa un esqueleto de carga animación (*skeleton screen*) mientras tu base de datos procesa información.

* **Ley de Postel** `[UX]`
  * **Concepto:** Sé flexible con los datos que introduce el usuario, pero estricto con lo que procesas.
  * **Ejemplo Real:** Formularios que aceptan números de teléfono con o sin guiones, espacios y paréntesis.
  * **Ejemplo Práctico:** Programa tu backend para que limpie automáticamente los espacios vacíos que deje el usuario por error.

---

## 🧠 2. Leyes de la Memoria y Cognición
*Cómo el cerebro procesa, recuerda y asimila la información visual.*

* **Ley de Miller** `[UX]`
  * **Concepto:** La memoria de trabajo a corto plazo solo retiene entre 5 y 9 elementos a la vez.
  * **Ejemplo Real:** Los menús principales de plataformas como Stripe no superan las 6 pestañas de navegación.
  * **Ejemplo Práctico:** Divide los números de las tarjetas de crédito en bloques de 4 dígitos en lugar de un bloque de 16 números juntos.

* **Efecto de Posición en Serie** `[UX + UI]`
  * **Concepto:** El ser humano siempre recuerda mejor el primer y el último elemento de una lista o menú.
  * **Ejemplo Real:** Instagram ubica "Home" al extremo izquierdo y "Perfil" al extremo derecho del menú inferior.
  * **Ejemplo Práctico:** En tu barra de navegación web, coloca "Inicio" al principio y el botón de "Contacto" al final del todo.

* **Efecto Von Restorff** `[UI]`
  * **Concepto:** Si hay varios objetos similares, el elemento que resalte visualmente será el más recordado.
  * **Ejemplo Real:** Destacar el plan "Más Popular" de una suscripción con una tarjeta más grande.
  * **Ejemplo Práctico:** Usa un color de contraste llamativo (como naranja o rojo) únicamente para el botón de llamada a la acción primordial (`CTA`).

* **Efecto Zeigarnik** `[UX]`
  * **Concepto:** Recordamos y nos enganchamos más con las tareas incompletas que con las terminadas.
  * **Ejemplo Real:** LinkedIn te muestra constantemente una barra indicando: *"Tu perfil está al 80%"*.
  * **Ejemplo Práctico:** Al diseñar un formulario largo, divídelo en etapas (Paso 1 de 3) para incentivar al usuario a terminarlo.

* **Carga Cognitiva** `[UX]`
  * **Concepto:** Es el esfuerzo mental necesario para entender una interfaz. Menos elementos = menos cansancio.
  * **Ejemplo Real:** El buscador de Google prefiere una pantalla blanca minimalista frente a portales antiguos saturados de anuncios.
  * **Ejemplo Práctico:** Evita el uso excesivo de diferentes tipografías, colores de texto cruzados o pop-ups automáticos intrusivos.

---

## 👁️ 3. Principios de Percepción (Gestalt)
*Reglas visuales basadas en cómo el ojo humano agrupa elementos automáticamente.*

* **Ley de Proximidad** `[UI]`
  * **Concepto:** Elementos que están físicamente cerca se perciben como un grupo con funciones similares.
  * **Ejemplo Real:** En Google Imágenes, la descripción y el tamaño de la foto están pegados justo debajo de ella.
  * **Ejemplo Práctico:** En tu código HTML, mantén la etiqueta de título (`<label>`) con un margen mínimo sobre su cuadro de texto (`<input>`).

* **Ley de Semejanza** `[UI]`
  * **Concepto:** Elementos que comparten color, forma o tamaño se perciben como parte de la misma categoría.
  * **Ejemplo Real:** El uso del color azul y el subrayado exclusivo para identificar enlaces cliqueables en la web.
  * **Ejemplo Práctico:** Si diseñas un botón de error o cancelación en color rojo, mantén ese mismo color para todas las acciones destructivas de la web.

* **Ley de Región Común** `[UI]`
  * **Concepto:** Los elementos se ven como un grupo unificado si están encerrados dentro de una caja o borde definido.
  * **Ejemplo Real:** Las tarjetas (*Cards*) de Airbnb que encierran foto, precio y estrellas de una casa.
  * **Ejemplo Práctico:** Envuelve los bloques de contenido dentro de etiquetas `<article>` o `<div>` aplicando bordes (`border`) o sombras en CSS.

* **Ley de Conectividad Uniforme** `[UI]`
  * **Concepto:** Elementos unidos por una línea u objeto visual se perciben como más relacionados que el resto.
  * **Ejemplo Real:** Las líneas que conectan los pasos "Empaquetado ➔ En Camino ➔ Entregado" en apps de delivery.
  * **Ejemplo Práctico:** Diseña flujos de compra o barras de progreso uniendo los números de cada paso con una línea gris recta.

---

## 🛠️ 4. Otros Principios Fundamentales
*Filosofías de diseño enfocadas en la simplicidad y optimización.*

* **Navaja de Occam** `[UX + UI]`
  * **Concepto:** La solución de diseño más simple suele ser siempre la mejor opción.
  * **Ejemplo Real:** Permitir el registro rápido en una web con un solo clic usando tu cuenta de Google.
  * **Ejemplo Práctico:** Elimina campos secundarios obligatorios como "Teléfono" o "Dirección" si solo necesitas que el usuario cree una contraseña.

* **Regla de Fin de Pico** `[UX]`
  * **Concepto:** Juzgamos las experiencias por su punto más intenso (pico) y por su desenlace (final).
  * **Ejemplo Real:** Duolingo lanza confeti y sonidos de victoria inmediatamente al terminar una lección.
  * **Ejemplo Práctico:** Diseña una pantalla de éxito de compra colorida, alegre y que incluya un mensaje de agradecimiento personalizado.

* **Principio de Pareto** `[UX]`
  * **Concepto:** El 80% de los usuarios solo utiliza de forma activa el 20% de las herramientas disponibles.
  * **Ejemplo Real:** En Word o Photoshop, la mayoría solo usa funciones básicas de corte, texto y guardado.
  * **Ejemplo Práctico:** Coloca las herramientas más usadas en la pantalla de inicio visible y oculta las avanzadas en menús secundarios.

* **Ley de Tesler** `[UX]`
  * **Concepto:** Todo sistema tiene una complejidad mínima inevitable; la aplicación debe asumirla para ayudar al usuario.
  * **Ejemplo Real:** Que la app use tu GPS para autocompletar tu dirección de envío en lugar de obligarte a escribirla completa.
  * **Ejemplo Práctico:** Diseña selectores inteligentes que detecten de forma automática el tipo de tarjeta bancaria al ingresar los primeros dígitos.

---

## 📊 Matriz Comparativa de Leyes

| Ley / Principio | Enfoque | Comparación Directa |
| :--- | :---: | :--- |
| **Ley de Jakob** | **UX** | Consistencia externa vs. Diseños confusos |
| **Ley de Hick** | **UX + UI** | Opciones reducidas vs. Sobrecarga de decisiones |
| **Ley de Fitts** | **UX + UI** | Botones grandes/cercanos vs. Objetos diminutos |
| **Ley de Parkinson** | **UX** | Tiempo controlado vs. Procrastinación |
| **Umbral de Doherty** | **UX** | Respuestas veloces (<400ms) vs. Esperas frustrantes |
| **Ley de Postel** | **UX** | Flexibilidad en inputs vs. Formularios rígidos |
| **Ley de Miller** | **UX** | Segmentación clara vs. Listados abrumadores |
| **Posición en Serie** | **UX + UI** | Extremos llamativos vs. Centro ignorado |
| **Efecto Von Restorff** | **UI** | Contraste intencional vs. Elementos idénticos |
| **Efecto Zeigarnik** | **UX** | Tareas inconclusas vs. Pérdida de interés |
| **Carga Cognitiva** | **UX** | Minimalismo limpio vs. Saturación visual |
| **Ley de Proximidad** | **UI** | Cercanía temática vs. Elementos dispersos |
| **Ley de Semejanza** | **UI** | Patrones visuales idénticos vs. Caos de colores |
| **Región Común** | **UI** | Cajas contenedoreras vs. Elementos floating |
| **Conectividad** | **UI** | Líneas de guía vs. Pasos aislados |
| **Navaja de Occam** | **UX + UI** | Rutas directas vs. Pasos redundantes |
| **Fin de Pico** | **UX** | Cierres memorables vs. Finales planos |
| **Principio de Pareto** | **UX** | Destacar el 20% vital vs. Mostrar el 100% |
| **Ley de Tesler** | **UX** | Automatizar procesos vs. Trabajo manual |