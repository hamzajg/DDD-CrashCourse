# Architecture — DDD-CrashCourse

Current-state map. Descriptive, not aspirational; see `docs/adr/` for why.

## Shape

```
DDD-CrashCourse/        documentation-only repo
├── README.md           series index + chapter table
├── chapter-1.md        Strategic DDD (domain, subdomains, EMR example)
├── ch-1-subdomains.png diagram for chapter 1
└── LICENSE
```

## Content model

Linear chapter series on **strategic** DDD:

- domain vs subdomain concepts
- core / supporting / generic subdomain classification
- applied to an EMR (electronic medical records) example
- problems → solutions progression

Chapter 1 is published; the series is designed to grow with
`chapter-N.md` files indexed from README.

## Sources

Based on Evans' *Domain-Driven Design* and Vernon's *Implementing
Domain-Driven Design* — author's own explanation, not a translation.

## No code

There is no application, build, or test — this is a technical reading
series. Any tooling would be out of scope.
