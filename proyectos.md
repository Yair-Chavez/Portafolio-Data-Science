---
layout: single
classes: wide
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. MENÚ: Pegado a la izquierda y siempre visible */
  .masthead {
    position: sticky !important;
    top: 0;
    background: #fff !important;
    z-index: 9999 !important;
    border-bottom: 1px solid #eee;
  }
  .masthead__menu {
    float: left !important;
    margin-left: 3rem !important;
  }
  .masthead__menu-item:hover {
    color: #ff0000 !important;
    border-bottom: 2px solid #ff0000 !important;
  }

  /* 2. LAYOUT: Crear el espacio real para la foto */
  .initial-content, .page__content, .page__footer {
    margin-left: 280px !important; /* Espacio exacto para tu sidebar */
    position: relative;
    z-index: 10;
  }

  /* 3. CAJAS DE PROYECTOS: Estilo de tarjetas */
  .grid-personalizado {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 20px;
  }
  
  .tarjeta {
    flex: 1 1 280px;
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    padding: 15px;
    background: white;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }

  .tarjeta:hover {
    border-color: #ff0000;
  }

  /* 4. NOTA ROJA */
  .nota-confidencial {
    border-left: 5px solid #ff0000;
    padding: 15px;
    background: #fff5f5;
    margin-bottom: 25px;
  }
</style>

<div class="nota-confidencial">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos y contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales no son públicos.
</div>

### Proyectos Destacados

<div class="grid-personalizado">
  <div class="tarjeta">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Modelación actuarial avanzada aplicada a sistemas de calidad.</p>
  </div>

  <div class="tarjeta">
    <h4 style="margin:0">Proyecto MIT 1</h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Análisis predictivo de mercados utilizando Python.</p>
  </div>

  <div class="tarjeta">
    <h4 style="margin:0">Análisis de Riesgo</h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Simulaciones para evaluación de solvencia estratégica.</p>
  </div>
</div>
