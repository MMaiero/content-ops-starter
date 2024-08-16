---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Maiero Ivano sas
      color: text-dark
      type: TitleBlock
    subtitle: Prototipazione e arredi su misura
    text: ''
    actions:
      - label: Più informazioni
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/hero-background.jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: 'La tradizione e l''innovazione, dal 1953'
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title:
      text: Prodotti e Servizi
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Ampia selezione di prodotti e servizi per l'arredamento e il su misura
    items:
      - title: Arredi
        tagline: ''
        subtitle: Realizzazione arredamenti su commissione
        text: ''
        image:
          url: /images/1244480_651139701576393_1418421173_o.jpg.webp
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: Visita
            altText: ''
            url: /arredi
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - title: Lavorazioni Laser
        tagline: ''
        subtitle: Taglio e marcatura laser
        text: ''
        image:
          url: /images/intarsio.jpg.webp
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: Visita
            altText: ''
            url: /lavorazioni_laser
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - title: Lavorazioni CNC
        tagline: ''
        subtitle: Fresatura a 3 e 5 assi
        text: ''
        image:
          url: /images/chiesa.jpg.webp
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: Visita
            altText: ''
            url: /cnc
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - type: FeaturedItem
        title: Complementi d'Arredo
        tagline: This is the tagline
        subtitle: Prototipi e componenti in legno
        text: |
          Follow the tutorial to build your first Netlify Create site.
        image:
          type: ImageBlock
          url: /images/tappetosequals.jpeg.webp
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Visita
            altText: ''
            url: /complementi
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - subtitle: ''
    text: |
      ### Indirizzo

      Via Giuseppe Verdi, 26

      33010 fr. Colugna di Tavagnacco (UD)

      ### Riferimenti

      Tel: +39 0432 401175

      email: <info@maiero.eu>

      ### Orari d'apertura

      Lun - Ven: 8:00 – 17:00

      Sabato: Chiuso

      Domenica: Chiuso
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Nome
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Messaggio
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contatti
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
