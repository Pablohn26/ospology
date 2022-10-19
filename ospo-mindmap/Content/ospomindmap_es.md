---
markmap:
  initialExpandLevel: 2
  maxWidth: 400
---

# 🧭 OSPO Mapa mental - [Disponible en varios idiomas](https://github.com/todogroup/ospology/tree/main/ospo-mindmap/Content)

## 🙋 Roles

- Gobernanza
- Gestión de proyectos
- Licenciamiento
- Seguridad
- Compromiso con la comunidad
- Formación de los desarrolladores
- Contribuidor individual
- Asesor de código abierto

## 🚀 Comportamiento

### Colaboración con la industria

- `Definición:` Código abierto como vía para una industria específica para convertirse en más eficiente a través de compartir los costes y la innovación para las necesidades específicas de la industria
- `Ejemplo:` Compañías de automoción de la Unión Europea

### Colaboración entre industrias

- `Definición:` Trabajar en problemas tecnológicos fundamentales que afectan a todos los sectores
- `Ejemplo:` Bloomberg trabajó con Microsoft para hacer contribuciones a TypeScript

### Colaboración a través de estándar

- `Definición:` Apoyar los estándares relevantes de proyectos de código abierto y proporcionar retroalimentación a las organizaciones de estándares correspondientes
- `Ejemplo:` Fomentar y guiar a los miembros de su organización a que participen tanto en la comunidad Let's Encrypt como en la comunidad de estándares del IETF  sobre ACME, TLS, y otros trabajos relacionados con los certificados X.509

### Facilitadores de grandes proyectos

- `Definición:`Formar o facilitar la formación de grandes y complejos proyectos de código abierto dentro de una organización y/o lanzar proyectos disponibles públicamente como código abierto 
- `Ejemplo:` Comcast incubó el proyecto Apache Traffic Control

### Priorizar el código abierto

- `Definición:` Ayudar a la organización a priorizar el consumo de software de código abierto y hacer el código abierto la primera opción
- `Ejemplo:` OSPOs que trabajan junto a los CTOs y los estrategas de las compañías para identificar proyectos de código abierto y sus capacidades

### Expertos en estrategia tecnológica

- `Definición:` Evaluar tecnologías de código abierto viables y ayudar a directores IT sénior a trazar la hoja de ruta tecnológica
- `Ejemplo:` OSPOs que actúan como consultores de código abierto internos para ayudar a los desarrolladores y al equipo

### Empresa de software

- `Definición:` Más propensas a incubar o participar en grandes proyectos y más propensas a tener desarrolladores dedicados trabajando exclusivamente en código abierto
- `Ejemplo:` Las compañías de software que dominan el núcleo del equipo de desarrollo de Linux

## 🌱  Tamaño

- Equipo grande a tiempo completo
- Equipo pequeño a tiempo completo
- Equipo virtual (no a tiempo completo)
- Equipo a tiempo completo con miembros virtuales de otros equipos
- Persona a tiempo completo gestionando múltiples equipos

## 🧩 Responsabilidades

### 📘 Desarrollar y ejecutar la estrategia de código abierto

- Comunidad de código abierto, contribuidores y liderazgo
- Cumplimiento normativo
- InnerSource
- Gestionar las consultas de clientes, empleados, inversores o miembros de la comunidad.
- Tolerancia al riesgo
  - Haciendo código abierto el código de la organización
  - Publicando código con problemas conocidos de código abierto (licenciamiento/seguridad)
  - Publicando código que puede impactar en la marca de la organización, diferenciación de producto o portfolio de propiedad intelectual
- Desarrollo corporativo
  - Fusiones y adquisiciones (M&A)
  - Desarrollo subcontratado (contratistas)
- Adquisición de software
- Publicidad
- Comunicaciones
- Crecimiento y retención del talento de código abierto

### 🔍 Supervisar el cumplimiento del código abierto

#### Consideraciones sobre el cumplimiento
- Cumplir con las obligaciones de las licencias de código abierto
  - Mezclando código
    - Proporcionando la atribución
    - Seguimiento de los cambios
  - Métodos de entrega
    - Contenedores
      - Definición del contenedor (Dockerfile)
      - Imagen del contenedor
    - Hardware
    - SDK
      - La entrega incluye todas las dependencias
      - La entrega descarga las dependencias en el momento de la instalación
      - El usuario de la entrega proporciona las dependencias
    - RESTful API
    - SaaS
    - Aplicación web
- Facilitar el uso efectivo de código abierto en productos o servicios propietarios
- Cumplir con las obligaciones contractuales del proveedor de software de terceros o del cliente
- Proteger la propiedad intelectual de la organización
  - Llevar a cabo la diligencia debida en materia de código abierto para las adquisiciones (o proyectos M&A)
  - Comprobar que el nombre del proyecto de código abierto de la nueva organización no infringe las marcas comerciales de terceros
- Proteger la diferenciación del producto de la organización
  - Verificar que no se incluyan secretos comerciales en el código que va a ser de código abierto


#### Educate Developers
- Training & Certification
  - [Open Source Licensing Basics for Software Developers (LFC191)](https://training.linuxfoundation.org/training/open-source-licensing-basics-for-software-developers/)
  - [Introduction to Open Source License Compliance Management (LFC193)](https://training.linuxfoundation.org/training/introduction-to-open-source-license-compliance-management-lfc193/)
  - [Implementing Open Source License Compliance Management (LFC194)](https://training.linuxfoundation.org/training/implementing-open-source-license-compliance-management-lfc194/)

#### Taking Software Inventory

- Security Standards
- License Compliance Policies


### 📝 Establish and Improve Open Source Policies

- Using open source and open source compliance policy
  - Forking an open source project
  - Copying open source licensed files/snippets into organization's codebase
  - Mixing code (owned and third-party OSS/proprietary) and distributing as products or services (sdk, REST API, SaaS, etc.)
  - Using standalone open source tools (e.g. Firefox, MySQL, CentOS)
- Policy on open source and proprietary licenses
  - Concluding of obligations of licenses
  - Classification of licenses
  - Complying with license obligations
- Policy on releasing code as open source
  - Contributing back to third party OSS project
  - Publishing a new open source project
  - Contributing in personal time
  - Signing contribution agreements (e.g. CLA or DCOs)
- Policy on making open source business decisions
  - Risk assessment and acceptance  
  - Business alignment

### 💪 Establish and Improve Open Source Processes

- Creating Open Source
  - Contributing to third-party OSS projects during work time
    - Which copyright statement to use for contributions on behalf of the organization?
    - What to do if there is already a copyright notice in the code?
    - What to do if there is no copyright notice in the code?
    - What to do if the community objects to any changes to the copyright notices?
  - Contributing to third-party OSS projects during personal time
  - Publishing a new open source project
    - Remove from the code any internal references (trade secrets, system names/urls)
    - Check if the new project name is already in use in the community or is trademarked
    - Perform a patent review
      - Freedom to operate: verify project does not infringe third-party's intellectual property
      - Protect organization's intellectual property
        - Does the contribution reveal organization's non-public plans?
        - Does the contribution share the organization's technology advantage with its competitors?
        - Does the contribution prevent the organization from filling new patents for features included in contributed code
        - What is the impact of the contribution on the organization's intellectual property licensing?
    - Perform a legal review
      - Review licenses applicable to contributed code, images or documents
      - Review licenses of dependencies used by contributed code
    - Provide guidance to contributors on open source community ways of working
    - Publishing of project's release artifacts to public repositories such as Maven Central, npm, etc.
  - Signing contribution related agreements
    - Contributor license agreement (individual / corporate)
    - Developer certificate of origin
  - Shutting down a new open source project
- Using Open Source
  - Using an open source project as a standalone tool
  - Including open source snippets or files
  - Including open source packages
  - Forking an open source project
  - Inventorying open source usage incl. packages, licensing and communities
  - Maintaining a classification and enforcing rules for open source and proprietary licenses
- Deciding on Open Source
  - Drive Open Source Review Board with senior leaders from relevant stakeholder to make decisions on open source
  - Drive Open Source Working Group with representatives / interested stakeholders throughout the organization with the aim of improving open source at the organization
- Marketing and/or communicating Open Source
  - Internal messaging
    - Maintaining internal wiki outlining policy, processes, tooling and best practices
  - External messaging
    - Organization's open-source principles
    - Simplified/redacted version of open source wiki
    - Organization GitHub ReadMe
    - Open Source landing page / portal
    - Obligation fulfillment
    - Organizing community events
- Educating people
  - Open source awareness which includes details on open source policy, processes, tools and the basics of open source licensing, community and contributions
  - Guidelines and best practices for using of, contributing to, complying with open source
  - Training on open source project management
  - New employee orientation
  - Checklist for product teams
  - Checklist for developers
  - Checklist for SW procurement
  - Executing a mentorship for open source leaders and/or organization leaders
  - Organizing events 
    - Present Open Source at the organization's all-hands and similar meetings
    - Organize brown bag seminars on open source topics (with invited speakers)
  - Assist speakers for coding forums / conferences
- Measuring Open Source
  - Develop, execute and improve measuring the impact of your organization's open source activities
- Sponsoring Open Source
  - Sponsoring third-party projects or individuals
  - Sponsoring open source organizations
  - Sponsoring own organization's open source projects or individual members
  - Sponsoring events

### 📈 Prioritize and Drive Open Source Upstream Development

#### Create Educational Programs

- Good OSS hygiene
- Technical programs
  - Basics in OS tech stack
  - How to request features
  - How to file bug reports
  - How to contribute basic code
  - How to do non-code contributions
    - How to contribute code review
    - How to contribute documentation
    - How to contribute testing
    - How to contribute to project management

#### Create Internal Open Source Ambassadors

- Drive event sponsorship
- Train speakers for coding forums

#### Contributes to Third-Party OSS Projects

- Ensure maintainability of OSS projects
- Develop new features upstream
- Fix bugs upstream
- Improve documentation
- Triage or reproduce issues
- Offer project management
- Perform tests such as hardware, usability, etc.
- Improve user experience
- Develop / improve graphics
- Create localizations (translate to another language)

#### Incubate and Launch Open Source Projects

- Develop internal resources for
project incubation and post launch

- Develop processes for project
incubation and post launch

- Develop playbooks, checklists and tooling
  - Vet, organize and operate OS projects
  - Train and coach OS Leaders

#### Optimize Open Outbound Source Contributions


### 🤝 Collaborate with Open Source Organizations

##### 📖 Open Standards

- OpenChain
- SPDX

##### 🏠 Foundations

- Apache Foundation
- Free Software Foundation Europe
  - Legal Network
- Eclipse Foundation
  - OSPO Alliance
- InnerSource Commons
- Linux Foundation
  - FINOS
  - OpenSSF
  - OpenChain
  - SPDX
  - TODO Group
- Open Source Initiative
- OpenForum Europe
- OW2
  - Good Governance Initiative


### ⏱️ Track Performance Metrics

- Ability to assess health of open source projects
- Measure community engagement / impact upstream
- Development of open source leaders
- Operate a metrics acquisition and dashboard
- Feedback loop to improve metrics and open source activities

### 🤝 Implement InnerSource Practices

- Increase productivity, quality, code re-use, transparency and trust
- Establish communication channels across the organization
- Improve collaboration across the organization
- Remove organizational silos and identify talent across the organization


### 🫶 Grow and Retain Open Source Talent Inside the Organization

- Train new and coach existing open source leaders
- Drive an internal open source ambassadors program
- Create programs to incentivize contributions of organization's members
- Recognize contributions of organization's members


### 🧑‍💼 Give Advice on Open Source

- Shaping the organization's software strategy and processes and role of open soure within the organization's software ecosystem
- Advise on which open source technologies to adopt, hold or avoid
- Provide open source guidance to people whether managers, contributors, open source project leaders/project maintainers with their issues
- Evaluate OSS projects whether technical, health or compliance assessment
- Help to understand and navigate project politics
  - Help maintain a neutral posture on the open source technology ecosystem
  - Cultivate personal and working relationship
- Bring the outside inside the organization
  - Provide insights into open source trends
  - Promote import of community best practices
  - Warn in case of major community incident or changes



### 🖥️  Manage Open Source IT Infrastructure

- Compliance and contribution tooling
  - Build in-house
  - Adopt existing tools
      - Commercial tools
      - [Open Source tools](https://oss-compliance-tooling.org/Tooling-Landscape/OSS-Based-License-Compliance-Tools/)
- Design OSS infrastructure
- Metrics acquisition and dashboard
- Third-party development tool management such as GitHub, GitLab, etc.


### 🧭 Eliminate Friction from Using and Contributing to Open Source

- Continuously improve processes and tools to reduce learning curve and manual effort required
- Help navigate internal politics or policies
- Maintain relationships with communities of strategic importance to your organization

### 📒 Support Corporate Development Activities

- Help an organization understand the open source technical stack, compliance and opportunities of the target company and related risk as part of the due diligence process
- Ensure contractors (outsourced developement) follow the organization's open source policies and processes
