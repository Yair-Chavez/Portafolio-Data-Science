---
layout: single
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. FIJAR EL MENÚ ARRIBA (Sticky) */
  .masthead {
    position: sticky !important;
    top: 0;
    z-index: 1000;
    background: white;
  }

  /* 2. MOVER MENÚ A LA IZQUIERDA */
  .masthead__menu {
    float: left !important;
    margin-left: 3rem !important;
  }

  /* 3. ELIMINAR ESPACIO EN BLANCO Y FIX DE ENCIMADO */
  .page {
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  .archive, .page__content {
    margin-left: 300px !important; /* Muro para que no toque tu foto */
    width: auto !important;
    max-width: 1000px !important;
  }

  /* 4. ESTÉTICA ROJA Y CAJAS */
  .caja-proyecto {
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    padding: 20px;
    display: inline-block;
    width: 30%;
    margin-right: 2%;
    vertical-align: top;
    background: white;
    transition: 0.3s;
  }

  .caja-proyecto:hover {
    border-color: #ff0000;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }

  .nota-roja {
    border-left: 5px solid #ff0000;
    padding: 15px;
    background: #fff5f5;
    margin-bottom: 20px;
  }
</style>

<div class="nota-roja">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos y contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales no son públicos.
</div>

### Proyectos Destacados

<div style="width: 100%; display: block; clear: both;">
  <div class="caja-proyecto">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.85em; margin-top:10px;">Modelación actuarial avanzada aplicada a sistemas de calidad.</p>
  </div>

  <div class="caja-proyecto">
    <h4 style="margin:0">Proyecto MIT 1</h4>
    <p style="font-size: 0.85em; margin-top:10px;">Análisis predictivo de mercados utilizando Python.</p>
  </div>

  <div class="caja-proyecto">
    <h4 style="margin:0">Análisis de Riesgo</h4>
    <p style="font-size: 0.85em; margin-top:10px;">Simulaciones para evaluación de solvencia estratégica.</p>
  </div>
</div>
