---
title: Sequent 3.0
---

Sequent is an opinionated CQRS and event sourcing framework (ES) written in Ruby. This site is intended
to help you learn and develop CQRS / ES applications in Ruby (using Sequent).
Sequent **focusses** on the **domain logic** of your application. It is web framework agnostic.
You can use it with Rails, Sinatra or whatever framework you like.

**Important:** The entire documentation applies to the **master**
branch
{: .notice--danger}

## Tutorials

There are several tutorials available:

### 1. Getting Started

New to Sequent? The [getting started guide](/docs/getting-started.html) is the place to be!

### 2. Modelling the domain

In this guide we will use the Sequent concepts and create and code a first domain model
of our blog application. Go checkout the [modelling the domain guide](/docs/modelling-the-domain.html)
for step by step tutorial to create an app from scatch.

### 3. Building a web-application

In the [building a web-application guide](/docs/building-a-web-application.html) we continue with the
application created in the modelling the domain guide and add a web interface for it using the Sinatra
web framework.

### 4. Finishing the webapplication
In the [finishing the web-application guide](/docs/finishing-the-web-application.html) we continue with
the blog application and add form validation and let the Author's add Posts.

## Guides

Next to the tutorials there is the [Reference Guide](/docs/concepts.html) to provide and
in-depth explanation of the several concepts (like `AggregateRoot`, `Event`, `Command` etc) used in Sequent.

## Further reading

There is a lot more information available on CQRS and event sourcing:

- [Event sourcing](http://martinfowler.com/eaaDev/EventSourcing.html)
- [Lars and Bob's presentation at GOTO Amsterdam](http://gotocon.com/dl/goto-amsterdam-2013/slides/BobForma_and_LarsVonk_EventSourcingInProductionSystems.pdf)
- [Erik's blog series](http://blog.zilverline.com/2011/02/10/towards-an-immutable-domain-model-monads-part-5/)
- [Simple CQRS example by Greg Young](https://github.com/gregoryyoung/m-r)
- [Google](http://www.google.nl/search?ie=UTF-8&q=cqrs+event+sourcing)

## License

Sequent is released under the MIT License.
