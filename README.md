# Condition-Based Maintenance of Electricity Pylons Using Drone Imagery

Optional project of the [Streaming Data Analytics](http://emanueledellavalle.org/teaching/streaming-data-analytics-2023-24/) course provided by [Politecnico di Milano](https://www11.ceda.polimi.it/schedaincarico/schedaincarico/controller/scheda_pubblica/SchedaPublic.do?&evn_default=evento&c_classe=811164&polij_device_category=DESKTOP&__pj0=0&__pj1=d563c55e73c3035baf5b0bab2dda086b).

Student: **[To be assigned]**

This project delves into the innovative application of image processing and event-driven architecture to ensure the maintenance of electricity pylons, a critical infrastructure component. Utilizing images captured by drones, the project aims to automate the detection and condition assessment of ceramic insulators on pylons across diverse environments.

**Components of the solution**:
- Insulator Detection & Condition Assessment component: Implementing, using transfer learning from YOLO or other pre-trained Neural Networks, an advanced computer vision solution to identify ceramic insulators in drone imagery accurately and assess the condition of detected insulators, identifying any that are compromised.
- Stream Processing Component: Leveraging a Stream Processor (SP) to aggregate detection events and evaluate the presence and condition of each insulator.
The project will utilize AI frameworks such as Edge Impulse or Roboflow, python libraries, and a stream processor among those illustrated in the course. The goal is to automate the detection of insulators and their condition, sending detailed events to the SP that, in turn, output a report at the end of each pylon inspection.

**Evaluation Metrics**: \
The effectiveness of the proposed system will be evaluated based on:
- Accuracy of insulator detection.
- Precision in condition assessment.
- Throughput and latency in event processing and aggregation.

**Dataset**: \
The system will be tested in controlled scenarios using drone imagery of pylons obtained [here](https://app.roboflow.com/motus-aeaxm/pylon-components/deploy)
The expected result is a dockerized application that demos the complete pipeline and analyzes the solution performance against the evaluation metrics. The project will culminate in a comprehensive discussion of the results, highlighting the system's potential to enhance the maintenance and reliability of electricity pylons through automated, condition-based monitoring strategies.


## Note for Students

* Clone the created repository offline;
* Add your name and surname into the Readme file;
* Make any changes to your repository, according to the specific assignment;
* Add a `requirement.txt` file for code reproducibility and instructions on how to replicate the results;
* Commit your changes to your local repository;
* Push your changes to your online repository.
