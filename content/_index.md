---
title: 'Home'
date: 2024-05-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Estructura y dinámica social 
      text: Escuela de verano del laboratorio de humanidades y ciencias sociales computacionales
      text: 25-28 de Junio de 2024
      primary_action:
        text: Registro
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: imagen1.jpeg
          filters:
            brightness: 0.5
  
  - block: features
    id: features
    content:
      title: Calendario
      text: Fechas importantes
      items:
        - name: Apertura del registro
          icon: bolt
          description: 15 de Mayo de 2024
        - name: Fecha limite del registro
          icon: bolt
          description: 29 de Mayo de 2024
        - name: Confirmación de aceptacion
          icon: bolt
          description: 30 de Mayo de 2024
        - name: Fecha de inicio de la Escuela
          icon: bolt
          description: 25 de Junio de 2024
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Temas
          text: Se impartiran tres talleres que aboradan los siguientes tópicos
          feature_icon: check
          features:
            - "Teoría de gráficas"
            - "Procesamiento de lenguaje natural"
            - "Historiografía"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Material de referencia
            url: https://hugoblox.com/templates/
        
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    id: location
    content:
      title: "Ubicacion de las seciones"
      text: ""
      address:
        street: Circuito Escolar
        city: Ciudad Universitaria
        region: Ciudad de México
        postcode: '04510'
        country: México
        country_code: MX
      directions: Third level, office 304.
      office_hours:
        - 'Monday 09:00 to 16:30'
        - 'Tuesday 09:00 to 16:30'
        - 'Wednesday 09:00 to 16:30'
        - 'Thursday 09:00 to 16:30'
        - 'Friday 09:00 to 16:30'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '19.33027'
        longitude: '-99.18066'  
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      columns: '2'

  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
