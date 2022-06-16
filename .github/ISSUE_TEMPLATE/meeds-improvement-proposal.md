---
name: Meeds Improvement Proposal
about: Design a new feature using functional and technical specifications templates
title: 'feat: FEATURE TITLE'
labels: ''
assignees: ''

---

## Rationale

Details of the GAP ( problem(s) to address ) expressed by few words using some screenshots.
**Note**: avoid describing the solution here.

## 1. Functional requirements
- Bullet points for User Journey Maps with some screenshots of the design to be implemented
## 2. Non Functional Requirements
- #### Expected volume & Performance requirements
- #### Security requirements (Authentication, Authorizations, Audit track / traceability, data retention…)
- #### Extensibility requirements (Identified extension points, plugables implementations...)
- #### Configurability requirements
- #### Requirements related to existing users data
- #### Requirements related to existing features (ex: Add a button to existing modules...)
- #### Feature Flag needed ? (shall we allow activation of the feaure on demand ?)
- #### Other NFR (ex: Use of VueX, Vue, Vuetify)
## 3. Software Architecture
- #### Security
- #### Access (GUI, API…)
   - Rest API design (Entry points, domain objects)
   - Portlet Vue & Vuetify, simple portlet, extension WAR ...
- #### Services & processing
   - Ex: Scheduled Jobs
- #### Data and persistence
   - Macro data model
   - Persistence layer (RDBMS, elasticsearch...)
   - Use of caches
- #### Support for clustering
- #### Support for multitenancy
- #### Integrations
- #### Migration strategy
## 4. Annexes
   - Reasoning that explain the technical choices
   - Impacts (ex: impact on public REST/Java API)
   - References (links...)
