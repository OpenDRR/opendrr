([Français](LISEZMOI.md))

# Parent repository for the Open Disaster Risk Reduction Platform

The OpenDRR platform is middleware between hazard or risk modeling environments like [OpenQuake](https://www.globalquakemodel.org/openquake) and end users who need to understand and evaluate risk to make economic and policy decisions. The end-user interface, launched as [RiskProfiler](https://www.riskprofiler.ca/), operates as a web application using standard web browsers in desktop, tablet or hand-held device environments.

Development and execution of hazard and risk assessment models is a separate concern, outside of the OpenDRR system. OpenDRR will receive output from these models as input, using one or more interfaces and interchange formats based on existing standards or on specifications developed by the implementation team if no standards meet requirements.

## Download data
* https://opendrr.github.io/downloads/en/

## Key repositories

* [RiskProfiler](https://github.com/OpenDRR/riskprofiler)
* [Model Factory](https://github.com/OpenDRR/model-factory)
* [Data Store](https://github.com/OpenDRR/opendrr-data-store)
* [OpenDRR API](https://github.com/OpenDRR/opendrr-api)
* [Documentation](https://github.com/OpenDRR/documentation)

## Progress tracking
* [Sprints](https://github.com/OpenDRR/opendrr-platform/wiki)

## Documentation
* [Documentation](https://github.com/OpenDRR/documentation)

## Contributing
1. Fork a repository by following the GitHub guidelines here: <https://docs.github.com/en/get-started/quickstart/fork-a-repo>.
2. Use the following steps to prepare a pull request:
    - `git fetch upstream`
    - `git checkout upstream/master` or `git checkout upstream/main`
    - `git checkout -b my-contribution-description`
    - test your additions
    - create a pull request
