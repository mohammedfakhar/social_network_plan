# Social Network Plan

Work in progress notes about how to build a social network for social good.

* [Introduction](#introduction)
  * [Abstract](#abstract)
  * [Feedback](#feedback)
  * [Work in progress](#work-in-progress)
* [About this document](#about-this-document)
  * [Goals](#goals)
  * [Scope ](#scope-)
  * [Style](#style)
* [Context](#context)
  * [Broad context](#broad-context)
  * [Advocacy context](#advocacy-context)
  * [Technical context](#technical-context)
* [Challenges](#challenges)
  * [Open issues](#open-issues)
  * [How to describe a social network?](#how-to-describe-a-social-network-)
* [User Experience](#user-experience)
  * [Sign in](#sign-in)
  * [Stories](#stories)
* [Implementation](#implementation)
  * [Planning](#planning)
  * [Full stack](#full-stack)


## Introduction


### Abstract

We believe social networks have significant benefits for people and society. However, the big social networks suffer from major problems: data breaches, fake accounts, poor accountability, rife advertising, and restricted rights; these problems harm people and society. We propose a social network plan that aims for social good, as a not-for-profit (NFP), using free/libre open source (FLOSS).


### Feedback

We welcome feedback, suggestions, and constructive criticism. 

Email joel@joelparkerhenderson.com, tweet [@joel_henderson](https://twitter.com/joel_henderson), or comment in our [issues](https://github.com/joelparkerhenderson/social_network_plan/issues).

### Work in progress

This social network plan is a work in progress. 

We will improve the plan as we learn more.


## About this document


### Goals

We want to explore the viability of new social network for social good. 

We want to explore the purpose i.e. why do this, and the pragmatics i.e. how to do this.


### Scope 

We want this to be a friendly introduction that invites discussion.

We do not want this to be a reference, or manifesto, or specification. 


### Style

We use quotations with light editing for content, context, readability, consistency, and anonymity.


## Context


### Broad context

We are looking at the biggest social networks such as 
[Facebook](https://facebook.com) and
[Twitter](https://twitter.com).

We like websites that use technology for social good such as 
[Wikipedia](https://wikipedia.org) and
[Craigslist](https://craigslist.org).

### Advocacy context

We look to foundations such as 
[Electronic Frontier Foundation (EFF)](http://eff.org/) and
[Free Software Foundation (FSF)](http://fsf.org).

We look to FLOSS groups such as 
[Open Source Initiative (OSI)](http://opensource.org/) and 
[Software Freedom Conservancy (SFC)](https://sfconservancy.org/).

### Technical context

We use social coding sites such as 
[GitHub](https://github.com) and
[StackOverflow](https://stackoverflow.com).

We use social identity tools such as 
[GPG](https://www.gnupg.org/) and
[Keybase](keybase.io).

We admire distributed social networks such as
[Mastodon](https://mastodon.social) and
[Patchwork](https://github.com/ssbc/patchwork).


## Challenges


### Open issues

Open issues that are especially important to discuss:

* [**Funding**: advertisements, donations, subscriptions?](docs/funding.md)
* [**Audiences**: general public, niche groups, special needs?](docs/audiences.md)
* [**Scopes**: benefits, features, minimum viable product?](docs/scopes.md)
* [**Comparisons**: similarities/differences versus others?](docs/comparisons.md)
* [**Names**: real names, fake names, no names?](docs/names.md)
* [**Data**: who owns it, who uses it, who controls it?](docs/data.md)
* [**Security**: spammers, hackers, masqueraders?](docs/security.md)
* [**Communities**: how can we encourage people to help?](docs/communities.md)
* [**Motivations**: gamification, extrinsic, intrinsic?](docs/motivations.md)
* [**Niches**: music, meets, malls, mashups, more?](docs/niches.md)
* [**Feeds**: linear, algorithmic, customizable?](docs/feeds.md)
* [**Topologies**: centralized, decentralized, distributed, federated?](docs/topologies.md)
* [**Routes**: how to reach people, places, items, resources?](docs/routes.md)
* [**References**: articles, blogs, commentaries, etc.?](docs/references.md)

<!--
Original content vs. resharing

* "Reshares are part and parcel of a community - even before the days of the Internet. For many, gossip is part of socializing. A friend posted that he's just getting married. People will want to spread the word. How can they without reshares? Rewrite it themselves? Resharing is simply part of usual human interaction."
-->


### How to describe a social network?

We see challenges in how people describe social networks; we suggest starter questions.

Examples:

* **Benefits**: give me reasons to try your product.
* **Privacy**: what is your privacy policy, including sharing with 3rd party?
* **Platform**: is your product aiming to be a platform, API, plugin, integation, etc.?
* **Access**: mobile, web, desktop, native, etc.?
* **Code**: open source, closed source, etc.?
* (more?)



## User Experience


### Sign in

Discuss sign in options via:
* Email address and password
* Multi-factor e.g. mobile phone SMS, Google Authenticator app
* Providers e.g. Google, Facebook, LinkedIn
* Protocols e.g. OAuth, SAML
* Integrators e.g. Okta.com


### Stories

Discuss stories:
* Can we use RSS?
* Can we use Atom?
* Why/how to provide what companies say they want, e.g. ads, analytics, branding?


## Implementation


### Planning

Discuss broad goals:
* This project is more akin to an ambitious web app, less akin to a blogging site.
* We value participation by many people and organizations.
* The security needs to be bulletproof and independently-verifiable.

Discuss organizational areas:
* Prefer truly free technology over corporate-restricted technology.
* Prefer more-welcoming communities over less-welcoming communities.
* Prefer agile over waterfall.

Discuss project management such as:
* Planning e.g. Asana, Trello
* Dicussion e.g. IRC, Slack
* Prototyping e.g. Balsamiq, Photoshop

Discuss planning methodologies:
* Agile, lean, kanban, waterfall, etc.
* Model, view, controller (MVC), data, context, interaction (DCI), etc. 
* Functional code may be easier to create reliably and easier to scale up.


### Full stack

Discuss languages such as:
* Popular tech e.g. React, Node, C++
* Powerful tech e.g. Java, Kotlin, Clojure
* Progressive tech e.g. Ember, Elixir, Rust
* Mobile tech e.g. iOS, Android, React Native

Discuss databases such as:
* Relation-oriented e.g. MySQL, PostgreSQL, SQL Server
* Document-oriented e.g. Mongo
* Speed-oriented e.g. Redis, Memcached
* Graph-oriented e.g. Fauna, Neo4J
* Vendor-oriented e.g. Google Spanner, Amazon Aurora

Discuss data exchange such as:
* Resource-oriented e.g. REST-like
* Graph-oriented e.g. GraphQL-like
* Object-oriented e.g. RPC
* Wire-oriented e.g. protocol buffers, thrift
* Publishing-oriented e.g. RSS, Atom, Pub/Sub
* API-oriented e.g. JSON API, OpenAPI, LD, RDF, SPARQL

Discuss platform areas such as:
* Mobile vs. desktop
* Phone size vs. tablet size vs. laptop size
* Distribution on Windows, Mac, Linux, iOS, Android, etc.
* Distribution via Apple App Store, Google Play, etc.


