# Unidades de medida en diseño web
## 📐 5. Glosario : Unidades de Medida en CSS
*Las reglas de medición técnicas para lograr que una interfaz sea flexible, accesible y responsive.*

> [!IMPORTANT]
> **Regla de Accesibilidad:** Nunca uses unidades absolutas (`px`) para textos. Si el usuario aumenta el tamaño de la fuente en la configuración de su navegador por problemas visuales, los píxeles bloquearán el cambio y tu web no será accesible.

* **El Píxel (px)** `[Unidad Absoluta]`
  * **Concepto:** Representa un punto fijo y exacto en la pantalla. No cambia ni se escala bajo ninguna circunstancia.
  * **Ejemplo Real:** Se usa para elementos rígidos de la interfaz que jamás deben deformarse, como bordes, sombras o iconos pequeños.
  * **Ejemplo Práctico:** `border: 1px solid #333;` o `width: 24px;` para un icono de menú.

* **REM (Root EM)** `[Unidad Relativa a la Raíz]`
  * **Concepto:** Escala en base al tamaño de fuente del elemento raíz (`<html>`). Por defecto, 1rem equivale a 16px.
  * **Ejemplo Real:** Es la unidad reina para la tipografía general de blogs, periódicos digitales y plataformas accesibles.
  * **Ejemplo Práctico:** `font-size: 1.5rem;` (equivalente a 24px en navegadores estándar) para asegurar que el texto sea escalable.

* **EM** `[Unidad Relativa al Padre]`
  * **Concepto:** Escala en base al tamaño de fuente de su contenedor o elemento padre directo.
  * **Ejemplo Real:** Se utiliza para crear componentes modulares y armónicos que mantienen sus proporciones internas (como botones o tarjetas).
  * **Ejemplo Práctico:** `padding: 1em;` dentro de un botón. Si la letra del botón se agranda, el espacio interior crece en perfecta proporción.

* **Porcentaje (%)** `[Unidad Relativa al Contenedor]`
  * **Concepto:** Toma como referencia el ancho o alto disponible que le hereda su contenedor directo.
  * **Ejemplo Real:** Es la base estructural para maquetar rejillas de diseño (*layouts*) tradicionales, barras laterales y secciones divididas.
  * **Ejemplo Práctico:** `width: 75%;` para el contenedor de artículos principales y `width: 25%;` para la barra lateral informativa.

* **VH y VW (Viewport Height / Width)** `[Unidades Relativas a la Ventana]`
  * **Concepto:** Representan el 1% exacto de la altura (`vh`) o del ancho (`vw`) total de la ventana del navegador.
  * **Ejemplo Real:** Ideal para secciones de bienvenida impactantes (*Hero Sections*) o pantallas de inicio de sesión que capturan la pantalla completa.
  * **Ejemplo Práctico:** `height: 100vh;` para forzar a una sección de landing page a cubrir verticalmente todo el monitor del usuario.

* **La Función Clamp()** `[Función de Control Fluido]`
  * **Concepto:** Define un rango dinámico mediante tres valores: un límite mínimo, un valor preferido y un límite máximo.
  * **Ejemplo Real:** Sitios modernos e innovadores (como Stripe o portafolios interactivos) que cambian el tamaño de sus títulos suavemente sin usar *media queries*.
  * **Ejemplo Práctico:** `font-size: clamp(1.5rem, 5vw, 3rem);` (Nunca bajará de 1.5rem en móviles, escalará en tablets y se detendrá en 3rem en monitores grandes).

---

## 📊 Matriz de Predicción: ¿Qué unidad usar y cuándo?

Esta tabla predice y clasifica la mejor unidad de medida dependiendo del tipo de elemento y el objetivo UX/UI del sitio web:

| Elemento UI | Tipo de Página/Sección | Unidad Recomendada | Predicción de Comportamiento UX/UI |
| :--- | :--- | :---: | :--- |
| **Títulos Principales (H1)** | Landing Pages y Sitios Corporativos | `clamp()` | **Fluidez perfecta:** El título se adapta al ancho de cualquier pantalla sin romperse ni desbordarse. |
| **Textos y Párrafos (p)** | Blogs, Foros y Páginas de Noticias | `rem` | **Accesibilidad garantizada:** Si el usuario tiene problemas de vista y agranda la fuente del navegador, el texto lo respeta. |
| **Botones y Badges** | Tiendas Virtuales (E-commerce) | `em` | **Proporción armónica:** El espacio interior (*padding*) mantendrá simetría visual si el botón cambia de tamaño. |
| **Estructura de Columnas** | Paneles de Control (Dashboards) | `%` | **Diseño adaptable:** Distribuye el espacio de trabajo de forma exacta sin importar las dimensiones del monitor. |
| **Pantallas de Portada / Hero** | Portafolios y Páginas de Producto | `vh` | **Impacto visual:** Asegura que la primera sección cubra el 100% de la pantalla del dispositivo al cargar. |
| **Bordes y Sombras** | Formularios e Interfaces Limpias | `px` | **Rigidez necesaria:** Mantiene las líneas divisorias nítidas y delgadas, sin riesgo de que se distorsionen. |