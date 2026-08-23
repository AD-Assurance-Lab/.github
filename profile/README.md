# Automated Driving Assurance Lab

Western Michigan University.

This organization hosts the neural network verification methods, safety assurance frameworks, and empirical datasets developed by our researchers.

Our work is on **formal verification for automated driving**: proving that a driving policy stays within a specified safety margin across a whole range of operating conditions, rather than sampling those conditions and reporting a pass rate. We check every certificate against closed-loop driving, and we report the cases where the two disagree.

---

## Areas of Research

### Certifying Driving Policies Under Adverse Conditions
We construct disturbance families that are physically parameterized and characterized in simulation, then compute provable bounds on a policy's outputs across the entire family rather than at sampled points within it. Applied so far to end-to-end steering under weather and lighting, and to automatic emergency braking under degraded visibility.

### Matching the Certificate to the Failure
A safety property violated by sustained drift and one violated by a single brief event call for different certified quantities, and using the wrong one fails in both directions. Establishing which statistic belongs to which failure mode — and stating plainly where a certificate is blind — is a deliberate part of the work.

### Automotive Safety Standards Compliance
We map formal verification evidence and robustness results onto established functional safety and regulatory frameworks, so that a certificate can serve as an evidence node in a safety case:
* ISO 26262 (Functional Safety)
* ISO 21448 (Safety of the Intended Functionality / SOTIF)
* ISO/PAS 8800 (Road Vehicles — Safety and Artificial Intelligence)
* UL 4600 (Evaluation of Autonomous Products)
* FMVSS No. 127 (Automatic Emergency Braking)
* ISO/TS 5083, forward-looking

### Real-World Winter Driving Datasets
We collect and publish synchronized multimodal sensor data — camera, high-grade IMU, GPS/RTK, CAN telemetry and pavement condition sensors — from real-world winter driving. The data supports perception validation and the study of how road condition changes the safety margin a controller has to work with.

### Scaling Verification to Larger Models
Verification cost is driven by model size rather than by the dimension of a physical disturbance family, which leaves an open question: how large a model can be certified this way, and whether models with memory can be certified at all. Architectures designed for verifiability, such as Lipschitz-bounded networks, are one avenue we are investigating.

---

## Anticipated Publications

| Topic | Venue |
|---|---|
| Formal verification of end-to-end steering under adverse conditions | arXiv preprint |
| Certifying automatic emergency braking across illumination conditions | arXiv preprint |
| Certificates for multiple and combined disturbance conditions | SAE WCX |
| The winter driving dataset | SAE WCX |
| Formal verification as evidence in automotive safety standards | SAE WCX |
| Winter driving dataset | SAE JCAV |

---

## Contact

Zach Asher, AD Assurance Lab, Western Michigan University.
