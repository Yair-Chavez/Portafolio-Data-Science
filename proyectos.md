---
layout: single
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. MENÚ A LA IZQUIERDA */
  .masthead__menu {
    float: left !important;
    margin-left: 3.5rem !important;
  }

  /* 2. FIX DE COLUMNAS: PERFIL + TEXTO */
  @media (min-width: 64em) {
    /* Contenedor que abraza perfil y contenido */
    .page__inner-wrap {
      display: grid !important;
      grid-template-columns: 260px 1fr !important; /* Carril fijo para foto, resto para texto */
      grid-template-areas: "sidebar content" !important;
      column-gap: 40px !important;
      width: 100% !important;
      max-width: 100% !important;
    }

    /* Forzar al título a ocupar todo el ancho superior */
    .page__title {
      grid-column: 1 / span 2 !important;
      margin-bottom: 30px !important;
    }

    .sidebar {
      grid-area: sidebar !important;
      width: 260px !important;
      display: block !important;
    }

    .page__content {
      grid-area: content !important;
      width: 100% !important;
      max-width: 1100px !important; /* Se estira hasta tu línea roja */
      margin: 0 !important;
    }
  }

  /* 3. CAJAS DE PROYECTOS */
  .grid-proyectos {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin-top: 30px;
  }

  .tarjeta-actuarial {
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    padding: 25px;
    background: #fff;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }
</style>

Como Actuario con más de **18 años** de trayectoria, he liderado proyectos de alta sensibilidad estratégica para diversas instituciones financieras y organismos internacionales.

<blockquote style="border-left: 5px solid #ff0000; background: #fff5f5; padding: 15px; margin: 20px 0;">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</blockquote>

---

### Proyectos Destacados

<div class="grid-proyectos">
  <div class="tarjeta-actuarial">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Modelación actuarial avanzada aplicada a sistemas de calidad y cálculo estructural.</p>
  </div>

  <div class="tarjeta-actuarial">
    <h4 style="margin:0; color: #333;">Proyecto MIT 1</h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Análisis predictivo de mercados utilizando técnicas de Machine Learning con Python.</p>
  </div>

  <div class="tarjeta-actuarial">
    <h4 style="margin:0; color: #333;">Análisis de Riesgo</h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Simulaciones Monte Carlo para evaluación de solvencia en carteras dinámicas.</p>
  </div>
</div>
