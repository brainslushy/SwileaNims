---
title: Home
slug: /
sections:
  - title: Divider
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: NIMS Training Links
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Create FEMA SID
        tagline: Step 1
        subtitle: Student Identification
        text: >
          This link will take you to register for a FEMA SID if you do not have
          one. 
        image:
          type: ImageBlock
          url: /images/images.png
          altText: Background alt text
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Get started
            altText: ''
            url: 'https://cdp.dhs.gov/femasid/register'
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
            flexDirection: row
      - type: FeaturedItem
        title: Create login.gov
        tagline: Step 2
        subtitle: More Government Red Tape
        text: >
          After setting up a FEMA SID, create a login.gov account. The
          information you used for the FEMA SID should match this account.
        image:
          type: ImageBlock
          url: /images/images.png
          altText: Background alt text
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Get started
            altText: ''
            url: 'https://training.fema.gov/signin/'
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
            flexDirection: row
      - type: FeaturedItem
        title: NIMS IS-700
        tagline: Step 3 - Course 1
        subtitle: Introduction to NIMS
        text: |
          National Incident Management System Introduction
        image:
          type: ImageBlock
          url: /images/images.png
          altText: Background alt text
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Get started
            altText: ''
            url: >-
              https://training.fema.gov/is/courseoverview.aspx?code=IS-700.b&lang=en
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
            flexDirection: row
      - type: FeaturedItem
        title: NIMS ICS-100.c
        tagline: Step 4 - Course 2
        subtitle: Introduction to ICS
        text: |
          Incident Command System Introduction
        image:
          type: ImageBlock
          url: /images/images.png
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Get started
            altText: ''
            url: >-
              https://training.fema.gov/is/courseoverview.aspx?code=IS-100.c&lang=en
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
            flexDirection: row
      - type: FeaturedItem
        title: NIMS ICS-200.c
        tagline: Step 5 - Course 3
        subtitle: Basic ICS for initial response
        text: |
          Initial Responder ICS & Supervisory Actions
        image:
          type: ImageBlock
          url: /images/images.png
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Get started
            altText: ''
            url: >-
              https://training.fema.gov/is/courseoverview.aspx?code=IS-200.c&lang=en
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
            flexDirection: row
    actions: []
    variant: two-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
