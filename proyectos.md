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

  /* 2. ENSANCHAR TEXTO HASTA TUS LÍNEAS ROJAS */
  /* Forzamos al contenedor padre a ignorar su límite de ancho */
  .page {
    width: 100% !important;
    max-width: 100% !important;
    padding-right: 2% !important;
  }

  .archive, .page__content {
    max-width: 1250px !important; /* Aquí es donde se estira el texto a la derecha */
    width: 100% !important;
    padding-right: 40px !important;
  }

  /* 3. ESTILO DE CAJAS (Cards) */
  .contenedor-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 30px;
    width: 100%;
  }

  .tarjeta-proyecto {
    flex: 1 1 300px;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    padding: 25px;
    background: #ffffff;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    transition: 0.3s;
  }

  .tarjeta-proyecto:hover {
    border-color: #ff0000;
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(255,0,0,0.1);
  }
</style>

<div style="text-align: justify;">
Como Actuario con más de 17 años de trayectoria, he liderado proyectos de alta sensibilidad estratégica para diversas instituciones financieras y organismos internacionales.

<blockquote style="border-left: 5px solid #ff0000; background: #fff5f5; padding: 15px; margin: 20px 0;">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</blockquote>
</div>

---

### Proyectos Destacados

<div class="contenedor-grid">
  <div class="tarjeta-proyecto">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Modelación actuarial avanzada aplicada a sistemas de calidad y cálculo estructural.</p>
  </div>

  <div class="tarjeta-proyecto">
    <h4 style="margin:0; color: #333;">Proyecto MIT 1</h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Análisis predictivo de mercados utilizando técnicas de Machine Learning.</p>
  </div>

  <div class="tarjeta-proyecto">
    <h4 style="margin:0; color: #333;">Análisis de Riesgo</h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Simulaciones Monte Carlo para evaluación de solvencia en carteras dinámicas.</p>
  </div>
</div>
