# Project Title

<a href="http://www.kios.ucy.ac.cy" style="display:inline-block;">
<img src="https://www.kios.ucy.ac.cy/wp-content/uploads/2021/07/Logotype-KIOS.svg" height="80"/>
</a>
<a href="https://waterfutures.eu/" style="display:inline-block; margin-left:40px;">
<img src="https://waterfutures-live-55f6525157a0459986227-3cc9563.divio-media.org/documents/logo-vertical-color.svg" height="80"/>
</a>
<p>

[![pypi](https://img.shields.io/pypi/v/epyt.svg)](https://pypi.org/project/epyt/)
[![Downloads](https://static.pepy.tech/badge/epyt)](https://pepy.tech/project/epyt)
[![Downloads](https://static.pepy.tech/badge/epyt/month)](https://pepy.tech/project/epyt)
[![build](https://github.com/OpenWaterAnalytics/EPyT/actions/workflows/build_tests.yml/badge.svg)](https://github.com/OpenWaterAnalytics/EPyT/actions/workflows/build_tests.yml)
[![Docs](https://img.shields.io/badge/docs-latest-blue)](http://wateranalytics.org/EPyT/)
[![DOI](https://joss.theoj.org/papers/10.21105/joss.05947/status.svg)](https://doi.org/10.21105/joss.05947)
[![license](https://img.shields.io/pypi/l/epyt.svg)](https://github.com/KIOS-Research/EPyT/blob/main/LICENSE.md)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.831493.svg)](https://doi.org/10.5281/zenodo.831493) [![View OpenWaterAnalytics/EPANET-Matlab-Toolkit on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/25100-openwateranalytics-epanet-matlab-toolkit)

---

## Project Description
Short and clear description of the software and its purpose.

e.g. 
The `EPANET-Python Toolkit` is an open-source software, originally developed by the [KIOS Research and Innovation Center of Excellence, University of Cyprus](http://www.kios.ucy.ac.cy/) which operates within the Python environment, for providing a programming interface for the latest version of [EPANET](https://github.com/OpenWaterAnalytics/epanet), a hydraulic and quality modeling software created by the US EPA, with Python, a  high-level technical computing software. The goal of the EPANET Python Toolkit is to serve as a common programming framework for research and development in the growing field of smart water networks.

The `EPANET-Python Toolkit` features easy to use commands/wrappers for viewing, modifying, simulating and plotting results produced by the EPANET libraries.  

For support, please use the OWA community forum: https://github.com/orgs/OpenWaterAnalytics/discussions

## Table of Contents

- [Project Description](#project-description)
- [Table of Contents](#table-of-contents)
- [How to cite](#how-to-cite)
- [Requirements](#requirements)
- [How to install](#how-to-install)
- [How to use the toolkit / Usage](#how-to-use-the-toolkit--usage)
- [How to fix/report bugs](#how-to-fixreport-bugs)
- [License](#license)
- [Contributors](#contributors)
- [Contributing](#contributing)
- [Reproducibility](#reproducibility)
- [Repository Structure](#repository-structure)
- [Publications](#publications)


## How to cite

If you use this software in academic work, please cite using the provided `CITATION.cff` file or the following format:

Kyriakou, M. S., Demetriades, M., Vrachimis, S. G., Eliades, D. G., & Polycarpou, M. M. (2023). EPyT: An EPANET-Python Toolkit for Smart Water Network Simulations. Journal of Open Source Software, 8(92), 5947. https://doi.org/10.21105/joss.05947

```
@article{Kyriakou2023,
author = {Kyriakou, Marios S. and Demetriades, Marios and Vrachimis, Stelios G. and Eliades, Demetrios G. and Polycarpou, Marios M.},
doi = {10.21105/joss.05947},
journal = {Journal of Open Source Software},
month = dec,
number = {92},
pages = {5947},
title = {{EPyT: An EPANET-Python Toolkit for Smart Water Network Simulations}},
url = {https://joss.theoj.org/papers/10.21105/joss.05947},
volume = {8},
year = {2023}
}
```
&uparrow; [Back to top](#table-of-contents)

## Requirements
* Python >=3.9
* Windows, OSX or Linux
* [EPANET 2.2](https://github.com/OpenWaterAnalytics/epanet)
* Operating System: Windows / Linux / macOS
* Language / Platform: e.g. Python, MATLAB, C++
* Dependencies: list required libraries or tools

&uparrow; [Back to top](#table-of-contents)

## How to install

```bash
pip install epyt
git clone https://github.com/KIOS-Research/project-name.git
cd project-name
```

Add any project-specific installation steps if needed.

&uparrow; [Back to top](#table-of-contents)


## How to use the toolkit / Usage

Basic example:

```bash
python main.py / matlab main.m
```

Provide additional usage instructions or configuration examples if required.

&uparrow; [Back to top](#table-of-contents)

## How to fix/report bugs

To fix a bug `Fork` the `EPyT`, `Edit` the code and make the appropriate change, and then `Pull` it so that we evaluate it. 

Keep in mind that some bugs may exist in the `EPANET` libraries, in case you are not receiving the expected results.

&uparrow; [Back to top](#table-of-contents)

## License
* `EPANET`: Public Domain
* `EPANET-Python Toolkit (EPyT)`: EUPL
This software is released under the **[License Name]**  
(e.g. European Union Public License v1.2 – EUPL-1.2)

&uparrow; [Back to top](#table-of-contents)

## Contributors
- Name Surname, KIOS Research and Innovation Center of Excellence, University of Cyprus
- Name Surname, KIOS Research and Innovation Center of Excellence, University of Cyprus

&uparrow; [Back to top](#table-of-contents)

## Contributing
If you want to contribute, please check out our [Code of Conduct](https://github.com/KIOS-Research/EPyT/blob/dev/CODE_OF_CONDUCT.md). Everyone is welcome to contribute whether reporting a new [issue](https://github.com/KIOS-Research/EPyT/issues), suggesting a new feature, or writing code. If you want to contribute code, you can create a new fork in the repo to your own account. Make your commits on your dev branch (based on dev) and when you are finished then you can create a [pull request](https://github.com/KIOS-Research/EPyT/pulls) to test the code and discuss your changes.

&uparrow; [Back to top](#table-of-contents)

## Reproducibility
Scripts and data required to reproduce results and figures are included in this repository.  
Refer to the `/scripts` or `/examples` directory for step-by-step execution.

&uparrow; [Back to top](#table-of-contents)


## Repository Structure

```text
project-name/
├── src/          # Source code
├── data/         # Datasets
├── scripts/      # Experiment / utility scripts
├── examples/     # Usage examples
├── results/      # Generated outputs
├── figures/      # Figures and plots
├── CITATION.cff
├── LICENSE
└── README.md
```

&uparrow; [Back to top](#table-of-contents)

## Publications
- Paper Title, Journal/Conference, Year — DOI: XXXXX  
- Paper Title, Journal/Conference, Year — DOI: XXXXX

&uparrow; [Back to top](#table-of-contents)


