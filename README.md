# Awesome Authentication & Authorization & SSO & IAM with stars

> Quality Authentication & Authorization & SSO & IAM software and libraries.

[Authentication (aka AuthN)](https://en.wikipedia.org/wiki/Authentication) and [authorization (aka AuthZ)](https://en.wikipedia.org/wiki/Authorization) are both security measures. Authentication is the process of verifying who you are. Authorization is the process of verifying that you have access to something. Authorization occurs after successful authentication.

## Contents

* [Awesome Authentication & Authorization & SSO & IAM ](#awesome-authentication--authorization--sso--iam-)
  * [Contents](#contents)
  * [SSO (Single-Sign-On), IAM (Identity Access Management)](#sso-single-sign-on-iam-identity-access-management)
  * [Authentication](#authentication)
    * [C#](#c)
    * [Golang](#golang)
    * [Java](#java)
    * [Node.js](#nodejs)
    * [Python](#python)
    * [Ruby](#ruby)
    * [Flutter](#flutter)
  * [Authorization](#authorization)
    * [Android](#android)
    * [C#](#c-1)
    * [Golang](#golang-1)
    * [Rust](#rust)
    * [iOS](#ios)
    * [Java](#java-1)
    * [Node.js](#nodejs-1)
    * [PHP](#php)
    * [Python](#python-1)
    * [Ruby](#ruby-1)
  * [AI Agent Auth](#ai-agent-auth)
  * [Articles](#articles)
  * [Contribute](#contribute)
  * [License](#license)

## SSO (Single-Sign-On), IAM (Identity Access Management)

* [Authelia](https://github.com/authelia/authelia) ⭐ 28,549 | 🐛 130 | 🌐 Go | 📅 2026-08-14 - The Single Sign-On Multi-Factor portal for web apps.
* [ZITADEL](https://github.com/caos/zitadel) ⭐ 14,721 | 🐛 1,113 | 🌐 Go | 📅 2026-08-13 - Cloud-native Identity & Access Management platform for secure authentication, authorization and identity management.
* [Logto](https://github.com/logto-io/logto) ⭐ 14,341 | 🐛 182 | 🌐 TypeScript | 📅 2026-08-14 - An IAM infrastructure with AuthN, AuthZ, MFA, SSO, user management, and multi-tenancy features, supporting OAuth 2.0, OIDC, and SAML.
* [Casdoor](https://github.com/casdoor/casdoor) ⭐ 14,185 | 🐛 102 | 🌐 Go | 📅 2026-08-13 - UI-first centralized authentication / Single-Sign-On (SSO) platform supporting OAuth 2.0 / OIDC and SAML.
* [NanoIDP](https://github.com/cdelmonte-zg/nanoidp) ⭐ 20 | 🐛 2 | 🌐 Python | 📅 2026-07-18 - Local development Identity Provider for testing OAuth2, OpenID Connect, and SAML flows without running a full IAM stack.
* [Keycloak](https://www.keycloak.org/) - Open Source Identity and Access Management.
* [Authentik](https://goauthentik.io) - authentik is an open-source Identity Provider that emphasizes flexibility and versatility. It can be seamlessly integrated into existing environments to support new protocols.
* [Stack Auth](https://stack-auth.com) - Open-source, developer-friendly authentication, authorization, and IAM solution.
* [Scalekit](https://scalekit.com) – Add enterprise SSO (SAML, OIDC) and SCIM provisioning on top of existing auth systems alongside additive auth stack for MCP and Agent Auth.
* [Cloud-IAM](https://cloud-iam.com) - Managed Keycloak SaaS platform supporting OpenID Connect, OAuth 2.0 and SAML, with ISO 27001, SOC 2 Type 2, NIS 2, GDPR, HDS and SecNumCloud 3.2 certifications.
* [SSOJet](https://ssojet.com) – Add enterprise SSO (SAML, OIDC) and SCIM user provisioning to your app without changing your existing authentication system.
* [Neon Auth](https://neon.com/docs/neon-auth/overview) - Managed authentication built on Better Auth that syncs users directly into your Neon Postgres database.

## Authentication

### <a name="authN-cSharp"></a>C\#

* [AspNet.Security.OAuth.Providers](https://github.com/aspnet-contrib/AspNet.Security.OAuth.Providers) ⭐ 2,510 | 🐛 18 | 🌐 C# | 📅 2026-08-12 - OAuth2 social authentication providers for ASP.NET Core.
* [Kentor Authentication Services](https://github.com/KentorIT/authservices) ⭐ 1,008 | 🐛 130 | 🌐 C# | 📅 2026-05-21 - Saml2 authentication services for ASP.NET.
* [OwinOAuthProviders](https://github.com/TerribleDev/OwinOAuthProviders) ⭐ 497 | 🐛 187 | 🌐 C# | 📅 2023-04-15 - OAuth providers for Owin.
* [AspNetSaml](https://github.com/jitbit/AspNetSaml) ⭐ 421 | 🐛 7 | 🌐 C# | 📅 2026-07-25 - SAML library for ASP.NET Core
* [SimpleAuthentication](https://github.com/SimpleAuthentication/SimpleAuthentication) ⭐ 287 | 🐛 39 | 🌐 C# | 📅 2024-02-22 - ASP.NET library that makes it really easy and simple for developers to add social authentication to an ASP.NET application.
* [IdentityServer4](https://github.com/IdentityServer/IdentityServer4) ⚠️ Archived - OpenID Connect & OAuth 2.0 framework for ASP.NET Core.
* [Authgear SDK for Xamarin](https://github.com/authgear/authgear-sdk-xamarin) ⭐ 1 | 🐛 11 | 🌐 C# | 📅 2024-11-04 - You can easily integrate authentication features into your Xamarin apps. In most cases, it involves just a few lines of code to enable multiple authentication methods.

### <a name="authN-golang"></a>Golang

* [Ory Hydra](https://github.com/ory/hydra) ⭐ 17,475 | 🐛 93 | 🌐 Go | 📅 2026-07-29 - OpenID Connect certified OAuth2 server.
* [ZITADEL](https://github.com/caos/zitadel) ⭐ 14,721 | 🐛 1,113 | 🌐 Go | 📅 2026-08-13 - Cloud-native Identity & Access Management platform for secure authentication, authorization and identity management.
* [Casdoor](https://github.com/casdoor/casdoor) ⭐ 14,185 | 🐛 102 | 🌐 Go | 📅 2026-08-13 - UI-first centralized authentication / Single-Sign-On (SSO) platform supporting OAuth 2.0 / OIDC and SAML.
* [Ory Kratos](https://github.com/ory/kratos) ⭐ 13,828 | 🐛 223 | 🌐 Go | 📅 2026-07-29 - API-first Identity and User Management system built for cloud applications.
* [Ory Oathkeeper](https://github.com/ory/oathkeeper) ⭐ 3,593 | 🐛 106 | 🌐 Go | 📅 2026-07-27 - Identity/Access proxy inspired by the BeyondCorp/Zero-Trust white paper.
* [Ory Fosite](https://github.com/ory/fosite) ⭐ 2,605 | 🐛 60 | 🌐 Go | 📅 2025-11-20 - Extensible OAuth 2.0 and OpenID Connect SDK for Golang.
* [OIDC](https://github.com/caos/oidc) ⭐ 1,865 | 🐛 38 | 🌐 Go | 📅 2026-08-10 - OpenID Connect Library (client and server) for Go

### <a name="authN-java"></a>Java

* [Spring Security OAuth](https://github.com/spring-projects/spring-security-oauth) ⚠️ Archived - Provides support for using Spring Security with OAuth (1a) and OAuth2.
* [Apache Shiro](https://github.com/apache/shiro) ⭐ 4,452 | 🐛 14 | 🌐 Java | 📅 2026-08-11 - Powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management.
* [pac4j](https://github.com/pac4j/pac4j) ⭐ 2,520 | 🐛 3 | 🌐 Java | 📅 2026-08-11 - Security engine for Java (authentication, authorization, multi frameworks): OAuth, CAS, SAML, OpenID Connect, LDAP, JWT.

### <a name="authN-node"></a>Node.js

* [Passport](https://github.com/jaredhanson/passport) ⭐ 23,531 | 🐛 398 | 🌐 JavaScript | 📅 2024-08-16 - Simple, unobtrusive authentication for Node.js. A comprehensive set of strategies support authentication using a username and password, Facebook, Twitter, and more.
* [bell](https://github.com/hapijs/bell) ⭐ 618 | 🐛 16 | 🌐 JavaScript | 📅 2025-03-12 - Third-party authentication plugin for hapi. Ships with built-in support for various well-known sites and simple configuration object will support other OAuth 1.0a and OAuth 2.0 sites.
* [client-certificate-auth](https://github.com/tgies/client-certificate-auth) ⭐ 80 | 🐛 7 | 🌐 JavaScript | 📅 2026-08-13 - Mutual TLS (mTLS) client certificate authentication middleware for Node.js with reverse proxy support, composable verification callbacks, and X.509 certificate parsing.
* [Stack Auth](https://stack-auth.com) - Open-source authN & authZ for modern web apps, comes with pre-built components for Next.js.

### <a name="authN-python"></a>Python

* [Authomatic](https://github.com/authomatic/authomatic) ⭐ 1,053 | 🐛 64 | 🌐 Python | 📅 2025-12-12 - Simple yet powerful authorization & authentication client library for Python web applications.
* [Python Social Auth](https://github.com/python-social-auth/social-core) ⭐ 918 | 🐛 54 | 🌐 Python | 📅 2026-08-13 - Easy to setup social authentication/registration mechanism with support for several frameworks and auth providers.
* [Keystone](https://github.com/openstack/keystone) ⭐ 716 | 🐛 1 | 🌐 Python | 📅 2026-08-06 - Provides authentication, authorization and service discovery mechanisms via HTTP primarily for use by projects in the OpenStack family.
* [Raider](https://github.com/OWASP/raider) ⭐ 101 | 🐛 54 | 🌐 Python | 📅 2023-07-20 - Web authentication testing framework, which treats the authentication process as finite state machines.

### <a name="authN-ruby"></a>Ruby

* [Authlogic](https://github.com/binarylogic/authlogic) ⭐ 4,346 | 🐛 12 | 🌐 Ruby | 📅 2026-02-08 - Clean, simple, and unobtrusive Ruby authentication solution.

### <a name="authN-flutter"></a>Flutter

* [Authgear SDK for Flutter](https://github.com/authgear/authgear-sdk-flutter) ⭐ 9 | 🐛 11 | 🌐 Dart | 📅 2026-08-04 - With Authgear SDK for Flutter, you can easily integrate authentication features into your Flutter apps. In most cases, it involves just a few lines of code to enable multiple authentication methods.

## Authorization

### <a name="authZ-android"></a>Android

* [AndPermission](https://github.com/yanzhenjie/AndPermission) ⭐ 6,627 | 🐛 176 | 🌐 Java | 📅 2024-01-04 - Android runtime permission, support the right to apply for permission at any place.
* [Authgear SDK for Android](https://github.com/authgear/authgear-sdk-android) ⭐ 3 | 🐛 12 | 🌐 Kotlin | 📅 2026-08-12 - Android SDK to authenticate and authorize users based on the OAuth 2.0 authorization framework.

### <a name="authZ-cSharp"></a>C\#

* [Casbin.NET](https://github.com/casbin/Casbin.NET) ⭐ 1,331 | 🐛 9 | 🌐 C# | 📅 2026-06-16 - Authorization library that supports access control models like ACL, RBAC, ABAC in .NET (C#).

### <a name="authZ-golang"></a>Golang

* [Casbin](https://github.com/casbin/casbin) ⭐ 20,322 | 🐛 42 | 🌐 Go | 📅 2026-08-13 - Authorization library that supports access control models like ACL, RBAC, ABAC in Golang.
* [ZITADEL](https://github.com/zitadel/zitadel) ⭐ 14,721 | 🐛 1,113 | 🌐 Go | 📅 2026-08-13 - Cloud-native Identity & Access Management platform for secure authentication, authorization and identity management.
* [SpiceDB](https://github.com/authzed/spicedb) ⭐ 6,960 | 🐛 148 | 🌐 Go | 📅 2026-08-10 - Open-source implementation of the Zanzibar paper, a performant database for fine-grained permissions.
* [Ory Keto](https://github.com/ory/keto) ⭐ 5,387 | 🐛 69 | 🌐 Go | 📅 2026-08-03 - Access control server capable of solving complex use cases (multi-tenant, attribute-based access control, etc.) with access control policies.
* [Oso](https://github.com/osohq/oso) ⭐ 3,492 | 🐛 119 | 🌐 Rust | 📅 2025-02-26 - Batteries-included framework for building authorization in your Go application.
* [Ladon](https://github.com/ory/ladon) ⭐ 2,459 | 🐛 2 | 🌐 Go | 📅 2025-10-22 - SDK for access control policies: authorization for the microservice and IoT age.
* [OIDC](https://github.com/zitadel/oidc) ⭐ 1,865 | 🐛 38 | 🌐 Go | 📅 2026-08-10 - OpenID Connect Library (client and server) for Go
* [goRBAC](https://github.com/mikespook/gorbac) ⭐ 1,673 | 🐛 4 | 🌐 Go | 📅 2026-07-21 - Lightweight role-based access control implementation in Go.
* [Topaz](https://www.topaz.sh) - Fine-grained authorization for cloud-native applications. Combining the best of OPA and Zanzibar

### <a name="authZ-rust"></a>Rust

* [Oso](https://github.com/osohq/oso) ⭐ 3,492 | 🐛 119 | 🌐 Rust | 📅 2025-02-26 - Batteries-included framework for building authorization in your Rust application.
* [Casbin-Rs](https://github.com/casbin/casbin-rs) ⭐ 1,130 | 🐛 2 | 🌐 Rust | 📅 2026-08-13 - Authorization library that supports access control models like ACL, RBAC, ABAC in Rust.

### <a name="authZ-ios"></a>iOS

* [Permission](https://github.com/delba/Permission) ⭐ 2,892 | 🐛 19 | 🌐 Swift | 📅 2022-07-11 - Unified API to ask for permissions on iOS.
* [Authgear SDK for iOS](https://github.com/authgear/authgear-sdk-ios) ⭐ 3 | 🐛 8 | 🌐 Swift | 📅 2026-08-12 - With Authgear SDK for iOS, you can easily integrate authorization features into your iOS apps.

### <a name="authZ-java"></a>Java

* [Apache Shiro](https://github.com/apache/shiro) ⭐ 4,452 | 🐛 14 | 🌐 Java | 📅 2026-08-11 - Powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management.
* [Oso](https://github.com/osohq/oso) ⭐ 3,492 | 🐛 119 | 🌐 Rust | 📅 2025-02-26 - Batteries-included framework for building authorization in your Java application.
* [jCasbin](https://github.com/casbin/jcasbin) ⭐ 2,653 | 🐛 4 | 🌐 Java | 📅 2026-08-12 - Authorization library that supports access control models like ACL, RBAC, ABAC in Java.
* [pac4j](https://github.com/pac4j/pac4j) ⭐ 2,520 | 🐛 3 | 🌐 Java | 📅 2026-08-11 - Security engine for Java (authentication, authorization, multi-frameworks): OAuth, CAS, SAML, OpenID Connect, LDAP, JWT.
* [TOTP Server-Side Library](https://github.com/wstrange/GoogleAuth) ⭐ 1,108 | 🐛 13 | 🌐 Java | 📅 2026-08-13 - TOTP server-side library.
* [AT\&T XACML](https://github.com/att/xacml-3.0) ⭐ 26 | 🐛 1 | 🌐 Java | 📅 2023-09-05 - XACML 3.0 implementation from AT\&T.

### <a name="authZ-node"></a>Node.js

* [Oso](https://github.com/osohq/oso) ⭐ 3,492 | 🐛 119 | 🌐 Rust | 📅 2025-02-26 - Batteries-included framework for building authorization in your Node.js application.
* [Node-Casbin](https://github.com/casbin/node-casbin) ⭐ 2,913 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-13 - Authorization library that supports access control models like ACL, RBAC, ABAC in Node.js.
* [accesscontrol](https://github.com/onury/accesscontrol) ⭐ 2,325 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-12 - Role and attribute-based access control for Node.js.
* [RBAC](https://github.com/CherryProjects/rbac) ⭐ 1,002 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-28 - Hierarchical role-based access control for Node.js.
* [pundit-ts](https://github.com/fatihky/pundit-ts) ⭐ 97 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-22 - Fully type-safe authorization library inspired by awesome [pundit](https://github.com/varvet/pundit) ⭐ 8,520 | 🐛 15 | 🌐 Ruby | 📅 2026-08-02 gem. Can be used for RBAC, ABAC access control models or any other model you wish.
* [ABAC](https://github.com/vovantics/abac) ⭐ 29 | 🐛 0 | 🌐 JavaScript | 📅 2014-03-04 - Attribute-based access control for Node.js.
* [Stack Auth](https://stack-auth.com) - Open-source authN & authZ for modern web apps, comes with pre-built components for Next.js.

### <a name="authZ-php"></a>PHP

* [laravel-permission](https://github.com/spatie/laravel-permission) ⭐ 12,957 | 🐛 2 | 🌐 PHP | 📅 2026-07-03 - Allows you to manage user permissions and roles in a database.
* [PHP-Casbin](https://github.com/php-casbin/php-casbin) ⭐ 1,335 | 🐛 0 | 🌐 PHP | 📅 2026-08-12 - Authorization library that supports access control models like ACL, RBAC, ABAC in PHP.
* [PHP-RBAC](https://github.com/OWASP/rbac) ⭐ 436 | 🐛 58 | 🌐 PHP | 📅 2024-04-19 - Authorization library for PHP which provides developers with NIST Level 2 hierarchical role-based access control.
* [php-abac](https://github.com/Kilix/php-abac) ⭐ 98 | 🐛 15 | 🌐 PHP | 📅 2019-07-23 - Attribute-based access control library.
* [ezRbac](https://github.com/xiidea/ezRbac) ⭐ 85 | 🐛 8 | 🌐 PHP | 📅 2019-02-06 - Simple yet easy to implement role-based access control library for popular PHP framework: [Codeigniter](https://github.com/bcit-ci/CodeIgniter) ⭐ 18,166 | 🐛 106 | 🌐 PHP | 📅 2024-07-15.
* [symfony-logical-authorization-bundle](https://github.com/ordermind/symfony-logical-authorization-bundle) ⭐ 23 | 🐛 5 | 🌐 PHP | 📅 2022-12-26 - This Symfony bundle provides a unifying solution for authorization that aims to be flexible, convenient and consistent.
* [logical-permissions-php](https://github.com/ordermind/logical-permissions-php) ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2021-01-06 - This is a generic library that provides support for array-based permissions with logic gates such as AND and OR.

### <a name="authZ-python"></a>Python

* [Oso](https://github.com/osohq/oso) ⭐ 3,492 | 🐛 119 | 🌐 Rust | 📅 2025-02-26 - Batteries-included framework for building authorization in your Python application.
* [PyCasbin](https://github.com/casbin/pycasbin) ⭐ 1,759 | 🐛 2 | 🌐 Python | 📅 2026-08-13 - Authorization library that supports access control models like ACL, RBAC, ABAC in Python.
* [Flask-RBAC](https://github.com/shonenada/flask-rbac) ⭐ 233 | 🐛 15 | 🌐 Python | 📅 2026-02-20 - Adds RBAC support to [Flask](https://github.com/pallets/flask) ⭐ 72,187 | 🐛 3 | 🌐 Python | 📅 2026-08-11.
* [Vakt](https://github.com/kolotaev/vakt) ⭐ 194 | 🐛 8 | 🌐 Python | 📅 2024-04-02 - Attribute-based access control (ABAC) SDK for Python.
* [casbin-fastapi-decorator](https://github.com/Neko1313/casbin-fastapi-decorator) ⭐ 7 | 🐛 3 | 🌐 Python | 📅 2026-08-10 - Decorator-based authorization for FastAPI using PyCasbin, providing per-route permissions with no middleware and support for JWT, async SQLAlchemy, and Casdoor.

### <a name="authZ-ruby"></a>Ruby

* [Pundit](https://github.com/varvet/pundit) ⭐ 8,520 | 🐛 15 | 🌐 Ruby | 📅 2026-08-02 - Minimal authorization through OO design and pure Ruby classes.
* [CanCanCan](https://github.com/CanCanCommunity/cancancan) ⭐ 5,688 | 🐛 93 | 🌐 Ruby | 📅 2026-08-09 - Authorization for Ruby on Rails.
* [Oso](https://github.com/osohq/oso) ⭐ 3,492 | 🐛 119 | 🌐 Rust | 📅 2025-02-26 - Batteries-included framework for building authorization in your Ruby application.
* [Casbin](https://github.com/CasbinRuby/casbin-ruby) ⭐ 67 | 🐛 1 | 🌐 Ruby | 📅 2024-05-18 - Authorization library that supports access control models like ACL, RBAC, ABAC in Ruby.

## AI Agent Auth

* [Composio](https://github.com/ComposioHQ/composio) ⭐ 29,682 | 🐛 52 | 🌐 TypeScript | 📅 2026-08-13 - Hosted integration platform with managed OAuth and tool calling for 1000+ apps.
* [Nango](https://github.com/NangoHQ/nango) ⭐ 11,447 | 🐛 113 | 🌐 TypeScript | 📅 2026-08-13 - Open-source OAuth and API key handling for 700+ APIs with token refresh and a unified API for agent workloads.
* [Arcade](https://github.com/ArcadeAI/arcade-ai) ⭐ 1,003 | 🐛 12 | 🌐 Python | 📅 2026-08-13 - Tool-calling platform with user approvals and authenticated actions for AI agents.
* [authsome](https://github.com/agentrhq/authsome) ⭐ 79 | 🐛 10 | 🌐 Python | 📅 2026-07-24 - Local-first credential broker for AI agents with an encrypted local vault and HTTPS proxy injection; no hosted service required.

## Articles

* [Modeling Authorization with PERM in Casbin](https://narendraj9.github.io/posts/generalized-authz.html)
* [Basic Role-Based HTTP Authorization in Go with Casbin](https://zupzup.org/casbin-http-role-auth)
* [Policy enforcements on Kubernetes with Banzai Cloud's Pipeline and Casbin](https://outshift.cisco.com/blog/policy-enforcement-k8s)
* [Organizational RBAC in Argo CD with Casbin](https://argo-cd.readthedocs.io/en/stable/operator-manual/rbac/)
* [Authorization Academy: A series of technical guides for building application authorization](https://www.osohq.com/academy)
* [Why Authorization is Hard](https://www.osohq.com/post/why-authorization-is-hard)

## Contribute

PR is welcomed.

## License

This project is licensed under the [CC0-1.0 license](https://github.com/casbin/awesome-auth/blob/master/LICENSE) ⭐ 1,214 | 🐛 6 | 🌐 Go | 📅 2026-08-13.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
