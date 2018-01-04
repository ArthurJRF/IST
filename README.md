Abstract:

Understanding and predicting all context conditions the self-adaptive systems will be exposed to during its life time and implementing appropriate adaptation techniques is a very challenging mission. If the system cannot recognize and adapt to unexpected contexts, this can be the cause of failures in self-adaptive systems, with possible implications of not being able to fulfill user requirements or even resulting in undesired behaviors. Especially for dependability attributes, this would have fatal implications. The earlier the broad range of high level context conditions can be specified, the better adaptation strategies can be implemented and validated into the self-adaptive systems. The objective of this work is to provide (automated) support to unveil context sets at early stages of the software development life cycle and verify how the contexts impact the system's dependability attributes. This task will increase the amount of potential issues identified that might threaten the dependability of self-adaptive systems. This work provides an approach for the automated detection and analysis of context conditions and their correlations at design time. Our approach employs a data mining process to suitably elicit context sets and is relying on the constructs of a contextual goal model (CGM) for the mapping of contexts to the system's behavior from a design perspective. We experimentally evaluated our proposal on a Body Sensor Network system (BSN), by simulating a myriad of resources that could lead to a variability space of 4096 possible context conditions. Our results show that our approach is able to elicit contexts that would significantly affect a high percentage of BSN assisted patients with high health risk profile in fulfilling their goals within the required reliability level. Additionally, we explored the scalability of the mining process in the BSN context, showing it is able to perform under a minute even for simulated data at the size of over five orders of magnitude. This research supports the development of self-adaptive systems by anticipating at design time contexts that might restrain the achievability of system goals by means of a sound and efficient data mining process.

  This repository is a vehicle to share the images, datasets, results and other complementary outputs that support the understanding of the method and the replication of the experiments. We structured the repository as follows:

    1 - BSN: Files relevant to the description and representation of the BSN structure and operation;

    2 - Evaluation Graphs: Outputs from the data mining method, containing results concerning the scalability and 
    the contribution itself;

    3 - Generated Datasets: Datasets generated by the simulated prototype, object of the Data Mining process.
