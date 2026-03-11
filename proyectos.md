---
layout: single
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. Fuerza el menú Proyectos a la IZQUIERDA */
  .masthead__menu {
    float: left !important;
    margin-left: 30px !important;
  }
  .masthead__menu-item:hover {
    color: #ff0000 !important;
    border-bottom: 2px solid #ff0000 !important;
  }

  /* 2. FIX DE ENCIMADO: Crea un muro para que no toque la foto */
  .page__inner-wrap {
    margin-left: 0 !important;
    padding-left: 5% !important;
    width: 100% !important;
  }

  /* 3. Estética de la nota de confidencialidad (ROJO) */
  .nota-roja {
    border-left: 5px solid #ff0000;
    padding: 15px;
    background: #fff5f5;
    margin-bottom: 30px;
    text-align: justify;
  }

  /* 4. LAS CAJAS (Grid) */
  .contenedor-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    width: 100%;
  }

  .caja-proyecto {
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    padding: 20px;
    transition: 0.3s;
    background: white;
  }

  .caja-proyecto:hover {
    border-color: #ff0000;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }
</style>

<div class="nota-roja">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</div>

### Proyectos Destacados

<div class="contenedor-grid">
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
