---
name: Zoom
description: >-
  This is a starter APIs.json that you can use to learn the specification and
  make your own.
url: https://raw.githubusercontent.com/api-search/videos/main/_apis/zoom/apis.md
created: 2024/04/14
modified: '2024-07-03'
specificationVersion: '0.18'
tags: []
apis:
  - name: Zoom Rest API
    description: >-
      Our REST APIs are organized based on Zoom product, but the base URL for
      all Zoom REST API requests is https://api.zoom.us/v2/ across products.
    tags: []
    properties:
      - type: Documentation
        url: https://developers.zoom.us/docs/api/#rest-apis
      - type: OpenAPI
        url: properties/zoom-openapi-original.yml
    aid: zoom:zoom-rest-api
  - name: Zoom GraphQL API
    description: >-
      Zoom GraphQL is in a public beta. See the GraphQL beta FAQ for details.
      GraphQL is a query language for APIs as well as a runtime environment for
      filling those queries with data.
    tags: []
    overlays: []
    aid: zoom:zoom-graphql-api
  - name: Zoom Chat API
    description: >-
      Developers can use the Zoom Chat API to access chat and chat channel data
      to build private services or public applications on the Zoom App
      Marketplace.
    tags:
      - Chat
    properties:
      - type: OpenAPI
        url: properties/zoom-chat--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/api/rest/chat-api/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-chat--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/api/rest/chat-api/
    aid: zoom:zoom-chat-api
  - name: Zoom Group API
    description: For managing Zoom groups.
    tags:
      - Groups
      - Edit
      - Members
    properties:
      - type: OpenAPI
        url: properties/zoom-group--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/zoom-group--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/api/
    aid: zoom:zoom-group-api
  - name: Zoom Device API
    description: >-
      You can access information from Zoom with Zoom Phone APIs to build private
      services or public applications on the Zoom App Marketplace.
    tags:
      - Device
      - H323
    properties:
      - type: OpenAPI
        url: properties/zoom-device--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/api/rest/zoom-phone-api/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-device--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/api/rest/zoom-phone-api/
    aid: zoom:zoom-device-api
  - name: Zoom Instant Message API
    description: Provides the ability to instant message.
    tags:
      - Groups
      - Edit
      - Members
    properties:
      - type: OpenAPI
        url: properties/zoom-im--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/api/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-im--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/api/
    aid: zoom:zoom-instant-message-api
  - name: Zoom Account API
    description: >-
      The Zoom Account API lets developers access data related to Accounts,
      Dashboards, Information Barriers, and Roles. Use this API to build private
      services or public applications on the Zoom App Marketplace. Learn how to
      get your credentials and create private/public applications in our
      Authorization Guide.
    tags:
      - Accounts
      - Billing
      - Plan
      - Subscribe
    properties:
      - type: OpenAPI
        url: properties/zoom-account--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/api/rest/account/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-account--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/api/rest/account/
    aid: zoom:zoom-account-api
  - name: Zoom Recording API
    description: Manage the recordings made of Zoom calls.
    tags:
      - Mc
      - Recording
    properties:
      - type: OpenAPI
        url: properties/zoom-recording--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/video-sdk/web/recording/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-recording--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/video-sdk/web/recording/
    aid: zoom:zoom-recording-api
  - name: Zoom Meeting API
    description: >-
      The Zoom Meeting API lets developers access meeting and webinar data from
      Zoom Meeting. Use this API to build private services or public
      applications on the Zoom App Marketplace.
    tags:
      - Meetings
      - Live
      - Register
    properties:
      - type: OpenAPI
        url: properties/zoom-meeting--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/api/rest/meeting/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-meeting--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/api/rest/meeting/
    aid: zoom:zoom-meeting-api
  - name: Zoom Metrics API
    description: Access and manage all of the metrics associate with operating on Zoom.
    tags:
      - Crc
      - Metrics
      - Meetingdetail
      - Meetings
      - Qos
      - Webinardetail
      - Webinars
      - Zoomroomdetail
      - Zoomrooms
    properties:
      - type: OpenAPI
        url: properties/zoom-metrics--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/zoom-metrics--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/api/
    aid: zoom:zoom-metrics-api
  - name: Zoom Recording API
    description: DELETE
    tags: []
    properties:
      - type: OpenAPI
        url: properties/zoom-recording--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/zoom-recording--openapi-search.yml
    aid: zoom:zoom-recording-api
  - name: Zoom Report API
    description: Access and manage reports associated with using Zoom.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/zoom-report--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/api/rest/reference/zoom-api/methods/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-report--openapi-search.yml
    humanURL: >-
      https://developers.zoom.us/docs/api/rest/reference/zoom-api/methods/#tag/Reports
    aid: zoom:zoom-report-api
  - name: Zoom User API
    description: >-
      The Zoom User API lets developers access data related to Contact Groups,
      Groups, and Users. Use this API to build private services or public
      applications on the Zoom App Marketplace. Learn how to get your
      credentials and create private/public applications in our Authorization
      Guide.
    tags:
      - Assistants
      - Users
      - Sets
      - Autocreate
      - Checkemail
      - Checkzpk
      - Custcreate
      - Activate
      - Deactivate
      - Getbyemail
      - Pending
      - Permanentdelete
      - Revoketoken
      - Scheduleforhost
      - Ssocreate
      - Updatepassword
    properties:
      - type: OpenAPI
        url: properties/zoom-user--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/api/rest/user/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-user--openapi-search.yml
    humanURL: https://developers.zoom.us/docs/api/rest/user/
    aid: zoom:zoom-user-api
  - name: Zoom Webinar API
    description: Provides the ability to manage details of webinars operated via Zoom.
    tags:
      - Attendees
      - Webinar
      - Registrations
      - Panelists
      - Polls
      - Questions
      - Register
      - Approve
      - Registrants
      - Cancel
      - Uu
    properties:
      - type: OpenAPI
        url: properties/zoom-webinar--openapi-original.yml
      - type: Documentation
        url: https://developers.zoom.us/docs/api/rest/reference/zoom-api/methods/
    overlays:
      - type: OpenAPI
        url: overlays/zoom-webinar--openapi-search.yml
    humanURL: >-
      https://developers.zoom.us/docs/api/rest/reference/zoom-api/methods/#tag/Webinars
    aid: zoom:zoom-webinar-api
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
aid: zoom
---