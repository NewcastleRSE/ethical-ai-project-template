# Template for setting up responsible data science projects
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-6-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

*This is a template for setting up a machine learning or broader data science project online, such as on GitHub.*

## About this Repository

This repository operationalises The Turing Way recommendations for structuring a project repository to support reproducibility and responsible practices in data science projects.
This repository includes the files and directories recommended for enabling reproducibility, collaboration in a project, and the sharing of research objects.

This repository follows the recommendations and guidance provided in *[The Turing Way](https://the-turing-way.netlify.app/welcome)* handbook to data science.
When reusing this repository, please update the information on your README page with information about your project.

## Repo Structure

Inspired by [Cookie Cutter Data Science](https://github.com/drivendata/cookiecutter-data-science).

```
├── LICENSE
├── README.md          <- The top-level README for users of this project.
├── CODE_OF_CONDUCT.md <- Guidelines for users and contributors of the project.
├── CONTRIBUTING.md    <- Information on how to contribute to the project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── project_management <- Meeting notes and other project planning resources
│
├── src                <- Source code for use in this project.
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualisation  <- Scripts to create exploratory and results-oriented visualisations
│       └── visualise.py
└──
```

**Maintainers**

This repository template is forked from the [reproducible project template](https://github.com/alan-turing-institute/reproducible-project-template) set up and maintained by Malvika Sharan to support the work of Open Research Community Management and Research Application Management teams under the Tools, Practices and Systems Research Programme at The Alan Turing Institute.

As an open-source repository, anyone beyond these teams is welcome to reuse this template for setting up their projects.

*Please create [an issue](../../issues) to share references or ideas related to the development of this project.*

## Responsible Data Science

Before starting your project you should work through the [Decision Tree for the Responsible Application of Artificial Intelligence ](https://www.aaas.org/ai2/projects/decision-tree-practitioners) provided by the [AAAS Center for Scientific Responsibility](https://www.aaas.org/programs/scientific-responsibility-justice).

This project has:

- [ ] Developed a list of possible solutions to the problem along with each solution’s benefits and limitations, including the relative risk of using AI in this application.
- [ ] Considered the training data, including procedures to periodically review the relevance and applicability of training data.
- [ ] Considered the tool itself, including a testing regimen and go/no-go review points
- [ ] Attempted to anticipate future risk and the various ways things could go wrong, legally, ethically, and morally. Researched analogous situations where automated decision-making has failed.

### Data Warnings

You are encouraged to apply warning logos depending on the context and data you are working with. The full set of warnings are available from [Data Hazards](https://datahazards.com/contents/data-hazards.html). Images are at standardised URLs, for example:

```
https://datahazards.com/_images/general-hazard.png
```

![General Hazard]([http://url/to/img.png](https://datahazards.com/contents/data-hazards.html))

🎯 Roadmap
---

### Checklist for setting up an online repository 

- [ ] Add a README file
- [ ] Add a [CONTRIBUTING](CONTRIBUTING.md) file
- [ ] Add a [LICENSE](LICENSE.md)
- [ ] Add a [Code of Conduct](CODE_OF_CONDUCT.md)
- [ ] Install [all-contributors](https://allcontributors.org/) bot
- [ ] .gitignore file (choose from a template)
- [ ] Issue templates
    - [ ] Optionally Install [Welcome/behavior](https://github.com/behaviorbot/welcome) bot (see The Turing Way [config](https://github.com/alan-turing-institute/the-turing-way/blob/main/.github/config.yml))
- [ ] Create a directory with files for project management (meetings, reports, proposals)
- [ ] Create a directory with files for communications
- [ ] Create a directory for research analysis
- [ ] Create a directory for research results/outcomes to share (?)
- [ ] Create a directory for ethics approval and project policies
- [ ] Create a directory with files for stakeholder's info and the nature of engagement
- [ ] Connect repo with Zenodo
- [ ] Add cff file for citation
- [ ] Add badges

♻️ License
---

This work is licensed under the MIT license (code) and Creative Commons Attribution 4.0 International license (for documentation).
You are free to share and adapt the material for any purpose, even commercially,
as long as you provide attribution (give appropriate credit, provide a link to the license,
and indicate if changes were made) in any reasonable manner, but not in any way that suggests the
licensor endorses you or your use with no additional restrictions.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="http://malvikasharan.github.io/"><img src="https://avatars.githubusercontent.com/u/5370471?v=4?s=100" width="100px;" alt="Malvika Sharan"/><br /><sub><b>Malvika Sharan</b></sub></a><br /><a href="#ideas-malvikasharan" title="Ideas, Planning, & Feedback">🤔</a> <a href="#content-malvikasharan" title="Content">🖋</a></td>
      <td align="center"><a href="https://github.com/EKaroune"><img src="https://avatars.githubusercontent.com/u/58147174?v=4?s=100" width="100px;" alt="Emma Karoune"/><br /><sub><b>Emma Karoune</b></sub></a><br /><a href="#ideas-EKaroune" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/alan-turing-institute/reproducible-project-template/commits?author=EKaroune" title="Documentation">📖</a></td>
      <td align="center"><a href="http://www.aleesteele.com"><img src="https://avatars.githubusercontent.com/u/18509789?v=4?s=100" width="100px;" alt="Anne Lee Steele"/><br /><sub><b>Anne Lee Steele</b></sub></a><br /><a href="#ideas-aleesteele" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/alan-turing-institute/reproducible-project-template/commits?author=aleesteele" title="Documentation">📖</a></td>
      <td align="center"><a href="https://github.com/vhellon"><img src="https://avatars.githubusercontent.com/u/93144591?v=4?s=100" width="100px;" alt="Vicky Hellon"/><br /><sub><b>Vicky Hellon</b></sub></a><br /><a href="#ideas-vhellon" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/alan-turing-institute/reproducible-project-template/commits?author=vhellon" title="Documentation">📖</a></td>
      <td align="center"><a href="http://jending.com"><img src="https://avatars.githubusercontent.com/u/5104098?v=4?s=100" width="100px;" alt="Jennifer Ding"/><br /><sub><b>Jennifer Ding</b></sub></a><br /><a href="#content-dingaaling" title="Content">🖋</a> <a href="https://github.com/alan-turing-institute/reproducible-project-template/commits?author=dingaaling" title="Documentation">📖</a> <a href="#ideas-dingaaling" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center"><a href="http://lappland.io"><img src="https://avatars.githubusercontent.com/u/51458?v=4?s=100" width="100px;" alt="Hilmar Lapp"/><br /><sub><b>Hilmar Lapp</b></sub></a><br /><a href="https://github.com/alan-turing-institute/reproducible-project-template/issues?q=author%3Ahlapp" title="Bug reports">🐛</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
