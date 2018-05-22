---
name: Google Translate
x-slug: google-translate
description: Cloud Translation API provides a simple programmatic interface for translating
  an arbitrary string into any supported language. Translation API is highly responsive,
  so websites and applications can integrate with Translation API for fast, dynamic
  translation of source text from the source language to a target language (e.g.,
  French to English). Language detection is also available In cases where the source
  language is unknown. The underlying technology pushes the boundary of Machine Translation
  and is updated constantly to seamlessly improve translations and introduce new languages
  and language pairs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-translate-hello-lead-2x.png
x-kinRank: "9"
x-alexaRank: ""
tags: Google Translate
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-translate/master/_listings/google-translate/apis.md
specificationVersion: "0.14"
apis:
- name: Google Translate API Translate Text
  x-api-slug: google-translate-api
  description: Returns text translations from one language to another.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-translate-hello-lead-2x.png
  humanURL: https://translate.google.com/
  baseURL: ://www.googleapis.com//language/translate//v2
  tags: Translate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-translate/master/_listings/google-translate/v2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-translate/master/_listings/google-translate/v2-get-openapi.md
- name: Google Translate API Detect Language
  x-api-slug: google-translate-api
  description: Detect the language of text.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-translate-hello-lead-2x.png
  humanURL: https://translate.google.com/
  baseURL: ://www.googleapis.com//language/translate//v2/detect
  tags: Language
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-translate/master/_listings/google-translate/v2detect-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-translate/master/_listings/google-translate/v2detect-get-openapi.md
- name: Google Translate API Get Languages
  x-api-slug: google-translate-api
  description: List the source/target languages supported by the API
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-translate-hello-lead-2x.png
  humanURL: https://translate.google.com/
  baseURL: ://www.googleapis.com//language/translate//v2/languages
  tags: Language
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-translate/master/_listings/google-translate/v2languages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-translate/master/_listings/google-translate/v2languages-get-openapi.md
- name: Google Translate API
  x-api-slug: google-translate-api
  description: Cloud Translation API provides a simple programmatic interface for
    translating an arbitrary string into any supported language. Translation API is
    highly responsive, so websites and applications can integrate with Translation
    API for fast, dynamic translation of source text from the source language to a
    target language (e.g., French to English). Language detection is also available
    In cases where the source language is unknown. The underlying technology pushes
    the boundary of Machine Translation and is updated constantly to seamlessly improve
    translations and introduce new languages and language pairs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-translate-hello-lead-2x.png
  humanURL: https://translate.google.com/
  baseURL: ://www.googleapis.com//language/translate
  tags: Google Translate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-translate/master/_listings/google-translate/openapi.md
x-common:
- type: x-attribution
  url: https://cloud.google.com/translate/attribution
- type: x-change-log
  url: https://cloud.google.com/translate/release-notes
- type: x-code
  url: https://cloud.google.com/translate/docs/reference/libraries
- type: x-developer
  url: https://cloud.google.com/translate/
- type: x-documentation
  url: https://cloud.google.com/translate/docs/
- type: x-faq
  url: https://cloud.google.com/translate/faq
- type: x-getting-started
  url: https://cloud.google.com/translate/docs/getting-started
- type: x-pricing
  url: https://cloud.google.com/translate/pricing
- type: x-rate-limits
  url: https://cloud.google.com/translate/limits
- type: x-support
  url: https://cloud.google.com/translate/support
- type: x-terms-of-service
  url: https://cloud.google.com/terms/
- type: x-website
  url: https://translate.google.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---