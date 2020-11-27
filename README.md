# Context Mapping DSL (CML) Standalone Example Project [![Build Status](https://travis-ci.com/ContextMapper/context-mapper-standalone-example.svg?branch=master)](https://travis-ci.com/ContextMapper/context-mapper-standalone-example) 

De volgende diagrams werden vanuit de CML (via PUML) gegenereerd:

![Insurance Business](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/cbonami/context-mapper-standalone-example/cbonami/gitpod-setup/src-gen/Insurance-Example-Model_ContextMap.puml)

![CustomerManagementDomain](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/cbonami/context-mapper-standalone-example/cbonami/gitpod-setup/src-gen/Insurance-Example-Model_BC_CustomerManagementContext.puml)

![PrintingDomain](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/cbonami/context-mapper-standalone-example/cbonami/gitpod-setup/src-gen/Insurance-Example-Model_BC_PrintingContext.puml)

![CustomerManagementDomain](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/cbonami/context-mapper-standalone-example/cbonami/gitpod-setup/src-gen/Insurance-Example-Model_BC_CustomerSelfServiceContext.puml)

![PolicyManagementDomain](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/cbonami/context-mapper-standalone-example/cbonami/gitpod-setup/src-gen/Insurance-Example-Model_BC_PolicyManagementContext.puml)

Nadat je de CML hebt aangepast, kan je de diagrams hergenereren dmv:

```bash
./gradlew runWithExecJarExecutable
```