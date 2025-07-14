---
contentType: article
createdAt: 2025-05-03T11:30:00.000Z
updatedAt: 2025-06-30T17:46:17.644Z
published: true
main:
  type: section
  value:
    title:
      type: string
      value: Article de test avec types
    body:
      type: richtext
      value: Ceci est le contenu de l'article
metadata:
  type: section
  value:
    author:
      type: string
      value: John Doe
    tags:
      type: array
      value:
        - test
        - types
    status:
      type: select
      value: ""
hero:
  type: section
  value:
    titre:
      type: string
      value: Mon titre hero
    datestart:
      type: date
      value: 2025-05-10T00:00:00.000Z
    testbool:
      type: boolean
      value: true
    testimg:
      type: image
      value:
        url: https://placehold.co/600x400
        alt: Image de test
    testref:
      type: reference
      value: article-reference
    galerietest:
      type: gallery
      value:
        - url: https://placehold.co/600x400
          alt: Image
          caption: Légende 1
          order: 0
        - url: https://placehold.co/600x400
          alt: Image 2
          caption: Légende 2
          order: 1
---




# Article de test avec types

Ceci est le contenu principal de l'article, écrit en Markdown.

## Une section

- Point 1
- Point 2
- Point 3