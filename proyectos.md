---
layout: single
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. MOVER MENÚ A LA IZQUIERDA Y FIJARLO */
  .masthead {
    position: sticky !important;
    top: 0;
    z-index: 1000 !important;
    background: white !important;
  }
  .masthead__menu {
    float: left !important;
    margin-left: 3.5rem !important; /* Ajuste para que pegue al título */
  }
  .masthead__menu-item:hover {
    color: #ff0000 !important;
    border-bottom: 2px solid #ff0000 !important;
  }

  /* 2. EL "MURO" PARA QUE NO SE ENCIME */
  /* Aplicamos el margen a todo el contenedor principal */
  #main {
    display: flex !important;
    max-width: 100% !important;
  }

  .archive, .page__content {
    margin-left: 50px !important; /* Espacio extra tras la foto */
    width: 100% !important;
    max-width: 1100px !important;
  }

  /* 3. RECUPERAR EL ROJO */
  blockquote {
    border-left: 5px solid #ff0000 !important;
    background-color: #fff5f5 !important;
    padding: 15px !important;
    color: #333 !important;
  }

  /* 4. LAS CAJAS DE PROYECTOS (GRID) */
  .contenedor-proyectos {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 30px;
  }

  .tarjeta-proyecto {
    flex: 1 1 300px; /* Tres cajas por fila si hay espacio */
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 20px;
    background: #fff;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    transition: 0.3s;
  }

  .tarjeta-proyecto:hover {
    border-color: #ff0000;
    transform: translateY(-5px);
  }
</style>

<div style="text-align: justify;">
Como Actuario con más de 17 años de trayectoria, he liderado proyectos de alta sensibilidad estratégica para diversas instituciones financieras y organismos internacionales.

> **Nota de Confidencialidad:** Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</div>

---

### Proyectos Destacados

<div class="contenedor-proyectos">
  
  <div class="tarjeta-proyecto">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Modelación actuarial avanzada aplicada a sistemas de calidad y cálculo estructural.</p>
  </div>

  <div class="tarjeta-proyecto">
    <h4 style="margin:0; color: #333;">Proyecto MIT 1</h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Análisis predictivo de mercados utilizando técnicas de Machine Learning.</p>
  </div>

  <div class="tarjeta-proyecto">
    <h4 style="margin:0; color: #333;">Análisis de Riesgo</h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Simulaciones Monte Carlo para evaluación de solvencia en carteras dinámicas.</p>
  </div>

</div>
