---
name: Meeds Improvement Proposal
about: Design a new feature using functional and technical requirements templates
title: 'feat: FEATURE TITLE'
labels: ''
assignees: ''

---
## Rationale

<!--
Details of the gap (problems to address) expressed by few words or using some screenshots.
No need to go into lenghty details. Bullet points are fine.
Not all sections should be filled. They are just meant to serve as a checklist. Only fill relevant ones and leave N/A in others.
-->

## 1. Functional Requirements
<!-- Fill only the applicable sections -->

### Top User Stories
<!-- Describe only main stories in the requirements :  As <Persona> When <Context> I need to <Pain> -->

### Impacts
<!-- 
Impacts on existing and transversal features
-->
#### Gamification
<!-- 
Does this add new event to trigger ? new rules in a program ?
-->

#### Notifications
<!-- 
Does it come with notificaitons ? Modifies some other notifications ?
-->

#### Analytics
<!-- 
Does it add/updates some data collection points for analytics? Does it aimpact any built-in reports ?
-->

#### Unified Search
<!-- 
Does it add a new element to search via unified search ? What are the facets to index ?
-->

## 2. Technical Requirements
<!--
Fill only applicable sections. 
-->

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
