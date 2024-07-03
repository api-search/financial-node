---
name: Symphony
description: >-
  Streamline work and automate workflows with bots and apps. Build integrations
  from a simple hello world example to fully fledged financial integrations on
  Symphony.
url: >-
  https://raw.githubusercontent.com/apis-json/artisanal/main/apis/factset/apis.yml
created: 2024/04/14
modified: '2024-07-03'
specificationVersion: '0.18'
tags: []
apis:
  - name: Symphony Pod API
    description: >-
      The Symphony Pod API is used to build tools in order to manage and
      administer Symphony for your organization. 
    tags: []
    aid: symphony:symphony-pod-api
    overlays:
      - type: APIs.io Search
        url: overlays/pod-openapi-search.yml
  - name: Symphony Agent API
    description: >-
      The Symphony Agent is responsible for encryption and decryption of
      messages and content sent to and from a bot.
    tags: []
    aid: symphony:symphony-agent-api
    overlays:
      - type: APIs.io Search
        url: overlays/agent-openapi-search.yml
  - name: Symphony Authenticator API
    description: >-
      Tailor your portfolio exposures and risks using our hedging and
      optimization tools. Dynamically manage objectives and constraints while
      controlling for cost and tradability to meet your investment goals.
    tags: []
    aid: symphony:symphony-authenticator-api
    overlays:
      - type: APIs.io Search
        url: overlays/authenticator-openapi-search.yml
  - name: Symphony Community Connect API
    description: >-
      Access the full range of Goldman Sachs indices and basket products, or
      create bespoke solutions to tailor your own investment strategies. Design,
      create, and rebalance fully-customized, ready-to-trade basket solutions to
      express thematic and risk views.
    tags: []
    aid: symphony:symphony-community-connect-api
    overlays:
      - type: APIs.io Search
        url: overlays/community-connect-openapi-search.yml
  - name: Symphony Login API
    description: >-
      Programmatically manage your portfolio lifecycle from creation and update
      to scheduling reports with full control over visibility and sharing.
      Automate your portfolio workflow using our APIs — leaving you to focus on
      the alpha driving decisions.
    tags: []
    aid: symphony:symphony-login-api
    overlays:
      - type: APIs.io Search
        url: overlays/login-openapi-search.yml
  - name: Symphony Profile Manager API
    description: Profile Manager is a microservice to manage users profile and groups.
    tags: []
    aid: symphony:symphony-profile-manager-api
    overlays:
      - type: APIs.io Search
        url: overlays/profile-manager-openapi-search.yml
maintainers:
  - FN: API Evangelist
    email: info@apievangelist.com
aid: symphony

---