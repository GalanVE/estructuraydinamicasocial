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
      text: <p style="color:white"; font-size:60px;> <b>25-28 de Junio de 2024</b></p>

         <p style="color:white"; font-size:40px;>Escuela de verano del laboratorio de humanidades y ciencias sociales computacionales</p>
      primary_action:
        text: Registro
        url: https://docs.google.com/forms/d/e/1FAIpQLSerckMK947imyvo8ZgKdE-EPCB3bMCRmFZFe24CIZ83KqBv3g/viewform?usp=sf_link
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
          filename: cartel_test01.png
          filters:
            brightness: 0.5
  
  - block: features
    id: features
    content:
      title: Calendario
      text: Fechas importantes
      items:
        - name: Apertura del registro
          icon: calendar
          description: 15 de Mayo de 2024
        - name: Fecha limite del registro
          icon: calendar
          description: 07 de Junio de 2024
        - name: Notificación de aceptación
          icon: calendar
          description: 10 de Junio de 2024
        - name: Fecha de inicio de la Escuela
          icon: calendar
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
          image: horario.png
          button:
            text: Material de referencia
            url: 
        
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
    
  - block: markdown
    id: location
    content:
      title: "Ubicacion de las seciones"
      subtitle: Faultad del Hábitad - Universidad Autónoma de San Luís Potosí
      text:
        <pre>
          Facultad del Hábitad - Universidad Autónoma de San Luís Potosí

          Av. Niño Artillero 150, Zona Universitaria, 78290 San Luis Potosí, S.L.P.
        </pre>

        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d957.1083972225258!2d-101.01427912682814!3d22.142868972626268!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x842a98ce1f07db65%3A0xe86ada8a5f638fcc!2sFacultad%20del%20H%C3%A1bitat!5e1!3m2!1ses-419!2smx!4v1715219726328!5m2!1ses-419!2smx" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

  - block: features
    id: organizadores
    content:
      title: Comité organizador
      items:
        - name: Dra. Karla Flores Zarur
          icon: my-uaslp
          icon_pack: custom
        - name: Mtro. Andres Raymundo Zuccolotto Villalobos
          icon: my-uaslp
          icon_pack: custom
        - name: Dr. Manuel Guerrero Salinas
          icon: my-uaslp
          icon_pack: custom
        - name: Erendida Cristina Mancilla
          icon: my-uaslp
          icon_pack: custom
        - name: Dr. Edgardo Ugalde
          icon: my-uaslp
          icon_pack: custom
          description: Instituto de Física UASLP
        - name: Dr. Edgardo Galán Vásquez
          icon: iimaslogo
          icon_pack: custom
          description: Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas - UNAM
        - name: Dr. José Antonio Motilla Chávez
          icon: my-uaslp
          icon_pack: custom
          description: Facultad del Hábitad - UASLP

  - block: markdown
    content:
      text: 
        <img class="special-img-class" src="./logos.png" width="400" height="800" />
        
---


  
---
