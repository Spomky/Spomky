![Cover image](1.webp)

### Hi there 👋

My name is **Florent Morselli** (*flɔʁɑ̃ mɔʁseli*). I am a French web developer and project manager passionate about PHP, ReactJS and Free, Libre & Open-Source Software.
As far as possible, I contribute to projects or publish my own work.

> 🧡 Since early 2025, I am proud to be a ![Symfony Core Team](https://img.shields.io/badge/Symfony-Core%20Team-orange?style=flat-square&logo=symfony).
> This allows me to help shape the future of the framework I use and love daily.

The projects I am working on are mainly related to security over web applications. In particular, you will find useful libraries of Symfony bundles for
* One-Time Passwords (TOTP/HOTP) => see https://github.com/Spomky-Labs/otphp,
* Json Web Tokens (JWT, including signed and encrypted ones) => see https://github.com/web-token,
* Web Push => see https://github.com/Spomky-Labs/web-push,
* Concise Binary Object Representation (CBOR) => see https://github.com/Spomky-Labs/cbor-php,
* Webauthn => see https://github.com/web-auth.

Among all of these projects, let me encourage you to read more about [**Webauthn**](https://github.com/web-auth), a PHP implementation I am working on since end of 2018 and that will help you to get rid of passwords.

In addition, I had the opportunity to share my knowledge during the following events:

* September 2022: I presented the possibilities offered by this technology during [the second edition of ApiPlatformCon](https://youtu.be/Y2_0omg1CFk) in September 2022 in Lille, France.
* March 2023, I gave two 1-day workshops during the [Symfony Live Paris 2023](https://live.symfony.com/2023-paris/workshop/maximiser-la-securite-de-vos-applications-avec-le-bundle-security).
* December 2023, I gave a 1-day workshop during the [Symfony Con Brussels 2023](https://live.symfony.com/2023-brussels-con/workshop/road-to-safer-applications).
* March 2024, I presented my feedback on [the Progressive Web Apps](https://live.symfony.com/2024-paris/schedule/de-web-app-a-progressive-web-app) and [gave a 1-day workshop](https://live.symfony.com/2024-paris/workshop#securite-amelioree-et-webauthn-avec-symfony-2) during the Symfony Live 2024.
* March 2025, [I gave a 1-day workshop](https://live.symfony.com/2025-paris/) during the Symfony Live 2025

[![APIP Con 2022](https://user-images.githubusercontent.com/1091072/191684778-b9e26104-038d-45c2-a1b3-287233d15ecc.jpg)](https://api-platform.com/con/2022/conferences/webauthn-se-debarrasser-des-mots-de-passe-definitivement/)

[![Symfony Live 2024](Symfony%20Live%202024.png)](https://symfony.com/blog/symfonylive-paris-2024-from-web-app-to-progressive-web-app)


Feel free to ask me about all of these FLOSS projects or reach me on any other topics you may want to discuss.

Hereafter an overview of my involvement in the Open-Source ecosystem.
If you wish, you can sponsor me. The [GitHub Sponsors page](https://github.com/sponsors/Spomky/) or the [Patreon page](https://www.patreon.com/FlorentMorselli) are made for that purpose. Any help is greatly appreciated and allows me to spend time on these projects.

#### 👷 Check out what I'm currently working on

- [beffroi-auth/.github](https://github.com/beffroi-auth/.github) -  (today)
- [beffroi-auth/application](https://github.com/beffroi-auth/application) - Read-only split of apps/beffroi of beffroi-auth/beffroi. The identity provider application of Beffroi: Symfony on FrankenPHP, its image set by the environment, the one way Beffroi is deployed. (today)
- [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) - Beffroi: an identity provider for the Symfony ecosystem. OAuth 2.0 / OpenID Connect first, pure-PHP components, one complete application. (today)
- [beffroi-auth/core](https://github.com/beffroi-auth/core) - Read-only split of src/core of beffroi-auth/beffroi. Identity core: tenants, users, credentials, linked identities, groups, authentication sessions, keys. Pure PHP. (today)
- [beffroi-auth/docs](https://github.com/beffroi-auth/docs) - Documentation of Beffroi, an identity provider for the Symfony ecosystem: the application that is the provider, and the identity core, OAuth 2.0 and OpenID Connect, and SAML 2.0 it is built on. A static site on GitHub Pages, one branch per version. (today)
- [beffroi-auth/oidc](https://github.com/beffroi-auth/oidc) - Read-only split of src/oidc of beffroi-auth/beffroi. OAuth 2.0 and OpenID Connect: clients, authorization requests, grants, tokens, discovery, JWKS, UserInfo, logout. Pure PHP. (today)
- [beffroi-auth/saml](https://github.com/beffroi-auth/saml) - Read-only split of src/saml of beffroi-auth/beffroi. SAML 2.0 for the identity provider: the identity provider and service provider roles of a tenant, metadata, attribute mapping, single logout on the session of the core. Pure PHP. (today)
- [beffroi-auth/saml2-bindings](https://github.com/beffroi-auth/saml2-bindings) - Read-only split of src/saml2-bindings of beffroi-auth/beffroi. The HTTP-Redirect and HTTP-POST bindings of SAML 2.0 for PHP, strings and arrays in and out. No HTTP object. (today)
- [beffroi-auth/saml2-model](https://github.com/beffroi-auth/saml2-model) - Read-only split of src/saml2-model of beffroi-auth/beffroi. The SAML 2.0 model for PHP: the samlp, saml and md objects of Web Browser SSO and Single Logout, read strictly and validated in code. No HTTP. (today)
- [beffroi-auth/tui](https://github.com/beffroi-auth/tui) - Read-only split of apps/tui of beffroi-auth/beffroi. The terminal client of the administration of a Beffroi instance: a confidential client of its provider, signed in by a phishing-resistant proof, holding tokens bound to a key of its run. (today)

#### 🔨 My recent Pull Requests

- [ci: every workflow runs on the runners github hosts, x86_64 and arm64, now that the repository is public (issue #1141)](https://github.com/beffroi-auth/beffroi/pull/1143) on [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) (today)
- [ci: every job runs on a runner GitHub hosts, the repository being public (issue #1140)](https://github.com/beffroi-auth/beffroi/pull/1142) on [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) (today)
- [fix(tui): bin/beffroi-tui takes the autoloader the proxy of Composer names, so that an install as a dependency starts (issue #1136)](https://github.com/beffroi-auth/beffroi/pull/1138) on [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) (today)
- [docs: every repository of the organisation without a security policy of its own sends a vulnerability to the advisories of the monorepo](https://github.com/beffroi-auth/.github/pull/3) on [beffroi-auth/.github](https://github.com/beffroi-auth/.github) (today)
- [feat(tui, ci): the screen says the version of the program, and whether a newer release of its line is out (issue #1134)](https://github.com/beffroi-auth/beffroi/pull/1135) on [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) (today)
- [docs: the pages quote the words the provider writes now, the titles of the account pages, the buttons that take something back and the sentences of a refusal](https://github.com/beffroi-auth/docs/pull/67) on [beffroi-auth/docs](https://github.com/beffroi-auth/docs) (today)
- [feat(app): every table of the account is narrowed by what its columns say, the revoked passkeys left out until they are asked for (issues #1131, #1092)](https://github.com/beffroi-auth/beffroi/pull/1132) on [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) (today)
- [chore(app): the pages of the provider say what a person needs in few words, and repeat neither their title nor their card (issue #1129)](https://github.com/beffroi-auth/beffroi/pull/1130) on [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) (today)
- [fix(app): the field of a certificate or a key on the page of encrypted mail is drawn as a field and fills its panel, and its two formats stand apart](https://github.com/beffroi-auth/beffroi/pull/1128) on [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) (today)
- [feat(tui): the administrator lists the mail signing keys of the tenant, draws its OpenPGP key, sets its S/MIME key from two PEM files and removes one (issue #1124)](https://github.com/beffroi-auth/beffroi/pull/1127) on [beffroi-auth/beffroi](https://github.com/beffroi-auth/beffroi) (today)

#### 🔭 Latest releases I've contributed to

- [DamienHarper/auditor](https://github.com/DamienHarper/auditor) ([4.4.0](https://github.com/DamienHarper/auditor/releases/tag/4.4.0), 1 day ago) - auditor, the missing audit log library
- [api-platform/core](https://github.com/api-platform/core) ([v5.0.9](https://github.com/api-platform/core/releases/tag/v5.0.9), 3 days ago) - The server component of API Platform: hypermedia and GraphQL APIs in minutes
- [web-auth/webauthn-framework](https://github.com/web-auth/webauthn-framework) ([5.3.15](https://github.com/web-auth/webauthn-framework/releases/tag/5.3.15), 4 days ago) - WebAuthn and passkeys for PHP and Symfony.
- [DamienHarper/auditor-bundle](https://github.com/DamienHarper/auditor-bundle) ([6.3.1](https://github.com/DamienHarper/auditor-bundle/releases/tag/6.3.1), 5 days ago) - The missing audit log library
- [symfony/symfony](https://github.com/symfony/symfony) ([v8.2.0-BETA2](https://github.com/symfony/symfony/releases/tag/v8.2.0-BETA2), 1 week ago) - The Symfony PHP framework
- [symfony/validator](https://github.com/symfony/validator) ([v8.2.0-BETA2](https://github.com/symfony/validator/releases/tag/v8.2.0-BETA2), 1 week ago) - Provides tools to validate values
- [symfony/security-bundle](https://github.com/symfony/security-bundle) ([v8.2.0-BETA2](https://github.com/symfony/security-bundle/releases/tag/v8.2.0-BETA2), 1 week ago) - Provides a tight integration of the Security component into the Symfony full-stack framework
- [symfony/key-management](https://github.com/symfony/key-management) ([v8.2.0-BETA2](https://github.com/symfony/key-management/releases/tag/v8.2.0-BETA2), 1 week ago) - Abstracts Key Management Systems (AWS KMS, Azure Key Vault, Google Cloud KMS, HashiCorp Vault Transit, Scaleway Key Manager, KMIP, ...) behind a single interface
- [symfony/mailer](https://github.com/symfony/mailer) ([v8.2.0-BETA2](https://github.com/symfony/mailer/releases/tag/v8.2.0-BETA2), 1 week ago) - Helps sending emails
- [symfony/doctrine-orm-key-management](https://github.com/symfony/doctrine-orm-key-management) ([v8.2.0-BETA2](https://github.com/symfony/doctrine-orm-key-management/releases/tag/v8.2.0-BETA2), 1 week ago) - Symfony Doctrine ORM Key Management Bridge

#### ❤️ These awesome people sponsor me (thank you!)

- [tacman](https://github.com/tacman) (2 years ago)
- [yousign](https://github.com/yousign) (3 years ago)
- [passbolt](https://github.com/passbolt) (5 years ago)

<a href="https://stackoverflow.com/users/2157818/florent-morselli"><img src="https://stackoverflow.com/users/flair/2157818.png" width="208" height="58" alt="profile for Florent Morselli at Stack Overflow, Q&amp;A for professional and enthusiast programmers" title="profile for Florent Morselli at Stack Overflow, Q&amp;A for professional and enthusiast programmers"></a>

[![Top Langs](https://wakatime.com/share/@Spomky/aa41d408-c524-4a5f-936d-0b9446698abd.svg)](https://wakatime.com/@Spomky)
