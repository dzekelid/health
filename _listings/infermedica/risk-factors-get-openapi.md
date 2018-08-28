---
swagger: "2.0"
x-collection-name: Infermedica
x-complete: 0
info:
  title: Infermedica Get Risk Factors
  description: Returns a list of all available risk factors.
  version: v2
host: api.infermedica.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /conditions:
    get:
      summary: Get Conditions
      description: Returns a list of all available conditions.
      operationId: getConditions
      x-api-path-slug: conditions-get
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Conditions
  /conditions/{id}:
    get:
      summary: Get Conditions
      description: Returns details of a single condition specified by id parameter.
      operationId: getConditions
      x-api-path-slug: conditionsid-get
      parameters:
      - in: path
        name: id
        description: condition id
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Conditions
      - Id
  /diagnosis:
    post:
      summary: Post Diagnosis
      description: Suggests possible diagnoses and relevant observations based on
        provided patient information.
      operationId: postDiagnosis
      x-api-path-slug: diagnosis-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Diagnosis
  /explain:
    post:
      summary: Post Explain
      description: Explains which evidence impact probability of selected condition.
      operationId: postExplain
      x-api-path-slug: explain-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Explain
  /info:
    get:
      summary: Get Info
      description: Returns information about data used by diagnostic engine.
      operationId: getInfo
      x-api-path-slug: info-get
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Info
  /lab_tests:
    get:
      summary: Get Lab Tests
      description: Returns a list of all available lab tests.
      operationId: getLabTests
      x-api-path-slug: lab-tests-get
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Lab
      - Tests
  /lab_tests/{id}:
    get:
      summary: Get Lab Tests
      description: Returns details of a single lab test specified by id parameter.
      operationId: getLabTests
      x-api-path-slug: lab-testsid-get
      parameters:
      - in: path
        name: id
        description: lab test id
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Lab
      - Tests
  /lookup:
    get:
      summary: Get Lookup
      description: Returns a single observation matching given phrase.
      operationId: getLookup
      x-api-path-slug: lookup-get
      parameters:
      - in: query
        name: phrase
        description: phrase to match
      - in: query
        name: sex
        description: sex filter
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Lookup
  /parse:
    post:
      summary: Post Parse
      description: Returns list of mentions of observation found in given text.
      operationId: postParse
      x-api-path-slug: parse-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Parse
  /risk_factors:
    get:
      summary: Get Risk Factors
      description: Returns a list of all available risk factors.
      operationId: getRiskFactors
      x-api-path-slug: risk-factors-get
      responses:
        200:
          description: OK
      tags:
      - Healthcare
      - Risk
      - Factors
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---