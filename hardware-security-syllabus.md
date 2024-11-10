# Hardware Security: Course Syllabus

## Course Description
This course provides a comprehensive introduction to hardware security, covering theoretical concepts and practical applications. Students will learn about various attack vectors, security primitives, verification techniques, and the application of machine learning in hardware security.

## Course Objectives
By the end of this course, students will be able to:
1. Understand the fundamentals of hardware security and its importance
2. Analyze cryptographic implementations in hardware
3. Identify and mitigate various hardware-based attacks
4. Design and evaluate hardware security primitives
5. Apply security verification techniques to hardware designs
6. Understand the role of machine learning in hardware security

## Weekly Schedule

### Week 1: Introduction to Hardware Security
- Overview of hardware security
- Threat models and attack surfaces
- Basic cryptographic concepts

### Week 2: Cryptography in Hardware
- Overview of hardware implementations of cryptographic algorithms
- Cryptographic accelerators

### Week 3-4: Side-Channel Attacks
- Power analysis attacks
- Timing attacks
- Electromagnetic analysis
- Countermeasures against side-channel attacks

### Week 5: Fault Injection and Supply Chain Attacks
- Types of fault injection techniques
- Differential Fault Analysis (DFA)
- Hardware Trojans
- Counterfeit detection
- Secure hardware design and manufacturing processes

### Week 6: Security Primitives
- Physical Unclonable Functions (PUFs)
- True Random Number Generators (TRNGs)
- Secure key storage

### Week 7: Architecture and Microarchitecture Level Security
- Secure processor architectures
- Memory protection mechanisms
- Trusted execution environments
- Secure boot

### Week 8: Hardware Reverse Engineering and Tampering
- Overview of hardware reverse engineering techniques
- Malicous and constructive applications of hardware RE
- Countermeasures against RE

### Week 9-10: Security Verification
- Formal verification techniques for hardware security
- Information Flow (IF) analysis
- Quantitative Information Flow (QIF) analysis

### Week 11: Machine Learning in Hardware Security
- ML-based side-channel analysis
- Hardware Trojan detection using ML
- Adversarial machine learning in hardware security
- ML for anomaly detection in hardware behavior
- Using GNN for hardware reverse engineering
- Using ML to break reverse engineering protection techniques
- Future directions and challenges

### Week 12: Student presentations

## Practical Assignments

### Assignment 1: Side-Channel Analysis (Week 4)
Students will perform a power analysis attack on a provided software or hardware implementation of a cryptographic algorithm. They will collect power traces, analyze the data, and attempt to extract the secret key.

### Assignment 2: Reverse Engineering (Week 8)
Students will perform reverse-engineering tasks on a simulation model of a hardware component using open-source hardware RE tools. As part of the assignment, the students will evaluate various countermeasures against RE. 

### Assignment 3: ML-based Hardware Security Analysis (Week 12)
Students will apply machine learning techniques to a hardware security problem, such as side-channel analysis or Hardware Trojan detection. They will train a model on provided data and evaluate its performance.

### Prerequisites:
- Basic understanding of computer architecture and digital logic.
- Familiarity with programming languages such as C and Python.
- Machine learning basics

## Grading
- Active participation in classes: 10%
- Practical Assignments (3 x 15%): 45%
- Final project and/or term paper: 45%

## Main textbooks and material
1. Szefer, J. (2022). Principles of Secure Processor Architecture Design. Morgan & Claypool Publishers.
2. Mukhopadhyay, Debdeep, and Rajat Subhra Chakraborty. Hardware security: design, threats, and safeguards. CRC Press, 2014
3. Köylü, T., et al. (2023). A Survey on Machine Learning in Hardware Security. ACM Journal on Emerging Technologies in Computing Systems, Volume 19, Issue 2

## Additional Resources
- Research papers and articles will be provided throughout the course
- Online tools and simulators for hardware security
