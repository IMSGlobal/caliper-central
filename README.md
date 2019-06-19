# IMS Global Learning Consortium, Inc.

# caliper-central
The [Caliper Analytics® Specification](https://www.imsglobal.org/caliper/v1p1/caliper-spec-v1p1) 
provides a structured approach to describing, collecting and exchanging learning activity data at 
scale. Caliper also defines an application programming interface (the Sensor API™) for marshalling 
and transmitting event data from instrumented applications to target endpoints for storage, 
analysis and use.  

*caliper-central* is a clearinghouse for cross-cutting issues that may impact the various Caliper 
repositories maintained in Github.  We use a [ZenHub](https://www.zenhub.com/) board to organize, 
track and report on our issues and current work.  ZenHub provides browser 
[extensions](https://www.zenhub.com/extension) for both Chrome and Firefox. 
A web/mobile [interface](https://app.zenhub.com/) is also available.

## Contributing
We welcome the posting of issues by non IMS Global Learning Consortium members (e.g., feature 
requests, bug reports, questions, etc.) but we *do not* accept contributions in the form of pull 
requests from non-members. See [CONTRIBUTING.md](./CONTRIBUTING.md) for more 
information.

## Caliper Github repositories

### Core Documents

| Name                                                                  | Is Public? | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|-----------------------------------------------------------------------|----|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [caliper-central](https://github.com/IMSGlobal/caliper-central)       | Yes| This repo. Central place to log and manage Github issues.                                                                                                                                                                                                                                                                                                                                                                                                     |
| [caliper-spec](https://github.com/IMSGlobal/caliper-spec)             | Yes | The main spec document.                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [caliper-impl-guide](https://github.com/IMSGlobal/caliper-impl-guide) | No |   The implementation guide document. <br>(For the current development of Caliper 1.2, this document has been moved into the [caliper-spec](https://github.com/IMSGlobal/caliper-spec/tree/develop) repository. For 1.1 it's still on the master branch of this repo.)                                                                                                                                                                                                        |
| [caliper-cert-guide](https://github.com/IMSGlobal/caliper-cert-guide) | Yes |  The Certification guide specifies the requirements and process for certification. <br>(For the current development of Caliper 1.2, this document has been moved into the [caliper-spec](https://github.com/IMSGlobal/caliper-spec/tree/develop) repository. For 1.1 it's still on the master branch of this repo.)                                                                                                                                                          |
| [caliper-ontology](https://github.com/IMSGlobal/caliper-ontology)     | Yes |  caliper-ontology provides machine-readable documents that define the concepts, relationships and constraints that together comprise the Caliper information model. The ontology is available in three flavors: JSON-LD, RDF/XML and Turtle. <br>(For the current development of Caliper 1.2, this document has been moved into the [caliper-spec](https://github.com/IMSGlobal/caliper-spec/tree/develop)  repository. For 1.1 it's still on the master branch of this repo.) |
| [caliper-contexts](https://github.com/IMSGlobal/caliper-contexts)     | Yes| Caliper JSON-LD context documents for mapping Caliper terms to IRIs. <br> <span style="font-size: small;">(For the current development of Caliper 1.2, this document has been moved into the [caliper-spec](https://github.com/IMSGlobal/caliper-spec/tree/develop) repository. For 1.1 it's still on the master branch of this repo.)</span>                                                                                                                                                                                                                                                                                                                                                                                          |

### Test fixtures and JSON schema

|Name|Is Public?|Description|
|--- |--- |--- |
|[caliper-common-fixtures](https://github.com/IMSGlobal/caliper-spec/tree/develop)|Yes|A set of unit test fixtures for reference implementations to test against. Great for finding examples of Caliper Event JSON. <br>(For the current development of Caliper 1.2, the fixtures have been moved into the [caliper-spec](https://github.com/IMSGlobal/caliper-spec) repository. For 1.1 it's still on the master branch of this repo.)|
|[caliper-json-schema](https://github.com/IMSGlobal/caliper-json-schema)|No |A set of JSON schemas that can be used to validate Caliper JSON-based documents.|

### Related Specs

|Name|Public Version|Description|
|--- |--- |--- |
|[LTI-spec-Caliper](https://github.com/IMSGlobal/LTI-spec-Caliper)|Unpublished |An LTI spec explaining how to use Caliper with LTI tools.|

### Example Apps

|Name|Is Public?|Description|
|--- |--- |--- |
|[caliper-java-example-public](https://github.com/IMSGlobal/caliper-java-example-public)|Yes||
|[caliper-js-example](https://github.com/IMSGlobal/caliper-js-example)|Yes||
|[caliper-eventstore-public](https://github.com/IMSGlobal/caliper-eventstore-public)|Yes||

### Reference Implementations

| Name                                                          | Is Public? | Description        |
|---------------------------------------------------------------|------------|--------------------|
| [caliper-java](https://github.com/IMSGlobal/caliper-java)     | Yes        | Java library       |
| [caliper-js](https://github.com/IMSGlobal/caliper-js)         | Yes        | Javascript library |
| [caliper-python](https://github.com/IMSGlobal/caliper-python) | Yes        | Python library     |
| [caliper-net](https://github.com/IMSGlobal/caliper-net)       | Yes        | .NET library       |
| [caliper-ruby](https://github.com/IMSGlobal/caliper-ruby)     | Yes        | Ruby library       |
| [caliper-php](https://github.com/IMSGlobal/caliper-php)       | Yes        | PHP library        |

©2018 IMS Global Learning Consortium, Inc. All Rights Reserved.
Trademark Information - http://www.imsglobal.org/copyright.html
