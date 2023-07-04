# Reference architecture of an SAP BTP CAP application using GPT Models of OpenAI

<!-- dc-ref-arch-metadata : 
    {
        "id": "ref-arch-1-gpt",
        "name": "Reference architecture of an SAP BTP CAP application using GPT Models of OpenAI",
        "shortDescription": "Short Description Edited",
        "archDiagramLink": "https://discovery-center.cloud.sap/documents/cmis/json/5e5fd7b197b6556fa80bc826/root?objectId=kdkTmUwmTIai4cWh5qfr4EZAvSqLCqY7u5vN6mgZkNk",
        "tags": "SAP, BTP, CAP",
        "detailPageLink": "https://github.com/AvikChakraborty18/testGitContent/blob/mission/10-CustomizeSeniorityRulesToYourOwnRequirements/README.md"
    }
dc-ref-arch-metadata  -->

<!-- dc-ref-arch-long-description-start -->
You want to make use of one of the Large Language Models (LLMs) like the GPT family of LLMs offered by Microsoft Azure OpenAI in combination with an application running on SAP Business Technology Platform (BTP), here is our recommendation how to achieve this and also benefit from the BTP capabilities.
<!-- dc-ref-arch-long-description-end -->

## Potential Use Cases

Why would you want to do this? The list of potential use cases for LLMs is endless, here just a few examples:
* Generate proposals or recommendations of common topics, e.g. "what can I do to reduce my CO2 footprint in the context of a vegan diet"
* Generate email text for a fixed purpose and enrich it with data from your application or the ERP system
* Classify free text input or incoming mails into predefined categories
* Combine the language processing power of an LLM with the search on domain specific data or documents
* ... see the [The ChatGPT Cheat Sheet](https://drive.google.com/file/d/1OcHn2NWWnLGBCBLYsHg7xdOMVsehiuBK/view) or similar resources for more

## The Reference Architecture

The major cornerstones of the architecture skeched below are
* [GPT Model of Azure OpenAI Services](#gpt-model-of-openai)
* [SAP AI Core Service](#ai-core)
* [CAP Application](#cap-application)

![](https://proxybridgesdck5a4a61d1b6a0fc1.us2.hana.ondemand.com/proxybridge-sdc-k5a4a6-1.0.0/readonly/cmis/json/dcc6394dd6b8bed2eca641a5/root?objectId=kDDABnIip7Gm_zThn9_zB7apfsyrEU00KwdeSfb_CCo)
 
## Further References
 <!-- dc-ref-arch-resources-start -->
* [The ChatGPT Cheat Sheet](https://drive.google.com/file/d/1OcHn2NWWnLGBCBLYsHg7xdOMVsehiuBK/view) <!-- dc-res-metadata: {"description":  "Some Description 1 Edited 1"} dc-res-metadata -->
* [Sample SAP BTP CAP application](https://github.com/SAP-samples/btp-build-resilient-apps)  <!-- dc-res-metadata: {"description":  "Some Description 2 Edited 2"} dc-res-metadata -->
* SAP CAP - [Blog on CAP starting point](https://blogs.sap.com/2018/10/10/application-programming-model-start-here/)
* SAP UI5 - [Blog on SAP UI5 starting point](https://blogs.sap.com/2021/08/23/what-is-sapui5/)
* [SAP Destination service](https://discovery-center.cloud.sap/serviceCatalog/destination?service_plan=lite&region=all&commercialModel=cloud)
* [Connectivity Service](https://discovery-center.cloud.sap/serviceCatalog/connectivity-service?service_plan=lite&region=all&commercialModel=cloud)
<!-- dc-ref-arch-resources-end -->

## Related Missions in Discovery Center
<!-- dc-ref-arch-related-missions-start -->
* [Getting Started with Discovery Center Missions](https://discovery-center.cloud.sap/missiondetail/3918/3389/)
* [Reduce your CO2 footprint using a smart Generative AI application on SAP BTP](https://discovery-center.cloud.sap/missiondetail/4264/4522/)
<!-- dc-ref-arch-related-missions-end -->

## BTP Services Used
<!-- dc-ref-arch-services-start -->
* [SAP BTP, Cloud Foundry Runtime](https://discovery-center.cloud.sap/serviceCatalog/cloud-foundry-runtime/)
* [SAP AI Core](https://discovery-center.cloud.sap/serviceCatalog/sap-ai-core/)
<!-- dc-ref-arch-services-end -->
