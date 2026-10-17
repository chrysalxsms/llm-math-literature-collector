# LLM Math Literature Collector

A Python tool that collects and organizes research papers on how large language models (LLMs) perform on mathematical tasks. It queries official academic APIs, stores structured metadata, and exports results for use in a literature review.

Built to support a bachelor research project at KU Leuven on the question: _how fast are LLMs progressing in mathematics?_

## Status

🚧 Work in progress. This project is being developed step by step; see the roadmap below.

## Features (roadmap)

- [ ] Search arXiv for papers matching a set of predefined queries
- [ ] Parse results into structured fields (title, authors, year, abstract, link)
- [ ] Store results in CSV/JSON and remove duplicates
- [ ] Enrich papers with citation counts and venue information via Semantic Scholar
- [ ] Filter and rank papers by relevance, recency and citations
- [ ] Export to BibTeX for use in reference managers and LaTeX
- [ ] Run automatically on a weekly schedule with GitHub Actions

## Data sources

- [arXiv API](https://info.arxiv.org/help/api/index.html)
- [Semantic Scholar API](https://www.semanticscholar.org/product/api)

This tool only uses official APIs and respects their rate limits and terms of use. It does not scrape websites.

## Why a reproducible search?

A literature review is only as good as its search strategy. By defining the queries and sources in code, the search can be rerun, inspected and extended at any time, and the results can be traced back to exactly how they were found.

## License

MIT (to be added).

## Author

Aishwarya Bringmans, Computer Science student at KU Leuven
