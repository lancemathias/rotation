<div id="top"></div>



<!-- ABOUT THE PROJECT -->
## 3D Rotation Visualizer

Visualization of how equatorial and alt-az telescope mounts work to track stars in the sky, showing equatorial and declination adjustment over time, demonstrating how either tracking schema can be used to track any motion over a 3D ball.  
Also uses some nifty quaternion math.

![tracker_animation](https://github.com/lancemathias/rotation/raw/main/images/tracking.gif)

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [numpy](https://numpy.org)
* [numpy-quaternion](https://pypi.org/project/numpy-quaternion/)
* [matplotlib](https://matplotlib.org)

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
Some cells create Matplotlib animations in the Jupyter notebook, which can be saved as `.gif`s.  
Also provides plot of the declination axis over time, which tells us how far we are from equatorial tracking.  

<p align="right">(<a href="#top">back to top</a>)</p>

