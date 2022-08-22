# openGCAS - open Ground Collision Avoidance System

![Coveralls GitHub](https://img.shields.io/coveralls/github/FAA-VAIL-Project/openGCA.svg)
![GitHub (Pre-)Release](https://img.shields.io/github/v/release/FAA-VAIL-Project/openGCAS?include_prereleases)
![GitHub (Pre-)Release Date](https://img.shields.io/github/release-date-pre/FAA-VAIL-Project/openGCAS)
![GitHub commits since latest release](https://img.shields.io/github/commits-since/FAA-VAIL-Project/openGCAS/0.9.6)

openGCAS is an open source aviation safety system designed to help aircraft avoid flight into the ground or terrain.  openGCAS works by evaluating current aircraft state information, predicting a possible escape trajectory, comparing the altitude of that trajecotry to the altitude of the ground at that location, and evaluating the results.  If the trajectory is found to come too close to the terrain at any point in the predicted trajectory, openGCAS commands an avoidance manuver to be preformed.  openGCAS was created to help save the hundreds of pilots and passengers that die every year from this type of accident. 

Please see the **[Documentation](https://faa-vail-project.github.io/openGCAS/)** for more detailed information.

## 1. Features

**TODO** = listing of the most important features of the software openGCAS -

## 2. Directory and File Structure of this Repository

### 2.1 Directories

| Directory         | Content                                               |
|-------------------|-------------------------------------------------------|
| .github/workflows | [GitHub Action](https://github.com/actions) workflows |
| data              | non-source files, like INI files                      |
| docs              | documentation files                                   |
| include           | public headers                                        |
| src               | source files and private headers                      |
| tests             | test cases                                            |

### 2.2 Files

| File          | Functionality                                                           |
|---------------|-------------------------------------------------------------------------|
| .gitignore    | Configuration of files and folders to be ignored.                       |
| CMakeList.txt | CMake configuration file.                                               |
| Dockerfile    | Docker image configuration file.                                        |
| LICENSE.md    | Text of the licence terms.                                              |
| MakefileDocs  | Definition of documentation task to be excuted with the `make` command. |
| mkdocs.yml    | Configuration file for [MkDocs](https://github.com/mkdocs/mkdocs/).     |
| Pipfile       | Definition of the Python package requirements.                          |
| Pipfile.lock  | Definition of the specific versions of the Python packages.             |
| README.md     | This file.                                                              |

### 2.3 Build and run (docker ubuntu:focal)

```sh
docker build -t faa_vail_opengcas:latest .
docker run --rm -it faa_vail_opengcas:latest
```

## 3. Support

If you need help with **openGCA**, do not hesitate to get in contact with us!

- For questions and high-level discussions, use **[Discussions](https://github.com/FAA-VAIL-Project/openGCA/discussions)** on GitHub.
- To report a bug or make a feature request, open an **[Issue](https://github.com/FAA-VAIL-Project/openGCA/issues)** on GitHub.

Please note that we may only provide support for problems / questions regarding core features of **openGCA**.
Any questions or bug reports about features of third-party themes, plugins, extensions or similar should be made to their respective projects.
But, such questions are **not** banned from the **[Discussions](https://github.com/FAA-VAIL-Project/openGCA/discussions)**.

Make sure to stick around to answer some questions as well!

## 4. Links

- **[Official Documentation](https://FAA-VAIL-Project.github.io/openGCA)**
- **[Release Notes](https://FAA-VAIL-Project.github.io/openGCA/release_notes)**
- **[Discussions](https://github.com/FAA-VAIL-Project/openGCA/discussions)** (Third-party themes, recipes, plugins and more)

## 5. Contributing to openGCA

The **openGCA** project welcomes, and depends on, contributions from developers and users in the open source community.
Please see the **[Contributing Guide](https://FAA-VAIL-Project.github.io/openGCA/contributing)** for
information on how you can help.

## 6. Code of Conduct

Everyone who interacts in the **openGCA** project's codebase, issue trackers, and discussion forums is expected to follow the **[Code of Conduct](https://FAA-VAIL-Project.github.io/openGCA/code_of_conduct)**.

## 7. License

**[TODO](https://FAA-VAIL-Project.github.io/openGCA/license)**
