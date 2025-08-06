# Web Map / Feature Services Cookbook

<img src="thumbnail.png" alt="thumbnail" width="300"/>

[![nightly-build](https://github.com/ProjectPythia/web-map-feature-services-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/web-map-feature-services-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/653301659.svg)](https://zenodo.org/badge/latestdoi/653301659)

This Project Pythia Cookbook covers retrieving and using web map / feature services to help provide the necessary spatial context to your data.

Now using MyST!

## Motivation

By leveraging web map / feature services, users can easily access pre-processed data layers, utilize ready-to-use tiles, and benefit from production-level data that is continuously updated. This streamlines the data acquisition process and enables users to focus on their analysis tasks rather than data processing.

- Pre-processed Data: Web map services provide access to a wide range of pre-processed geospatial data layers. This eliminates the need for users to perform data processing tasks themselves, saving time and effort.

- Ready-to-Use Tiles: Users can simply fetch the tiles from the web map services and use them as a reference or overlay in their analysis. This makes it convenient to integrate the data into their own applications without the need to handle complex data processing workflows.

- Production-Level Data: Web map services are often deployed at production level, ensuring that the data is up-to-date and near real-time. This is particularly advantageous for applications that require the latest information, such as weather monitoring or real-time asset tracking.

## Authors

[Andrew Huang](https://github.com/ahuang11)

### Contributors

<a href="https://github.com/ProjectPythia/web-map-feature-services-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/web-map-feature-services-cookbook" />
</a>

## Structure

This cookbook is broken up into two main sections - “Foundations” and “Example Workflows.”

### Foundations

The foundational content includes:

- Web Map Services
- Web Feature Services

### Example Workflows

Example workflows include:

- NASA Earthdata GIBS Explorer

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

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/web-map-feature-services-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/web-map-feature-services-cookbook.git
   ```

1. Move into the `web-map-feature-services-cookbook` directory
   ```bash
   cd web-map-feature-services-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate web-map-feature-services-cookbook-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
