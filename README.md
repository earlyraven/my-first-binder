# my-first-binder
Testing out binderization with the mybinder.org site.

## Introduction
This is a project that demonstrates how to make a GitHub repository's project accessible to anyone with just a web browser. It includes a simple "hello world" script written in Python, which can be run locally or remotely via a Binder environment.

## Features
* Simple "hello world" script that can be run locally or remotely.

## Installation & Usage
The local option will require python 3 and pip.  The remote option will only require a web browser.

### Local install & run:
Open command terminal and write:

```git clone <repo-link>```

```cd my-first-binder```

```python hello.py```

### Remote install & run:
Remote installation is handled automatically by BinderHub. Click the following link to launch the remote virtual environment.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/earlyraven/my-first-binder/HEAD)
Within the environment, open up the Python 3 command line and run the following command:
python hello.py

## Credits
Thanks to the following for their contributions to the project:
### Infrastructure
BinderHub: The BinderHub Team, Thanks for providing the infrastructure that made it possible to run our project in an online virtual environment. Visit them at https://mybinder.org to learn more.
### Libraries
Numpy: An array-processing package used in the project. Visit https://numpy.org/ to learn more.
### Resources
"The Turing Way" by The Turing Way Community (Accessed on April 6, 2023) is licensed under CC BY 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by/4.0/.
  - "Zero-to-Binder" by The Turing Way Community (Accessed on April 6, 2023) is licensed under CC BY 4.0 and was used as a reference for setting up the project environment using Binder. The article can be found at https://the-turing-way.netlify.app/communication/binder/zero-to-binder.html.  Thanks for this wonderful guide!

All external resources are used under their respective licenses.

## License
See LICENSE file in this repository.
