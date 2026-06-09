# Automated Driving Assurance Lab

Welcome to the Automated Driving Assurance Lab workspace at Western Michigan University. This organization hosts the neural network verification architectures, safety assurance frameworks, simulation-free validation tools, and empirical datasets developed by our researchers.

Our work focuses on bridging the gap between theoretical formal verification methods and practical automotive engineering safety standards.

---

## Areas of Research

### Neural Network Safety Verification
We develop formal methods to calculate provable safety bounds for deep learning models used in automated driving. By propagating physical weather perturbations (such as contrast drop or brightness bias) through neural networks, we establish mathematical guarantees on vehicle steering outputs without relying solely on empirical simulation.

### Automotive Safety Standards Compliance
We map formal verification evidence and neural network robustness metrics to established functional safety and regulatory standards, including:
* ISO 26262 (Functional Safety)
* ISO 21448 (Safety of the Intended Functionality / SOTIF)
* ISO 8800 (Road Vehicles — Safety and Artificial Intelligence)
* UL 4600 (Standard for Safety for Evaluation of Autonomous Products)

### Real-World Winter Driving Datasets
We collect and publish synchronized multimodal sensor data (camera, high-grade IMU, GPS/RTK, CAN telemetry, and pavement condition sensors) from real-world winter driving tests. This data is used to validate perception models and train safety-critical control systems under adverse weather conditions.

### Verification-Friendly Architectures
To address the computational complexity of neural network verification, we research inherently stable network designs (such as Lipschitz-bounded networks) that allow lightweight safety solvers to achieve tight bounds efficiently.

---

## Anticipated Publications

Our current active publications cover the following topics:
* **Physics-Based Neural Network Certification**: Certifying steering safety margins under real-world weather bounds.
* **Verification-to-Standards Mapping**: Establishing formal verification as compliance evidence in automotive engineering safety cases.
* **Multimodal Winter Perception Datasets**: Introducing synchronized weather telemetry and vehicle dynamics data for adverse condition verification.
