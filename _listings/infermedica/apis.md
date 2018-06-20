---
name: Infermedica
x-slug: infermedica
description: At Infermedica we believe in people. Every team member brings unique
  skills, talent and knowledge. Together we solve the most complex healthcare problems.
  Infermedica improves the diagnostic process using the most advanced reasoning technology
  for preliminary medical diagnosis.White-labelled enterprise platform (web, mobile,
  chatbot or voice-enabled applications) for symptom checking, patient triage and
  clinical decision support. Open developer portal that allows to easily integrate
  our diagnostic engine into 3rd party software.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
x-kinRank: "7"
x-alexaRank: "0"
tags: Health
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/apis.md
specificationVersion: "0.14"
apis:
- name: Infermedica Get Conditions
  x-api-slug: infermedica
  description: Returns a list of all available conditions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//conditions
  tags: Healthcare,Conditions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/conditions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/conditions-get-openapi.md
- name: Infermedica Get Conditions
  x-api-slug: infermedica
  description: Returns details of a single condition specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//conditions/{id}
  tags: Healthcare,Conditions,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/conditionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/conditionsid-get-openapi.md
- name: Infermedica Post Diagnosis
  x-api-slug: infermedica
  description: Suggests possible diagnoses and relevant observations based on provided
    patient information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//diagnosis
  tags: Healthcare,Diagnosis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/diagnosis-post-openapi.md
- name: Infermedica Post Explain
  x-api-slug: infermedica
  description: Explains which evidence impact probability of selected condition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//explain
  tags: Healthcare,Explain
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/explain-post-openapi.md
- name: Infermedica Get Info
  x-api-slug: infermedica
  description: Returns information about data used by diagnostic engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//info
  tags: Healthcare,Info
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/info-get-openapi.md
- name: Infermedica Get Lab Tests
  x-api-slug: infermedica
  description: Returns a list of all available lab tests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//lab_tests
  tags: Healthcare,Lab,Tests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/lab-tests-get-openapi.md
- name: Infermedica Get Lab Tests
  x-api-slug: infermedica
  description: Returns details of a single lab test specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//lab_tests/{id}
  tags: Healthcare,Lab,Tests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/lab-testsid-get-openapi.md
- name: Infermedica Get Lookup
  x-api-slug: infermedica
  description: Returns a single observation matching given phrase.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//lookup
  tags: Healthcare,Lookup
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/lookup-get-openapi.md
- name: Infermedica Post Parse
  x-api-slug: infermedica
  description: Returns list of mentions of observation found in given text.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//parse
  tags: Healthcare,Parse
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/parse-post-openapi.md
- name: Infermedica Get Risk Factors
  x-api-slug: infermedica
  description: Returns a list of all available risk factors.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//risk_factors
  tags: Healthcare,Risk,Factors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/risk-factors-get-openapi.md
- name: Infermedica Get Risk Factors
  x-api-slug: infermedica
  description: Returns details of a single risk factor specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//risk_factors/{id}
  tags: Healthcare,Risk,Factors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/risk-factorsid-get-openapi.md
- name: Infermedica Get Search
  x-api-slug: infermedica
  description: Returns list of observations matching the given phrase.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//search
  tags: Healthcare,Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/search-get-openapi.md
- name: Infermedica Post Suggest
  x-api-slug: infermedica
  description: Suggests possible symptoms based on provided patient information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//suggest
  tags: Healthcare,Suggest
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/suggest-post-openapi.md
- name: Infermedica Get Symptoms
  x-api-slug: infermedica
  description: Returns a list of all available symptoms.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//symptoms
  tags: Healthcare,Symptoms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/symptoms-get-openapi.md
- name: Infermedica Get Symptoms
  x-api-slug: infermedica
  description: Returns details of a single symptom specified by id parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//symptoms/{id}
  tags: Healthcare,Symptoms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/symptomsid-get-openapi.md
- name: Infermedica Post Triage
  x-api-slug: infermedica
  description: Estimates triage level based on provided patient information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1//triage
  tags: Healthcare,Triage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/triage-post-openapi.md
- name: Infermedica
  x-api-slug: infermedica
  description: At Infermedica we believe in people. Every team member brings unique
    skills, talent and knowledge. Together we solve the most complex healthcare problems.
    Infermedica improves the diagnostic process using the most advanced reasoning
    technology for preliminary medical diagnosis.White-labelled enterprise platform
    (web, mobile, chatbot or voice-enabled applications) for symptom checking, patient
    triage and clinical decision support. Open developer portal that allows to easily
    integrate our diagnostic engine into 3rd party software.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/infermedica-logo.jpeg
  humanURL: http://infermedica.com
  baseURL: https://api.infermedica.com//v1
  tags: Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/health/master/_listings/infermedica/openapi.md
x-common:
- type: x-blog
  url: https://blog.infermedica.com/
- type: x-blog-rss
  url: https://blog.infermedica.com/rss/
- type: x-curated-source
  url: https://developer.infermedica.com/
- type: x-developer
  url: http://developer.infermedica.com
- type: x-github
  url: https://github.com/infermedica
- type: x-status
  url: http://status.infermedica.com/
- type: x-twitter
  url: https://twitter.com/infermedica
- type: x-website
  url: http://infermedica.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---