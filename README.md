# PlanXFlow
Welcome to PlanXFlow, a software development lifecycle designed for engineering AI planning systems. PlanXFlow is developed with the ambition to provide a structured, waterfall-like yet iterative approach tailored to the unique challenges in AI planning. This lifecycle encompasses ten carefully designed phases, guiding practitioners and researchers from the conceptualization of AI planning systems to their deployment and beyond.

PlanXFlow acts as a foundational guide, promoting a holistic understanding of AI planning system development. It is designed to foster a common language among practitioners, researchers, and stakeholders, guiding them through the intricacies of AI planning.

## The Ten Phases

<p align="center">
  <img width="460" height="350" src="https://github.com/user-attachments/assets/73a7636d-29a0-41e1-a9e2-a83cd6f6d48f")
>
</p>


1. **Requirements Analysis**: Identifying various requirements (functional, non-functional, domain-oriented, and user-related) and ensuring the system can support a wide range of functionalities, from modeling and solving planning problems to executing, validating, and managing the overall planning system.

2. **AI Planning Model Formulation**: Creating a suitable planning model, defined by planning type, world context, and user features, as a blueprint for the AI planning system. This phase is critical and complex, requiring expertise to ensure the model meets functional and domain-specific requirements and adequately addresses different aspects of planning, such as actions, tasks, and environmental contexts.

3. **Domain Model Design**: Involves creating a planning domain model by deriving domain information from requirements, conceptualizing and formalizing it using a planning language like PDDL or HDDL, and addressing challenges in domain modeling with tools and methodologies to aid the process.

4. **System Design and Architecture**: Creating an abstract architecture that integrates various planning functionalities, using the planning model and domain model to ensure component compatibility and correct interactions. Given that existing planning tools are often developed in isolation, designing robust, flexible, and scalable AI planning systems involves conceptualizing these functionalities as services and coordinating them through workflows, addressing communication and interoperability issues effectively.

5. **Planning Technology Selection**: Exploring and selecting existing domain-independent planning tools to meet required functionalities before implementing new components, leveraging the extensive range of available planners and tools despite their diverse operating systems, dependencies, and languages. However, identifying suitable tools is challenging due to the vast number of options and varying features, necessitating thorough research and analysis to integrate them effectively into planning systems.

6. **Implementation**: Developing new planning components and communication mechanisms based on the system architecture, modifying planning domain models as needed, and following the classical software development lifecycle for each component.

7. **Testing**: Involves validating and verifying the AI planning system against initial requirements through isolated and integration tests of all planning components, domain models, problem instances, and workflows.

8. **Deployment**: Making the AI planning system ready for use by installing and configuring its components in an environment with sufficient processing power. While manual deployment is complex and error-prone, automated deployment is more suitable but still faces challenges, especially for distributed planning systems that require coordination across diverse environments.

9. **Monitoring**: Involves tracking the planning system and its environment to understand their behavior, with a focus on collecting and processing data provenance to ensure process quality, reproducibility, and performance. Data provenance, categorized into Domain Knowledge, Planning Process, Plan, and System Data, is crucial for understanding and improving planning artifacts, establishing causality, responsibility, and explainability in AI planning systems.

10. **Analysis**: focuses on examining data provenance to identify issues, generate insights, and improve various aspects of the planning system, thereby enabling traceability, reproducibility, and explainability, and guiding subsequent iterations and refinements.



## Innovative Elements

PlanXFlow introduces and emphasizes crucial concepts often sidelined in the academic literature on AI planning:

- **Planning Model**: A conceptual model encompassing the interplay among a suitable planning type, relevant world context, and desired user features.
- **Technology Selection**: Highlights the importance of choosing appropriate planning technologies and the necessary support for such decision-making.
- **Data Provenance**: To ensure clarity and traceability of data sources and transformations throughout all lifecycle phases.

## Core Features

- **Adaptability**: Tailor the lifecycle to meet the specific needs of the respective project.
- **Scalability**: Expand or condense phases to match the project's development scale.
- **Transparency**: Based on clear, understandable processes.
- **Future-Proof**: Stay ahead with easily upgradable methodologies.

## Engagement and Contribution

Your experience and insights are invaluable to the evolution of PlanXFlow. Whether applied in an industrial setting or academic research, sharing your thoughts can help enhance PlanXFlow for everyone.

- **For industrial applications**: Please reach out to share how PlanXFlow has been integrated and adapted for your projects.
- **For academic research**: If you use PlanXFlow in your research work, please cite the following papers:

[1] Georgievski, I. Software Development Lifecycle for Engineering AI Planning Systems. International Conference on Software Technologies, pages 751–760, 2023.

[2] Georgievski, I. Conceptualising Software Development Lifecycle for Engineering AI Planning Systems. IEEE/ACM International Conference on AI Engineering – Software Engineering for AI, pages 88–89, 2023.
