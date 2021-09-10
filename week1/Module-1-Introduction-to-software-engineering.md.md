# Module 1: Introduction to Software Engineering

## Objectives

After completing this module, you should be able to:

describe historical events in software engineering
describe the current state of the software industry
identify social and ethical responsibilities of software development
define a system and system engineering
construct an architectural context diagram
identify the scope and boundaries of software engineering
define the relationship between the software development process and the product
cite the characteristics of software process models
identify the role of UML in system and software engineering
identify the role of technical documentation in software development
write sections of system specifications as outlined in the IEEE guidelines

---

## 1. Emergence of Software Engineering

- In the past the processes used for designing and developing software were very informal, which contributed to the rise in development and maintenance costs. 
- The results of ad hoc development processes contributed to a higher percentage of unreliable and lesser quality products entering the marketplace. 
- Many accidents resulted from failures in computer-based systems with hardware devices that were controlled with software. 
- At the time, the industry was considered to be in a crisis state, which then led to the emergence of new practices and methods in software engineering.

- The emergence of new communication protocols, hardware devices, and graphical user interface components have placed a greater demand on software engineers to design quality, reliable, and safe software.


Brief History of Software Engineering

- In the 1950s and the early 1960s, the various engineering disciplines were beginning to analyze how aspects of the engineering field could be applied to methods used in developing software products. As computing power evolved over the decades, the demand increased along with the complexity of the problems that needed to be addressed in the design of software
- The term software engineering was introduced in 1968 at the first international software engineering conference, held by the North Atlantic Treaty Organization (NATO) Science Committee (Mahoney 2004)
- Software was developed to control critical hardware devices in the mid- to late-1960s and early 1970s
- Defects in software were uncovered, which heightened public awareness to the need for better quality and reliability of software. 
- The escalating cost of building quality and reliable software was on the rise in the computer industry and the demand for skilled programmers could not be met. 
- The state of software development was viewed by practitioners as being in a "crisis" state and was commonly referred to as the software crisis.
- In response to the software crisis, researchers and practitioners have been trying to develop a set of methodologies, processes, and tools as the "silver bullet" for building software. 
- The combination of these methodologies, processes, and tools is what comprises the field of software engineering, which continues to emerge today
- The software in question is custom software written to solve large, unique data-processing problems.


Software Engineering Defined

- Software is much more than just the code of a computer program. Software is accompanied by a set of documentation that is necessary to describe the details of the requirements, design, and any external aspects of the software that are necessary for it to execute successfully.
- These documents include any configuration files and any aspects of the external environment that surround the building and use of the software. 
- We can refer to these items as a collective whole, the software system or the software configuration.
- Software has unique characteristics that differ from hardware, which is manufactured and tangible. Software is abstract and intangible and is not manufactured or governed by physical laws.
- There are four characteristics that best describe software: 
  - its maintainability, 
  - dependability, 
  - efficiency, 
  - and usability
- The uniqueness of programming solutions makes these characteristics difficult to measure.
- In order to build software, we use processes to address a unique problem to be solved or a particular need to be satisfied. Software engineering focuses on improving these processes to build a better quality and more reliable product. 
- In early times these processes were often ad hoc and chaotic and resulted in poor quality and unreliable software that was expensive to maintain after deployment.
- The ultimate goal of good software engineering methodologies is to reduce these maintenance costs by building a better product earlier in the development phases of the life cycle.

IEEE definition of Software Engineering:

1. The application of a systematic, disciplined, quantifiable approach to the development, operation, and maintenance of software; that is the application of engineering to software.
2. The study of approaches as in 1.

- In order to build quality software, companies need to be committed to developing sound processes, which requires the establishment of a set of methods and tools.
- When we develop these processes we also need to consider support for the business needs of the organization or company.
- If you search the Internet you can find a variety of automated tools that have been developed to provide support for software processes and methods. These tools are referred to as computer-aided software engineering (CASE) tools.


Social and Ethical Responsibility

- Software engineering is a respected profession and engineers are expected to use good judgment when developing software products.
- Applications to solve a wide range of problems are created and used in society, and society expects the software to be correct and of high quality. 
- Companies entrust engineers with their assets and private data. It is the responsibility of the software engineer to maintain professionalism in the areas of confidentiality, competence, intellectual property rights, and computer misuse (Sommerville, 2004). 
- Professional software engineers are encouraged to join organizations in which ethical standards are established. The Association for Computing Machinery (ACM) and IEEE are known for establishing rules of professional conduct and ethics.

---

## 2. Introduction to Systems Engineering

- In this section we will define system engineering and list some of its distinct characteristics.
- To help you understand the development of the software component within the system framework, we will introduce the basic system life cycle model. 
- Because software requirements are derived from system requirements, we will introduce the System Specifications document.


Definition of System Engineering

- The basic definition of system engineering (Blanchard, 1998, p. 12) is: 
  - "the effective application of scientific and engineering efforts to transform an operational need into a defined system configuration through a top-down iterative process of requirements analysis, functional analysis and allocation, synthesis, design optimization, test and evaluation, and validation."
- The Department of Defense (1996) defines system engineering as the … process that shall:
  - Transform operational needs and requirements into an integrated system design solution through concurrent considerations of all life-cycle needs (i.e., development, manufacturing, test, and evaluation, verification, deployment, operations, support, training, and disposal).
  - Ensure the compatibility, interoperability, and integration of all functional and physical interfaces and ensure that system definitions and design reflect the requirements for all systems elements (i.e., hardware, software, facilities, people, data).
  - Characterize and manage technical risks.
- System engineering has distinct characteristics (Stevens, n.d.) that make its life cycle unique from software engineering
  - handles communication among disparate disciplines, each with its own technical language
  - is primarily a project management activity
  - deals with multiple semi-independent subsystems
  - deals with engineering requirements, constraints for hardware
  - is difficult to change
  - has mechanics and architecture that make progress easier to measure
  - is unlikely to require taking as many risks
  - has a concrete working environment dependent on hardware
  - has components that are manufactured or replicated and that can be damaged
  - has upgrades requiring physical contact to implement because systems contain tangible components
  - has development costs that are easier to determine
  - has the primary maintenance goal of returning to its original state by repairing units
- If we think of system engineering from the perspective of hardware, these characteristics can be easily understood. After all, hardware is tangible, and it can be manufactured.


System Boundaries and Environment

- The term system is used loosely in society to define systems that emerge from organizations and institutions, systems that consist of hardware components, and systems that consist of hardware and software components.
- Hardware systems involve mechanical parts that work together to perform a specific task; power tools are good examples. Systems that contain both hardware and software components are best described as integrated subsystems that work together to accomplish an objective.
- Sommerville (2004, p. 21) defines a system as "a purposeful collection of interrelated components that work together to achieve some objective."
- The focus of our systems engineering discussion will be on systems that contain hardware and software components, or subsystems, which are interrelated. An example is a self-service checkout system that is used in stores by customers to purchase items.
- A system operates within a set of boundaries and limitations unique to its overall environment. These are not considered part of the overall system itself, but the mechanisms and constraints can affect the system state at any given time.
- Anything that crosses the system boundary is defined as the system's distinct set of inputs and outputs.


System Components of Subsystems

- Functionality within a system is performed at the component level. A component can also be referred to as a subsystem.
- Components require the involvement of engineers from different disciplines working together to perform all the necessary functions required within the entire system. Interdisciplinary involvement consists of engineers from the software, electronics, mechanical, structural, civil, human factors, environmental, and architectural disciplines.
- Relationships between subsystems are defined in their interfaces. These interfaces need to be defined at the system level.


System Life Cycle

- The basic life cycle of a system begins with identification of a need to be fulfilled through the system's development, implementation, and retirement phases.
- To satisfy the need for the system, a solution is established and presented to the customer in a document called the system specifications (SS). 
- The SS describes what is needed by the system, its subsystems, and the interfaces that need to exist between the subsystems and other systems. 
- When the SS is complete it is submitted to the customer for approval.
- Once the SS is approved by the customer, the life cycle for each subsystem can independently commence. 
- Defining the requirements for the software subsystem can commence after the system requirements are agreed upon by the stakeholders and the engineers.
- Subsequent development phases of software and hardware can continue in parallel and then be integrated for testing on a scheduled date as a whole working system. Integration of software and hardware can take months, even years, depending on the size and complexity of the system.
- Consistency and communication are the goals of the specifications phase in the system life cycle. General guidelines for the SS include:
  - stating the goals of the system
  - defining the system boundary, which includes any constraints imposed on the system
  - specifying the inputs and outputs
  - identifying the various components
  - defining the structure
  - specifying any interactions between the components
  - identifying any safety concerns


Architectural Diagram

- To illustrate the system and its environment, a top-level architectural diagram is used. Pressman (2005) describes the architectural context diagram (ACD) as a block diagram that represents the flow of information into and out of the system.
- The proposed software subsystem is placed in the middle of the diagram (shown as a circle) surrounded by the external entities. The software subsystem is treated as a black box, without regard for the internal workings. The connecting lines with directional arrows reflect the expected flow of data inputs and outputs between the external entities and the software component. You should note that each directional line has a label describing the data flow or object. Proper labeling of all inputs and outputs at the system specifications stage will form the foundation for subsequent definition of the operational scenarios and data objects during software requirements development. 


---

## 3. Software Process and Product

- To accommodate the differing roles of software products, we will study several process models that vary the sequence and frequency of the basic tasks of software development.
- The basic tasks, however, are invariant and are illustrated below in one of the predominant software development processes, linear-sequential:

Analysis -> Design -> Code -> Test

- Roger Pressman defines a software process as "the approach that is taken as software is engineered" (Pressman, 2005, p. 21).
- This approach includes all the technical methods and automated tools that create the process used to make a complex software product.
- You should note that the most important element of this framework is communications


Process Improvement

- The demand for software today requires high-quality systems to be delivered to the customer at a low cost and within a specified time frame. 
- The organization is faced with challenges to meet this demand and to produce software products within tight constraints. 
- A greater challenge exists for the development of the safety-related system because software and project risk factors can impede the completion of the final product. 
- There is no guarantee that a software system can be 100 percent safe and reliable, but studies have shown that implementing a good technical and management process in the development life cycle can help reduce the chance of software and project failures.
- A process is best described as the means used to bring together the necessary knowledge that is integrated into the final product (Pressman, 2005).


Process Improvement Models

- A process improvement model offers a framework for assessing the current state of an organization's way of developing software. This blueprint of effective activities is used to evaluate the current state of the process and to offer a baseline for improvement to reach a higher level of maturity.
- The underlying premise of process improvement is based on Total Quality Management principles that were taught by Shewhart, Juran, Deming, and Humphrey (1989). These principles stress the importance of the process that is used to develop and maintain a product. The process used to develop the product will determine its overall quality; if a high-quality process is used in software development, the product will also be of high quality.
- A process model can only offer guidance on what to do to improve maturity of the process. No specific direction is given on how to actually do it (Phillips, 2003). Each organization must customize its activities according to its business objectives and the type of product it produces. It should be noted that process models vary and not all guidelines may be applicable to a particular project or application.
- To help select a process model, Pressman (2005) recommends making the process model decision based on several factors:
  - the nature of the project and application
  - the methods and tools to be used
  - the required controls and deliverables  
- Humphrey (1989) further defines a software process as all the tools, methods, and practices that are used in the creation of the software product. Some examples of activities that are used in a process during the development life cycle are:
  - software quality assurance
  - configuration management
  - project management
  - subcontract management
  - requirements management
- A summary of benefits (Phillips, 2003) derived from studies on organizations that have followed process models are categorized as improvements in the following areas:
  - predictability of schedules and budgets
  - development cycle time
  - productivity levels
  - quality (measured by the number of defects)
  - customer satisfaction
  - employee morale
  - return on investment
  - cost factor of quality


Process Assessment

- To assess an organization's software process, all activities used in building the product must be evaluated against a set of standards.
- Process assessment is used by organizations and companies in different ways:
  - to determine the capability of a development organization in the selection process
  - to determine the organization's capability to keep in line with its business aims


Capability Maturity Model

- In 1984, Carnegie Mellon University, in response to software needs in the Department of Defense (DOD), formed the Software Engineering Institute (SEI). 
- The SEI developed the Software Process Maturity Model as part of its early work at the DOD. In 1986, the SEI initiated the Software Capability Evaluation (SCE) project as requested by the United States Air Force (Humphrey, 1992). 
- After several more years of refinement, in 1991, the SEI developed the Capability Maturity Model (CMM) at Carnegie Mellon to denote a class of maturity models.
- Over the years, the SEI has revised the CMM based on new knowledge acquired from studies conducted on private industry and government. 
- The conceptual framework for the CMM was developed by Watts Humphrey, who acted as the advisor during the refinement process of the model (Paulk et al., 1993).
- In December 2001, the Software Engineering Institute released the Capability Maturity Model Integrated (CMMI), which was an upgrade from the CMM. The CMMI is currently being supported by the SEI and followed by organizations and companies in the computer industry.


Computer-Aided Software Engineering (CASE)

- The software development process is information-intensive. The information generated takes different formats as software development progresses through the tasks of analysis, design, code, and test. 
- Much of the information is textual, e.g., requirements, design descriptions, source code, test case descriptions, and so on. 
- The remainder of the information is either graphical or binary, e.g., data flow diagrams (DFDs), entity-relationship (E-R) diagrams, state-transition diagrams (STDs), flowcharts, executable code, and so on.
- For large systems, the amount of information that must be created, managed, controlled, and evaluated is far too great for developers to manage with paper and pencil. For this reason, the use of automated tools to assist in the development of software is crucial. Tools used for this purpose are called CASE (computer-aided software engineering) tools.


Integrated CASE Environments

- The use of individual CASE tools can provide significant help to the software engineer, but the process of getting the tools to work together can sometimes be a difficult and frustrating task. 
- If the tools work with different file formats, perform different functions, and execute on different machines, the engineer is left with having to expend extra effort just to coordinate the tools and their outputs. 
- If, however, the tools can be integrated in some way so that they work together seamlessly, with compatible interfaces, then the engineer's job is made much easier and he or she can focus on the creative aspects of development. Specifically, the challenge is to integrate the various CASE tools together into a single capability, i.e., integrated case (I-CASE).
- One key concept that is necessary to achieve I-CASE is that of the CASE repository. For individual CASE tools to share information during the software development process, each tool will require access to the outputs of the other CASE tools. One potentially effective approach to achieving this goal is to store the outputs of the CASE tools in a central location called a repository.

---

## 4. Software Process Models

Life Cycle of Software

- The full life cycle of a software system begins with its initial concept and ends with its retirement from service.
- Each step of this life cycle requires one or more activities to occur for the product to be completed successfully. 
- To direct the processes within the development life cycle, the project manager selects a model that best describes the flow of the tasks needed within the project.
- All life cycle models used in software development contain the following core components, as outlined by Christensen and Thayer (2001):
  - a description of the major development phases
  - a detailed description of the major processes and activities for each phase
  - a specification of the products and inputs for each phase
  - a mapping of the activities to a framework


Basic Life Cycle Models

- There are different types of life cycle models that exist for the development of software.
  - linear sequential
  - prototyping
  - evolutionary
  - rapid application development
  - component-based


Waterfall Model

- The classic linear-sequential life-cycle model for software engineering is sometimes referred to as the waterfall model. The basis of the waterfall model originated in the late 1960s to address needs for a complex military software development (Baird, 2002).
- In 1970, Royce introduced the model following an iterative approach to software development in which he stressed the importance of documentation at each step. In Royce's paper, he also argued that the waterfall model was flawed and needed strengthening by providing additional supporting development steps to make it less risky.
- The lack of feedback between each phase and in getting the approval for each document of the life cycle has proved to be costly and has required a significant amount of rework when changes were introduced during later phases. For these reasons, the waterfall model is best suited for projects in which requirements are stable and well-defined (Sommerville, 2004, p. 67).
- To address the deficiencies in the waterfall model, hybrids have been emerging over the decades that address: 
  - iteration of phases
  - difficulty in getting all the requirements up front
  - lateness of working product
  -


---

## 5. Agile Approach to Software Development



## 6. Unified Modeling Language



