# HRI Pipeline Adapters
Provides details and links to NiFi Flows that utilize the IBM Watson Health, FHIR server and Health Record Ingestion service.

The layout has directories that highlight each flow with details within the directory on the usage, flow and additional information for each of the sample flows.  

There is also a link below to the health-patterns repository that includes some sample flows that read in kafka topics containing FHIR resources and writes those to a FHIR server.  This repository will be the main location for NIFI flows in addition to some of the samples highlighted below.

The main github repository for the nifi flow examples is the health-patterns repository in the Alvearie Organization

[Health Patterns Alvearie](https://github.com/Alvearie/health-patterns)

Sample clinical ingestion flow:  [https://github.com/Alvearie/health-patterns/tree/main/clinical-ingestion](https://github.com/Alvearie/health-patterns/tree/main/clinical-ingestion)

### Contributing
For contributing flows, view the health-patterns contributing link for details:

[Contributing flows](https://github.com/Alvearie/health-patterns/blob/main/CONTRIBUTING.md)

### Additional sample flows
In addition, there are other sample flows provided here to assist in working with a number of IBM or open source flows.

#### Handle FHIR Content Type
The shows the workflow in handling the FHIR+JSON content types that might be returned when interacting with a FHIR server.  This allows the flows and provenance contents to be viewed in the NIFI canvas.

Main flow:  [https://github.com/Alvearie/hri-pipeline-adapters/tree/master/Handle FHIR Content Type](https://github.com/Alvearie/hri-pipeline-adapters/tree/master/Handle%20FHIR%20Content%20Type)
