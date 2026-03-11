---
layout: single
classes: wide
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. Recuperar el ROJO en el menú y links */
  .masthead__menu-item:hover {
    color: #ff0000 !important;
    border-bottom: 2px solid #ff0000 !important;
  }
  
  /* 2. Barra de confidencialidad en ROJO */
  blockquote {
    border-left: 5px solid #ff0000 !important;
    background-color: #fff5f5 !important;
  }

  /* 3. Mover menú a la izquierda */
  .masthead__menu {
    float: left !important;
    margin-left: 2rem !important;
  }

  /* 4. FIX ANTICOLISIÓN: Evita que se encime en la foto */
  .page {
    padding-left: 300px !important; /* Espacio reservado para tu foto */
  }

  @media (max-width: 1024px) {
    .page { padding-left: 0 !important; }
  }

  /* 5. CUADRÍCULA DE PROYECTOS */
  .grid-container {
    display: flex;
    gap: 20px;
    margin-top: 30px;
    flex-wrap: wrap;
  }

  .proyecto-card {
    flex: 1;
    min-width: 250px;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    background: #fff;
    transition: transform 0.2s;
  }

  .proyecto-card:hover {
    border-color: #ff0000;
    transform: translateY(-5px);
  }
</style>

<div style="text-align: justify;">
Como Actuario con más de 18 años de trayectoria, he liderado proyectos de alta sensibilidad estratégica para diversas instituciones financieras y organismos internacionales.

> **Nota de Confidencialidad:** Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</div>

---

### Proyectos Destacados

<div class="grid-container">
  
  <div class="proyecto-card">
    <h4 style="margin: 0;"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Modelación actuarial avanzada y control de calidad estructural.</p>
  </div>

  <div class="proyecto-card">
    <h4 style="margin: 0; color: #333;">Proyecto MIT 1</h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Análisis predictivo de mercados utilizando Python.</p>
  </div>

  <div class="proyecto-card">
    <h4 style="margin: 0; color: #333;">Análisis de Riesgo</h4>
    <p style="font-size: 0.85em; margin-top: 10px;">Simulaciones estocásticas bajo cumplimiento de NDA.</p>
  </div>

</div>
