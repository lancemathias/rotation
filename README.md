<div id="top"></div>



<!-- ABOUT THE PROJECT -->
## About The Project

3D visualization of an equatorial mounted telescope tracking a moving star. Provides visualization for both polar-aligned equatorial mounts and misaligned equatorial mounts, along with plot of the required movement to stay on target.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [numpy](https://numpy.org)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->

### Prerequisites

Requires pipenv to install dependencies.

  ```sh
  pip install pipenv
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/lancemathias/rotation.git
   ```
2. Install pipenv depenencies from pipfile
   ```sh
   pipenv install 
   ```
3. Select the `rotation` kernel in Jupyter notebook.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

The cells in the Jupyter notebook have functions useful for visualizing star position and tracker deviation over time.
The coordinates of the star in question or the alignment of the tracker can be edited in their respective cells.
Some cells create Matplotlib animations in the Jupyter notebook, such as the one below:

![tracker_animation](https://github.com/lancemathias/rotation/tree/main/images/tracking.gif)

<p align="right">(<a href="#top">back to top</a>)</p>

