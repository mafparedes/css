# SEO (DESAROLLAR EL CONTENIDO) 

---
## **📚 Clase: SEO (Posicionamiento Web) desde Cero hasta Nivel Intermedio**
*Docente: Profesor de Desarrollo de Aplicaciones Web*

---

### **🔹 Módulo 1: ¿Qué es el SEO? (Conceptos Básicos)**
**Definición:**
SEO (*Search Engine Optimization* o **Optimización para Motores de Búsqueda**) es el conjunto de técnicas para **mejorar la visibilidad de un sitio web** en los resultados orgánicos (no pagados) de motores de búsqueda como **Google, Bing o Yahoo**.

**Objetivo principal:**
Que tu página aparezca en las **primeras posiciones** cuando alguien busque palabras clave (*keywords*) relacionadas con tu contenido.

---
#### **📌 ¿Por qué es importante el SEO?**
- **Tráfico orgánico:** El 70% de los clics en Google son en resultados orgánicos (no anuncios).
- **Credibilidad:** Los usuarios confían más en los primeros resultados.
- **Experiencia de usuario:** Un buen SEO mejora la usabilidad y velocidad de tu sitio.
- **Ventaja competitiva:** Si tu competencia no lo hace, tú puedes destacar.

---
#### **🔍 ¿Cómo funcionan los motores de búsqueda?**
1. **Rastreo (*Crawling*):** Robots (como *Googlebot*) exploran la web siguiendo enlaces.
2. **Indexación:** Analizan el contenido y lo guardan en una base de datos (índice).
3. **Ranking:** Ordenan los resultados según **relevancia y calidad** para cada búsqueda.

---
---
### **🔹 Módulo 2: Tipos de SEO**
Hay **3 pilares principales**:

1. **SEO On-Page (En la página):**
   - Optimización **dentro de tu sitio web**.
   - Ejemplos:
     - **Títulos y meta descripciones** (etiquetas `<title>`, `<meta name="description">`).
     - **URLs amigables** (ej: `tusitio.com/seo-para-principiantes` en lugar de `tusitio.com/p=123`).
     - **Encabezados** (`<h1>`, `<h2>`, etc.).
     - **Contenido de calidad** (útil, original, con palabras clave naturales).
     - **Optimización de imágenes** (etiqueta `alt`, tamaño, formato).

2. **SEO Off-Page (Fuera de la página):**
   - Acciones **fuera de tu sitio** para mejorar su autoridad.
   - Ejemplos:
     - **Backlinks** (enlaces desde otros sitios a tu página).
     - **Redes sociales** (compartir contenido para generar tráfico).
     - **Menciones de marca** (que hablen de ti en blogs o foros).

3. **SEO Técnico:**
   - Optimización de la **estructura técnica** del sitio.
   - Ejemplos:
     - **Velocidad de carga** (usar herramientas como *Google PageSpeed Insights*).
     - **Mobile-Friendly** (adaptado a móviles).
     - **Estructura de URLs** (jerarquía clara).
     - **Archivo `robots.txt`** (indicar a los robots qué rastrear).
     - **Sitemap XML** (mapa del sitio para motores de búsqueda).

---
---
### **🔹 Módulo 3: Palabras Clave (*Keywords*)**
**¿Qué son?**
Términos o frases que los usuarios escriben en los motores de búsqueda (ej: *"cómo hacer pan casero"*).

**Herramientas para encontrarlas:**
- **Google Keyword Planner** (gratis con cuenta de Google Ads).
- **Ubersuggest** (versión gratuita limitada).
- **AnswerThePublic** (muestra preguntas relacionadas).

**Tipos de palabras clave:**
| Tipo               | Ejemplo                     | Intención del usuario          |
|--------------------|-----------------------------|--------------------------------|
| **Genéricas**      | "zapatos"                   | Información general            |
| **De cola larga**  | "zapatos para correr mujer" | Más específica, menos competencia |
| **Comerciales**    | "comprar zapatos Nike"      | Intención de compra            |
| **Informativas**   | "cómo limpiar zapatos"      | Busca una guía o tutorial      |

**Dónde usarlas:**
- Título de la página.
- Primer párrafo del contenido.
- Encabezados (`<h2>`, `<h3>`).
- Atributo `alt` de imágenes.
- Meta descripción.

---
---
### **🔹 Módulo 4: Contenido y SEO**
**Regla de oro:** *"El contenido es el rey"* (Bill Gates, 1996).

**Características de un buen contenido para SEO:**
✅ **Original:** No copiado de otros sitios.
✅ **Útil:** Resuelve una necesidad o pregunta del usuario.
✅ **Bien estructurado:** Usa párrafos cortos, listas, imágenes.
✅ **Actualizado:** El contenido fresco rankea mejor.
✅ **Optimizado para palabras clave:** Pero **sin exceso** (evita el *keyword stuffing*).

**Ejemplo de estructura ideal para un artículo:**
1. **Título** (incluye palabra clave principal).
2. **Introducción** (explica de qué trata el artículo).
3. **Cuerpo** (desarrolla el tema con subtítulos `<h2>`, `<h3>`).
4. **Conclusión** (resumen y llamado a la acción, ej: "Suscríbete para más tips").
5. **Meta descripción** (150-160 caracteres, atractiva).

---
---
### **🔹 Módulo 5: SEO Técnico (Profundizando)**
#### **1. Velocidad de carga**
- **Herramientas para medirla:**
  - [Google PageSpeed Insights](https://pagespeed.web.dev/)
  - [GTmetrix](https://gtmetrix.com/)
- **Cómo mejorarla:**
  - Comprimir imágenes (usar formatos *WebP* o herramientas como *TinyPNG*).
  - Minificar CSS y JavaScript.
  - Usar un *CDN* (Content Delivery Network) como Cloudflare.

#### **2. Mobile-Friendly**
- Google usa **indexación móvil primero** (*Mobile-First Indexing*).
- **Prueba tu sitio:** [Mobile-Friendly Test de Google](https://search.google.com/test/mobile-friendly).

#### **3. HTTPS (Seguridad)**
- Los sitios con **SSL (https://)** tienen ventaja en el ranking.
- Usa certificados gratuitos como *Let's Encrypt*.

#### **4. Estructura de URLs**
- **Mala:** `tusitio.com/blog/?p=123`
- **Buena:** `tusitio.com/blog/seo-para-principiantes`

#### **5. Archivo `robots.txt`**
- Indica a los robots qué páginas **no rastrear**.
- Ejemplo:
  ```
  User-agent: *
  Disallow: /admin/
  Disallow: /private/
  ```

#### **6. Sitemap XML**
- Lista todas las URLs importantes de tu sitio.
- Ejemplo:
  ```xml
  <?xml version="1.0" encoding="UTF-8"?>
  <urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
    <url>
      <loc>https://tusitio.com/</loc>
      <lastmod>2026-05-27</lastmod>
    </url>
  </urlset>
  ```
- **Generadores:** [XML-Sitemaps.com](https://www.xml-sitemaps.com/).

---
---
### **🔹 Módulo 6: SEO Off-Page (Backlinks y Autoridad)**
**¿Qué es un backlink?**
Un enlace desde **otro sitio web** hacia el tuyo. Google los considera como **"votos de confianza"**.

**Tipos de backlinks:**
| Tipo               | Ejemplo                          | Calidad          |
|--------------------|----------------------------------|------------------|
| **Natural**        | Un blog te enlaza por tu contenido | ⭐⭐⭐⭐⭐ (Alta) |
| **Manual**         | Tú pides a un sitio que te enlace | ⭐⭐⭐ (Media)    |
| **Creado**         | Compras enlaces en directorios    | ⭐ (Baja)        |

**Estrategias para conseguir backlinks:**
- **Guest Blogging:** Escribir artículos en otros blogs a cambio de un enlace.
- **Contenido viral:** Infografías, estudios o guías que otros quieran compartir.
- **Directorios locales:** Registrar tu negocio en Google My Business, Yelp, etc.
- **HARO (Help a Reporter Out):** Responder a consultas de periodistas.

**Métricas importantes:**
- **Domain Authority (DA):** Puntuación de 1 a 100 que predice el ranking (Moz).
- **Page Authority (PA):** Similar al DA, pero para una página específica.
- **Trust Flow:** Calidad de los enlaces que apuntan a tu sitio (Majestic).

---
---
### **🔹 Módulo 7: Herramientas de SEO**
| Herramienta          | Uso principal                          | Enlace                                  |
|----------------------|----------------------------------------|----------------------------------------|
| Google Search Console | Monitorear índice, errores, CTR        | [Enlace](https://search.google.com/search-console) |
| Google Analytics     | Analizar tráfico y comportamiento      | [Enlace](https://analytics.google.com/) |
| Ahrefs               | Análisis de backlinks y palabras clave | [Enlace](https://ahrefs.com/)          |
| SEMrush              | Competencia, palabras clave, auditorías| [Enlace](https://www.semrush.com/)     |
| Screaming Frog       | Auditoría técnica de SEO               | [Enlace](https://www.screamingfrog.co.uk/) |

---
---
### **🔹 Módulo 8: SEO Local**
**¿Qué es?**
Optimización para que tu negocio aparezca en búsquedas **locales** (ej: *"restaurante italiano en Lima"*).

**Acciones clave:**
1. **Google My Business:**
   - Crea y verifica tu ficha.
   - Completa toda la información (horario, fotos, descripción).
   - Pide **reseñas** a tus clientes.
2. **Palabras clave locales:**
   - Incluye la ciudad o región (ej: *"abogado en Miraflores"*).
3. **Consistencia NAP:**
   - Asegúrate de que tu **Nombre, Dirección y Teléfono** sean iguales en todos los directorios.

---
---
### **🔹 Módulo 9: Tendencias y Futuro del SEO**
- **Búsqueda por voz:** Optimiza para preguntas naturales (ej: *"¿Dónde comprar zapatos baratos en Lima?"*).
- **Featured Snippets:** Respuestas destacadas en Google (posiciones 0).
- **E-A-T:** *Expertise, Authoritativeness, Trustworthiness* (Google valora la experiencia y confianza).
- **Core Web Vitals:** Métricas de experiencia de usuario (LCP, FID, CLS).
- **IA y SEO:** Herramientas como *Jasper* o *SurferSEO* usan IA para optimizar contenido.

---
---