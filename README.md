# MisinfoMe-API

This repository contains the OpenAPI declaration for the [API of MisinfoMe](http://socsem.kmi.open.ac.uk/misinfo/api/) and related APIs.
In particular the following APIs are supported:
* Misinfo.me base API: http://socsem.kmi.open.ac.uk/misinfo/api/
* Misinfo.me parametrised credibility API (not deployed yet)
* Misinfo.me Claim identification API (not deployed yet)

## API Specification
Each API is deployed as a separate service:

| API                      | Description                                    | Specification                                                   | Maintainer | Deployment                                            |
| ------------------------ |------------------------------------------------| ----------------------------------------------------------------| -----------|-------------------------------------------------------|
| Base API                 | Misinfome general API (UI/Legacy Credibility). | [misinfome-api.yaml](misinfome-api.yaml)                        | Martino    |[Live API](http://socsem.kmi.open.ac.uk/misinfo/api/)  |
| Parametrised Credibility | Computational Graph Credibility API.           | [misinfome-credibility-api.yaml](misinfome-credibility-api.yaml)| Greg       |-                                                      |
| Claim ID API                | Claim identification and emmbedding API.    | [misinfome-claimid-api.yaml](misinfome-claimid-api.yaml)        | Greg       |-                                                      |
