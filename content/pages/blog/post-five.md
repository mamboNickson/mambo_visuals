---
type: PostLayout
title: My work
colors: colors-a
date: '2024-05-02'
excerpt: More context that may or may not be helpful
featuredImage:
  type: ImageBlock
  url: /images/DSC05425.JPG
  altText: Post thumbnail image
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: Stay up-to-date with my words ✍️
    colors: colors-f
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
          width: full
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/DSC03799.JPG
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/DSC06057.JPG
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/DSC04671.JPG
        altText: '16:9'
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/DSC03681.JPG
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/DSC01813.JPG
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/DSC07638.jpeg
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/DSC04814.JPG
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/DSC02099.JPG
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
    colors: colors-a
    spacing: 10
    columns: 2
    aspectRatio: auto
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
media:
  type: ImageBlock
  url: /images/DSC05549.JPG
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
---
