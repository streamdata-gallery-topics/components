---
name: New Relic
x-slug: new-relic
description: New Relic???s digital intelligence platform lets developers, ops, and
  tech teams measure and monitor the performance of their applications and infrastructure.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
x-kinRank: "8"
x-alexaRank: "10322"
tags: Components
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/apis.md
specificationVersion: "0.14"
apis:
- name: New Relic - Get Components  . Format
  x-api-slug: componentsid-format-get
  description: |-
    This API endpoint returns a single component, identified by its ID.

    See our documentation for a discussion on listing components by ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentsid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentsid-format-get-openapi.md
- name: New Relic - Get Components Component  Metrics. Format
  x-api-slug: componentscomponent-idmetrics-format-get
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetrics-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetrics-format-get-openapi.md
- name: New Relic - Get Components Component  Metrics Data. Format
  x-api-slug: componentscomponent-idmetricsdata-format-get
  description: "This API endpoint returns a list of values for each of the requested
    metrics. The list of available metrics\ncan be returned using the Metric Name
    API endpoint.\n\nMetric data can be filtered by a number of parameters, including
    multiple names and values, and by time range.\nMetric names and values will be
    matched intelligently in the background.\n\nYou can also retrieve a summarized
    data point across the entire time range selected by using the summarize\nparameter.\n\nSee
    our documentation for a discussion on \noutput pagination,  time range \nrelated
    considerations, and for examples of requesting and using metric values."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetricsdata-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetricsdata-format-get-openapi.md
- name: New Relic - Get Components Component  Metrics. Format
  x-api-slug: componentscomponent-idmetrics-format-get
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetrics-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetrics-format-get-openapi.md
- name: New Relic - Get Components Component  Metrics Data. Format
  x-api-slug: componentscomponent-idmetricsdata-format-get
  description: "This API endpoint returns a list of values for each of the requested
    metrics. The list of available metrics\ncan be returned using the Metric Name
    API endpoint.\n\nMetric data can be filtered by a number of parameters, including
    multiple names and values, and by time range.\nMetric names and values will be
    matched intelligently in the background.\n\nYou can also retrieve a summarized
    data point across the entire time range selected by using the summarize\nparameter.\n\nSee
    our documentation for a discussion on \noutput pagination,  time range \nrelated
    considerations, and for examples of requesting and using metric values."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetricsdata-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetricsdata-format-get-openapi.md
- name: New Relic - Get Components. Format
  x-api-slug: components-format-get
  description: |-
    This API endpoint returns a list of the plugin components associated with your New Relic account.

    Plugins can be filtered by their name, the list of component IDs or a plugin ID.

    See our documentation for a discussion on  listing components
    and  output pagination.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/components-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/components-format-get-openapi.md
- name: New Relic - Get Components Component  Metrics. Format
  x-api-slug: componentscomponent-idmetrics-format-get
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetrics-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetrics-format-get-openapi.md
- name: New Relic - Get Components Component  Metrics Data. Format
  x-api-slug: componentscomponent-idmetricsdata-format-get
  description: "This API endpoint returns a list of values for each of the requested
    metrics. The list of available metrics\ncan be returned using the Metric Name
    API endpoint.\n\nMetric data can be filtered by a number of parameters, including
    multiple names and values, and by time range.\nMetric names and values will be
    matched intelligently in the background.\n\nYou can also retrieve a summarized
    data point across the entire time range selected by using the summarize\nparameter.\n\nSee
    our documentation for a discussion on \noutput pagination,  time range \nrelated
    considerations, and for examples of requesting and using metric values."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetricsdata-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetricsdata-format-get-openapi.md
- name: New Relic - Get Components. Format
  x-api-slug: components-format-get
  description: |-
    This API endpoint returns a list of the plugin components associated with your New Relic account.

    Plugins can be filtered by their name, the list of component IDs or a plugin ID.

    See our documentation for a discussion on  listing components
    and  output pagination.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/components-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/components-format-get-openapi.md
- name: New Relic - Get Components Component  Metrics. Format
  x-api-slug: componentscomponent-idmetrics-format-get
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetrics-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetrics-format-get-openapi.md
- name: New Relic - Get Components Component  Metrics Data. Format
  x-api-slug: componentscomponent-idmetricsdata-format-get
  description: "This API endpoint returns a list of values for each of the requested
    metrics. The list of available metrics\ncan be returned using the Metric Name
    API endpoint.\n\nMetric data can be filtered by a number of parameters, including
    multiple names and values, and by time range.\nMetric names and values will be
    matched intelligently in the background.\n\nYou can also retrieve a summarized
    data point across the entire time range selected by using the summarize\nparameter.\n\nSee
    our documentation for a discussion on \noutput pagination,  time range \nrelated
    considerations, and for examples of requesting and using metric values."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetricsdata-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/componentscomponent-idmetricsdata-format-get-openapi.md
- name: New Relic - Get Components. Format
  x-api-slug: components-format-get
  description: |-
    This API endpoint returns a list of the plugin components associated with your New Relic account.

    Plugins can be filtered by their name, the list of component IDs or a plugin ID.

    See our documentation for a discussion on  listing components
    and  output pagination.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Monitoring, Performance, Stack Network, Technology, SaaS, API Service Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/components-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/components/master/_listings/new-relic/components-format-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://netlicensing.api.gallery.streamdata.io
- type: x-api-stack
  url: http://new.relic.stack.network
- type: x-blog
  url: https://blog.newrelic.com/
- type: x-blog-rss
  url: https://blog.newrelic.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/new-relic
- type: x-developer
  url: https://rpm.newrelic.com/api/explore/
- type: x-email
  url: billing@newrelic.com
- type: x-email
  url: resume@newrelic.com
- type: x-email
  url: PR@newrelic.com
- type: x-email
  url: copyright@newrelic.com
- type: x-email
  url: dataprivacy@newrelic.com
- type: x-email
  url: PersonalDataRequest@newrelic.com
- type: x-email
  url: support@newrelic.com
- type: x-email
  url: compliance@newrelic.com
- type: x-github
  url: https://github.com/newrelic
- type: x-twitter
  url: https://twitter.com/NewRelic
- type: x-website
  url: https://newrelic.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---