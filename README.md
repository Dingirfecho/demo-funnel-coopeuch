# Demo animada · Funnel de reclutamiento

Página única (`index.html`), sin dependencias ni build. Solo usa Google Fonts por CDN (sin conexión cae a tipografías del sistema).

## Secciones (guía de 60 min)
1. Recorrido animado de una búsqueda (5')
2. Arquitectura: componentes y 8 flujos del orquestador (10')
3. Funnel: simulador de etapas, próxima acción, días en etapa y tareas vencidas (10')
4. Correos: plantillas, autenticación del dominio, reglas de envío y calculador de volumen (10')
5. Candidato único: validador de RUT y puntaje de coincidencia (5')
6. LLM y datos: qué ve el LLM, tareas, retención, roles y derechos (10')
7. Fallas: detección, contención, corrección y prevención (5')
8. Roadmap: fases con actividades, entregables, flujos, requisitos y criterio de salida; vista en 4 fases o en 2 etapas (5')
9. Preguntas técnicas y lo que se define en Fase 0 (5')

Acceso directo a una sección: `index.html#funnel`, `#mail`, `#arq`, `#dedup`, `#llm`, `#fallas`, `#road`, `#faq`.

## Publicar en GitHub Pages
Settings → Pages → Deploy from a branch → `main` / root.

## Notas
- Datos y ejemplos ficticios; los payloads, cabeceras y registros DNS son ilustrativos.
- Lo que depende de la cuenta del cliente (API del sistema de RR.HH., portales, proveedor de correo, región) está marcado "a confirmar en Fase 0".
- La página lleva `noindex`, pero la URL es accesible para quien la tenga.
- Para tener respaldo sin internet, abrir `index.html` local en el navegador.
