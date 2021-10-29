---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-a
    backgroundWidth: full
    backgroundImage:
      altText: lorem-ipsum
      caption: lorem-ipsum
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    title: Things the interest me
    actions:
      - label: How to Get Rich
        altText: Learn more
        url: /
        showIcon: false
        icon: arrowLeft
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: flex-end
        justifyContent: center
        flexDirection: col
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    subtitle: Learn how to get rich and where to surf.
  - type: FeaturedPostsSection
    variant: variant-c
    colors: colors-a
    backgroundWidth: full
    title: How to Get Rich
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    subtitle: The first steps you should take to make yourself rich
  - type: ContactSection
    colors: colors-a
    backgroundWidth: full
    title: Get future posts
    feature:
      type: ImageBlock
      url: /images/contact.png
      altText: Fisherman holding lobster
    form:
      type: FormBlock
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
      submitLabel: Send Message
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
---
