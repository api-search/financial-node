---
name: Ion Group
description: >-
  We’re visionary innovators who are delivering mission-critical trading and
  workflow automation software to financial institutions, corporations, central
  banks, and governments. By combining our passion for automation with a
  strategic view on the industries we serve, we design solutions that improve
  decision-making, simplify complex processes, and empower people. Simply put,
  we help our customers do more, faster and better than before. We believe our
  investments in research and development are shaping the future of automation
  and enabling our customers to transform their business. And we embrace the
  power of community, working with each other and with our customers to succeed
  through a positive culture of continuous improvement.
url: >-
  https://raw.githubusercontent.com/apis-json/artisanal/main/apis/ion-group/apis.yml
created: 2024/04/14
modified: '2024-07-03'
specificationVersion: '0.18'
tags: []
apis:
  - name: Acuris Entities API
    description: >-
      The Acuris Entities API allows you to search over 1M records of private
      and public companies, firms, assets, and private investors.
    tags: []
    overlays:
      - type: APIs.io Search
        url: overlays/entities-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/entities-openapi-api-evangelist-ratings.yml
    aid: ion-group:acuris-entities-api
  - name: Dealogic Analytics Spac API
    description: >-
      Detailed profiling of Special Purpose Acquisition Companies (SPACs). Gain
      access to real-time content and analytics covering the full spectrum of
      the SPAC market, from IPO Filing/Pricing, additional fundraising via
      PIPEs, through to the M&A de-SPAC.
    tags: []
    overlays:
      - type: APIs.io Search
        url: overlays/dealogic-analytics-spac-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/dealogic-analytics-spac-openapi-api-evangelist-ratings.yml
    aid: ion-group:dealogic-analytics-spac-api
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
aid: ion-group

---