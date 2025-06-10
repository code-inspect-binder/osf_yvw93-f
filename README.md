# Executable Environment for OSF Project [yvw93](https://osf.io/yvw93/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Response Surface Analysis in Personality and Social Psychology: Checklist and Clarifications for the Case of Congruence Hypotheses

**Project Description:**
> Response Surface Analysis (RSA) enables researchers to test complex psychological effects, for example, whether the congruence of two psychological constructs is associated with higher values in an outcome variable. RSA is increasingly applied in the personality and social psychological literature, but the validity of published results has been challenged by some persistent oversimplifications and misconceptions. Here, we describe the mathematical fundamentals required to interpret RSA results, and we provide a checklist for correctly identifying congruence effects. We clarify two prominent fallacies by showing that the test of a single RSA parameter cannot indicate a congruence effect, and when there is a congruence effect, RSA cannot indicate whether a predictor mismatch in one direction (e.g., overestimation of one’s intelligence) is better or worse than a mismatch in the other direction (underestimation). We hope that this contribution will further enhance the validity and strength of empirical studies that apply this powerful approach.

Humberg, S., Nestler, S., &amp; Back, M. D. (2019). Response Surface Analysis in Personality and Social Psychology: Checklist and Clarifications for the Case of Congruence Hypotheses. Social Psychological and Personality Science, 10(3), 409–419. doi:10.1177/1948550618757600

Here, we provide you with additional materials to this article. 

The folder "Example R-Code" contains the simulated data used in the manuscript, and example R-code that guides readers through the test of congruence effects.

The folder "OSF-Materials" contains:
- p-values and confidence intervals of the example analyses reported in the manuscript (OSF-Material A), 
- a recap of the interpretation of quadratic equations (OSF-Material B), 
- the proofs of mathematical statements provided in the manuscript or in the OSF materials (OSF-Materials C, E, and F), 
- and information on RSA variants and more advanced response surface methodology (OSF-Material D). 

**Original OSF Page:** [https://osf.io/yvw93/](https://osf.io/yvw93/)

---

**Important Note:** The contents of the `yvw93_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## flowR Integration

This version of the repository has the **[flowR Addin](https://github.com/flowr-analysis/rstudio-addin-flowr)** preinstalled. flowR allows visual design and execution of data analysis workflows within RStudio, supporting better reproducibility and modular analysis pipelines.

To use flowR, open the project in RStudio and go to `Addins` > `flowR`.

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_yvw93-f/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_yvw93-f/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `yvw93_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

### Pull the Docker Image

```bash
docker pull meet261/repo2docker-yvw93-f:latest
```

### Launch RStudio Server

Run the container (with a name, e.g. `rstudio-dev`):
```bash
docker run -it --name rstudio-dev --platform linux/amd64 -p 8888:8787 --user root meet261/repo2docker-yvw93-f bash
```

Inside the container, start RStudio Server with no authentication:
```bash
/usr/lib/rstudio-server/bin/rserver --www-port 8787 --auth-none=1
```

Then, open your browser and go to: [http://localhost:8888](http://localhost:8888)

> **Note:** If you're running the container on a remote server (e.g., via SSH), replace `localhost` with your server's IP address.
> For example: `http://<your-server-ip>:8888`

## Looking for the Base Version?

For the original Binder-ready repository **without flowR**, visit:
[osf_yvw93](https://github.com/code-inspect-binder/osf_yvw93)

