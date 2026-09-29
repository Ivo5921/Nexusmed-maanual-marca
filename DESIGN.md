# DESIGN.md — NexusMed Clinical Center

> Sistema de marca completo de **NexusMed** (@nexusmedclinic · nexusmedclinic.com).
> Fuentes analizadas el 2026-09-28: código CSS y textos de la web (ES + EN), perfil de Instagram (bio, 9 historias destacadas, 12 últimas publicaciones con sus portadas y captions completos) y los recursos locales de `VIDEOS TEMPORAL/`.
> Los HEX de la web salen de los tokens CSS reales del sitio (`:root`). Los de Instagram se muestrearon píxel a píxel sobre las portadas.
> **§12 = dirección visual aspiracional** (moodboard de 20 referencias en `VIDEOS TEMPORAL/MOODBOARD/`). Las §1–11 describen lo que la marca *es hoy*; la §12 describe *hacia dónde va* el contenido gráfico.

---

## 1. Esencia de marca

| | |
|---|---|
| **Qué es** | Clínica de medicina avanzada en Cumbayá (Quito, Ecuador): plasmaféresis / aféresis terapéutica, terapia celular (células madre, exosomas, NK, Muse, péptidos), longevidad y ginecología. |
| **Diferencial central** | *"El único centro médico de Latinoamérica que opera con tecnología de aféresis propia"*: el dispositivo **GEMA**, desarrollado por la empresa hermana **Apheresis Technology** (más de 850 centros, más de 550.000 procedimientos). |
| **Autoridad** | Dr. Gerardo G. Zumbana L. (director médico, más de 25 años, coautor con el Prof. Valery Voinov del primer libro de plasmaféresis en Latinoamérica), Dra. Irina Podaneva (ginecología), Dra. Kristina Zumbana (coordinación internacional, Nueva York). ASFA, ISSCA, Sechenov, USFQ. |
| **Promesa** | *"Tu salud merece un nuevo estándar."* Medicina clínica de precisión, sin intermediarios y sin promesas. |
| **Personalidad** | Clínica · precisa · sobria · científica · internacional · honesta. Más cerca de un centro universitario que de un spa de bienestar. |
| **Público** | Pacientes con enfermedades crónicas, autoinmunes, neurológicas o hepáticas (y sus familiares), pacientes internacionales (EE. UU., LATAM, más de 40 países), médicos que derivan pacientes y personas que buscan longevidad. |
| **Idiomas** | Español e inglés al 50 %. Atención en 6 idiomas (ES · EN · RU · FR · IT · DE). |

**Bio de Instagram (literal):**
```
Clínica líder en Plasmaferesis & Regenerative Medicine
Plasma Exchange • Stem Cells • NK • Muse • Exosomas • Péptidos
Casos crónicos | Apheresis Tech
```

---

## 2. Paleta de color

### 2.1 Paleta web oficial (tokens CSS del sitio)

| Rol | Token | HEX | Uso |
|---|---|---|---|
| **Tinta / texto principal** | `--ink` / `--charcoal-deep` | `#0E1217` | Titulares, texto, botón primario (fondo) |
| **Primario** | `--primary` (`--green`) | `#20252A` | Grafito azulado: bloques oscuros, H2 |
| Fondo oscuro profundo | `--green-deep` | `#050A0F` | Secciones oscuras |
| Casi negro | `--near-black` | `#020306` | Borde superior de 3 px en las tarjetas, sombras |
| Degradado oscuro | `--gradient-dark` | `#090E13 → #020306` (180°) | Fondos de secciones premium |
| **Acento (dorado taupe)** | `--gold` / `--accent` / `--ring` | `#7C6F60` | Eyebrows, detalles, foco, líneas finas |
| Dorado suave | `--gold-soft` | `#CBC3B6` | Separadores, fondos de chips |
| Gris texto secundario | `--gray` | `#50565C` | Párrafos secundarios, metadatos |
| **Fondo** | `--bg` / `--paper-tint` | `#FCFDFE` | Fondo general (blanco frío) |
| Crema (secundario) | `--cream` | `#F9FBFD` | Texto sobre oscuro, superficies |
| Niebla | `--surface-mist` | `#FAFCFE` | Superficies alternas |
| Papel blanco | `--paper-white` | `#FEFEFF` | Tarjetas |
| **Celeste** | `--celeste` | `#B1D7EF` | Resplandores radiales sutiles, resaltados |
| Celeste suave | `--celeste-soft` | `#DFF2FE` | Fondos informativos |
| **Azul profundo** | `--deep-blue` | `#153358` | Acento institucional |
| Azul profundo suave | `--deep-blue-soft` | `#4675A4` | Resplandor radial de esquina, enlaces |
| Línea fina | `--hairline` | `#302D2B` al 14 % | Bordes, inputs, divisores |
| Error | `--destructive` | `#CC2827` | Solo para errores de formulario |

**Fondos característicos de la web:** blanco frío con dos resplandores radiales casi imperceptibles: celeste `#B1D7EF` al 4–8 % arriba a la derecha y azul `#4675A4` al 3–5 % abajo a la izquierda. Sobre las fotos se aplica un degradado vertical `rgba(9,16,36,.10) → .35 → .88`.

### 2.2 Paleta de Instagram (muestreada de las portadas)

| Elemento | HEX | Nota |
|---|---|---|
| Texto de portada | `#FFFFFF` | Siempre blanco sobre la foto |
| **Banda de subtítulo** | `#4E6F80` (visible) ≈ `#2E566E` al 75–80 % | Banda horizontal azul pizarra semitransparente |
| **Resaltado amarillo** | `#E6BD1B` (rango `#DFAC13`–`#E8CC4F`) | Caja detrás de palabras clave en infografías ("¿QUÉ HAY EN TU") |
| **Resaltado celeste** | `#B3D2E8` | Marcador detrás de la palabra clave en carruseles ("Edad Biológica"). Es el mismo celeste de la web (`#B1D7EF`) |
| Texto de infografía | `#010101` | Negro puro sobre blanco |
| Fondo de infografía | `#FFFFFF` / `#F1F1F2` | Blanco o gris muy claro con ADN y moléculas en marca de agua |
| Azul del uniforme (en escena) | ≈ `#1F4FBF`–`#51A1D7` | El azul rey del uniforme médico es el color dominante en todas las fotos: forma parte de la identidad visual |
| Historias destacadas | Marfil / porcelana ≈ `#EFEAE4`–`#F6F3EF` | Íconos 3D en relieve, monocromos |

### 2.3 Paleta de video (ya configurada en remotion-editor, `scripts/lib/config.mjs`)

| Rol | HEX |
|---|---|
| primary (azul marino del logo) | `#1B2C61` |
| primaryLight | `#3D5AAE` |
| primaryDark | `#0E1838` |
| accent (plata) | `#9F9FA6` |
| light (tarjeta clara) | `#F7F8FB` |
| aurora | `#C3D0F0` |

> ⚠️ **Hay tres sistemas de color distintos** (web grafito y taupe, Instagram amarillo más celeste más pizarra, video navy más plata). Consulta la sección 10.

### 2.4 Paleta unificada recomendada (para todo lo nuevo)

| Rol | HEX |
|---|---|
| Base oscura | `#0E1217` |
| Grafito | `#20252A` |
| Azul institucional | `#153358` |
| Azul medio | `#4675A4` |
| Celeste (resaltado de marca) | `#B1D7EF` |
| Taupe (acento premium) | `#7C6F60` |
| Crema / fondo | `#F9FBFD` |
| Gris texto | `#50565C` |
| Amarillo de alerta (solo infografías) | `#E6BD1B`, como máximo 1 elemento por pieza |

> Para contenido editorial de Instagram, esta paleta base se complementa con las **paletas por tema** de la §12.3 (ámbar plasma, rojo sangre, azul polvo, verde metabólico…), que provienen de la fotografía y no de bloques planos.

---

## 3. Tipografía

### 3.1 Web (Google Fonts)

| Rol | Fuente | Pesos | Especificación |
|---|---|---|---|
| **Display / titulares** | **Urbanist** | 800 (también 300, 400 y 600, e itálica) | H1 en mayúsculas 800, tracking negativo ≈ -0,022 em. H2 de 28 px a 800 con interlineado 1,14. H3 de 21 px a 800. **Firma de estilo:** la segunda mitad del H2 va en *itálica* ("Clinical areas where our protocols carry *the strongest evidence.*") |
| **Cuerpo / UI** | **Epilogue** | 400, 500, 600, 700 e itálica 400 | Párrafos, navegación y botones. Letter-spacing ≈ -0,05 px |
| **Etiquetas técnicas** | **JetBrains Mono** | 400 y 500 | 10,5–11 px, mayúsculas, tracking amplio (0,12 em). Ejemplos: `ES · EN`, `EST. 2024 — Nº 001 / 001`, `CUMBAYÁ · QUITO — EC`, `40–50 MIN`, `MG/DL` |
| **Énfasis (NUEVA, oficial desde 2026-09-28)** | **Instrument Serif** | Italic 400 (solo itálica) | Una palabra o frase breve de énfasis dentro de un titular sans. Reemplaza a la itálica de Urbanist en el H2 de la web: "Clinical areas where our protocols carry *the strongest evidence.*" pasa a llevar esa parte en Instrument Serif Italic, un 8–10 % más grande que el sans para igualar alturas. Mismo color que el titular, o un solo acento tomado de la foto (§12.3) |

Import (fuentes oficiales de la marca):
```html
<link href="https://fonts.googleapis.com/css2?family=Urbanist:ital,wght@0,300;0,400;0,600;0,800;1,400;1,800&family=Epilogue:ital,wght@0,200;0,300;0,400;0,500;0,700;1,400&family=JetBrains+Mono:wght@400;500&family=Instrument+Serif:ital@1&display=swap" rel="stylesheet">
```
```css
:root { --font-accent: "Instrument Serif", Georgia, serif; }
.em-serif { font-family: var(--font-accent); font-style: italic; font-weight: 400; font-size: 1.09em; letter-spacing: -0.01em; }
```

**Reglas de Instrument Serif Italic:**
- ✅ Solo **1 palabra o frase corta** por pieza (máximo 3 palabras), siempre dentro de un titular.
- ✅ Úsala para la palabra que carga el significado: *antes*, *realmente*, *propia*, *medible*, *evidencia*.
- ❌ Nunca en párrafos, botones, etiquetas, subtítulos de video ni textos en mayúsculas.
- ❌ Nunca en redonda (no itálica), porque la marca solo usa su versión itálica.
- ❌ Nunca combinada con negrita o subrayado.

**Eyebrows (sobretítulos):** mayúsculas finas (Urbanist 300 o Epilogue) con tracking de 0,28–0,32 em, en crema al 90 % sobre oscuro o en taupe sobre claro. Formato numerado: `01 · ÁREA CLÍNICA`.

### 3.2 Instagram y video

| Pieza | Fuente | Especificación |
|---|---|---|
| **Títulos de portada (reels)** | Sans geométrica ancha y muy pesada (tipo **Montserrat ExtraBold/Black**) | MAYÚSCULAS, blanco, sombra suave hacia abajo, 2–4 líneas, alineada a la izquierda o centrada sobre el torso |
| Banda de subtítulo | Sans semibold (Montserrat SemiBold) | Mayúscula inicial y minúsculas, blanco, dentro de la banda pizarra |
| Carrusel educativo | Sans grotesca negra (tipo Montserrat/Inter Bold) | Mayúscula inicial y minúsculas, negro, palabra clave con marcador celeste |
| Infografía | Montserrat Bold (título) y Regular (etiquetas) | Título en caja amarilla y etiquetas pequeñas con líneas curvas finas |
| **Título de apertura en video** | Bebas Neue más skewX(-8°) | Ver la memoria *title-style*: condensada, itálica, última línea en caja oscura |
| **Subtítulos en video** | Montserrat Bold 700 | ≈ 57 px a 1080, trazo negro, sombra `0 5px 13.5px rgba(0,0,0,.4)`, **1 línea máximo**, a la altura del pecho |

---

## 4. Logo y elementos de identidad

- **Monograma "NM":** trazos finos y geométricos. La diagonal de la N se une con la M en un solo trazo continuo, en grafito o pizarra sobre blanco. En el avatar de IG va dentro de un círculo blanco.
- **Wordmark:** `NEXUSMED` en mayúsculas con tracking muy amplio y, debajo, `CLINICAL CENTER` más pequeño entre filetes horizontales.
- **Aplicaciones reales:** letrero de pared retroiluminado en la recepción (se ve en la portada "Cómo la plasmaféresis cambia tu cuerpo"), avatar de IG, historia destacada "GEMMA" y endings de video.
- **Endings de video disponibles:** `ENDING/Nexusmed` (vertical) y `ENDING/Nexusmed horizontal`. Para la marca hermana existen `Apheresis vertical.MP4` y `Apheresis horizontal.MP4`.
- **Firma de nombre:** "NexusMed" (N y M mayúsculas, en una sola palabra). En los captions se usa "**NexusMed Clinical Center**".

---

## 5. Estilo visual

### 5.1 Web: *"editorial clínico de lujo"*
- Mucho aire, fondos blancos fríos y bloques oscuros de grafito con degradado.
- Fotografía real de la clínica (fachada al atardecer, sala de IV privada, bolsas de plasma y albúmina, equipo en sala limpia), con degradado oscuro abajo para el texto.
- **Radio:** base de 2 px (casi recto, serio). Tarjetas de 14 px con **borde superior de 3 px casi negro**. Botones en **píldora** (totalmente redondeados).
- **Sombras:** prácticamente ninguna (`--shadow-card: none`). La elevación se logra con un anillo de 1 px.
- **Botón primario:** fondo `#0E1217`, texto `#F9FBFD`, píldora. Invertido sobre oscuro.
- **Datos como diseño:** contadores (25+ años, 850+ centros, 550.000+ procedimientos), gráficos antes/después de biomarcadores y fichas técnicas en mono (`40–50 min · ~70 ml · Periférico`).
- **Marquesinas** infinitas de condiciones y de aliados (ASFA, ISSCA, Sechenov…).
- Easing: `cubic-bezier(.22,1,.36,1)` (out-quint) y `cubic-bezier(.76,0,.24,1)` (in-out-quart). Revelado al hacer scroll.
- Separadores tipográficos: punto medio ` · `, raya ` — `, flecha `→`.

### 5.2 Instagram: 4 formatos de publicación

**A. Portada de reel (el 80 % del feed)**
- Foto vertical real en la clínica: el doctor con **uniforme azul rey**, gorro quirúrgico, máquina GEMA con bolsas de plasma y pacientes en sillones azules. Luz natural y blancos limpios.
- Título blanco en MAYÚSCULAS, geométrico y muy pesado, con sombra suave, colocado sobre el **torso** y **sin tapar nunca la cara**.
- Estructura: `TEMA:` + `AVANCE/CONTEXTO` + banda pizarra con el dato clave en minúsculas (ej.: **PLASMAFÉRESIS: AVANCE EN** / banda "Hepatitis Aguda").
- A veces los caracteres de énfasis van entre comillas: `PLASMAPHERESIS "TPE"`.

**B. Infografía de producto** (ej.: "¿QUÉ HAY EN TU PLASMA")
- Fondo blanco, objeto fotorrealista centrado (bolsa de plasma amarilla) y etiquetas alrededor con flechas curvas finas negras: *Anticuerpos patógenos · Complejos inmunes · Mediadores inflamatorios · Microplásticos · Metales pesados*.
- Título: caja amarilla `#E6BD1B` con texto blanco y continuación en negro.

**C. Carrusel educativo** (ej.: "Qué es la Edad Biológica y por qué importa")
- Fondo blanco o gris claro con hélice de ADN y moléculas de cristal en marca de agua.
- Texto negro en minúsculas con la palabra clave resaltada con un marcador celeste `#B3D2E8`. Firma `@nexusmed` pequeña abajo.

**D. Historias destacadas**
- Íconos **3D de porcelana o marfil en relieve** sobre fondo crema, monocromos y con estética de laboratorio premium: rodilla, célula, molécula de péptido, bolsa de suero, escudo con moléculas, hígado, exosomas, célula NK con escudo y logo NM.
- Etiquetas: `REUMATOLÓGICAS · CÉLULAS MADRE · PÉPTIDOS · SUEROTERAPIA · E. INMUNOLÓGICA · E. HEPÁTICAS · EXOSOMAS · CÉLULAS NK · GEMMA`.

### 5.3 Video (reglas vigentes del editor)
Formato nativo (9:16 a 1080×1920 o 16:9 a 1920×1080). Estabilizado siempre. Subtítulos de 1 línea a la altura del pecho. Título de apertura de 5 s con entrada blur-izquierda de 0,2 s y whoosh. B-roll contextual con clic suave. Zooms punch-in. Música a 0,042. Ending NexusMed. Detalle en `remotion-editor/GUIA.md` y en la memoria.

---

## 6. Tono de voz

**En una frase:** *un médico especialista explicando con precisión y calma, sin vender.*

| Atributo | Cómo se ve |
|---|---|
| **Clínico y preciso** | Vocabulario técnico sin disculparse: *inmunocomplejos, autoanticuerpos, mediadores inflamatorios, compartimento plasmático, estrategia extracorpórea, reservas fisiológicas, relojes epigenéticos* |
| **Prudente / basado en evidencia** | Modaliza siempre: *"puede integrarse", "en casos seleccionados", "bajo criterio médico", "dentro de un protocolo individualizado", "se estudia"* |
| **Honesto, anti-hype** | *"No garantizamos resultados." "Sin intermediarios. Sin promesas." "No tratamos todo. Tratamos donde podemos generar impacto medible."* |
| **Aclara malentendidos** | Estructura **"No es X, sino Y"**: *"Su función no es simplemente 'reemplazar' tejido, sino…" · "Más que 'filtrar la sangre', se trata de…" · "Su función no es eliminar el virus, sino…"* |
| **Secuencial / de proceso** | *"Preparar primero, intervenir después." "Primero evaluar… luego introducir…" "Measure first. Then intervene with precision."* |
| **Autoridad tranquila** | Datos concretos en vez de adjetivos: *"cuatro sesiones", "paciente de 67 años", "40–50 min", "80+ biomarcadores"* |
| **Cercano solo en el gancho** | El título tutea (*"tu plasma", "tu cuerpo"*) y el desarrollo pasa a un registro clínico en tercera persona |

**Nivel de formalidad:** alto. Sin jerga, sin exclamaciones, sin mayúsculas gritonas en el texto (las mayúsculas quedan solo para las portadas). Frases de longitud media y larga en los captions. Frases cortas y rotundas en la web.

---

## 7. Fórmulas y frases que usamos

### 7.1 Fórmulas de título (portadas y primera línea del caption)
1. **`[Terapia] en [condición]`** → *Células madre en enfermedades hepáticas* · *Plasmaféresis en autoinmunidad*
2. **`[Terapia]: [papel] en [condición]`** → *Plasmaféresis: avance en hepatitis aguda* · *Plasmaféresis: motor principal en Guillain-Barré*
3. **`[Condición]: [terapia] y [resultado]`** → *Guillain-Barré: plasmaféresis y recuperación funcional*
4. **Pregunta de curiosidad con "realmente"** → *¿Qué está circulando realmente en tu plasma?*
5. **"¿Y si…?"** → *¿Y si dos horas pudieran cambiar cómo se siente tu cuerpo?* · *¿Y si pudieras medir tu edad biológica y actuar sobre ella?*
6. **"Cómo…" / "Qué es… y por qué importa"** → *Cómo la plasmaféresis cambia tu cuerpo en dos horas* · *Qué es la Edad Biológica y por qué importa*
7. **Caso clínico con edad** → *Plasmaféresis: paciente de 88 años con bronquiectasia*
8. **Regla o principio** → *Antes de la plasmaféresis, primero hay que preparar al paciente*
9. **En inglés, en formato de revista** → *Lyme: Beyond the Infection — When Symptoms Continue* · *Brain Inflammation May Start in the Gut* · *Advanced Medicine Has a New Destination: LATAM · Ecuador* · *Plasma Exchange First: Preparing the Biological Environment*

### 7.2 Estructura del caption (siempre igual)
```
[Título con dos puntos: tema + ángulo]

[Párrafo 1: el mecanismo o el problema, explicado clínicamente]

[Párrafo 2: cómo interviene NexusMed, siempre con modalizadores
 y cierre en "protocolo individualizado / criterio médico"]

(Opcional, párrafo 3: principio general en forma de lección)

NexusMed Clinical Center
🌐 www.nexusmedclinic.com
📲 USA: +1 (646) 319 7951
📲 Ecuador: +593 99 297 8178
```
- 2–3 párrafos, sin hashtags, sin CTA agresivo, sin emojis en el cuerpo (solo 🌐 📲 en la firma).
- Se permite **negrita** para frases clave de caso clínico.

### 7.3 Vocabulario y frases firma
- *protocolo individualizado / estructurado / personalizado*
- *bajo criterio médico, monitoreo continuo y una indicación clínica precisa*
- *reducir la carga circulante / plasmática*
- *modular el entorno circulante / el proceso inflamatorio*
- *crear un entorno biológico más favorable*
- *estrategia extracorpórea (avanzada)*
- *en casos seleccionados*
- *la correcta selección del paciente*
- *intervenir de forma controlada / selectiva*
- *medicina de precisión / medicina avanzada*
- *Preparar primero, intervenir después.*
- *Tu salud merece un nuevo estándar.*
- *Sin intermediarios. Sin promesas.*
- *Tecnología propia · dispositivo de desarrollo propio · cada paso, trazable*
- *Respuestas directas a preguntas reales.*
- *Pacientes informados toman mejores decisiones.*
- *Casos clínicos, contados por quienes los vivieron.*
- *Measure first. Then intervene with precision.*
- EN: *clinical sequencing · biological environment · structured medical sequence · precision is not a single procedure, it's the way the entire medical journey is designed*

### 7.4 Nomenclatura
- **Plasmaféresis** (ES), **Plasma Exchange / TPE / Therapeutic Plasma Exchange** (EN), **Recambio Plasmático Terapéutico (TPE)**
- **Aféresis terapéutica**, **GEMA** (dispositivo), **Apheresis Technology / Apheresis Tech** (empresa hermana)
- Pacientes: "una paciente de 67 años", "paciente oncológica", nunca con nombre propio

---

## 8. Frases que NUNCA usamos

| ❌ Nunca | ✅ En su lugar |
|---|---|
| "cura", "curamos", "milagro", "definitivo" | "recuperación funcional", "respuesta clínica", "mejoría medible" |
| "garantizado", "100 % efectivo", "resultados asegurados" | "los resultados individuales pueden variar" |
| "limpia / desintoxica / filtra tu sangre" (a secas) | "reduce componentes circulantes seleccionados" |
| "elimina el virus / la enfermedad" | "modula el entorno circulante y apoya al organismo" |
| "reemplaza la quimio / tu tratamiento" | "soporte complementario, coordinado con tu oncólogo" |
| "rejuvenece X años", "anti-aging" | "edad biológica medible, protocolos de longevidad personalizados" |
| "para todos", "trata cualquier enfermedad" | "no tratamos todo; tratamos donde podemos generar impacto medible" |
| "oferta", "promo", "descuento", "últimos cupos", urgencia artificial | "agenda una evaluación inicial" |
| Exclamaciones (¡!), jerga, "increíble", "brutal", "top" | Afirmaciones sobrias con dato |
| Emojis en el cuerpo del texto, hashtags en bloque | Solo 🌐 📲 en la firma |
| "natural", "sin efectos secundarios", "sin riesgo" | "procedimiento médico controlado, bajo supervisión" |
| Primera persona emocional ("¡Estamos felices de…!") | Tercera persona institucional ("NexusMed coordina…") |
| Nombres reales de pacientes | "Paciente de 42 años con artritis reumatoide" |

---

## 9. Recursos gráficos disponibles

**Web (`nexusmedclinic.com/assets/`):** `nexusmed-clinic.webp` (fachada), `zumbana-plasma-bags.webp`, `exosome-secretome.webp`, `team-cleanroom.webp`, `iv-lounge-plasma.webp`, `plasma-albumina.webp`, `favicon.png` y `apple-touch-icon.png`, 3 videos con audio (testimonio, caso de perfil lipídico, GEMA explicado por la Dra. Cristina Zumbana) y 4 PDFs descargables (guía de aféresis, biomarcadores, estado de la evidencia en terapia celular 2026, libro en ES/EN/RU).

**Instagram:** 9 portadas de historias destacadas (íconos de porcelana), avatar NM y aproximadamente 182 publicaciones (portadas de reel, infografías y carruseles).

**Local (`Desktop/VIDEOS TEMPORAL/`):**
- `ENDING/`: Nexusmed, Nexusmed horizontal, Apheresis vertical y horizontal
- `IMAGENES DE APOYO/`: tomas de dron DJI (8), máquina GEMA (`Maquina gemma.PNG`, `Maleta Gemma.jpeg`, `Filtro maquina gemma.MP4`, `maquina plasma en funcionaiento.MP4`), CGI de sangre (`sangre en movimiento.mp4`, `AApoyo sangre.MP4`, `Burbujas plsma.mp4`), `Bronquiectacia.jpeg` y clips IMG_93xx/95xx/157x de la clínica
- `MUSICA DE FONDO/`: pista inspiradora-dramática y efectos de sonido
- `PORTADAS/`: `Solo audio 1.PNG`
- Catálogo del editor: `remotion-editor/estilos/biblioteca.json`

---

## 10. Inconsistencias detectadas (conviene corregirlas)

1. **Erratas en portadas publicadas:** "PLASMAF**É**REIS" (reel de la paciente de 88 años) y "PLASM**F**ÉRESIS" (reel de hepatitis aguda). La bio dice "Plasmaferesis" sin tilde. Revisa la ortografía antes de publicar cada portada.
2. **GEMA vs GEMMA:** la web escribe "GEMA" y la historia destacada de IG escribe "GEMMA". Hay que elegir uno.
3. **Teléfonos distintos:** la web usa +593 99 232 5886 / +593 96 280 3109, y los captions usan +593 99 297 8178 / +1 (646) 319 7951.
4. **Tres paletas:** la web es grafito, taupe y celeste; IG usa amarillo, celeste y pizarra; el video usa navy `#1B2C61` y plata. Para unificar, la recomendación es usar la **paleta 2.4** (el celeste `#B1D7EF`/`#B3D2E8` ya es el puente natural) y dejar el amarillo solo como acento puntual de infografía.
5. **Tipografía de títulos:** la web usa Urbanist, las portadas de IG una sans geométrica ancha (tipo Montserrat Black) y el título en video Bebas Neue condensada en itálica. Para coherencia, lo ideal es que las portadas de IG y el título de apertura del video usen la misma familia.
6. **Mezcla de idioma sin regla:** hay portadas en inglés dentro del feed en español. Una regla sugerida: español para casos clínicos locales e inglés para temas dirigidos al paciente internacional (Lyme, gut–brain, destino LATAM).

---

## 11. Checklist rápido antes de publicar

- [ ] Título con fórmula de la §7.1, sin errata y con tildes correctas (PLASMAFÉRESIS)
- [ ] Texto de portada sobre el torso, sin tapar la cara, en blanco con sombra suave
- [ ] Caption con la estructura de la §7.2 y la firma "NexusMed Clinical Center" con 🌐 📲
- [ ] Al menos un modalizador ("en casos seleccionados", "bajo criterio médico")
- [ ] Nada de la lista de la §8
- [ ] Colores dentro de la paleta 2.4 y como máximo un acento amarillo
- [ ] Video: subtítulos de 1 línea a la altura del pecho, título de 5 s, ending NexusMed
- [ ] Pieza editorial: una sola idea, un solo dispositivo gráfico de la §12.5 y mucho aire (§12)

---

## 12. Dirección visual aspiracional (moodboard)

**Referencias:** 20 piezas guardadas en `VIDEOS TEMPORAL/MOODBOARD/1.png … 20.webp`, de Function Health, The Ordinary, Kitsu, Method Spa, Heavenly Heat, Rübaab y otras marcas de longevidad, suplementos y skincare. Los HEX de esta sección se muestrearon de esas imágenes.

### 12.1 La idea en una frase
> **"Laboratorio de lujo, silencioso."** Imagen macro o científica a sangre completa, una sola frase corta, muchísimo aire y pequeños elementos de interfaz (puntos, líneas finas, etiquetas mono) que hacen que la foto se sienta *medida*, como un dato clínico.

Esto encaja con la web actual: su itálica de énfasis, sus etiquetas en JetBrains Mono y su estética editorial son el mismo lenguaje. **El objetivo es llevar a Instagram la calidad que ya tiene la web.**

### 12.2 Qué tienen en común las 20 referencias

| Rasgo | Cómo se ve | Referencias |
|---|---|---|
| **Fotografía textural** | Macros de líquidos, burbujas, geles, ADN, micrografías de células, vidrio esmerilado o acanalado | 10, 11, 14, 15, 16, 18, 19, 20 |
| **Cuerpo sin rostro** | Fragmentos de manos, espalda, pie o silueta: el cuerpo como objeto de estudio, no como modelo | 1, 2, 3, 5, 6, 12, 13 |
| **Desenfoque intencional** | Vidrio esmerilado, barrido de movimiento o vidrio acanalado (reeded glass) | 1, 4, 13, 15, 17 |
| **Luz cálida monocroma** | Toda la pieza teñida de un solo color: ámbar, rojo, sepia o bronce | 3, 4, 7, 8, 15, 16, 19 |
| **Tipografía pequeña y calmada** | Titulares en minúsculas con punto final y peso regular o medio. Nada grita | casi todas |
| **Interfaz sobre la foto** | Puntos, conectores, corchetes, anillos, marcadores HUD, etiquetas mono | 1, 2, 3, 4, 8, 13, 14, 17–20 |
| **Un dato, una idea** | Una cifra grande, una frase o un ingrediente por slide | 4, 12, 13, 15, 16 |
| **Sistema en serie** | La misma plantilla repetida con distinto contenido | 17–20 (Kitsu) |

### 12.3 Paletas por tema (fotografía más acento)
El color lo pone **la foto**, no una caja plana. Cada familia de contenido tiene su temperatura:

| Tema NexusMed | Paleta | HEX muestreados | Ref. |
|---|---|---|---|
| **Plasmaféresis / plasma** | Ámbar plasma | `#E6BD1B` · `#BF7214` · `#AF5C07` · sombra `#652207` | 3, 19 (y tu propia bolsa de plasma) |
| **Sangre / inmunidad / autoinmunes** | Rojo sangre | `#A5381B` · `#881100` · `#5D0809` · negro rojizo `#1B0C06` | 4, 15 |
| **Terapia celular / micrografías** | Sepia celular | `#E08957` · `#A54D1B` · crema `#EFBE96` | 16 |
| **Longevidad / diagnóstico / biomarcadores** | Azul polvo | `#5B7391` · `#677D9E` · esmerilado `#A8B2BC` · celeste `#95B9D0` | 1, 2 |
| **Intestino / metabolismo / hígado** | Verde metabólico | `#717D11` · `#A6B254` · lima pálido `#CCD98F` · `#F3F4E1` | 10, 11 |
| **Sueroterapia / péptidos / IV** | Plata líquida | `#737781` · `#93989F` · `#E6E6E6` | 18, 6 |
| **Ginecología / bienestar / sala IV** | Arena cálida | `#EADEDB` · `#C5B8AF` · espresso `#251E1C` | 5, 7 |
| **Programa / proceso / marca** | Bronce | `#6C563B` · `#8B7D68` · `#2A2013` (coincide con el taupe web `#7C6F60`) | 8 |

**Reglas:**
- El texto va siempre en **blanco `#FFFFFF`** sobre fotos oscuras o saturadas, o en **tinta `#0E1217`** sobre fondos claros.
- El acento de color en tipografía es **uno solo por pieza**, tomado de la propia foto (como "*Iron*" en terracota, ref. 13).
- El amarillo `#E6BD1B` deja de ser una caja plana y pasa a ser **luz y textura de plasma**.

### 12.4 Tipografía editorial (propuesta, unificada con la web)

| Rol | Fuente | Estilo (referencias) |
|---|---|---|
| **Titular** | **Epilogue 500** (o Urbanist 600) | Minúscula inicial, **punto final**, tracking −2 a −3 %, interlineado 1,0–1,05. *"Testosterone levels are dropping."* (4), *"Your gut microbes can influence metabolism."* (11) |
| **Palabra de énfasis** | **Instrument Serif Italic** (oficial, ver §3.1) | Una palabra en itálica serif dentro del titular sans: *"Find it **before** you feel it."* (2), "***Iron** deficient.*" (13), *"Hydration at a molecular level."* (14) |
| **Cifra héroe** | **Epilogue 200–300**, enorme | *81%* (12), *50%* (13), *~5,136* (15): delgada y gigante, nunca en negrita |
| **Etiquetas / HUD** | **JetBrains Mono 400**, MAYÚSCULAS, 9–11 pt, tracking +8–12 % | `FLEXION + ABDUCTION` (3), `SKIN ISN'T A TREND.` (10), `ALGAE` (10) → en NexusMed: `VOLUMEN EXTRACORPÓREO · ~70 ML` |
| **Rótulo de serie** | Epilogue 500, MAYÚSCULAS, tracking +4 % | `INGREDIENT SPOTLIGHT` / `WHAT'S INSIDE` (17–20) → `PROTOCOL SPOTLIGHT` / `CASO CLÍNICO` |
| **Cuerpo** | Epilogue 400, 2–3 líneas como máximo | Siempre subordinado y pequeño |

> ✅ **Decidido (2026-09-28):** Instrument Serif Italic es la fuente de énfasis oficial de la marca en web, Instagram y tarjetas de video. Sistema completo: **Epilogue** (titulares editoriales y cuerpo) · **Urbanist** (display web) · **Instrument Serif Italic** (énfasis) · **JetBrains Mono** (etiquetas).
>
> Ejemplos: *"Medirlo **antes** de sentirlo."* · *"¿Qué está circulando **realmente** en tu plasma?"* · *"Una institución médica con tecnología **propia**."* · *"Tu salud merece un **nuevo estándar**."*

### 12.5 Biblioteca de dispositivos gráficos
Se usa **uno por pieza**, con trazos de 1–1,5 px en blanco o tinta:

1. **Punto + línea conectora**: un punto con halo que baja en línea fina hasta el texto (ref. 1). Sirve para señalar la zona de punción o la vena.
2. **Constelación de datos**: etiquetas-píldora de vidrio esmerilado unidas por líneas con puntos (ref. 2). Úsalo para biomarcadores (*Inflamación · Lípidos · Autoinmunidad*).
3. **Marco punteado redondeado**: rectángulo de radio 40 px con borde punteado fino que contiene el titular o la firma (ref. 2).
4. **HUD clínico**: pequeños cuadrados marcadores sobre el cuerpo o la máquina, más un recuadro con etiquetas mono arriba y abajo (ref. 3). Ideal sobre fotos de GEMA: `FLUJO · 40–50 MIN`.
5. **Gráfico de marcas verticales**: líneas verticales finas que dibujan una tendencia (ref. 4) para biomarcadores antes/después *sin ejes*.
6. **Anillo de progreso**: dona fina con la cifra en el centro (ref. 13).
7. **Círculos concéntricos**: fases anidadas (ref. 8) para *Evaluación → Diagnóstico integral → Programa de longevidad* o *Preparar → Intervenir → Seguir*.
8. **Círculos numerados**: pasos de un protocolo (ref. 7), sin repetir números (la referencia tiene el error "1 2 3 2 3").
9. **Corchete de medida**: corchete vertical fino a la derecha, como una regla de laboratorio (ref. 18–20). Es la plantilla de serie.
10. **Filete divisor**: línea horizontal fina sobre el titular o línea vertical que parte la composición (ref. 5, 9, 12, 14).
11. **Píldora contorno**: `¿Sabías que?` en píldora con borde de 1 px (ref. 11).
12. **Botón de flecha circular**: `Leer más →` dentro de un círculo (ref. 12), para el último slide del carrusel.
13. **Tarjeta de vidrio esmerilado**: panel translúcido con blur sobre la foto (ref. 6, 2).
14. **Vidrio acanalado**: filtro de vidrio estriado sobre un sujeto rojo o ámbar (ref. 13). Muy aplicable a bolsas de plasma y sangre.

### 12.6 Composición
- **Márgenes amplios**: ≥ 7 % del ancho. El texto nunca toca el borde.
- **Posición del texto**: abajo a la izquierda (3, 4, 15, 16), centrado en el tercio medio (1, 10, 11) o en columna partida (5, 14).
- **Jerarquía de 3 niveles como máximo**: rótulo mono o serie → titular → una línea de apoyo.
- **Formato**: 4:5 (1080×1350) para feed y 9:16 (1080×1920) para historias y portadas.
- **Grano sutil** (2–3 %) sobre fondos lisos para evitar un aspecto digital plano.
- **Logo** pequeño arriba a la izquierda (como Kitsu, ref. 17–20), o solo en el último slide.

### 12.7 Tono de copy que tomamos (y el que no)

**Tomamos, porque encaja con la §6:**
- Afirmación corta con punto final: *"Testosterone levels are dropping."*
- Reencuadre en dos tiempos: *"Skin isn't a trend. It's an organ."* → *"El plasma no es solo líquido. Es información clínica."*
- Anticipación: *"Find it before you feel it."* → *"Medirlo antes de sentirlo."*
- Dato con matiz: *"Up to 81%…"*, *"~5,136 genes… can behave…"* (usa "hasta", "~" y "puede", igual que nuestros modalizadores)
- Cierre que remite a la evidencia: *"Here's what the research points to."* → *"Esto es lo que indica la evidencia."*
- Triada rítmica: *"More clarity. More focus."* → *"Menos carga circulante. Más control clínico."*

**No tomamos, porque choca con la §8:**
- ❌ *"Detox at the cellular level"*, *"Glow… fine lines soften"* (ref. 8): promesa cosmética o detox
- ❌ *"THE SIMPLE WAY YOU CAN DO!"* (ref. 7): exclamación y tono de autoayuda
- ❌ Precios, `#EXCLUSIVE`, sellos de promoción (ref. 9)
- ❌ *"New supplement is here."* (ref. 6): anuncio de producto
- ❌ *"Activate Your Potential"* (ref. 1): frase vacía sin dato clínico

> **Regla de oro:** copiamos la *forma* de estas marcas de bienestar, nunca sus *claims*. NexusMed es medicina: cada cifra lleva su fuente en el caption.

### 12.8 Plantillas NexusMed derivadas

| # | Plantilla | Basada en | Ejemplo NexusMed |
|---|---|---|---|
| T1 | **Dato héroe** | 12, 13, 15 | `~70 ml` · *de volumen extracorpóreo por sesión.* Rótulo mono `GEMA · APH-T` |
| T2 | **Protocol Spotlight** (serie) | 17–20 | Logo arriba a la izquierda · **Glutatión IV** · *Soporte antioxidante y hepático.* · 2 líneas · corchete a la derecha · `PROTOCOL SPOTLIGHT` abajo. Serie: Vitamina C IV, Myers, Azul de metileno, NAD+, Exosomas |
| T3 | **Mapa de biomarcadores** | 2 | Manos o brazo con vía y píldoras *Inflamación · Lp(a) · Autoanticuerpos* · titular *"Medirlo **antes** de sentirlo."* |
| T4 | **HUD clínico** | 3 | Foto de la máquina GEMA o del doctor en ámbar o azul con marcadores y `SEPARACIÓN DE PLASMA · 40–50 MIN` |
| T5 | **Manifiesto mono** | 10 | Macro de plasma sobre blanco · `PREPARAR PRIMERO. / INTERVENIR DESPUÉS.` centrado en mono · `PLASMA` abajo a la izquierda |
| T6 | **Ciclo del programa** | 8 | Círculos concéntricos: *Evaluación inicial (60–90 min) → Diagnóstico integral → Programa de longevidad (12 meses)* |
| T7 | **Tendencia** | 4 | Barrido rojo · *"La inflamación silenciosa se acumula."* · gráfico de marcas · *"Esto es lo que indica la evidencia."* |
| T8 | **Split editorial** | 14 | Mitad macro ámbar y mitad blanca con titular serif itálico y línea con puntos. Para tecnología y libro del Dr. Zumbana |
| T9 | **¿Sabías que?** | 11 | Píldora contorno + titular grande en tinta + 2 líneas, sobre macro verde (intestino o hígado) |
| T10 | **Micrografía** | 16 | Células o exosomas en sepia · **Exosomas** · *"Los mensajeros que las células usan para comunicarse."* |

### 12.9 Cómo se traslada al video (remotion-editor)
- **Tarjetas (cards):** migrar de "aurora azul + barra plata" a los fondos de la §12.3 según el tema del video, con titular en minúsculas, punto final y una palabra en itálica.
- **Datos en pantalla:** usar T1 (cifra delgada gigante) y T5 (etiquetas HUD mono) en lugar de texto grande en negrita.
- **B-roll:** priorizar macros de plasma, sangre, burbujas y vidrio (ya existen `Burbujas plsma.mp4`, `sangre en movimiento.mp4`, `AApoyo sangre.MP4`) y buscar en stock *"macro liquid amber"*, *"microscope cells"*, *"frosted glass"*.
- **No cambia:** el estilo de subtítulos y el título de apertura (memorias *subtitle-style* y *title-style*) siguen vigentes hasta que decidas otra cosa. Las portadas de reel con texto grande en mayúsculas funcionan para retener. La propuesta es aplicar esta estética primero a **posts, carruseles e historias**.
