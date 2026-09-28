# Mykola Polupan

Business student at Comenius University in Bratislava, with part-time experience in IT support at CePIT.

I am looking for paid student work with **SQL, Python and data quality**, with the aim of growing into a full-time data role after graduation.

## Selected project

### [Retail Catalogue Guard](https://github.com/Home-ad/retail-catalogue-guard)

A local data pipeline and Power BI report combining public product records, price observations and historical recall notices. Built with Python, DuckDB and FastAPI, with a small bundled demo and automated checks.

**One decision worth reviewing:** prices and recall links are aggregated separately before joining to the product catalogue. This keeps one row per product and prevents a many-to-many join from inflating the counts.

- [Data model and source rules](https://github.com/Home-ad/retail-catalogue-guard/blob/main/docs/data-contract.md)
- [Transformation code](https://github.com/Home-ad/retail-catalogue-guard/blob/main/src/catalogue_guard/pipeline.py#L190) and [JOIN regression test](https://github.com/Home-ad/retail-catalogue-guard/blob/main/tests/test_pipeline.py#L6)
- [Run the small demo](https://github.com/Home-ad/retail-catalogue-guard#try-the-real-data-demo) or [open the Power BI report](https://github.com/Home-ad/retail-catalogue-guard/releases/tag/v1.1.0)

[![Retail catalogue coverage report](https://raw.githubusercontent.com/Home-ad/retail-catalogue-guard/main/docs/powerbi-coverage.png)](https://github.com/Home-ad/retail-catalogue-guard)

## Current focus

SQL joins and aggregation, reliable data transformations, checking missing values and explaining technical decisions clearly. The projects here are learning and portfolio work.

Bratislava · [LinkedIn](https://www.linkedin.com/in/mykola-polupan-6668ab30b)
