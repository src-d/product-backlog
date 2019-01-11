# Product Backlog

This repository hosts the [Product backlog](https://github.com/src-d/product-tbacklog/issues/).

## Methodology

To learn about our methodology please read carefully this following documents at guide:

- [General Workflow](https://github.com/src-d/guide/blob/master/engineering/workflow.md)
- [Engineering methodology](https://github.com/src-d/guide/blob/master/engineering/methodology.md)

## Label Categories

The labels are used in different ways, we have 3 main categories:

- __Team__ used to filter by team, this tag is mandatory.
- __Priority__: these labels are used by the Product Team to prioritize the issues.
- __State__: a granular way to classify the status of an issue. Used on issues that are assigned to an ongoing sprint.

The Product Backlog is fully managed by the Product team,
and fed by the proposals accepted on the [feature idea](https://github.com/src-d/product-idea) repository.

New issues can only be created by members of the Product organization, including VP of Product and Product Owner.

That said, members of the Engineering organization are welcome and expected to give input, comment, and update on the issues they're involved with.

### Label Description

| label          | team  | category | meaning
|----------------|-------|----------|-----------------------------------------------------------------------|
| EPIC           | *     | kind     | Defines a new EPIC task, directly linked to an OKR.
|                |       |          |
| high           | PR    | priority | High-priority task.
| medium         | PR    | priority | Medium-priority task.
| low            | PR    | priority | Low-priority task.
|                |       |          |
| draft          | *     | state    | Defines an EPIC with a design document pending to be reviewed.
| pending-doc    | *     | state    | Defines an EPIC pending of be completed with a design document.
|                |       |          |
| data-retrieval | DR    | team     | Data Retrieval.
| data-science   | ML    | team     | Machine Learning.
| devrel         | DRL   | team     | Developer Relations.
| infrastructure | I     | team     | Infrastructure.
| languages      | LA    | team     | Language Analysis.
| applications   | AP    | team     | Applications.
| product        | PR    | team     | Product & Data Intelligence.
|                |       |          |
| gemini         | *     | project  | Related to [src-d/gemini](https://github.com/src-d/gemini) or [src-d](https://github.com/src-d/apollo)
| babelfish      | *     | project  | Related to [bblfsh](https://github.com/bblfsh).
| engine         | *     | project  | Related to [src-d/engine](https://github.com/src-d/engine).
|                |       |          |
| apply-model    | ML    | feature  | The model is designed, some routine work is needed to use it one a new dataset.
| coding         | ML    | feature  | Engineering task which involves writing some real code and not playing in notebooks.
| source{d}-api  | ML    | feature  | Exposing the training pipeline, it's artifacts and tools to the public.

Team abbreviations:

- **DR** - Data Retrieval
- **DRL** - Developer Relations
- **I** - Infrastructure
- **LA** - Language Analysis
- **ML** - Machine Learning
- **AP** - Applications
- **PR** - Product

## Tips and tricks

- I want to turn my issue into a TODO list: https://help.github.com/articles/about-task-lists/

# Contribute

We have made our backlog public for transparency's sake, but we do not expect any contributions from the community to be done on this repository. If you think this is wrong and would like to participate, you can get in touch with us via email to devrel@sourced.tech.

 # Code of Conduct

 All activities under source{d} projects are governed by the [source{d} code of conduct](.github/CODE_OF_CONDUCT.md).

 # License

 This work is licensed under a Creative Commons — Attribution-ShareAlike 4.0 International License. See [LICENSE](./LICENSE.md).