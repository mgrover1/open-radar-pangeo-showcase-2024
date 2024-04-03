<img src="thumbnail.png" alt="thumbnail" width="300"/>

# The Open Radar Stack: Bringing Weather Radar Data into Pangeo

[![nightly-build](https://github.com/mgrover1/open-radar-pangeo-showcase-2024/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/mgrover1/open-radar-pangeo-showcase-2024/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/mgrover1/open-radar-pangeo-showcase-2024/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

## Motivation

(Add a few sentences stating why this cookbook will be useful. What skills will you, "the chef", gain once you have reached the end of the cookbook?)

## Authors

[Max Grover](https://github.com/mgrover1), [Kai Mühlbauer](https://github.com/kmuehlbauer), [Alfonso Ladino](https://github.com/aladino), [Scott Collis](https://github.com/scollis), [Zach Sherman](https://github.com/zssherman), [Bobby Jackson](https://github.com/rcjackson), [Joe O'Brien](https://github.com/jrobrien91)

### Contributors

<a href="https://github.com/mgrover1/open-radar-pangeo-showcase-2024/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=mgrover1/open-radar-pangeo-showcase-2024" />
</a>

## Structure

### Slide Presentation

[Slides related to the presentation!](notebooks/slides.md)

### Live Demo

[This is where things get fun... and we try things!]()

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "open-radar-pangeo-showcase-2024" with the title of your cookbooks)

1. Clone the `https://github.com/mgrover1/open-radar-pangeo-showcase-2024` repository:

   ```bash
    git clone https://github.com/mgrover1/open-radar-pangeo-showcase-2024.git
   ```

1. Move into the `open-radar-pangeo-showcase-2024` directory
   ```bash
   cd open-radar-pangeo-showcase-2024
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate open-radar-pangeo-showcase-2024-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
