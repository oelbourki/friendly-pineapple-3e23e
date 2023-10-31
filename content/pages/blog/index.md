---
layout: PostFeedLayout
title: Projects
numOfPostsPerPage: 10
styles:
  title:
    textAlign: center
bottomSections: []
addTitleSuffix: true
topSections:
  - type: CtaSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Check my Github for latest projects
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        showIcon: true
        icon: arrowRight
        url: /
        style: primary
    backgroundImage: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedPostsSection
    colors: colors-e
    elementId: ''
    showDate: true
    showAuthor: false
    showExcerpt: false
    showReadMoreLink: true
    readMoreLinkLabel: Join adventure
    variant: variant-b
    actions: []
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    title: Seasonal adventure
    subtitle: ''
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
---
