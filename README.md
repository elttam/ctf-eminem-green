# Overview

**Title:** Eminem Green (Amityville)   
**Category:** Web  
**Flag:** `libctf{951ac412-2e5e-4ed0-9e7f-dbc384b84b1b}`  
**Difficulty:** Medium

# Usage

The following will pull the latest 'elttam/ctf-eminem-green' image from DockerHub, run a new container named 'libctfso-eminem-green', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-eminem-green \
  elttam/ctf-eminem-green:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-eminem-green' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-eminem-green:latest
```