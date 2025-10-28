# Running LLMs Locally with Docker Model Runner

Materials for the "Running LLMs Locally with Docker Model Runner" workshop at the [ODSC AI West 2025](https://odsc.ai/) conference. 

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
- Docker Desktop (version 4.48.0 and above) is installed on your computer
- Docker Hub account
- Hugging Face account (optional)

## Environment

```shell
uv venv python-3.11-dev --python 3.11
```


``` shell
source python-3.11-dev/bin/activate
```

``` shell
uv pip install  --no-cache-dir -r docker/requirements.txt
```

## Workshop Outline
The workshop will cover the following topics:
- Settings - review how to set up the workshop prerequisites 
- Models - learn how to download LLMs from Docker Hub and Hugging Face
- Running models locally - review how to run LLMs locally via the CLI
- Python workflow - use the OpenAI Python SDK to call LLMs locally in Python


## License

This tutorial is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/) License.
