
# Hi, I'm Carlos 👋

**Symfony lover. TDD crazy. API-cultor** (*apicultor* is Spanish for beekeeper; I collect APIs instead 🐝). **Saiyan pride.**

I live in Cambados, Galicia, and I've been building PHP backends since 2012. I'm self-taught: I learned by reading manuals, breaking things, figuring out why they broke and trying again.

I'm **available immediately for fully remote roles**.

## The problems I enjoy solving

Legacy PHP/Symfony systems that nobody wants to touch. External integrations that have grown five different ways of doing the same thing. Test suites that stopped running so long ago nobody remembers why.

I like getting those systems back under control, **making them safe to change without stopping the people who depend on them**.

A few things I've done in production:

- Took a legacy core from **PHPStan level 5 to 9**, cut its baseline by **93%**, and revived a broken suite to **2,100+ passing tests**.
- Migrated **100+ endpoints** from PHP 7.4 / Symfony 4 to PHP 8.3 / Symfony 6 with **zero downtime**.
- Designed a messaging layer handling **300,000+ rider-position messages/min**.

## My proudest project: [IntegrationEngine](https://github.com/CarlosGude/integrationEngine)

[![CI](https://github.com/CarlosGude/integrationEngine/actions/workflows/ci.yml/badge.svg)](https://github.com/CarlosGude/integrationEngine/actions/workflows/ci.yml)
[![Packagist](https://img.shields.io/packagist/v/carlosgude/integration-engine)](https://packagist.org/packages/carlosgude/integration-engine)
[![Installs](https://img.shields.io/packagist/dt/carlosgude/integration-engine)](https://packagist.org/packages/carlosgude/integration-engine/stats)
[![PHPStan](https://img.shields.io/badge/PHPStan-max-brightgreen)](https://github.com/CarlosGude/integrationEngine/blob/main/phpstan.neon)
[![Mutation testing](https://img.shields.io/badge/Mutation%20testing-Infection-brightgreen)](https://github.com/CarlosGude/integrationEngine/blob/main/infection.json5)

After years of integrating external APIs, I got tired of solving the same problems over and over: authentication, HTTP requests, response mapping and error handling. Each integration seemed to grow its own conventions.

So I built a Symfony bundle around a repeatable contract: **Action → Mapper → typed Response**. It makes integrations predictable while leaving room for the weird things external providers inevitably do.

What I'm especially proud of:

- The docs explain **when not to use it** and which security controls it **doesn't** provide. I'd rather be clear about the limits.
- **PHPStan max, Deptrac and mutation testing** help keep architectural promises honest. I've even deliberately checked that CI fails when it should.
- There's an [executable demo](https://github.com/CarlosGude/integrationEngine-demo), and I got a [Symfony Flex recipe merged into `symfony/recipes-contrib`](https://github.com/symfony/recipes-contrib/pull/2058).

[Docs](https://integrationengine.dev) · [Packagist](https://packagist.org/packages/carlosgude/integration-engine)

## How I think about software

**Good architecture gives structure without taking away freedom. Like bamboo: it bends, it doesn't break.**

I like strong contracts and boundaries, but not rules for their own sake. Tests, static analysis and architecture checks should make change safer, not turn every decision into a ceremony. No architecture astronautics just to draw prettier diagrams.

AI coding agents are welcome behind those same quality gates, with a human reviewing the result. I prefer stating trade-offs and limitations out loud, and I enjoy a good technical disagreement when it's backed by evidence.

I can be stubborn about quality. I also try to be willing to change my mind when someone makes a better argument.

## Stack I reach for

PHP 8 · Symfony · Doctrine · API Platform · REST · GraphQL · RabbitMQ · Amazon SQS · Azure Queue · MySQL · PostgreSQL · Redis · Docker · Kubernetes / AKS · GitHub Actions

## Say hi

If you're hiring, I'd rather talk about a real engineering problem than recite a list of technologies.

🌐 [carlosgude.dev](https://carlosgude.dev) ([ES](https://carlosgude.dev/es/)) · 📄 [CV](https://carlosgude.dev/Carlos_Gude_Sanchez_CV_EN.pdf) · 💼 [LinkedIn](https://www.linkedin.com/in/carlos-gude/) · ✉️ carlos.sgude@gmail.com
