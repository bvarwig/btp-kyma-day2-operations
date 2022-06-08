# Easy Franchise: Extend a Kyma based multitenant application with day 2 operations

TODO: update the url of the Discovery mission once it's created.   
TODO: generate and add the reuse license

> Important information: The content of this GitHub repository has been created as source for the SAP Discovery Center Mission [Enrich a Kyma based multitenant application with new identity features](https://discovery-center.cloud.sap/missiondetail/url-to-be-updated). So we recommend using directly the mission in the SAP Discovery Center for a better experience.

## Description
This mission explains how to extend a Kyma based multitenant application with day 2 operations. It is related to the mission [Develop a Multitenant Extension Application in SAP BTP, Kyma Runtime](https://discovery-center.cloud.sap/missiondetail/3683/3726/) and extends it by focusing on day 2 operations topics like CI/CD, observability and metering.

As a result, in this mission everything will be based on the multitenant application called Easy Franchise, which is a multitenant application running on the Kyma environment of the SAP Business Technology Platform (SAP BTP) extending SAP S/4 HANA Cloud. We highly recommend you to have a look at the above mentioned mission where you can find there all the necessary details. Therefore be aware that we will not spend so much time here on explaining the application. We will rather focus on enriching it with new features.

For a sake of simplicity, our team has taken some compromise compared to a real application. So, this application doesn't aim to be used for productive usage.

Here is an overview diagram of the EasyFranchise application:
![](https://raw.githubusercontent.com/SAP-samples/btp-kyma-multitenant-extension/main/documentation/images/easyfranchise-diagrams/Slide4.jpeg)

The repository has been structured into 2 sections:
* [documentation](/documentation/README.md): Here you will find the content of the mission, explaining in details how to enrich the existing application Easy Franchise.
* [code](/code/README.md): Here you will find the code anf the deployment files of the multitenant application Easy Franchise and the Metering Dashboard App. In addition to that, there is a folder "setup" where you can find one script to setup the required SAP BTP environment and a second script to deploy the Easy Franchise automatically.


## Who Is This Mission For?

The business scenario of this tutorial has been created with the partner as focus persona. But this is of course not exclusively relevant for SAP partners and can be useful for every person (developer, operator, architect) looking for details on how to enrich a multitenant application running on Kyma with day 2 operations topics like CI/CD, observability and metering.
As mentioned before, we highly recommend to start with the mission [Develop a Multitenant Extension Application in SAP BTP, Kyma Runtime](https://discovery-center.cloud.sap/missiondetail/3683/3726/) as we are expecting some knowledge (e.g. Kyma, SAP BTP, ...) to run this mission. As we are concentrating us here on advanced topics, this mission is mainly suitable for experienced developers on SAP Business Technology Platform (SAP BTP). 

## Focus Topics of the Mission

The tutorial focus on the following aspects:
- Observability (logging, monitoring and alerting)
- Metering
- CI/CD deployment

## Requirements

You can find all requirements to execute the tutorial in this [section](/documentation/discover/prerequisites/README.md).

## Known Issues

The tutorial is provided on the "as-is" basis. Currently, there are no known issues for the project.

## How to Obtain Support?

Check if you find an answer in the [troubleshooting](/documentation/troubleshooting/README.md) section.

Create an issue to get support or to report a bug [here](https://github.com/SAP-samples/btp-kyma-multitenant-extension/issues/new/choose) or interact with us via the SAP Discovery Center questions channel of the mission.

## How to Provide Feedback?

Have you found the enablement material easy to understand? Are you missing something? What can we improve? [Share your feedback](https://github.com/SAP-samples/btp-kyma-multitenant-extension/issues/new/choose), so that we can improve the documentation and provide a better material for future stakeholders.

## What's New

Check the details of our last [releases](/documentation/discover/whats-new/README.md).

## License

Copyright (c) 2022 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the (TODO update licence licences link) file.
