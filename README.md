# Docker_and_Reproducibility
Turin, 13-14 Jun 2019

## Course  introduction
Bioinformatics analysis typically integrate a large number of different tools, reference data to elaborate the input data and derive results. Reproducing the same analysis by other researchers is often a hard task as many pieces of the puzzle are missing from the used methodology.
While the raw datasets are generally available; a clear workflow detailing the results reproducibility is often missing. Indeed, a simple list of tools used in the workflow could be not enough to guarantee the result reproducibility: different releases of the same tools or/and of the system libraries (exploited by such tools) might lead to sneaky reproducibility issues. The biggest obstacle in computational reproducibility is then to create a reliable, standalone, multiplatform and lightweight-working environment in which all the computational needs for a study are installed and frozen. Virtualisation and containerisation are the two approaches proposed to address this issue.

Virtual machines are very good at isolating system resources and entire working environments, while , containers’ philosophy is to isolate only individual applications, not the entire system. Thus, containers are a lightweight fast and scalable alternative to Virtual machines when an completely isolated execution is not mandatory.

Docker is a container framework for Linux that allows a developer to make easier the creation, deployment, and execution of applications by using containers.
Recently it is becoming a promising approach to computational biology research reproducibility by:

Saving time and expenses on human and computational resources allocated to already performed analysis;
  - Boosting communication between computational biologists working on similar topics;
  - Enhancing transparency within the community;
  - Granting open access computational knowledge to the community.
During the workshop the participant learn the core concepts of Docker and how to easily embed bioinformatic pipelines/workflows into a docker container.
