## The Antgroup Open Source Project Template

This template is based on the [CFPB Open Source Project Template Instructions](https://github.com/cfpb/open-source-project-template), thanks to the CFPB for their work. Furthermore, we also provide the [Simplified Chinese(简体中文) version of this document](README_ZH.md).

1. Create a new project.
2. [Copy these files into the new project](#installation)
3. Update the README, replacing the contents below as prescribed.
4.  A formatted name can be provided for the documents if your documents have multi-language support. You can use the formatted form, which is `{name}_{language code}.{ext}`.
      - NOTICE: The language code lists can be [found here](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes). For instance, if the document is in Chinese, it is possible to use the name `README_ZH.md`.
      - We recommend that English be used as the primary language in documents and other contents.
      - A great README project that we may use as a reference is provided [here](https://github.com/matiassingers/awesome-readme).
5. Add any libraries, assets, or hard dependencies whose source code will be included
   in the project's repository to the _Exceptions_ section in the [TERMS](TERMS.md).
     - If no exceptions are needed, remove that section from TERMS.
7. If working with an existing code base, answer the questions on the [open source checklist](opensource-checklist.md)
8. Delete these instructions and everything up to the _Project Title_ from the README.
9. Write some great software and tell people about it.

> Keep the README fresh! It's the first thing people see and will make the initial impression.

## Installation

*Deprecated: this scirpt is outdated and will be rewriting in the future ([more](https://github.com/antgroup/open-source-project-template/issues/4)).*

To install all of the template files, run the following script from the root of your project's directory:

```
bash -c "$(curl -s https://raw.githubusercontent.com/CFPB/development/main/open-source-template.sh)"
```

----

# Project Title

**Description**:  Put a meaningful, short, plain-language description of what
this project is trying to accomplish and why it matters.
Describe the problem(s) this project solves.
Describe how this software can improve the lives of its audience.

Other things to include:

  - **Technology stack**: Indicate the technological nature of the software, including primary programming language(s) and whether the software is intended as standalone or as a module in a framework or other ecosystem.
  - **Status**:  Alpha, Beta, 1.1, etc. It's OK to write a sentence, too. The goal is to let interested people know where this project is at. This is also a good place to link to the [CHANGELOG](CHANGELOG.md).
  - **Links to production or demo instances**
  - Describe what sets this apart from related-projects. Linking to another doc or page is OK if this can't be expressed in a sentence or two.


**Screenshot**: If the software has visual components, place a screenshot after the description; e.g.,

![](https://raw.githubusercontent.com/cfpb/open-source-project-template/main/screenshot.png)


## Dependencies

Describe any dependencies that must be installed for this software to work.

This includes programming languages, databases or other storage mechanisms, build tools, frameworks, and so forth.
If specific versions of other software are required, or known not to work, call that out.

## Installation

Detailed instructions on how to install, configure, and get the project running.
This should be frequently tested to ensure reliability. Alternatively, link to
a separate [INSTALL](INSTALL.md) document.

## Configuration

If the software is configurable, describe it in detail, either here or in other documentation to which you link.

## Usage

Show users how to use the software.
Be specific.
Use appropriate formatting when showing code snippets.

## How to test the software

If the software includes automated tests, detail how to run those tests.

## Known issues

Document any known significant shortcomings with the software.

## Getting help

Instruct users how to get help with this software; this might include links to an issue tracker, wiki, mailing list, etc.

**Example**

If you have questions, concerns, bug reports, etc, please file an issue in this repository's Issue Tracker.

## Getting involved

This section should detail why people should get involved and describe key areas you are
currently focusing on; e.g., trying to get feedback on features, fixing certain bugs, building
important pieces, etc.

General instructions on _how_ to contribute should be stated with a link to [CONTRIBUTING](CONTRIBUTING.md).


----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. <del>[CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)</del> (deprecated)


----

## Credits and references

1. Projects that inspired you
2. Related projects
3. Books, papers, talks, or other sources that have meaningful impact or influence on this project
