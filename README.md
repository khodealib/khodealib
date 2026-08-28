# Ali Bagheri

**Python Backend Engineer · Template Author · Freelancer**  
Tehran, Iran  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://linkedin.com/in/khodealib)
[![Email](https://img.shields.io/badge/Email-khodealib@gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:khodealib@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-khodealib-181717?logo=github&logoColor=white)](https://github.com/khodealib)

---

## What I Build

- **Production-ready Python backend foundations** — cookiecutter templates for FastAPI and Django with auth, async ORM, migrations, rate-limiting, i18n, structured logging, Celery, and strict type/lint/test pipelines
- **Developer experience tooling** — uv-based workflows, ruff/mypy/pytest configs, pre-commit, GitHub Actions CI, DevContainers
- **Backend systems** — JWT authentication, async SQLAlchemy 2.0, Redis caching, PostgreSQL, observability, background task processing

---

## Core Engineering Stack

| Backend | Data & Infrastructure | Engineering & DX |
|---------|----------------------|------------------|
| Python, FastAPI, Django 5.2, DRF, SQLAlchemy 2.0, Pydantic v2 | PostgreSQL, Redis, Alembic, Docker, Docker Compose, Nginx | uv, ruff, mypy (`--strict`), pytest, cookiecutter, pre-commit, GitHub Actions, DevContainers |

---

## Featured Projects

### [fastapi-production-template](https://github.com/khodealib/fastapi-production-template)
Cookiecutter template generating production FastAPI projects with admin panel, async SQLAlchemy 2.0 + Alembic, JWT access/refresh rotation, rate-limiting (fixed/moving/sliding window), i18n, email, Redis caching, Celery, structured JSON logging (structlog), Prometheus metrics, health checks — strict ruff/mypy/pytest under uv.

**Stack:** `FastAPI` `SQLAlchemy 2.0` `Redis` `Celery` `uv` `ruff` `mypy` `pytest` `Alembic` `Docker` `GitHub Actions`

```bash
uvx cookiecutter gh:khodealib/fastapi-production-template
```

[Repository](https://github.com/khodealib/fastapi-production-template) · [Generated Example](https://github.com/khodealib/fastapi-production-template/tree/main/%7B%7Bcookiecutter.project_slug%7D%7D)

---

### [django-production-template](https://github.com/khodealib/django-production-template)
Cookiecutter template for Django 5.2 LTS: uv, ruff, mypy, DRF + drf-spectacular, PostgreSQL, Redis, Celery, Docker, DevContainer, pytest + factory_boy, pre-commit, GitHub Actions CI, database seeding, 12-factor settings via django-environ.

**Stack:** `Django 5.2` `DRF` `drf-spectacular` `PostgreSQL` `Redis` `Celery` `uv` `ruff` `mypy` `pytest` `Docker` `DevContainer` `GitHub Actions`

```bash
uv tool install cookiecutter && cookiecutter gh:khodealib/django-production-template
```

[Repository](https://github.com/khodealib/django-production-template)

---

### [designpattern-in-python](https://github.com/khodealib/designpattern-in-python)
Reference implementations of all 23 GoF design patterns in modern Python: Creational (Singleton, Factory, Builder, Prototype), Structural (Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Proxy), Behavioral (Chain, Command, Iterator, Mediator, Memento, Observer, State, Strategy, Template, Visitor).

**Stack:** `Python` `Design Patterns` `Software Architecture` `Clean Code` `SOLID`

[Repository](https://github.com/khodealib/designpattern-in-python)

---

## Engineering Principles

- **Type safety by default** — mypy `--strict`, Pydantic v2, django-stubs, zero `Any` in application code
- **Async correctness** — structured concurrency, explicit lifecycles, no fire-and-forget tasks
- **Developer experience is a feature** — templates eliminate boilerplate, DX tooling catches errors before CI, docs are executable
- **Observability built-in** — structured JSON logging (structlog), health endpoints, Prometheus metrics, request tracing
- **Migrations are contracts** — Alembic revisions reviewed, reversible, tested against staging data

---

## GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=khodealib&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=default)

---

## Contact

- **LinkedIn:** [linkedin.com/in/khodealib](https://linkedin.com/in/khodealib)
- **Email:** [khodealib@gmail.com](mailto:khodealib@gmail.com)
- **GitHub:** [github.com/khodealib](https://github.com/khodealib)