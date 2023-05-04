# ds4beginners
Welcome to the Data Science for Beginners course! This 5-week course is designed to provide you with a solid foundation in the fundamentals of data science. In this course, you will learn how to manipulate, analyze, and visualize data using Python and popular data science libraries. We will also introduce you to machine learning concepts and techniques.

# Course Outline
Please note that the course outline can be found on the course website <a href="https://sldatasc.github.io/" target="_blank">here</a>.

# Getting Started
To get started with this course, you will need to have Python and Jupyter Notebooks installed on your computer or your can use cloud-based notebboks like <a href="https://colab.research.google.com/" target="_blank">Google Colab</a>. You can find instructions on how to install them bellow.

## Installing Conda

To follow along with this course, you will need to install Conda, which is an open-source package management system and environment management system that can help you install and manage dependencies for your data science projects. Conda is available for Windows, Mac OSX, and Linux.

### Windows

To install Conda on Windows, you can follow these steps:

1. Download the Anaconda installer for Windows from the [Anaconda website](https://www.anaconda.com/download#download-section).
2. Double-click the installer to launch it.
3. Follow the instructions in the installer.

### Mac OSX
To install Conda on Mac OSX, you can follow these steps:

1. Download the Anaconda installer for Mac OSX from the [Anaconda website](https://www.anaconda.com/products/individual#download-section).
2. Double-click the installer to launch it.
3. Follow the instructions in the installer.

### Linux
To install Conda on Linux, you can follow these steps:
1. Download the Anaconda installer for Linux from the [Anaconda website](https://www.anaconda.com/products/individual#download-section).
2. Open a terminal and navigate to the directory where you downloaded the installer.
3. Run the following command to make the installer executable:

``` bash 
chmod +x Anaconda-latest-Linux-x86_64.sh
```
4. Run the installer with the following command:
```bash
./Anaconda-latest-Linux-x86_64.sh
```
5. Follow the instructions in the installer.
Once you have installed Conda, you can create a new environment for this course by running the following command:
```bash
conda env create -f environment.yml
```
or 
```bash 
conda create --name ds4beginners --file requirements.txt
```
This will create a new environment called ds4beginners with the dependencies listed in the requirements.txt file installed.

#### Activate environment
Activate the environment by running the following command:
```bash
conda activate ds4beginners
```

To get started with this course, you can follow these steps:

- Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/sldatasc/ds4beginners.git
```

- Navigate to the root directory of the repository.

```bash 
cd ds4beginners
```

- Install the necessary dependencies by running the following command:

```bash
pip install -r requirements.txt
```
- Once you have installed the dependencies, you can open Jupyter Notebook by running the following command:
```bash
jupyter notebook
```
- Navigate to the "notebooks" directory and open the Jupyter Notebooks for each week to start learning!

# Community
We encourage you to join our community forum [TBA], where you can ask questions, share your work, and interact with other learners.

# Contributors
This course was developed by [<a href="https://yusufbrima.github.io/" target="_blank">Yusuf Brima</a>] and [Moses Kargbo]. If you have any questions or feedback, please feel free to reach out to us.

# Acknowledgements
We would like to thank the open-source community for developing the tools and libraries that make this course possible. 

# Course Website
- <a href="https://sldatasc.github.io/" target="_blank">Course Website</a>

# License
This course is licensed under the MIT license. See the LICENSE file for more information.

<a href="" target="_blank"></a>