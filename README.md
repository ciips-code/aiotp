### [English]

# All In One Telehealth Platform -AIOTP-

## Overview

The **All In One Telehealth Platform (AIOTP)** is an open-source software solution commissioned by the **Pan American Health Organization (PAHO/WHO)** through the Information Systems and Digital Health Unit (EIH/IS) from the Department of Evidence and Intelligence for Action in Health, to the **Center for Implementation and Innovation in Health Policies (CIIPS)** at the **Institute for Clinical Effectiveness and Health Policy (IECS)**. This platform aims to improve access to healthcare for people and communities in Latin America and the Caribbean.

This solution is part of the [**IS4H**](https://www.paho.org/en/is4h-information-systems-health) (Information Systems for Health) initiative, and relates to the [**8 Guiding Principles for Digital Transformation of the Health Sector**](https://iris.paho.org/handle/10665.2/54256).

AIOTP is a telehealth suite containing 2 main modules: a Clinical Record Module based on OpenEMR, and a Videoconference module, based on Jitsi and Laravel. More modules will be added progressively. Documentation is available at the wiki webpage.

- **Documentation Package / AIOTP Wiki**: [https://github.com/ciips-code/aiotp/wiki](https://github.com/ciips-code/aiotp/wiki)

- **AIOTP OpenEMR Package**: [https://github.com/ciips-code/openemr-telesalud](https://github.com/ciips-code/openemr-telesalud)

- **AIOTP Videoconference Package** (Jitsi, Laravel, APIs, and containers): [https://github.com/ciips-code/ciips-telesalud](https://github.com/ciips-code/ciips-telesalud)

## Purpose

The platform was created to address the healthcare access challenges faced by remote and underserved populations. By leveraging and adapting open-source components such as [OpenEMR](https://www.open-emr.org) and [Jitsi](https://jitsi.org), the platform provides a secure, scalable, and reliable telehealth solution. Initially, the platform includes an Electronic Medical Record (EMR) module and a Telehealth module, which can be deployed jointly or independently. The ongoing development aims to expand the platform's functionality and interoperability with other systems through standard interfaces.

## Key Features

- **Open Source:** Built on open-source components, ensuring transparency and flexibility.
- **Modular Design:** Includes an EMR and Telehealth module, with additional modules under development.
- **Scalability:** Designed to be easily implemented and scaled to meet various healthcare needs.
- **Interoperability:** Capable of integrating with existing systems using standard interfaces.
- **Security:** Emphasizes secure deployment to protect patient data and ensure privacy.

## Digital Public Goods and Digital Health Global Goods

[**Digital public goods**](https://digitalpublicgoods.net) (DPGs) are open source software, open data, open artificial intelligence (AI) models, open standards, and open content that adhere to privacy and other applicable regulations and best practices, do no harm by design, and help attain the Sustainable Development Goals (SDGs). The DPG Alliance developed a set of [standards](https://digitalpublicgoods.net/standard/) that any software solution must comply with to be considered a DPG.

[**Digital Health Global Goods**](https://digitalsquare.org/digital-health-global-goods) (DHGG) have a close relationship to DPGs, in that they overlap with many aspects of the DPG Standard. However, the difference stems from the fact that Digital Square Global Goods are focused on the Sustainable Development Goal 3 (Health and Wellness) and primarily focused on the health domain with a market focus of Low-Middle Income Countries (LMIC) settings. Global Goods are also tools with an identified drive towards strengthening the maturity, interoperability, and shelf readiness. To be considered a global good, applicants must meet certain minimum requirements, such as having an open license, and complete a checklist to confirm their eligibility. Once the minimum requirements are met, applicants must fill out an application form and complete a self-assessment using the Digital Square Maturity Model (for software or content). The Peer Review Committee will then review all the applications and make recommendations. The Global Goods Review Board will meet quarterly to consider the PRC’s recommendations and decide whether to accept, reject, or request additional review. All applicants will be notified of the decision. Successful applicants will be added to the Global Goods Interactive Guidebook and will be publicized through our communication channels.

AIOTP is currently undergoing a review, update and submission processes to be considered as a Digital Public Global Good for both the DPG and the DHGG software lists. 

## Development and Collaboration

The All In One Telehealth Platform is a collaborative effort involving multiple stakeholders. The CIIPS at IECS and Integrando Salud have carried out the development, with leadership, financial and strategic support from PAHO/WHO. The platform's development is ongoing, with new modules and features being added regularly to enhance its functionality and reach. A [PATH](https://www.path.org) project for creating a telehealth suite supports its expansion with new features like: an interoperability module following the [OpenHIE](https://ohie.org/es/) framework, using [HL7 FHIR](https://hl7.org/fhir/) and any necessary semantic standards, to connect e-prescribing, e-pharmacy, laboratory, e-referral and community health services, among others; a clinical decision support module based on [CDS Hooks](https://cds-hooks.org), aligned with current and future L3 [WHO Smart Guidelines](https://www.who.int/teams/digital-health-and-innovation/smart-guidelines); a Patient Portal module to help navigate patients in their journey through the healthcare system. Detailed documentation, standard operating procedures,  and video guides, will be updated in English and Spanish.

## Getting Started

To get started with the All In One Telehealth Platform, please visit the following resources:

- **AIOTP OpenEMR Package**: [https://github.com/ciips-code/openemr-telesalud](https://github.com/ciips-code/openemr-telesalud)

- **AIOTP Videoconference Package** (Jitsi, Laravel, APIs, and containers): [https://github.com/ciips-code/ciips-telesalud](https://github.com/ciips-code/ciips-telesalud)

- [PAHO News Article](https://www.paho.org/en/news/12-1-2023-paho-platform-brings-health-monitoring-chronic-diseases-remote-populations)

- [OpenEMR Community Channel on AIOTP](https://community.open-emr.org/t/all-in-one-telehealth-platform-aiotp-openemr-jitsi/22617)

## Contributing

We welcome contributions from the community to help improve and expand the All In One Telehealth Platform. Please refer to our [Contribution Guidelines](CONTRIBUTING.md) for more information on how to get involved.

## License

This project is licensed under the CC License - see the [LICENSE](LICENSE) file for details.

## Contact

For more information or to get in touch with the development team, please visit our [Contact Page](CONTACT.md).

---

Thank you for your interest in the All In One Telehealth Platform. Together, we can improve healthcare access and outcomes for communities across Latin America and the Caribbean, and beyond.


---

### [Español]

# Plataforma de Telesalud All In One -AIOTP-

## Visión General

La **Plataforma de Telesalud All In One (AIOTP)** es una solución de software de código abierto encargada por la **Organización Panamericana de la Salud (OPS/OMS)** a través de la Unidad de Sistemas de Información y Salud Digital (EIH/IS) del Departamento de Evidencia e Inteligencia para la Acción en Salud, al **Centro de Implementación e Innovación en Políticas de Salud (CIIPS)** en el **Instituto de Efectividad Clínica y Sanitaria (IECS)**. Esta plataforma tiene como objetivo mejorar el acceso a la atención médica para personas y comunidades en América Latina y el Caribe.

Esta solución es parte de la iniciativa [**IS4H**](https://www.paho.org/en/is4h-information-systems-health) (Sistemas de Información para la Salud) y está relacionada con los [**8 Principios Rectores para la Transformación Digital del Sector Salud**](https://iris.paho.org/handle/10665.2/54256).

AIOTP es una suite de telesalud que contiene 2 módulos principales: un Módulo de Registro Clínico basado en OpenEMR, y un módulo de Videoconferencia, basado en Jitsi y Laravel. Progresivamente se irán agregando más módulos. La documentación está disponible en la página web Wiki.

- **Paquete de Documentación / Wiki AIOTP**: [https://github.com/ciips-code/aiotp/wiki]([https://github.com/ciips-code/aiotp/wiki])

- **Paquete AIOTP OpenEMR**: [https://github.com/ciips-code/openemr-telesalud](https://github.com/ciips-code/openemr-telesalud)

- **Paquete AIOTP Videoconferencia** (Jitsi, Laravel, APIs, and containers): [https://github.com/ciips-code/ciips-telesalud](https://github.com/ciips-code/ciips-telesalud)


## Propósito

La plataforma fue creada para abordar los desafíos de acceso a la atención médica que enfrentan las poblaciones remotas y desatendidas. Al aprovechar y adaptar componentes de código abierto como [OpenEMR](https://www.open-emr.org) y [Jitsi](https://jitsi.org), la plataforma proporciona una solución de telemedicina segura, escalable y confiable. Inicialmente, la plataforma incluye un módulo de Historia Clínica Electrónica (EMR) y un módulo de Telemedicina, que pueden implementarse conjuntamente o de manera independiente. El desarrollo en curso tiene como objetivo expandir la funcionalidad de la plataforma e interoperabilidad con otros sistemas a través de interfaces estándar.

## Características Clave

- **Código Abierto:** Construido sobre componentes de código abierto, asegurando transparencia y flexibilidad.
- **Diseño Modular:** Incluye un módulo de EMR y un módulo de Telemedicina, con módulos adicionales en desarrollo.
- **Escalabilidad:** Diseñado para implementarse y escalarse fácilmente para satisfacer diversas necesidades de atención médica.
- **Interoperabilidad:** Capaz de integrarse con sistemas existentes utilizando interfaces estándar.
- **Seguridad:** Enfatiza un despliegue seguro para proteger los datos de los pacientes y garantizar la privacidad.

## Bienes Públicos Digitales y Bienes Globales de Salud Digital

Los [**bienes públicos digitales**](https://digitalpublicgoods.net) (DPG) son software de código abierto, datos abiertos, modelos de inteligencia artificial (IA) abiertos, estándares abiertos y contenido abierto que cumplen con las regulaciones y mejores prácticas aplicables de privacidad, no causan daño por diseño y ayudan a alcanzar los Objetivos de Desarrollo Sostenible (ODS). La Alianza de DPG desarrolló un conjunto de [estándares](https://digitalpublicgoods.net/standard/) que cualquier solución de software debe cumplir para ser considerada un DPG.

Los [**Bienes Globales de Salud Digital**](https://digitalsquare.org/digital-health-global-goods) (DHGG) tienen una relación estrecha con los DPG, ya que se superponen con muchos aspectos del Estándar DPG. Sin embargo, la diferencia radica en que los Bienes Globales de Digital Square se enfocan en el Objetivo de Desarrollo Sostenible 3 (Salud y Bienestar) y se centran principalmente en el dominio de la salud con un enfoque de mercado en entornos de Países de Ingresos Bajos y Medios (PIBM). Los Bienes Globales también son herramientas con un impulso identificado hacia el fortalecimiento de la madurez, interoperabilidad y preparación en el mercado. Para ser considerados un bien global, los solicitantes deben cumplir con ciertos requisitos mínimos, como tener una licencia abierta, y completar una lista de verificación para confirmar su elegibilidad. Una vez que se cumplen los requisitos mínimos, los solicitantes deben llenar un formulario de solicitud y completar una autoevaluación utilizando el Modelo de Madurez de Digital Square (para software o contenido). El Comité de Revisión por Pares revisará todas las solicitudes y hará recomendaciones. El Consejo de Revisión de Bienes Globales se reunirá trimestralmente para considerar las recomendaciones del CRP y decidir si aceptarlas, rechazarlas o solicitar una revisión adicional. Todos los solicitantes serán notificados de la decisión. Los solicitantes exitosos serán añadidos a la Guía Interactiva de Bienes Globales y se publicitarán a través de nuestros canales de comunicación.

AIOTP está actualmente en proceso de revisión, actualización y presentación para ser considerado como Bien Público Digital Global, tanto en las listas de software de DPG como de DHGG.

## Desarrollo y Colaboración

La Plataforma de Telesalud All In One es un esfuerzo colaborativo que involucra a múltiples partes interesadas. El CIIPS en IECS e Integrando Salud han llevado a cabo el desarrollo, con liderazgo, apoyo financiero y estratégico de la OPS/OMS. El desarrollo de la plataforma está en curso, con nuevos módulos y características que se añaden regularmente para mejorar su funcionalidad y alcance. Un proyecto de [PATH](https://www.path.org) para crear una suite de telemedicina apoya su expansión con nuevas características como: un módulo de interoperabilidad siguiendo el marco [OpenHIE](https://ohie.org/es/), utilizando [HL7 FHIR](https://hl7.org/fhir/) y cualquier estándar semántico necesario, para conectar la prescripción electrónica, e-farmacia, laboratorio, e-referencia y servicios de salud comunitarios, entre otros; un módulo de soporte de decisiones clínicas basado en [CDS Hooks](https://cds-hooks.org), alineado con las Directrices Inteligentes de la OMS [L3](https://www.who.int/teams/digital-health-and-innovation/smart-guidelines) actuales y futuras; un módulo de Portal del Paciente para ayudar a los pacientes a navegar en su trayectoria a través del sistema de salud. La documentación detallada, los procedimientos operativos estándar y las guías en video, se actualizarán en inglés y español.

## Primeros Pasos

Para comenzar con la Plataforma de Telesalud All In One, por favor visite los siguientes recursos:

- **Paquete AIOTP OpenEMR**: [https://github.com/ciips-code/openemr-telesalud](https://github.com/ciips-code/openemr-telesalud)

- **Paquete AIOTP Videoconferencia** (Jitsi, Laravel, APIs, and containers): [https://github.com/ciips-code/ciips-telesalud](https://github.com/ciips-code/ciips-telesalud)

- [Artículo de Noticias sobre AIOTP de la OPS](https://www.paho.org/en/news/12-1-2023-paho-platform-brings-health-monitoring-chronic-diseases-remote-populations)

- [Canal sobre AIOTP en la Comunidad OpenEMR](https://community.open-emr.org/t/all-in-one-telehealth-platform-aiotp-openemr-jitsi/22617)

## Contribuir

Damos la bienvenida a contribuciones de la comunidad para ayudar a mejorar y expandir la Plataforma de Telesalud All In One. Por favor, consulte nuestras [Directrices de Contribución](CONTRIBUTING.md) para obtener más información sobre cómo participar.

## Licencia

Este proyecto está licenciado bajo la Licencia CC - vea el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para obtener más información o ponerse en contacto con el equipo de desarrollo, por favor visite nuestra [Página de Contacto](CONTACT.md).

---

Gracias por su interés en la Plataforma de Telesalud All In One. Juntos, podemos mejorar el acceso a la atención médica y los resultados para las comunidades de América Latina y el Caribe, y más allá.


