# Running LLMs Locally with Docker Model Runner

Materials for the "Running LLMs Locally with Docker Model Runner" workshop at the [ODSC AI West 2025](https://odsc.ai/) conference. This workshop is based on a set of tutorials from the [AIOps Newsletter](https://theaiops.substack.com/). 

The [Docker Model Runner](https://docs.docker.com/ai/model-runner/) (DMR) - a Docker Desktop feature that enables the run of Large Language Models natively with Docker Desktop.

Session info: https://odsc.ai/speakers-portfolio/running-llms-locally-with-docker-model-runner/


When 📆: October 30th, 2025

<figure>
 <img src="assets/bay_area_map.png" width="100%" align="center"/></a>
<figcaption> Bay Area 3D map (created with Midjourney)</figcaption>
</figure>

<br>
<br />



## Prerequisites

To be able to follow along with the workshop, you will need:
- Docker Desktop (on Mac version 4.40.0 and above, and on Windows version 4.41.0 and above) and Docker Engine on Linux
- Docker Hub account
- Hugging Face account (optional)
- OpenCode (optional)

## Python Environment

Throughout the workshop, we will demo how to use DMR with Python. If you are using Docker, this repo has Dev Containers settings, and you can run the workshop examples inside a container. Otherwise, you can use the requirements.txt file under the docker folder to set a local virtual environment using the below code using [UV](https://docs.astral.sh/uv/):

```shell
uv venv python-3.11-dev --python 3.11
```

Activate the environment:
``` shell
source python-3.11-dev/bin/activate
```
And install the required libraries
``` shell
uv pip install  --no-cache-dir -r docker/requirements.txt
```

## Workshop Outline
The workshop will cover the following topics:
- Settings - review how to set up the workshop prerequisites 
- Models - learn how to download LLMs from Docker Hub and Hugging Face
- Running models locally - review how to run LLMs locally via the CLI
- Python workflow - use the OpenAI Python SDK to call LLMs locally in Python
- Running OpenCode with DMR



## License

This tutorial is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/) License.
