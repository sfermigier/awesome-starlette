# Awesome Starlette

> A curated list of awesome projects, extensions, and resources for the Starlette ASGI framework/toolkit.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Starlette is a lightweight [ASGI](https://asgi.readthedocs.io/) framework/toolkit for Python, which is ideal for building high-performance asyncio services. It is production-ready and gives you tools for building APIs, WebSockets, GraphQL endpoints, and more. Many high-level frameworks (like FastAPI) are built on top of Starlette.

**Starlette:** [Docs](https://www.starlette.io/) | [Source](https://github.com/encode/starlette)

**Legend:** ⚠️ = Unmaintained or Archived

## Contents

- [Extensions](#extensions)
  - [Admin](#admin)
  - [API](#api)
  - [APM & Monitoring](#apm--monitoring)
  - [Authentication & Authorization](#authentication--authorization)
  - [Compression](#compression)
  - [Core Utilities](#core-utilities)
  - [Debugging](#debugging)
  - [Deployment / Serverless](#deployment--serverless)
  - [Forms](#forms)
  - [Internationalization (i18n)](#internationalization-i18n)
  - [Routing](#routing)
  - [Static Files](#static-files)
  - [WebSockets](#websockets)
- [Frameworks](#frameworks)
- [Contributing](#contributing)
- [About](#about)

## Extensions

### Admin

- [Starlette-Admin](https://github.com/jowilf/starlette-admin) ★736 - Simple and extensible admin interface framework built with Tabler and Datatables. Supports complex filtering, exports, file uploads. [Docs](https://jowilf.github.io/starlette-admin)
- ⚠️ [starlette-admin](https://github.com/accent-starlette/starlette-admin) ★40 - (Archived) Simple admin site for CRUD operations from the `accent-starlette` project group.

### API (REST, GraphQL...)

- [Apiman](https://github.com/strongbugman/apiman) ★111 - Integrate Swagger/OpenAPI documentation easily, providing SwaggerUI and RedocUI.
- [SpecTree](https://github.com/0b01001001/spectree) ★332 - Generate OpenAPI documentation and validate requests & responses using Python annotations. [Docs](https://spectree.readthedocs.io/)
- [Starlette APISpec](https://github.com/Woile/starlette-apispec) ★53 - Simple APISpec integration. Document your REST API by declaring OpenAPI schemas in YAML format in endpoint docstrings.
- [Strawberry GraphQL](https://github.com/strawberry-graphql/strawberry) ★4218 - Python GraphQL library based on dataclasses, works well with Starlette/FastAPI. [Docs](https://strawberry.rocks/)
- [uapi](https://github.com/Tinche/uapi) ★92 - An elegant, high-level, extremely low-overhead microframework for writing HTTP APIs, either synchronously or asynchronously.

### APM & Monitoring

- [Apitally](https://github.com/apitally/apitally-py) ★71 - Analytics, request logging and monitoring for REST APIs. [Docs](https://docs.apitally.io/frameworks/starlette)
- [Scout APM](https://github.com/scoutapp/scout_apm_python) ★68 - Application Performance Monitoring (APM) solution to find performance bottlenecks. [Docs](https://docs.scoutapm.com/#python-agent)
- [Sentry](https://github.com/getsentry/sentry-python) ★1975 - Error tracking and performance monitoring platform. [Docs](https://docs.sentry.io/platforms/python/guides/starlette/)
- [Starlette Exporter](https://github.com/stephenhillier/starlette_exporter) ★317 - Prometheus integration for FastAPI and Starlette.
- [Starlette OpenTracing](https://github.com/acidjunk/starlette-opentracing) ★65 - Opentracing support for Starlette and FastAPI.
- [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) ★289 - Plugin providing an endpoint that exposes Prometheus metrics.

### Authentication & Authorization

- [Authlib](https://github.com/lepture/Authlib) ★4757 - The ultimate Python library for building OAuth and OpenID Connect clients and servers. [Starlette Integration Docs](https://docs.authlib.org/en/latest/client/starlette.html).
- [Imia](https://github.com/alex-oleshkevich/imia) ★98 - Authentication framework with pluggable authenticators and login/logout flow.
- [Starlette OAuth2 API](https://gitlab.com/jorgecarleitao/starlette-oauth2-api) - Middleware to add authentication and authorization through JWTs, relying on an external auth provider.
- [Starlette-Login](https://github.com/jockerz/Starlette-Login) ★13 - User session management, inspired by Flask-Login. [Docs](https://starlette-login.readthedocs.io/en/stable/)
- ⚠️ [starlette-auth](https://github.com/accent-starlette/starlette-auth) ★11 - (Archived) Provides a SQLAlchemy backend for user authentication from the `accent-starlette` project group.

### Compression

- [Starlette Compress](https://github.com/Zaczero/starlette-compress) ★16 - Fast middleware for compressing responses with Zstd, Brotli, and GZip.
- [Starlette Cramjam](https://github.com/developmentseed/starlette-cramjam) ★12 - Middleware adding Brotli, Gzip, and Deflate compression with minimal requirements via the `cramjam` library.

### Core Utilities

- [Starlette Bridge](https://github.com/tarsil/starlette-bridge) ★4 - Backwards compatibility shim for `on_startup` / `on_shutdown` event handlers using the newer `lifespan` context manager internally. [Docs](https://starlette-bridge.tarsild.io/)
- [Starlette Context](https://github.com/tomwojcik/starlette-context) ★478 - Middleware to store and access request context data easily, useful for logging request IDs.
- [Starsessions](https://github.com/alex-oleshkevich/starsessions) ★103 - Alternate session implementation with customizable storage backends.
- [webargs-starlette](https://github.com/sloria/webargs-starlette) ★39 - Declarative request parsing and validation (query, JSON, form, headers, cookies) using type annotations, built on webargs.
- ⚠️ [starlette-core](https://github.com/accent-starlette/starlette-core) ★12 - (Archived) Basic functionality (database, flash messages, email, pagination) from the `accent-starlette` project group.

### Debugging

- [Starception](https://github.com/alex-oleshkevich/starception) ★96 - Beautiful interactive exception page for Starlette/FastAPI applications.

### Deployment / Serverless

- [Mangum](https://github.com/erm/mangum) ★1852 - Serverless ASGI adapter for AWS Lambda & API Gateway. [Docs](https://mangum.io/)
- [Vellox](https://github.com/junah201/vellox) ★16 - Serverless ASGI adapter for Google Cloud Functions.
- ⚠️ [starlette-docker](https://github.com/accent-starlette/starlette-docker) ★3 - (Archived) Base Docker images from the `accent-starlette` project group.

### Forms

- [Starlette WTF](https://github.com/muicss/starlette-wtf) ★89 - Simple integration of Starlette and WTForms, modeled on Flask-WTF.

### Internationalization (i18n)

- [Starlette-Babel](https://github.com/alex-oleshkevich/starlette_babel) ★19 - Provides translations, localization, and timezone support via Babel integration.

### Routing

- [DecoRouter](https://github.com/MrPigss/DecoRouter) ★23 - FastAPI-style routing for Starlette using decorators.

### Static Files

- [Starlette-StaticResources](https://github.com/DavidVentura/starlette-static-resources) ★0 - Allows mounting package resources for static data, similar to `StaticFiles`.
- ⚠️ [starlette-files](https://github.com/accent-starlette/starlette-files) ★11 - (Archived) Save files using S3 or local FS, with image manipulation options, from the `accent-starlette` project group.

### WebSockets

- [ChannelBox](https://github.com/Sobolev5/channel-box) ★16 - Solution for WebSocket broadcast; send messages to channel groups from anywhere in your code. [Demo Chat](https://channel-box.andrey-sobolev.ru/)
- [Nejma](https://github.com/taoufik07/nejma) ★47 - Manage and send messages to groups of WebSocket channels. [Demo Chat](https://github.com/taoufik07/nejma-chat)

## Frameworks

*Frameworks built using Starlette as a core component.*

- [FastAPI](https://github.com/tiangolo/fastapi) ★82747 - A modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints. [Docs](https://fastapi.tiangolo.com/)
- [Dark Star](https://github.com/lllama/dark-star) ★19 - Changes your file paths into Starlette routes and puts your view code right next to your template. Includes support for htmx. [Docs](https://lllama.github.io/dark-star)
- [Ellar](https://github.com/eadwinCode/ellar) ★55 - ASGI web framework for building fast, efficient and scalable REST APIs and server-side applications, inspired by NestJS. Built on Starlette, Pydantic, and Injector. [Docs](https://eadwincode.github.io/ellar/)
- [Flama](https://github.com/vortico/flama) ★274 - Data-science oriented framework to rapidly build modern and robust machine learning APIs with automatic deployment. [Docs](https://flama.dev/)
- [Greppo](https://github.com/greppo-io/greppo) ★399 - Python framework for building geospatial dashboards and web-applications with data mutation hooks. [Docs](https://docs.greppo.io/)
- [Shiny](https://github.com/posit-dev/py-shiny) ★1431 - Effortless Python web applications using reactive programming, built by Posit (formerly RStudio). [Docs](https://shiny.posit.co/py/)
- [Starlette-apps](https://github.com/yourlabs/starlette-apps) ★3 - Roll your own framework with a simple app system, like Django-GDAPS or CakePHP.
- [Xpresso](https://github.com/adriangb/xpresso) ★180 - Flexible and extendable web framework built on top of Starlette, Pydantic and `di`. [Docs](https://xpresso-api.dev/)
- ⚠️ [Responder](https://github.com/taoufik07/responder) ★3604 - (Archived) A familiar HTTP Service Framework for Python, built on Starlette anduvloop. [Docs](https://python-responder.org/en/latest/)


## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) (if one exists in the repository, otherwise encourage PRs/Issues) before submitting your suggestions. Ensure your pull request follows the general structure of this list.

## About

This list aims to be a comprehensive collection of useful packages and resources for Starlette developers. It was originally forked from the unmaintained <https://github.com/shitianfang/awesome-starlette> and has been significantly updated and expanded.
