---
layout: single
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
classes: wide
---

<style>
  /* 1. Forzar el Menú a la izquierda */
  .masthead__menu {
    float: left !important;
    margin-left: 2rem !important;
  }

  /* 2. Recuperar el color ROJO */
  .nota-roja {
    border-left: 5px solid #ff0000;
    padding: 15px;
    background: #fff5f5;
    margin-bottom: 25px;
  }

  /* 3. Evitar el encimado: El truco del margen dinámico */
  @media (min-width: 64em) {
    .page__content {
      padding-right: 5% !important;
      margin-left: 0 !important;
      width: 100% !important;
    }
  }

  /* 4. Cuadrícula de proyectos (Cards) */
  .grid-container {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    margin-top: 30px;
  }

  .proyecto-card {
    flex: 1 1 250px;
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    padding: 20px;
    background: #fff;
    transition: 0.3s;
    box-shadow: 0 1px 3px rgba(0,0,0,0.1);
  }

  .proyecto-card:hover {
    border-color: #ff0000;
    transform: translateY(-5px);
  }
</style>

<div class="nota-roja" style="text-align: justify;">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</div>

---

### Proyectos Destacados

<div class="grid-container">
  <div class="proyecto-card">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.85em; margin-top:10px;">Modelación actuarial avanzada aplicada a sistemas de calidad.</p>
  </div>

  <div class="proyecto-card">
    <h4 style="margin:0; color: #333;">Proyecto MIT 1</h4>
    <p style="font-size: 0.85em; margin-top:10px;">Análisis predictivo de mercados utilizando Machine Learning.</p>
  </div>

  <div class="proyecto-card">
    <h4 style="margin:0; color: #333;">Análisis de Riesgo</h4>
    <p style="font-size: 0.85em; margin-top:10px;">Simulaciones estocásticas para evaluación de solvencia.</p>
  </div>
</div>
