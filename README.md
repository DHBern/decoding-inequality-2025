# Decoding Inequality 2025

This repository contains the materials for the course "Decoding Inequality: Kritische Perspektiven auf Machine Learning und gesellschaftliche Ungleichheit" held at the University of Bern in the spring semester 2025. The data in this repository is openly available to everyone and is intended to support reproducible research.

[![GitHub issues](https://img.shields.io/github/issues/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/issues)
[![GitHub forks](https://img.shields.io/github/forks/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/network)
[![GitHub stars](https://img.shields.io/github/stars/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/stargazers)
[![Code license](https://img.shields.io/github/license/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/blob/main/LICENSE-AGPL.md)
[![Data license](https://img.shields.io/github/license/DHBern/decoding-inequality-2025.svg)](https://github.com/DHBern/decoding-inequality-2025/blob/main/LICENSE-CCBYSA.md)
[![DOI](https://zenodo.org/badge/ZENODO_RECORD.svg)](https://zenodo.org/badge/latestdoi/ZENODO_RECORD)

<!-- ## Repository Structure

The structure of this repository follows the [Advanced Structure for Data Analysis](https://the-turing-way.netlify.app/project-design/project-repo/project-repo-advanced.html) of _The Turing Way_ and is organized as follows:

- `analysis/`: scripts and notebooks used to analyze the data
- `assets/`: images, logos, etc. used in the README and other documentation
- `build/`: scripts and notebooks used to build the data
- `data/`: data files
- `docs/`: documentation for the data and the repository
- `project-management/`: project management documents (e.g., meeting notes, project plans, etc.)
- `src/`: source code for the data (e.g., scripts used to collect or process the data)
- `test/`: tests for the data and source code
- `syllabus.qmd`: a report describing the analysis of the data

## Data Description

- TODO Describe the data in this repository, including what it represents, how it was collected or obtained, any preprocessing or cleaning that was done, and any limitations or potential biases.
- TODO Data models, including field names, descriptions, and controlled values, should be clearly documented in a static document that is maintained with the data and is part of the products.
- TODO All rights and intellectual property issues should be clearly documented. Where possible, data and products should be released under open licenses (Creative Commons, GNU, BSD, MPL).

## Use

These data are openly available to everyone and can be used for any research or educational purpose. If you use this data in your research, please cite as specified in [CITATION.cff](CITATION.cff). The following citation formats are also available through _Zenodo_:

- [BibTeX](https://zenodo.org/record/ZENODO_RECORD/export/hx)
- [CSL](https://zenodo.org/record/ZENODO_RECORD/export/csl)
- [DataCite](https://zenodo.org/record/ZENODO_RECORD/export/dcite4)
- [Dublin Core](https://zenodo.org/record/ZENODO_RECORD/export/xd)
- [DCAT](https://zenodo.org/record/ZENODO_RECORD/export/dcat)
- [JSON](https://zenodo.org/record/ZENODO_RECORD/export/json)
- [JSON-LD](https://zenodo.org/record/ZENODO_RECORD/export/schemaorg_jsonld)
- [GeoJSON](https://zenodo.org/record/ZENODO_RECORD/export/geojson)
- [MARCXML](https://zenodo.org/record/ZENODO_RECORD/export/xm)

_Zenodo_ provides an [API (REST & OAI-PMH)](https://developers.zenodo.org/) to access the data. For example, the following command will return the metadata for the most recent version of the data

```bash
curl -i https://zenodo.org/api/records/ZENODO_RECORD
``` -->

## Installation

Install [Node.js](https://nodejs.org/en/) and run the following commands in the root directory of the repository:

```bash
npm install
npm run prepare
```

## Use

Check that all files are properly formatted.

```bash
npm run check
```

Format all files.

```bash
npm run format
```

Run the wizard to write meaningful commit messages.

```bash
npm run commit
```

Run the wizard to create a CHANGELOG.md.

```bash
npm run changelog
```

Preview the documentation.

```bash
quarto preview
```

## Support

This project is maintained by [@DHBern](https://github.com/DHBern). Please understand that we can't provide individual support via email. We also believe that help is much more valuable when it's shared publicly, so more people can benefit from it.

| Type                                   | Platforms                                                                            |
| -------------------------------------- | ------------------------------------------------------------------------------------ |
| 🚨 **Bug Reports**                     | [GitHub Issue Tracker](https://github.com/DHBern/decoding-inequality-2025/issues)    |
| 📊 **Report bad data**                 | [GitHub Issue Tracker](https://github.com/DHBern/decoding-inequality-2025/issues)    |
| 📚 **Docs Issue**                      | [GitHub Issue Tracker](https://github.com/DHBern/decoding-inequality-2025/issues)    |
| 🎁 **Feature Requests**                | [GitHub Issue Tracker](https://github.com/DHBern/decoding-inequality-2025/issues)    |
| 🛡 **Report a security vulnerability** | See [SECURITY.md](SECURITY.md)                                                       |
| 💬 **General Questions**               | [GitHub Discussions](https://github.com/DHBern/decoding-inequality-2025/discussions) |

## Roadmap

- [x] Syllabus with reading list
- [ ] Slides for lectures
- [ ] Additional resources (e.g., links to papers, blog posts, etc.)
- [ ] Blog posts, posters, or other materials produced by students

## Contributing

All contributions to this repository are welcome! If you find errors or problems with the data, or if you want to add new data or features, please open an issue or pull request. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Versioning

We use [SemVer](http://semver.org/) for versioning. The available versions are listed in the [tags on this repository](https://github.com/DHBern/decoding-inequality-2025/tags).

## Authors and acknowledgment

- **Digital Humanities University of Bern** - _Initial work_ - [DHBern](https://github.com/DHBern)
- **Rachel Huber** - _Instructor_ - [HistoRaHub](https://github.com/HistoRaHub)
- **Moritz Mähr** - _Instructor_ - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/DHBern/decoding-inequality-2025/graphs/contributors) who contributed to this project.

## License

The data in this repository is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) License - see the [LICENSE-CCBYSA](LICENSE-CCBYSA.md) file for details. By using this data, you agree to give appropriate credit to the original author(s) and to indicate if any modifications have been made.

The code in this repository is released under the GNU Affero General Public License v3.0 - see the [LICENSE-AGPL](LICENSE-AGPL.md) file for details. By using this code, you agree to make any modifications available under the same license.
