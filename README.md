# Awesome Starlette

> A curated list of awesome extensions and resources for the Starlette Python Web Framework.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Slarlette: [Docs](https://www.starlette.io/) | [Source](https://github.com/encode/starlette)


## Contents
- [Extensions](#extensions)
    - [Base](#base)
    - [Auth](#auth)
    - [Admin](#admin)
    - [WebSocket](#websocket)
    - [API](#api)
    - [APM](#apm)
    - [Other](#other)


## Extensions

### Base

- [Starsessions](https://github.com/alex-oleshkevich/starsessions) ★103 - An alternate session support implementation with customizable storage backends.
- [webargs-starlette](https://github.com/sloria/webargs-starlette) ★39 - Declarative request parsing and validation for Starlette, built on top of webargs.Allows you to parse querystring, JSON, form, headers, and cookies using type annotations.
- [starlette-core](https://github.com/accent-starlette/starlette-core) ★12 - Basic functionality for every site. Includes database, flash messages, email, pagenation. (Dead project).

### Auth

- [Authlib](https://github.com/lepture/Authlib) ★4754 - The ultimate Python library in building
OAuth and OpenID Connect clients and servers. Check out how to integrate with Starlette.
- [Imia](https://github.com/alex-oleshkevich/imia) ★98 - An authentication framework for Starlette with pluggable authenticators and login/logout flow.
- [Starlette-Login](https://github.com/jockerz/Starlette-Login) ★13 - User session management for Starlette. Very much inspired by [Flask-Login](https://github.com/maxcountryman/flask-login)
- [starlette-auth](https://github.com/accent-starlette/starlette-auth) ★11 - provides a SQLAlchemy backend for user authentication within starlette. (Dead project).
- [Starlette OAuth2 API](https://gitlab.com/jorgecarleitao/starlette-oauth2-api) - A starlette middleware to add authentication and authorization through JWTs. It relies solely on an auth provider to issue access and/or id tokens to clients.

### Admin

- [starlette-admin](https://github.com/accent-starlette/starlette-admin) ★40 - Simple, easy to manage admin site for crud operations. Includes all templates required for starlette-auth styled in this theme. (Dead project).

### WebSocket

- [Nejma](https://github.com/taoufik07/nejma) ★47 - Manage and send messages to groups of channels using websockets. Checkout nejma-chat, a simple chat application built using nejma and starlette.
- [ChannelBox](https://github.com/Sobolev5/channel-box) ★16 - Another solution for websocket broadcast. Send messages to channel groups from any part of your code. Checkout MySimpleChat, a simple chat application built using channel-box and starlette.

### API

- [Strawberry GraphQL](https://github.com/strawberry-graphql/strawberry) ★4218 - Python GraphQL library based on dataclasses.
- [SpecTree](https://github.com/0b01001001/spectree) ★332 - Generate OpenAPI spec document and validate request & response with Python annotations. Less boilerplate code(no need for YAML).
- [Starlette APISpec](https://github.com/Woile/starlette-apispec) ★53 - Simple APISpec integration for Starlette. Document your REST API built with Starlette by declaring OpenAPI (Swagger) schemas in YAML format in your endpoint's docstrings.
- [uapi](https://github.com/Tinche/uapi) ★92 - An elegant, high-level, extremely low-overhead Python microframework for writing HTTP APIs, either synchronously or asynchronously.

### APM

- [Starlette Exporter](https://github.com/stephenhillier/starlette_exporter) ★317 - One more prometheus integration for FastAPI and Starlette.
- [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) ★289 - A plugin for providing an endpoint that exposes Prometheus metrics based on its official python client.
- [Scout APM](https://github.com/scoutapp/scout_apm_python) ★68 - An APM (Application Performance Monitoring) solution that can instrument your application to find performance bottlenecks.
- [Starlette OpenTracing](https://github.com/acidjunk/starlette-opentracing) ★65 - Opentracing support for Starlette and FastAPI.

### Other

- [starlette-docker](https://github.com/accent-starlette/starlette-docker) ★3 - Base images for starlette.Base images for starlette.
- [starlette-files](https://github.com/accent-starlette/starlette-files) ★11 - Save files using s3 or fs, includes ability to crop, resize, reformat images etc. (Dead project).
- [Mangum](https://github.com/erm/mangum) ★1851 - Serverless ASGI adapter for AWS Lambda & API Gateway.
- [Starlette Context](https://github.com/tomwojcik/starlette-context) ★478 - Middleware for Starlette that allows you to store and access the context data of a request. Can be used with logging so logs automatically use request headers such as x-request-id or x-correlation-id.
- [Starlette Cramjam](https://github.com/developmentseed/starlette-cramjam) ★12 - A Starlette middleware that allows brotli, gzip and deflate compression algorithm with a minimal requirements.
- [Starlette WTF](https://github.com/muicss/starlette-wtf) ★89 - A simple tool for integrating Starlette and WTForms. It is modeled on the excellent Flask-WTF library.

## About

Forked from the unmaintained <https://github.com/shitianfang/awesome-starlette>.
