# Workflow

## Workflow management systems (WFMS)

A workflow management system (WfMS) is a software system for setting up, performing, and monitoring a defined sequence of processes and tasks, with the broad goals of increasing productivity, reducing costs, becoming more agile, and improving information exchange within an organization. These systems may be process-centric or data-centric, and they may represent the workflow as graphical maps. A workflow management system may also include an extensible interface so that external software applications can be integrated and provide support for wide area workflows that provide faster response times and improved productivity.

## Related concepts

The concept of workflow is closely related to several fields in operations research and other areas that study the nature of work, either quantitatively or qualitatively, such as artificial intelligence (in particular, the sub-discipline of AI planning) and ethnography. The term "workflow" is more commonly used in particular industries, such as in printing or professional domains such as clinical laboratories, where it may have particular specialized meanings.

**`Processes`**: A process is a more general notion than workflow and can apply to, for example, physical or biological processes, whereas a workflow is typically a process or collection of processes described in the context of work, such as all processes occurring in a machine shop.

**`Planning and scheduling:`** A plan is a description of the logically necessary, partially ordered set of activities required to accomplish a specific goal given certain starting conditions. A plan, when augmented with a schedule and resource allocation calculations, completely defines a particular instance of systematic processing in pursuit of a goal. A workflow may be viewed as an often optimal or near-optimal realization of the mechanisms required to execute the same plan repeatedly.

**`Flow control`**: This is a control concept applied to workflows, to distinguish from static control of buffers of material or orders, to mean a more dynamic control of flow speed and flow volumes in motion and in process. Such orientation to dynamic aspects is the basic foundation to prepare for more advanced job shop controls, such as just-in-time or just-in-sequence.

**`In-transit visibility:`** This monitoring concept applies to transported material as well as to work in process or work in progress, i.e., workflows.

## Components

A workflow can usually be described using formal or informal flow diagramming techniques, showing directed flows between processing steps. Single processing steps or components of a workflow can basically be defined by three parameters:

**`input description:`** the information, material and energy required to complete the step

**`transformation rules:`** algorithms which may be carried out by people or machines, or both

**`output description:`** the information, material, and energy produced by the step and provided as input to downstream steps

Components can only be plugged together if the output of one previous (set of) component(s) is equal to the mandatory input requirements of the following component(s). Thus, the essential description of a component actually comprises only input and output that are described fully in terms of data types and their meaning (semantics). The algorithms' or rules' descriptions need only be included when there are several alternative ways to transform one type of input into one type of output – possibly with different accuracy, speed, etc.

When the components are non-local services that are invoked remotely via a computer network, such as Web services, additional descriptors (such as **`QoS`** and **`availability`**) must also be considered.

## Applications

A **workflow application** is a software application that automates, to at least some degree, a process or processes. The processes are usually business-related but can be any process that requires a series of steps to be automated via software. Some steps of the process may require human intervention, such as approval or the development of custom text, but functions that can be automated should be handled by the application. Advanced applications allow users to 

## Examples

The following examples illustrate the variety of workflows seen in various contexts:

- In **machine shops**, particularly **job shops and flow shops**, the flow of a part through the various processing stations is a workflow.
- **Insurance claims processing** is an example of an information-intensive, document-driven workflow.[21]
- Wikipedia editing can be modeled as a stochastic workflow.
- The **Getting Things Done system** is a model of personal workflow management for information workers.
- In **software development**, support and other industries, the concept of follow-the-sun describes a process of passing unfinished work across time zones.
- In **traditional offset and digital printing**, the concept of workflow represents the process, people, and usually software technology (RIPs raster image processors or DFE digital front end) controllers that play a part in pre/post processing of print-related files, e.g., PDF pre-flight checking to make certain that fonts are embedded or that the imaging output to plate or digital press will be able to render the document intent properly for the image-output capabilities of the press that will print the final image.
- In **scientific experiments**, the overall process (tasks and data flow) can be described as a directed acyclic graph (DAG). This DAG is referred to as a workflow, e.g., Brain Imaging workflows.
- In **healthcare data analysis**, a workflow can be identified or used to represent a sequence of steps that comprise a complex data analysis.
- In **service-oriented architectures**, an application can be represented through an executable workflow, where different, possibly geographically distributed, service components interact to provide the corresponding functionality under the control of a workflow management system.
- In **shared services**, an application can be in the practice of developing robotic process automation (called **RPA** or **RPAAI for self-guided RPA 2.0 based on artificial intelligence**) which results in the deployment of attended or unattended software agents to an organization's environment. These software agents, or robots, are deployed to perform pre-defined structured and repetitive sets of business tasks or processes. Artificial intelligence software robots are deployed to handle unstructured data sets and are deployed after performing and deploying robotic process automation.
  
## Features and phenomenology

- **Modeling:** Workflow problems can be modeled and analyzed using graph-based formalisms like Petri nets.
- **Measurement:** Many of the concepts used to measure scheduling systems in operations research are useful for measuring general workflows. These include throughput, processing time, and other regular metrics.
- **Specialized connotations:** The term "workflow" has specialized connotations in information technology, document management, and imaging. Since 1993, one trade consortium specifically focused on workflow management and the interoperability of workflow management systems, the Workflow Management Coalition.
- **Scientific workflow systems:** These found wide acceptance in the fields of bioinformatics and cheminformatics in the early 2000s, when they met the need for multiple interconnected tools that handle multiple data formats and large data quantities. Also, the paradigm of scientific workflows resembles the well-established practice of Perl programming in life science research organizations, making this adoption a natural step towards more structured infrastructure setup.
- **Human-machine interaction:** Several conceptualizations of mixed-initiative workflows have been studied, particularly in the military, where automated agents play roles just as humans do. For innovative, adaptive, and collaborative human work, the techniques of human interaction management are required.
- **Workflow analysis:** Workflow systems allow users to develop executable processes with no familiarity with formal programming concepts. Automated workflow analysis techniques can help users analyze the properties of user workflows to conduct verification of certain properties before executing them, e.g., analyzing flow control or data flow. Examples of tools based on formal analysis frameworks have been developed and used for the analysis of scientific workflows and can be extended to the analysis of other types of workflows.

---

from [https://en.wikipedia.org/wiki/Workflow](https://en.wikipedia.org/wiki/Workflow)
