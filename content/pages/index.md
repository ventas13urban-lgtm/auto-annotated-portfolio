---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/5e46w457ww5ysr.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: HeroSection
    title: Marketing digital para Pymes
    subtitle: 'Somos una agencia de marketing y diseño con una misión principal. '
    actions: []
    media:
      type: ImageBlock
      url: /images/SELLO BLANCO.png
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-a
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-6
          - pb-11
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
    text: |
      Que tu negocio venda más, Sin rodeos ni complicaciones.
  - type: HeroSection
    title: Es momento...
    subtitle: >-
      Necesitas definir tu estrategia digital y empezar a vender más por
      internet.
    actions: []
    media:
      type: ImageBlock
      url: /images/9ur20eoaiwuoeuaowuç.png
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
  - type: ContactSection
    title: Agenda una asesoría
    text: >
      en 45 minutos podemos escuchar tu situación y orientarte hacia una
      estrategia digital para que vendas más por internet
    form:
      type: FormBlock
      title: Asesoría 1 a 1
      fields:
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: false
          placeholder: Tu Correa
          width: 1/2
          isRequired: 'true'
      submitLabel: Sign Up
      elementId: contact-form
      styles:
        self:
          textAlign: left
    colors: colors-a
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
  - type: CtaSection
    title: Agenda una asesoría
    text: >
      En menos de 45 minutos podemos escuchar tu situación y orientarte hacia
      una estrategia digital para que vendas más por internet
    actions:
      - type: Button
        label: AGENDA SIN COSTO
        altText: ''
        url: /
        showIcon: true
        icon: chevronRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-c
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        flexDirection: col
        textAlign: center
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-three.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Artículos
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
