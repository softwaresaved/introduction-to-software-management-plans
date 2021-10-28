# ELIXIR Software Management Plan Template

Reused under a CC BY 4.0 International license from https://github.com/elixir-europe/smp 

### Accessibility / License

|||
|--- |--- |
|1) How can the software be accessed by third parties? | checklist |
| | Publicly available (e.g. GitHub, via URL, etc.) |
| | Not relevant/applicable to me |
| | Other |
| 2) Software without a license cannot be used by others. Does your software have a license? | Yes/No |
| 3) If yes, what is the license of your software? | SPDX List + Other + NA |



### Documentation


||||
|--- |--- |--- |
|1) What type of documentation is available, provided with the software and delivered under the same conditions? Please provide a URL (when available).|checklist|Please provide the corresponding URL, if available|
||User documentation||
||Programmers documentation||
||API documentation||
||README file||
||Release notes||
||Docstring/comments in the source code||
||CHANGELOG||
||Other (for more than one, please add multiple rows)||
||None||
|2) Is the purpose of the software stated in the documentation?|Yes/No||
|3) Does the documentation describe how to|test the software|Yes/No|
||use the software|Yes/No|
||build the software|Yes/No/NA|
||deploy the software|Yes/No/NA|
||install the software|Yes/No/NA|


### Testing


||||||
|--- |--- |--- |--- |--- |
|1) What type of testing do you use?|||||
||None|Yes||No|
||Unit|Yes (Manual)|Yes (Automatic)|No|
||Integration|Yes (Manual)|Yes (Automatic)|No|
||Functional|Yes (Manual)|Yes (Automatic)|No|
||End-to-end|Yes (Manual)|Yes (Automatic)|No|
||Linting|Yes (Manual)|Yes (Automatic)|No|
||Regression|Yes (Manual)|Yes (Automatic)|No|
||Frontend - GUI|Yes (Manual)|Yes (Automatic)|No|
||Other (e.g.)||||
|2) Are sample data and/or parameters that can be used to test the software available with the source code?|Yes|No|NA||


### Interoperability


|||||
|--- |--- |--- |--- |
|1) Do you use existing and standard input/output formats?|Yes|Yes (partially)|No|
|If yes (either all, or partial), please select the standards you are using from the list. If it’s not listed, please use the [FAIRsharing](https://fairsharing.org/) registry to provide both name and URL. If it’s not listed in FAIRsharing, please provide a name and a URL that is as machine actionable as possible.|Name (for each standard)|URL (for each standard)|Description (optional) (for each standard)|


### Versioning

||||
|--- |--- |--- |
|1) Do you use a version control system?|Yes|No|
|2) What version control system do you use?|Multiple selection with Other as Text||
||Git||
||Mercurial||
||Subversion||
||CVS||
||Other||
|3) Do you use Semantic Versioning (for more information go here: https://semver.org/)?|Yes|No|

### Reproducibility

||||
|--- |--- |--- |
|1) Do you provide releases of your software?|Yes|No|
|2) How do you define language-specific dependencies of your software and their version? For instance Maven (for Java), requirements.txt or environment.yml (Python), package.json (JS)|Text|NA|
|3) How do you capture the environment (operating system, system-level libraries) necessary to run the software (e.g. containers, conda, virtual machine)?|||
|4) Do you provide input and output examples that can be used to reproduce the functioning of your software?|Yes|No|
|If yes, where can they be found?|URL - Please provide the URL, if available||
|5) Do you state how to report bugs and/or usability problems by the software user(s)? This could be a simple sentence in the software documentation, stating an email, or an issue tracker, or a direct messaging protocol, or even a statement that bug reporting/issues are not supported.|Yes|No|


### Recognition

||||
|--- |--- |--- |
|1) Do you include citation information (i.e. how to cite your software in the form of citation.cff, codemeta.json or bibtex)?|Yes|No|
|2) Do the releases have a persistent global unique identifier (such as release on Zenodo with DOI, snapshot or/and release referenced on Software Heritage with SWHID)? For more information on PIDs and the differences between the various types (intrinsic, extrinsic, etc), please see [here](https://www.softwareheritage.org/2020/07/09/intrinsic-vs-extrinsic-identifiers/).|Yes|No|
|3) Does the citation information contain ORCIDs of (at least one of) the authors|Yes|No|
|4) Is the software registered in a domain-specific registry|Yes|No|
|If yes, please list the corresponding registries (Name and URL for each)|Name and URL|NA|
