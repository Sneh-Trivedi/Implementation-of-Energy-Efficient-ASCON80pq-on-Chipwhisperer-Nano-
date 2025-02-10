# Implementation-of-Energy-Efficient-ASCON80pq-on-Chipwhisperer-Nano-


This repository contains the implementation and optimization details for the ASCON-80pq cryptographic algorithm on the ChipWhisperer Nano platform. The primary focus of this project was to enhance energy efficiency while maintaining robust cryptographic security. Below are the key highlights of the project.

## Introduction

This project outlines the implementation and subsequent optimization of the ASCON-80pq cryptographic algorithm on the ChipWhisperer Nano platform, focusing on enhancing energy efficiency while maintaining robust security.

The integration of the ASCON algorithm—celebrated for its lightweight and secure design—into the ChipWhisperer Nano, a device renowned for conducting power analysis and voltage fault injection, enabled a comprehensive evaluation of its performance in terms of security and energy consumption.

Optimization techniques, including Loop Unrolling, were explored after the initial implementation to refine the algorithm's efficiency. This strategy led to a significant improvement in energy efficiency for both encryption and decryption processes, emphasizing the potential of algorithmic optimizations to reduce energy consumption for cryptographic operations in resource-constrained environments.

## Results and Achievements

Implementation Highlights:
Successfully integrated the ASCON-80pq algorithm into the ChipWhisperer Nano environment.
Modified simpleserial-base.c and defined a custom main function for the ASCON library to enable the execution of the algorithm.
Performance Measurements:
Initial energy consumption with default ASCON code:
Encryption: 0.5502 µJ
Decryption: 0.5775 µJ
Optimization Through Loop Unrolling:
Optimized the encryption and decryption processes, achieving:
Encryption: 0.3935 µJ (32.4% improvement)
Decryption: 0.4025 µJ (30.3% improvement)
Key Innovations:
Integrated trigger high and trigger low mechanisms for detailed power trace analysis using Jupyter.
Demonstrated the significant impact of algorithmic optimization on energy consumption while maintaining secure cryptographic performance.
Conclusion

This project successfully implemented the ASCON-80pq algorithm on the ChipWhisperer Nano platform, achieving notable milestones in cryptographic optimization. The use of Loop Unrolling resulted in remarkable energy efficiency improvements, showcasing its effectiveness for secure, energy-conscious software development.

By achieving energy reductions of over 30% for both encryption and decryption, this work underscores the potential of algorithmic enhancements in modern cryptographic solutions, particularly for resource-constrained environments. These findings contribute to the ongoing advancement of secure and energy-efficient cryptographic technologies.

#### _This implementation is based on the research paper titled "Implementation of Energy Efficient ASCON80pq on Chipwhisperer Nano" by Sneh Trivedi et al. For detailed insights, refer to the publication on [ResearchGate](https://www.researchgate.net/publication/383823692_Implementation_of_Energy_Efficient_ASCON80pq_on_Chipwhisperer_Nano)._

