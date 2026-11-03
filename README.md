# Hi, I'm Carlos 👋

Symfony lover. TDD crazy. API-cultor (Spanish pun: *apicultor* = beekeeper, but for APIs 🐝). Sayajin pride.

Yes, the avatar is a Saiyan. It's staying.

I live in Cambados, Galicia, and I've been building PHP backends since 2012. Self-taught: I learned by reading manuals, breaking things and fixing them. Right now I'm **available immediately** for fully remote work.

## What I'm good at

Taking legacy PHP/Symfony systems that everyone is afraid to touch and making them safe to change. And building the layers that stop external APIs from taking over a codebase.

## The project I'm proudest of: [IntegrationEngine](https://github.com/CarlosGude/integrationEngine)

[![CI](https://github.com/CarlosGude/integrationEngine/actions/workflows/ci.yml/badge.svg)](https://github.com/CarlosGude/integrationEngine/actions/workflows/ci.yml)
[![Packagist](https://img.shields.io/packagist/v/carlosgude/integration-engine)](https://packagist.org/packages/carlosgude/integration-engine)
[![Installs](https://img.shields.io/packagist/dt/carlosgude/integration-engine)](https://packagist.org/packages/carlosgude/integration-engine/stats)
[![PHPStan](https://img.shields.io/badge/PHPStan-max-brightgreen)](https://github.com/CarlosGude/integrationEngine/blob/main/phpstan.neon)
[![Mutation score](https://img.shields.io/badge/MSI-%E2%89%A5%2090%25-brightgreen)](https://github.com/CarlosGude/integrationEngine/blob/main/infection.json5)

Every time I integrated an external API into a Symfony app, I ended up solving the same problems again: authentication, requests, response mapping, error handling. And every integration grew its own shape. So I built a bundle that gives them all the same one: an Action, a Mapper and a typed Response.

A few things I like about it:

- It gives structure without taking away freedom. Like bamboo: it bends, it doesn't break.
- Its docs say when **not** to use it, and which security controls it does *not* cover. I'd rather you hear the limits from me.
- My power level: PHPStan max with no baseline, Deptrac, and mutation testing. I even tried to break my own CI on purpose to check it noticed.
- There's an [executable demo](https://github.com/CarlosGude/integrationEngine-demo) and a [Flex recipe I got merged into symfony/recipes-contrib](https://github.com/symfony/recipes-contrib/pull/2058).

[Docs](https://integrationengine.dev) · [Packagist](https://packagist.org/packages/carlosgude/integration-engine)

## Things I'm happy to have done

- Took a legacy core from PHPStan level 5 to 9 (−93% baseline) and from a test suite that no longer ran to 2,100+ passing tests.
- Moved a system with 100+ endpoints from PHP 7.4 / Symfony 4 to PHP 8.3 / Symfony 6 with zero downtime.
- Designed a messaging layer that handles 300,000+ messages/min for rider positions alone.
- Went looking for trouble in a security review nobody asked for, and found and fixed two IDOR vulnerabilities.

## How I like to work

- Tests, static analysis and architecture rules decide what merges. AI coding agents are welcome behind those same gates, with a human reviewing.
- Say the limits out loud.
- If you're hiring: a real 30-minute conversation beats any keyword filter.

## Stack I reach for

PHP 8 · Symfony · Doctrine · API Platform · REST · GraphQL · RabbitMQ · Amazon SQS · Azure Queue · MySQL · PostgreSQL · Redis · Docker · Kubernetes / AKS · GitHub Actions

## Say hi

🌐 [carlosgude.dev](https://carlosgude.dev) ([ES](https://carlosgude.dev/es/)) · 📄 [CV](https://carlosgude.dev/Carlos_Gude_Sanchez_CV_EN.pdf) · 💼 [LinkedIn](https://www.linkedin.com/in/carlos-gude/) · ✉️ carlos.sgude@gmail.com
