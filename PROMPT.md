# Resumen de Proyecto & Prompt de Continuidad — Nova Pisos

Este documento contiene la ficha técnica, directrices de diseño, datos reales de contacto y estructura del proyecto para continuar o escalar el desarrollo de **Nova Pisos** en sesiones futuras.

---

## 1. Identidad de Marca

- **Nombre comercial:** Nova Pisos
- **Eslogan principal:** *"Renovamos tu espacio, elevamos tu brillo"*
- **Eslogan secundario:** *"Brillo que perdura"*
- **Giro:** Pulido, desbastado, abrillantado y encerado profesional de pisos en Monterrey y su área metropolitana, Nuevo León, México.
- **Canales de contacto oficiales:**
  - **Teléfono / WhatsApp:** `81 3565 6598`
  - **Enlace directo WhatsApp:** `https://wa.me/5218135656598`
  - **Correo electrónico:** `ventasnovapisos01@gmail.com`

---

## 2. Sistema de Diseño & Tokens CSS

- **Estilo visual:** Oscuro, sobrio, premium y reflectivo (evitar estéticas genéricas de IA como tarjetas blancas con sombras suaves o fondos crema con terracota).
- **Paleta de Color:**
  - **Fondo base cálido:** `#0B0A08`
  - **Superficie de tarjetas / contenedores:** `#12110E` / `#1A1814`
  - **Acentos dorados / bronce:** `#C9A24B` (primario), `#E4C374` (luz), `#7A5A2C` (bronce profundo)
  - **Texto principal:** `#F2EEE3` (marfil cálido)
  - **Texto secundario:** `#B9B2A2` (piedra claro), `#8C8575` (piedra medio)
- **Tipografía (Google Fonts):**
  - **Titulares:** `Fraunces` (Serif de alto carácter)
  - **Cuerpo y botones:** `Archivo` (Sans-serif limpia y geométrica)
- **Motivo protagonista:** El reflejo del piso pulido tipo espejo como hilo conductor del diseño (destellos especulares sutiles, líneas doradas degradadas, acabados reflectivos).
- **Accesibilidad:** Soporte para `prefers-reduced-motion`, `:focus-visible` dorado de alto contraste, enlaces de salto (`skip-link`) y landmarks semánticos de HTML5.

---

## 3. Contenido Oficial

### Servicios
1. **Pulido industrial:**
   - Naves industriales y bodegas de alto tráfico.
   - Centros comerciales y tiendas retail.
   - Estacionamientos y concreto decorativo.
2. **Pulido residencial:**
   - Mármol y granito para acabado de lujo.
   - Concreto pulido decorativo y terrazo.
   - Mantenimiento periódico y encerado especializado.
3. **Encerado profesional:**
   - Protección duradera contra el desgaste.
   - Acabado espejo que resalta la belleza del piso.

### Materiales que trabajan
- Mármol
- Granito
- Concreto
- Cerámico
- Vinil
- Madera
- Terrazo

### Proceso de Venta (4 Pasos)
1. El cliente manda foto del piso por WhatsApp.
2. Cotización en menos de 10 minutos.
3. Diagnóstico técnico en sitio.
4. Pulido y sellado, normalmente en un solo día y sin escombro.

### Zonas de Cobertura (10 Municipios en Nuevo León)
- Monterrey
- Guadalupe
- San Pedro Garza García
- Santa Catarina
- Apodaca
- General Escobedo
- Santiago
- Salinas Victoria
- Pesquería
- García

---

## 4. Estructura de Archivos

```
nova-pisos-site/
├── index.html          # Landing page completa, semántica y responsiva
├── css/
│   └── style.css       # Estilos puros vanilla sin dependencias ni build step
├── images/
│   ├── logo-nova-pisos-transparente.png # Logo oficial con fondo transparente
│   ├── logo-nova-pisos.png              # Logo original en alta resolución
│   ├── hero-piso-espejo.jpg             # Foto real con acabado espejo y reflejo
│   ├── servicio-industrial.jpg          # Operador con pulidora en piso industrial
│   ├── servicio-residencial.jpg         # Acabado espejo en piso de mármol
│   ├── servicio-encerado.jpg            # Acabado reflectivo en piso comercial
│   ├── galeria-comercial.jpg            # Proyecto en centro comercial
│   ├── galeria-bodega.jpg               # Operador y maquinaria en bodega
│   ├── trabajo-comercial.png            # Publicidad de trabajo comercial
│   ├── trabajo-industrial-operador.png  # Maquinaria para grandes superficies
│   ├── trabajo-industrial-maquinaria.png# Desbaste en bodega con andamio
│   └── README.md       # Guía detallada de fotos y dimensiones
└── PROMPT.md           # Ficha de especificaciones y prompt de continuidad
```

---

## 5. Secciones Implementadas en `index.html`

1. **Header fijo:** Logotipo oficial Nova Pisos, navegación anclada (`#servicios`, `#fichas`, `#resultados`, `#proceso`, `#zonas`, `#contacto`), botón CTA de WhatsApp y menú móvil responsivo.
2. **Hero:** Layout asimétrico con titular sobre no reemplazar sino renovar el piso, llamada a cotización en WhatsApp, botón a resultados y ventana visual con fotografía real de operador en uniforme Nova Pisos y efecto espejo.
3. **Franja de 4 valores:** Acabados de alta gama, protección y durabilidad, equipo profesional, sin obra/sin escombro.
4. **Servicios:** 3 bloques detallados con listas de beneficios, fotografías reales de proceso y acabado espejo, y botones directos a WhatsApp.
5. **Banda de materiales:** Chips interactivos para los 7 materiales que trabaja la empresa.
6. **Fichas Técnicas y Campañas Oficiales (`#fichas`):** Rejilla con las 3 infografías completas de Nova Pisos con toda la información publicitaria, argumentos de valor y botón para abrir en alta resolución.
7. **Referencias de Obra en Sitio (`#resultados`):** Rejilla con fotografías reales de trabajos en proceso, personal uniformado y el acabado espejo de entrega con visor interactivo.
8. **Proceso de venta:** 4 pasos numerados con iconos explicativos.
9. **Zonas de cobertura:** Cuadrícula con los 10 municipios de Nuevo León atendidos.
10. **CTA final:** Tarjeta destacada con acceso directo a WhatsApp y correo de ventas.
11. **Footer:** Datos de contacto repetidos, enlaces rápidos, eslogan y copyright.
12. **Botón flotante de WhatsApp:** Fijo en la esquina inferior derecha con efecto radar suave.
13. **Modal Lightbox:** Visor emergente para examinar cualquier fotografía o ficha en pantalla completa.

---

## 6. Prompt para Reanudar en Futuras Sesiones

Si deseas retomar el proyecto para añadir nuevas funciones, puedes copiar y pegar el siguiente prompt:

```markdown
Hola, estamos trabajando en la landing page de "Nova Pisos" (ubicada en nova-pisos-site/).
El sitio está construido con HTML y CSS planos (vanilla), paleta oscuro-dorada (#0B0A08, #C9A24B, #F2EEE3), fuentes Fraunces y Archivo, y enfoque en Monterrey y su área metropolitana.
Por favor revisa index.html, css/style.css y images/README.md para mantener coherencia con la identidad de marca, datos de contacto (WhatsApp 81 3565 6598, ventasnovapisos01@gmail.com) y tono visual antes de realizar cambios.
```
