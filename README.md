# BRL Chicken 2D Navigation

The `brl_chicken_2dnav` package is a ROS-based navigation system designed for 2D environments. It utilizes the `move_base` package for path planning and navigation, along with AMCL for localization.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the package directory:**

   ```bash
   cd ../brl_issac_ws
   ```

3. **Build the package:**

   ```bash
   catkin_make
   ```

4. **Source the setup file:**

   ```bash
   source devel/setup.bash
   ```

## Usage

To launch the navigation system, use the following command:
   ```bash
   roslaunch brl_chicken_2dnav brl_move_base.launch
   ```

## Configuration

Configuration files for the navigation system can be found in the `config` directory. These files allow you to customize parameters for the `move_base` and AMCL nodes.

## Dependencies

The package depends on the following ROS packages:

- `move_base`
- `navigation`
- `pointcloud_to_laserscan`

Ensure these packages are installed and available in your ROS workspace.

## License

This project is licensed under the [TODO] License - see the `LICENSE` file for details.



