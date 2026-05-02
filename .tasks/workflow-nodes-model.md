# Workflow: a model of graph of nodes

## introduction

A workflow, in a **event-driven** architecture paradigm, is specified by a **graph** built upon a set of different **types of nodes** and **types of edges**:

- action
- event
- data
- sequential branch
- parrallel branch
- conditional branch
- loops
- trigger
- scheduler

Running a workflow implies to:

- monitor **performance** (produce metrics, logging) at any node and at any time
- monitor **states** and **errors**
- manage starting, cancelling, resuming, error reporting and providing results
- manage a persistent state of a workflow run, so it can be pause and retry over a volatile execution environment

- an **workflow run context** is created for each run, that contains the agent run logs, configuration, state, input, output, and any other relevant data. The agent run id is a uuid.

Workflows are runned by a **workflow engine**

## workflow components models

### base workflow component model

Any workflow component share these characteristics:

- **reference** : unique id inside the workflow the action belongs to
- **name**
- **description**

### action

An **action** specification is a description of an action behavior, including its goals, inputs, outputs, and environment. It is used to define the action capabilities and limitations, and to guide its behavior in a specific context.

An action is a computer program that can perform tasks autonomously or with human guidance. It can be designed to perform a specific task or a set of tasks, and can be used to automate repetitive or time-consuming tasks. Actions can be used to perform a wide range of tasks, including data analysis, web scraping, and machine learning.

An action always have these characteristics:

- **input** : has no input or consumes any **unstructured data** or **structured data**
- **output** : has no output or produces any data
- **configuration** : has no configuration or consumes any **json configuration** object
- **behavior** : the agent behavior is defined by software implementation. The implementation is defined by a **serialized sofware part**. Actions must be able to respond to these signals:
  - **start** : begins activity
  - **stop** : stops activity
  - **pause** : pauses activity
  - **resume** : resumes activity
- an action can **fire** and **wait** **events**
- **log** : any action activity and/or activity change is logged. each activity step is logged with a timestamp, a message, and a level (info, warning, error).
- **performance measures** : Each action run exection time is logged in a performance measures file.
- **running state** : indicates the action current state. can be :
  - **running** : the action is running
  - **paused** : the action is paused
  - **stopping** : the action is stopping
  - **stopped** : the action is stopped
  - **error** : the action run has resulted in an error
  
- an **action run context** is created for each new run, that contains the action run logs, configuration, state, input, output, and any other relevant data. The action run id is a uuid. it belongs to a **worflow run context**

