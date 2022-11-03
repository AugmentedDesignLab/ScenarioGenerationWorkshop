Autonomous vehicles (AVs) need to be rigorously tested for safety before being deployed in the real world. Scenario based testing of AVs is a promising approach since it evaluates the response of the complete AV system. Significant research has been conducted in this area [1]. Scenarios are an essential form of data to represent environments in simulation and the real world. Simulation testing provides a faster feedback loop to AV developers since it is highly accessible, controllable and cheaper to run tests in relative to the real world. In simulation, to provide a comprehensive evaluation of the safety of an AV, the AV would need to be tested on a large number of desirable scenarios. Desirable scenarios would typically expose hazardous or risky AV responses in simulation itself. Scenarios broadly contain static components (such as roads and roadside objects) and dynamic components (such as vehicle and pedestrian behaviors). Further, they are broadly defined at varying levels of abstraction [2]. There’s a need to represent them in a 3D photorealistic environment to evaluate perception responses and in physics-based environments to evaluate vehicle control responses. This has been addressed in the development of several game engine based simulators such as CARLA [3]. Scenario standards are currently being developed (such as in the case of Opendrive [4] and Openscenario [5]) and iterated upon. 

While the field has largely settled on terminology and initial standards exist for roads and scenarios, the current emphasis is shifting to creation of scenarios from naturalistic datasets, adding greater dynamism to scenarios via interactive NPC cars and pedestrian models and use of procedural content generation methods. Further, much work remains to represent the astonishing diversity of roads, pedestrian and driver behavior, and situations encountered across the globe. Significant discussion is required in the design of the aforementioned models and processes.

## Topics
* Scenario modeling, extraction and reconstruction from naturalistic data.
* Data standards and datasets for roads and scenarios.
* Taxonomies and Ontologies for scenario generation. 
* Dynamic scenario generation - vehicles and pedestrian behaviors, weather and other object dynamics.
* Procedural content generation algorithms.
* Augmenting datasets with synthetic scenario data.  
* Machine Learning for scenario generation.
* Adversarial scenario generation.
* Tools for scenario generation.
* Programming languages for scenario generation. 
* AV stacks as systems under test and candidates for scenario generation methods.
* Metrics for evaluating scenarios.
