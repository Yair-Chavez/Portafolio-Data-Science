---
layout: single
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. MOVER MENÚ A LA IZQUIERDA */
  .masthead__menu {
    float: left !important;
    margin-left: 3.5rem !important;
  }

  /* 2. ELIMINAR EL "CENTRADO" FORZADO DEL TEMA */
  /* Esto hace que Proyectos se alinee igual que la Principal */
  .page {
    width: 100% !important;
    padding-right: 0 !important;
    margin-right: 0 !important;
  }

  .page__inner-wrap {
    float: left !important; /* Fuerza la alineación a la izquierda */
    width: 100% !important;
    max-width: 100% !important; /* Rompe el corsé de lectura */
  }

  .archive, .page__content {
    text-align: left !important;
    width: 100% !important;
    max-width: 100% !important;
  }

  /* 3. RECUPERAR EL ROJO Y CUADRÍCULA */
  .nota-roja {
    border-left: 5px solid #ff0000;
    padding: 15px;
    background: #fff5f5;
    margin-bottom: 25px;
    width: 100%;
  }

  .grid-proyectos {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    width: 100%;
  }
</style>

<div class="nota-roja">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</div>

---

### Proyectos Destacados

<div class="grid-proyectos">
  <div style="border: 1px solid #eee; padding: 20px; border-radius: 10px; background: #fff;">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.9em; margin-top: 10px;">Modelación actuarial avanzada aplicada a sistemas de calidad.</p>
  </div>
  <div style="border: 1px solid #eee; padding: 20px; border-radius: 10px; background: #fff;">
    <h4 style="margin:0">Proyecto MIT 1</h4>
    <p style="font-size: 0.9em; margin-top: 10px;">Análisis predictivo de mercados con Python.</p>
  </div>
  <div style="border: 1px solid #eee; padding: 20px; border-radius: 10px; background: #fff;">
    <h4 style="margin:0">Análisis de Riesgo</h4>
    <p style="font-size: 0.9em; margin-top: 10px;">Simulaciones para evaluación de solvencia estratégica.</p>
  </div>
</div>
