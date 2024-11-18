---
title: Home
slug: /
sections:
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
          url: /images/abstract-feature1.svg
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
        colors: bg-neutral-fg-dark
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
          url: /images/abstract-feature2.svg
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
        colors: bg-neutral-fg-dark
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
          url: /images/abstract-feature3.svg
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
        colors: bg-neutral-fg-dark
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
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify Create site.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutral-fg-dark
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
    colors: bg-light-fg-dark
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
