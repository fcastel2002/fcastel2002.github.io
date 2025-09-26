---
layout: default
title: Guía paso a paso
nav_order: 1
permalink: /
description: Estructura base para documentar el flujo completo de la guía.
classes: guia-single
nav_exclude: true
---

<div class="guide-layout">
  <nav class="guide-toc" aria-label="Índice de la guía">
    <h2 class="guide-toc__title">Índice</h2>
    <ol class="guide-toc__list">
      <li><a href="#preparativos">Paso 0 · Preparativos</a>
        <ul>
          <li><a href="#preparativos-checklist">0.1 Checklist inicial</a></li>
          <li><a href="#preparativos-entorno">0.2 Entorno de trabajo</a></li>
          <li><a href="#preparativos-verificacion">0.3 Verificación previa</a></li>
        </ul>
      </li>
      <li><a href="#conexion">Paso 1 · Conexión física</a>
        <ul>
          <li><a href="#conexion-pinout">1.1 Pinout y cableado</a></li>
          <li><a href="#conexion-comprobaciones">1.2 Comprobaciones rápidas</a></li>
        </ul>
      </li>
      <li><a href="#configuracion">Paso 2 · Configuración del entorno</a>
        <ul>
          <li><a href="#configuracion-software">2.1 Instalación de software</a></li>
          <li><a href="#configuracion-openocd">2.2 Ajustes de OpenOCD</a></li>
          <li><a href="#configuracion-vscode">2.3 Integración con VS Code</a></li>
        </ul>
      </li>
      <li><a href="#diagnostico">Paso 3 · Diagnóstico y pruebas</a>
        <ul>
          <li><a href="#diagnostico-sesion">3.1 Sesión de depuración</a></li>
          <li><a href="#diagnostico-errores">3.2 Resolución de errores comunes</a></li>
        </ul>
      </li>
      <li><a href="#automatizacion">Paso 4 · Automatización y mantenimiento</a>
        <ul>
          <li><a href="#automatizacion-scripts">4.1 Scripts útiles</a></li>
          <li><a href="#automatizacion-buenas-practicas">4.2 Buenas prácticas</a></li>
        </ul>
      </li>
      <li><a href="#recursos">Paso 5 · Recursos adicionales</a>
        <ul>
          <li><a href="#recursos-documentacion">5.1 Documentación recomendada</a></li>
          <li><a href="#recursos-anexos">5.2 Anexos opcionales</a></li>
        </ul>
      </li>
      <li><a href="#bitacora">Bitácora de cambios / pendientes</a></li>
    </ol>
  </nav>

  <div class="guide-content" markdown="1">

## Paso 0 · Preparativos
{: #preparativos }

_Resumen breve del objetivo general del paso._

### 0.1 Checklist inicial
{: #preparativos-checklist }

- Elemento clave #1 → _detalla aquí qué debe verificarse._
- Elemento clave #2 → _añade instrucciones puntuales._
- Elemento clave #3 → _incluye criterios de aceptación._

> 💡 _Tip: reemplaza este bloque con advertencias o recordatorios relevantes antes de comenzar._

### 0.2 Entorno de trabajo
{: #preparativos-entorno }

1. **Herramienta/Librería:** _explica qué instalar o preparar._
2. **Configuración mínima:** _describe los parámetros imprescindibles._
3. **Validación:** _indica cómo confirmar que todo quedó listo._

### 0.3 Verificación previa
{: #preparativos-verificacion }

- [ ] Prueba rápida #1 — _define qué resultado esperar._
- [ ] Prueba rápida #2 — _anota posibles fallos y cómo detectarlos._
- [ ] Prueba rápida #3 — _documenta el criterio de éxito._

---

## Paso 1 · Conexión física
{: #conexion }

_Describe el objetivo de la conexión física y cualquier precaución._

### 1.1 Pinout y cableado
{: #conexion-pinout }

- Diagrama o tabla de pines que necesitas documentar.
- Secuencia de conexión sugerida.
- Controles visuales o con multímetro a realizar.

### 1.2 Comprobaciones rápidas
{: #conexion-comprobaciones }

1. **Prueba 1:** _indica qué medir o revisar._
2. **Prueba 2:** _explica la condición esperada._
3. **Prueba 3:** _añade una observación adicional._

---

## Paso 2 · Configuración del entorno
{: #configuracion }

_Introduce brevemente la finalidad de este paso._

### 2.1 Instalación de software
{: #configuracion-software }

- Programa/Paquete #1 → _detalla comandos o instaladores._
- Programa/Paquete #2 → _especifica la versión sugerida._
- Programa/Paquete #3 → _agrega notas de compatibilidad._

### 2.2 Ajustes de OpenOCD
{: #configuracion-openocd }

1. **Archivo de configuración:** _define ruta y parámetros clave._
2. **Comandos esenciales:** _lista los comandos que usarás después._
3. **Verificación:** _describe cómo validar que OpenOCD responde._

### 2.3 Integración con VS Code
{: #configuracion-vscode }

- Extensión necesaria → _indica el nombre exacto y cualquier ajuste._
- Archivo `launch.json` → _señala secciones a personalizar._
- Archivo `tasks.json` → _documenta tareas relevantes._

---

## Paso 3 · Diagnóstico y pruebas
{: #diagnostico }

_Explica brevemente el objetivo del diagnóstico._

### 3.1 Sesión de depuración
{: #diagnostico-sesion }

1. **Inicio de sesión:** _describe cómo lanzar la depuración._
2. **Breakpoints clave:** _detalla dónde colocarlos y por qué._
3. **Inspección:** _explica qué variables o registros observar._

### 3.2 Resolución de errores comunes
{: #diagnostico-errores }

- Error frecuente #1 → _anota síntomas y solución._
- Error frecuente #2 → _describe cómo detectarlo._
- Error frecuente #3 → _propone una alternativa de workaround._

---

## Paso 4 · Automatización y mantenimiento
{: #automatizacion }

_Introduce buenas prácticas para mantener el flujo a largo plazo._

### 4.1 Scripts útiles
{: #automatizacion-scripts }

- Script #1 → _explica propósito, ubicación y parámetros._
- Script #2 → _documenta requisitos adicionales._
- Script #3 → _añade nota sobre cómo extenderlo._

### 4.2 Buenas prácticas
{: #automatizacion-buenas-practicas }

1. **Rutina programada:** _indica periodicidad y objetivo._
2. **Control de versiones:** _resume la estrategia recomendada._
3. **Checklist de mantenimiento:** _documenta qué revisar regularmente._

---

## Paso 5 · Recursos adicionales
{: #recursos }

_Sugiere material externo o anexos que complementen la guía._

### 5.1 Documentación recomendada
{: #recursos-documentacion }

- Recurso #1 → _nombre y enlace._
- Recurso #2 → _breve nota de utilidad._
- Recurso #3 → _criterio para consultarlo._

### 5.2 Anexos opcionales
{: #recursos-anexos }

- Anexo #1 → _resumen del contenido adicional._
- Anexo #2 → _tipo de archivos o plantillas incluidas._
- Anexo #3 → _indicaciones para mantenerlos al día._

---

### Bitácora de cambios / pendientes
{: #bitacora }

- _Usa esta sección para registrar actualizaciones, aclaraciones o pendientes futuros._

  </div>
</div>

<style>
body.guia-single .page,
body.guia-single .site-main {
  display: block;
}

body.guia-single .side-bar,
body.guia-single .page__sidebar {
  display: none;
}

body.guia-single .main,
body.guia-single .page__content {
  margin: 0 auto;
  max-width: 72rem;
  padding-left: clamp(1.5rem, 3vw, 3rem);
  padding-right: clamp(1.5rem, 3vw, 3rem);
}

:root {
  --guide-sidebar-width: clamp(14rem, 25vw, 18rem);
  --guide-border-color: var(--color-border-muted, #d9d9d9);
}

.guide-layout {
  display: grid;
  grid-template-columns: minmax(12rem, var(--guide-sidebar-width)) minmax(0, 1fr);
  gap: clamp(1.5rem, 4vw, 2.5rem);
  margin: 0 auto;
}

.guide-toc {
  position: sticky;
  top: 2rem;
  align-self: start;
  max-height: calc(100vh - 4rem);
  overflow: auto;
  padding-right: 1rem;
  border-right: 1px solid var(--guide-border-color);
}

.guide-toc__title {
  margin-top: 0;
  font-size: 0.95rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
}

.guide-toc__list,
.guide-toc__list ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.guide-toc__list > li {
  margin-bottom: 0.85rem;
}

.guide-toc a {
  display: inline-block;
  padding: 0.15rem 0;
  color: var(--color-link, #2f6fbb);
  text-decoration: none;
}

.guide-toc a:hover,
.guide-toc a:focus {
  text-decoration: underline;
}

.guide-content h2,
.guide-content h3,
.guide-content h4 {
  scroll-margin-top: 4rem;
}

.guide-content > *:first-child {
  margin-top: 0;
}

@media (max-width: 960px) {
  body.guia-single .main,
  body.guia-single .page__content {
    padding-left: 1.5rem;
    padding-right: 1.5rem;
  }

  .guide-layout {
    grid-template-columns: 100%;
  }

  .guide-toc {
    position: relative;
    top: auto;
    max-height: none;
    border-right: none;
    border-bottom: 1px solid var(--guide-border-color);
    margin-bottom: 2rem;
    padding-bottom: 1.5rem;
  }
}

@media (max-width: 640px) {
  .guide-toc__title {
    font-size: 0.875rem;
  }

  .guide-toc a {
    font-size: 0.9rem;
  }
}
</style>
