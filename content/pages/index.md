---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'Hei! Haluaisitko oppia tekemään nettisivut, pelejä ja paljon muuta?'
      color: text-dark
      type: TitleBlock
    subtitle: '-Olet oikeassa verkkoosoitteessa!'
    text: |
      Näillä sivuilla opit varmasti kuinka tehdä omat nettisivut, pelejä yms.
    actions:
      - label: Aloita
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Niman sivut
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
  - type: FeaturedItemsSection
    title:
      text: Näissä autamme ja opetamme!
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Subtitle goes here
    items:
      - type: FeaturedItem
        title: Nettisivut
        subtitle: Voit oppia tekemään netttisivut itse!
        text: >
          Me autamme sinua tekemään nettisivut itse alusta loppuun! Käytämme
          seuraavia kieliä -> HTML, CSS, JS
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/hero2.svg
          styles:
            self:
              borderRadius: x-large
      - title: Pelejä!
        subtitle: Voit oppia tekemää yksinkertaisia ja haastavia pelejä tietokoneelle!
        text: |
          Käytämme seuraavia kieliä -> c, c++, java, python
        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Sovellukset
        subtitle: Voit tehdä kanssamme mobiili sovelluksia.
        text: >
          **Teemme ne Androidille.** käytämme ainakin seuraavia kieliä ->
          kotlin, java
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: Aloita
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: 'Katso alas :)'
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: ''
    images:
      - type: ImageBlock
        url: /images/hero2.svg
        altText: Image alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
    badge:
      type: Badge
      label: Tervetuloa!
      color: text-primary
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
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
  - type: CarouselSection
    title: null
    subtitle: MItä mieltä muut ovat
    items:
      - title: '"Koodaaminen saattaa aluksi tuntua vaikealta! Anna meidän auttaa"'
        tagline: Kehittäjältä
        subtitle: Nima Sahraravand
        text: |
          Arvostele palvelumme saat arvostelusi myöhemmin tähän!
        image:
          url: /images/icon3.svg
          altText: Nima Sahraravand
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - type: FeaturedItem
        title: Otsikko tulee tähän
        tagline: Voit lisätä pienen mainoksen yrityksestäsi
        subtitle: Tekstiä
        text: |
          Lisää pitkää tekstiä
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
      - type: FeaturedItem
        title: Otsikko tähän
        tagline: Voit lisätä suuren mainoksen yrityksestäsi
        subtitle: Tekstiä
        text: |
          Lisää tekstiä
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
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
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Ota yhteyttä!
      color: text-dark
      type: TitleBlock
    subtitle: 'Täytä seuraava lomake:'
    text: >
      Tiedot ähetetään vain meille eikä niitä käytetä esim. manosten
      personoinnissa!
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Nimi
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Sähköposti
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: 'Viesti:'
          width: full
          type: TextareaFormControl
          isRequired: true
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
        label: Lähetä
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Onko asiaa?
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Naksu
  metaDescription: Tervetuloa Naku sivuille täällä opetamme koodaamaan!
  socialImage: /images/hero2.svg
  type: Seo
  metaTags:
    - type: MetaTag
      property: 'og:title'
      content: Naksu
type: PageLayout
---
