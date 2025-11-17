# Institute for Automotive Engineering (ika) <img src="https://www.ika.rwth-aachen.de/images/ika-logo-a-blau-blau-rgb.svg" align="right" width="240"> <br/> RWTH Aachen University

<img src="https://github.com/ika-rwth-aachen/.github/assets/46258835/a6afc4f2-39f5-4455-aafd-1e6612963c23">

<p align="center"> <br> <img src="https://img.shields.io/github/stars/ika-rwth-aachen?style=social"/> &nbsp; <img src="https://img.shields.io/github/followers/ika-rwth-aachen?style=social"/> </p>

This is the official space for projects open-sourced and maintained by the [**Institute for Automotive Engineering (ika)**](https://www.ika.rwth-aachen.de/).

As an institute of [RWTH Aachen University](https://www.rwth-aachen.de/go/id/a/), ika is leading education and research in automotive engineering. At ika, we research future, efficient, sustainable, and safe solutions for a wide range of mobility use cases. Our research spans the entire vehicle and mobility system, including:
- [Vehicle Concepts & HMI](https://www.ika.rwth-aachen.de/en/competences/fields-of-research/vehicle-concepts-hmi.html)
- [Vehicle Dynamics & Acoustics](https://www.ika.rwth-aachen.de/de/kompetenzen/forschungsfelder/fahrdynamik-akustik.html)
- [Energy Management & Drivetrains](https://www.ika.rwth-aachen.de/en/competences/fields-of-research/energy-management-drivetrains.html)
- [Vehicle Intelligence & Automated Driving](https://www.ika.rwth-aachen.de/en/competences/fields-of-research/vehicle-intelligence-automated-driving.html)
- [Traffic Psychology & Acceptance](https://www.ika.rwth-aachen.de/en/competences/fields-of-research/traffic-psychology-acceptance.html)

> [!IMPORTANT]  
> **If you would like to learn more about how you can use our tools or how we can support your efforts in any of these domains, feel free to reach out to us!**  
> :email: ***opensource@ika.rwth-aachen.de***

## Maintained Building Blocks for Automated Driving, SDVs, and C-ITS

### Interfaces & V2X Communication

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [mqtt_client](https://github.com/ika-rwth-aachen/mqtt_client) | Bi-directional bridge between ROS & MQTT: *Connect your robots running ROS and robustly exchange native ROS messages over any network* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/mqtt_client?style=social"/> <br/> [Paper (2022)](https://ieeexplore.ieee.org/document/9987813) |  |
| [mqtt-in-docker](https://github.com/ika-rwth-aachen/mqtt-in-docker) | Secure IoT communication with MQTT and Docker: *Learn how to combine the MQTT protocol with Docker and a Public Key Infrastructure for secure IoT communication* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/mqtt-in-docker?style=social"/> |  |
| [etsi_its_messages](https://github.com/ika-rwth-aachen/etsi_its_messages) | ROS support for ETSI ITS messages: *Use standardized ETSI ITS messages for V2X communication in ROS systems* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/etsi_its_messages?style=social"/> <br/> [Paper (2024)](https://ieeexplore.ieee.org/document/10920150) | <img src="https://github.com/ika-rwth-aachen/etsi_its_messages/raw/main/assets/teaser.gif" width="80" /> |
| [perception_interfaces](https://github.com/ika-rwth-aachen/perception_interfaces) | ROS message definitions for perception: *Use these ROS messages for the communication of perception data in ROS systems* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/perception_interfaces?style=social"/> |  |
| [planning_interfaces](https://github.com/ika-rwth-aachen/planning_interfaces) | ROS message definitions for behavior planning: *Use these ROS messages for the communication of behavior planning data in ROS systems* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/planning_interfaces?style=social"/> |  |

### Data Collection

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [omega-prime](https://github.com/ika-rwth-aachen/omega-prime) | Data model, data format and Python library for handling ground truth traffic data  | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/omega-prime?style=social"/> | <img src="https://github.com/ika-rwth-aachen/omega-prime/blob/main/docs/logo/omega-prime.svg?raw=true" width="70" /> |
| [omega-prime-trajdata](https://github.com/ika-rwth-aachen/omega-prime-trajdata) | Fork of [trajdata](https://github.com/ika-rwth-aachen/omega-prime-trajdata/blob/main/github.com/NVlabs/trajdata) that includes a converter from motion prediction datasets to [omega-prime](https://github.com/ika-rwth-aachen/omega-prime) and solves some dependency issues  | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/omega-prime-trajdata?style=social"/> | <img src="https://github.com/ika-rwth-aachen/omega-prime-trajdata/blob/main/omega-prime-trajdata.svg?raw=true" width="70" /> |
| [omega-prime-visibility](https://github.com/ika-rwth-aachen/omega-prime-visibility) | Compute 2D visibility of moving objects for [omega-prime](https://github.com/ika-rwth-aachen/omega-prime) | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/omega-prime-visibility?style=social"/> | <img src="https://github.com/ika-rwth-aachen/omega-prime-visibility/blob/main/omega-prime-visibility.svg?raw=true" width="70" /> |
| [betterosi](https://github.com/ika-rwth-aachen/betterosi) | Python library for reading and writing ASAM OSI files using betterproto2 | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/betterosi?style=social"/> | <img src="https://github.com/ika-rwth-aachen/betterosi/blob/main/betterosi.svg?raw=true" width="200" /> |

### Scenarios & Simulation

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [alks-scenarios](https://github.com/ika-rwth-aachen/alks-scenarios) | Recreate test scenarios from [UN/ECE R.157 E/ECE/TRANS/505/Rev.3/Add.156/Amend.4](https://unece.org/transport/documents/2023/03/standards/un-regulation-no-157-amend4) Annex 3 pp. 45-56 using [simple-scenario](https://github.com/ika-rwth-aachen/simple-scenario) | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/alks-scenarios?style=social"/> | <img src="https://raw.githubusercontent.com/ika-rwth-aachen/alks-scenarios/refs/heads/main/alks-scenarios.svg" width="200" /> |
| [CARLOS](https://github.com/ika-rwth-aachen/carlos) | An Open, Modular, and Scalable Simulation Framework for the Development and Testing of Software for C-ITS: *Take CARLA simulation to the next level* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/carlos?style=social"/> <br/> [Paper (2024)](https://ieeexplore.ieee.org/document/10588502) | <img src="https://github.com/ika-rwth-aachen/carlos/blob/main/utils/images/logo.png?raw=true" width="80" /> |
| [CRUISE](https://github.com/ika-rwth-aachen/cruise_scenario_concept) | Scenario concept for driving scenarios  | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/cruise_scenario_concept?style=social"/> <br/> [Paper (2023)](https://ieeexplore.ieee.org/document/10186385) | |
| [simple-scenario](https://github.com/ika-rwth-aachen/simple-scenario) | Quickly generate prototype test scenarios for automated driving  | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/simple-scenario?style=social"/> | <img src="https://raw.githubusercontent.com/ika-rwth-aachen/simple-scenario/refs/heads/main/simple-scenario.svg" width="200" /> |
| [simple-simulation](https://github.com/ika-rwth-aachen/simple-simulation) | Execute simulation runs defined by simple-scenario to develop scenario-based testing methods  | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/simple-simulation?style=social"/> | <img src="https://raw.githubusercontent.com/ika-rwth-aachen/simple-simulation/refs/heads/main/simple-simulation.svg" width="200" /> |

### Containerization

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [docker-ros](https://github.com/ika-rwth-aachen/docker-ros) | Microservice-based Development and Deployment: *Containerize your ROS / ROS 2 packages or package stacks for simple deployment* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/docker-ros?style=social"/> <br/> [Paper (2024)](https://ieeexplore.ieee.org/document/10611586) | <img src="https://github.com/ika-rwth-aachen/docker-ros/blob/main/assets/logo.png?raw=true" width="80" /> |
| [docker-ros-ml-images](https://github.com/ika-rwth-aachen/docker-ros-ml-images) | Lightweight Docker images for machine learning: *Use our lightweight multi-arch machine learning-enabled ROS Docker images for your development and deployment* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/docker-ros-ml-images?style=social"/> <br/>[Paper (2024)](https://ieeexplore.ieee.org/document/10611586) | <img src="https://github.com/ika-rwth-aachen/dorotos/blob/main/assets/logo.png?raw=true" width="80" /> |
| [docker-run](https://github.com/ika-rwth-aachen/docker-run) | Official Docker CLI with useful defaults: *Simplify your container-driven development and deployment by using docker-run for your container interaction* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/docker-run?style=social"/> <br/> [Paper (2024)](https://ieeexplore.ieee.org/document/10611586) | <img src="https://github.com/ika-rwth-aachen/docker-run/blob/main/assets/logo.png?raw=true" width="80" /> |

### Orchestration

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [Event Detector](https://github.com/ika-rwth-aachen/event_detector) | ROS 2 event detection framework: *Detect developer-defined events in arbitrary data and trigger consequent developer-defined actions* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/event_detector?style=social"/> <br/> [Paper (2025)](https://www.uni-das.de/images/pdf/fas-workshop/2025/FAS2025-13-Reiher.pdf) |  |
| [Application Manager](https://github.com/ika-rwth-aachen/application_manager) | Application management framework based on Kubernetes and ROS 2: *Orchestrate demand-driven deployments and reconfigurations* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/application_manager?style=social"/> <br/> |  |

### Machine Learning

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [libtensorflow_cc](https://github.com/ika-rwth-aachen/libtensorflow_cc) | Pre-built TensorFlow C++ API: *Easily deploy TensorFlow deep learning models in high-performance C++ applications* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/libtensorflow_cc?style=social"/> |  |
| [tensorflow_cpp](https://github.com/ika-rwth-aachen/tensorflow_cpp) | Helpful model wrappers around TensorFlow C++ API: *Easily load, inspect, and run your TensorFlow deep learning models from C++ applications* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/tensorflow_cpp?style=social"/> |  |

### Education

| Repository | Description |  | <div style="width:80"></div> |
| --- | --- | :---: | :---: |
| [acdc](https://github.com/ika-rwth-aachen/acdc) / <br/> [acdc-notebooks](https://github.com/ika-rwth-aachen/acdc-notebooks) | ACDC MOOC: *Gain practical experience in automated driving with coding exercises that teach you the latest methods and tools* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/acdc?style=social"/> <br/> <img src="https://img.shields.io/github/stars/ika-rwth-aachen/acdc-notebooks?style=social"/> <br/> [edX Course](https://www.edx.org/learn/automation/rwth-aachen-university-automated-and-connected-driving-challenges) | <img src="https://pbs.twimg.com/ext_tw_video_thumb/1447574999506771970/pu/img/-02L166C-CeO2UGO.jpg" width="80" /> |
| [acdc-research-projects](https://github.com/ika-rwth-aachen/acdc-research-projects) | Research projects of ACDC MOOC: *Learn how to apply automated driving-related methods and tools by conducting a research project on your own* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/acdc-research-projects?style=social"/> <br/> [edX Course](https://www.edx.org/learn/automation/rwth-aachen-university-automated-and-connected-driving-challenges) | <img src="https://pbs.twimg.com/ext_tw_video_thumb/1447574999506771970/pu/img/-02L166C-CeO2UGO.jpg" width="80" /> |

### Utilities

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [ros2-pkg-create](https://github.com/ika-rwth-aachen/ros2-pkg-create) | Powerful ROS 2 Package Generator: *Easily generate complex ROS 2 C++ and Python packages* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/ros2-pkg-create?style=social"/> |  |
| [ros2_unbag](https://github.com/ika-rwth-aachen/ros2_unbag) | A ROS 2 tool for exporting bags to human-readable files. Supports pluggable export routines to handle any message type. | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/ros2_unbag?style=social"/> | <a href="https://github.com/ika-rwth-aachen/ros2_unbag"><img src="https://github.com/ika-rwth-aachen/ros2_unbag/blob/main/ros2_unbag/ui/assets/badge.svg" width=90 /></a> |
| [ros2_calib](https://github.com/ika-rwth-aachen/ros2_calib) | A manual ROS 2 tool for extrinsic calibration LiDAR-Camera calibration. | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/ros2_calib?style=social"/> | <a href="https://github.com/ika-rwth-aachen/ros2_calib"></a> |


## Repositories related to Scientific Publications

### Perception

| Repository | Description |  | <div style="width:80"></div> |
| --- | --- | :---: | :---: |
| [Cam2BEV](https://github.com/ika-rwth-aachen/Cam2BEV) | Surround View Computation based on Hybrid AI: *Enable vehicles to understand their environment by leveraging Hybrid AI methods to process camera data* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/cam2bev?style=social"/> <br/> [Paper (2020)](https://ieeexplore.ieee.org/document/9294462) | <img src="https://github.com/ika-rwth-aachen/Cam2BEV/raw/master/assets/teaser.gif" width="80" /> |
| [EviLOG](https://github.com/ika-rwth-aachen/evilog) / <br/> [DEviLOG](https://github.com/ika-rwth-aachen/devilog) | Uncertainty-aware environment modeling: *Estimate occupied and free space based on lidar point clouds* |  <img src="https://img.shields.io/github/stars/ika-rwth-aachen/evilog?style=social"/> <br/> <img src="https://img.shields.io/github/stars/ika-rwth-aachen/devilog?style=social"/> <br/> [Paper (2021)](https://ieeexplore.ieee.org/document/9575715) <br/> [Paper (2022)](https://ieeexplore.ieee.org/document/9988605) |  |
| [Point-Cloud-Compression](https://github.com/ika-rwth-aachen/point-cloud-compression) | Compression of lidar data: *Efficiently transmit point clouds between connected and automated vehicles* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/point-cloud-compression?style=social"/> <br/> [Paper (2022)](https://ieeexplore.ieee.org/document/9827270) |  |
| [MultiCorrupt](https://github.com/ika-rwth-aachen/multicorrupt) | A multi-modal robustness dataset and benchmark of lidar-camera fusion for 3D object detection: *Evaluate the robustness of multi-modal 3D object detectors against ten distinct types of corruptions* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/multicorrupt?style=social"/> <br/> [Paper (2024)](https://arxiv.org/abs/2402.11677)   [Trailer](https://youtu.be/55AMUwy13uE?si=Vr72CCC0aREXZ-vs) [Poster](https://github.com/ika-rwth-aachen/MultiCorrupt/blob/main/assets/WePol3.15-Poster.pdf) | <a href="https://github.com/ika-rwth-aachen/multicorrupt"><img src="https://github.com/ika-rwth-aachen/multicorrupt/blob/main/docs/multicorrupt_transparent.png?raw=true" width="80" /></a> |
| [OCCUQ](https://github.com/ika-rwth-aachen/OCCUQ) | Exploring Efficient Uncertainty Quantification for 3D Occupancy Prediction: *3D Occupancy Predction with voxel-wise epistemic uncertainty estimates* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/OCCUQ?style=social"/> <br/> [Paper (2025)](https://arxiv.org/abs/2503.10605)   [Trailer](https://www.youtube.com/watch?v=yVDy-lHESY0&ab_channel=TillBeemelmanns) | <a href="https://github.com/ika-rwth-aachen/OCCUQ"><img src="https://github.com/ika-rwth-aachen/OCCUQ/blob/main/assets/occuq.png" width="80" alt="OCCUQ GitHub Repository" /></a> |

### V2X & Communication

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [ros2-v2x-benchmarking-suite](https://github.com/ika-rwth-aachen/ros-v2x-benchmarking-suite) | Benchmarking suite for V2X case study: *Benchmark latencies between two connected robots in a V2X case study on edge-cloud lidar object detection* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/ros-v2x-benchmarking-suite?style=social"/> <br/> [Paper (2022)](https://ieeexplore.ieee.org/document/9987813) |  |

### Orchestration

| Repository | Description |  | <div style="width:80"></div> | 
| --- | --- | :---: | :---: |
| [RobotKube](https://github.com/ika-rwth-aachen/robotkube) | Fully automated fleet orchestration: *Orchestrate large-scale cooperative multi-robot systems with Kubernetes and the Robot Operating System* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/robotkube?style=social"/> <br/> [Paper (2023)](https://ieeexplore.ieee.org/document/10422370) | <img src="https://github.com/ika-rwth-aachen/robotkube/blob/main/assets/robotkube_logo.png?raw=true" width="80" /> |

### Simulation & Safety Assurance

| Repository | Description |  | <div style="width:80"></div> |
| --- | --- | :---: | :---: |
| [RoadGeneration](https://github.com/ika-rwth-aachen/roadgeneration) | ASAM OpenDrive map generator: *Generate variations of complex ASAM OpenDRIVE maps using a simplified logical description format* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/simdriver?style=social"/> <br/> [Paper (2020)](https://ieeexplore.ieee.org/document/9294664) <br/> [Paper (2022)](https://ieeexplore.ieee.org/document/9988312) |  |
| [SimDriver](https://github.com/ika-rwth-aachen/simdriver) | Closed-loop traffic agent model: *Simulate responsive agents in exact and closed-loop microscopic traffic scenarios* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/simdriver?style=social"/> |  |
| [agent-model-integration](https://github.com/ika-rwth-aachen/agent-model-integration) | Integration of an Agent Model into an Open Simulation Architecture for Scenario-Based Testing of Automated Vehicles: *Deploy driver models in your custom simulation environment* | <img src="https://img.shields.io/github/stars/ika-rwth-aachen/agent-model-integration?style=social"/> |  |

