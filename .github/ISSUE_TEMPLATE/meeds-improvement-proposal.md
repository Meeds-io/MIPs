---
name: Meeds Improvement Proposal
about: Design a new feature using functional and technical specifications templates
title: 'feat: FEATURE TITLE'
labels: ''
assignees: ''

---
## Rationale

<!--
Details of the GAP (problems to address) expressed by few words using some screenshots.
**Note**: avoid describing the solution here.
-->

## 1. Functional Requirements
<!-- 
Bullet points for User Journey Maps with some screenshots of the design to be implemented
-->

## 2. Technical Requirements

### Expected Volume & Performance

### Security 
<!-- 
Authentication, Authorizations, Audit track / traceability, data retention…
-->

### Extensibility 
<!--
Identified extension points, plugables implementations...
-->

### Configurability 
<!-- 
Properties introduced, default settings, jobs, etc...
-->


### Upgradability
<!-- 
Requirements related to upgrading existing systems, if any. 
Specify how if the system self upgrades, or requires some procedure. 
Should cover data migration, API impacts and properties involved 
-->

### Existing Features
<!--
Requirements related to existing features 
ex: Add a button to existing modules...
-->

### Feature Flags

<!--
Feature flags inserted in code to allow controlling availability of the feature to end users
-->

| Property Name  | Default Value | Target Audience | Functional Behaviour |
| ------------- | ------------- | ------------- | ------------- |
|  |   |   |   |



### Other Non Functional Requirements
<!--
Non functional requirements 
Ex: Use of VueX, Vue, Vuetify
-->

## 3. Impacts

### Documentation 

<!-- 
Docs to update
-->

### Training 
<!--
training level required, change management needs
-->
## 4. Software Architecture

### Security

### Access 
   - GUI <!-- Portlet Vue & Vuetify, simple portlet, extension WAR ... -->
   - API <!-- REST API design : Entry points, domain objects -->


### Services & processing
   - Ex: Scheduled Jobs

### Data and persistence
   - Macro data model
   - Persistence layer <!-- RDBMS, elasticsearch...-->
   - Use of caches
### Clustering

### Multitenancy

### Integrations

### Migration strategy

## 5. Annexes
   - Reasoning that explain the technical choices
   - Impacts <!-- ex: impact on public REST/Java API -->
   - References <!-- links... -->
