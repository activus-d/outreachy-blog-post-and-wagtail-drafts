---
title: Wagtail
repo: wagtail/wagtail
homepage: https://wagtail.org/
twitter: WagtailCMS
opensource: "Yes"
typeofcms: "API Driven"
supportedgenerators:
  -  All
description: Wagtail CMS supports headless development through a built-in REST API. Wagtail CMS also supports a GraphQL API via a plugin.
---

## All about Headless Wagtail
Wagtail is an open-source and API-driven CMS built on the Django web framework.

Wagtail provides headless architecture support through a number of built-in and add-on capabilities. By using Wagtail, you can use your favorite front-end framework instead of the traditional Django templates. In addition, you can manage all your content from one location, thanks to the powerful Wagtail admin interface.

Wagtail is flexible and highly customizable. Since it's built on the Django framework, you can integrate all Django features and third-party plugins. For example, if you don't want to use Wagtail's built-in REST API, you can build your own using the [Django REST framework](https://www.django-rest-framework.org).

With Wagtail, you also get a [built-in page preview and image optimization.](https://areweheadlessyet.wagtail.org/)

## REST API
REST APIs are [native features of Wagtail](https://docs.wagtail.org/en/stable/advanced_topics/api/index.html) with some built-in functionality. You can use Wagtail's REST API to retrieve any page, image, document, or other data as a JSON response that your website can consume via the HTTP protocol. However, if you don't want to use Wagtail's built-in REST API, you can build your own using the [Django REST framework](https://www.django-rest-framework.org).

## GraphQL
You can use GraphQL to interact with your website's content using the [wagtail-grapple](https://github.com/torchbox/wagtail-grapple) library. By using wagtail-grapple, you can build GraphQL endpoints on a model-by-model basis as quickly as possible with a simple configuration. The wagtail-grapple library provides support for the following:
-   Easily create GraphQL types by adding a small annotation in your models.
-   Traditional Wagtail models:
    -   Pages (including Streamfield & Orderables)
    -   Snippets
    -   Images
    -   Documents
    -   Media
    -   Settings
    -   Redirects
    -   Search (on all models)
-   Custom Image & Document model
-   Pagination
-   Middleware
-   Advanced headless preview functionality built with GraphQL subscriptions to allow for page previews on any device.
