---
type: PageLayout
title: contacto
sections:
  - type: ContactSection
    title: Nos ponemos en contacto
    text: >
      Estamos interesados en pymes que quieran ejecutar una estrategia de
      marketing digital.


      Deja tus datos y nos pondremos en contacto para agendar una llamada.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: Tu Nombre
          label: Nombre
          hideLabel: false
          placeholder: Tu Nombre
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Correo
          hideLabel: false
          placeholder: Tu Correo
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: Información sobre tu negocio
          label: Cuentanos sobre tu proyecto/ empresa
          hideLabel: false
          placeholder: Tienda de antiguedades con 4 empleados...
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        self:
          textAlign: left
    media:
      type: ImageBlock
      url: /images/contact.jpg
      altText: Contact form image
      caption: Caption of the image
      elementId: ''
    colors: colors-a
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
