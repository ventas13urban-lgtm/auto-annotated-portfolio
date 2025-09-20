---
type: PageLayout
title: contacto
sections:
  - type: TextSection
    title: Nos ponemos en contacto
    subtitle: >-
      Estamos interesados en pymes que quieran ejecutar una estrategia de
      marketing digital.
    text: |
      Deja tus datos y nos pondremos en contacto para agendar una llamada.
    colors: colors-f
    variant: variant-a
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-10
          - pl-4
          - pr-4
        textAlign: left
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
          name: name
          label: Name
          hideLabel: false
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: false
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: Información sobre tu negocio
          label: Cuentanos sobre tu proyecto/ empresa
          hideLabel: false
          placeholder: Cuentanos sobre tu proyecto/ empresa
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
    colors: colors-d
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
