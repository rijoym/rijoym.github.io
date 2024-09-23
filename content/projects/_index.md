---
title: "Research"
description: ""
---
# Current research

## 1. Application of LLM in Electronic Design Automation
<p style='text-align: justify;'>Recent efforts have been aimed at elevating 
the abstraction level and ease of digital hardware design, where the goal is to allow designers to articulate 
functional specifications of the logic to be described in a natural language. State-of-the-art Large 
Language Models (LLMs) have shown the potential to revolutionize digital hardware design and validation methodology, 
by automatically generating correct-by-construction circuit descriptions in HDL, and HDL code for hardware 
validation ("testbench"), when prompted by the functional description of the circuit in a natural language, e.g.
English. My current research work focuses on combining hardware design workflow through the emerging LLMs, 
which represents progress toward the vision of automatic, error-free and secure hardware logic design via
natural language interaction.
</p>

<p style='text-align: justify; font-size: 15px;'> Related Works: </p>

<p style='text-align: justify; font-size: 15px;'> 1) Sneha Swaroopa, <strong>Rijoy Mukherjee</strong>, Anushka Debnath, and Rajat Subhra Chakraborty, <a href='https://arxiv.org/abs/2408.02793'>"Evaluating Large Language Models for Automatic Register Transfer Logic Generation via High-Level Synthesis,"</a> submitted to IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems.</p>

## 2.  High-Level Synthesis Security
<p style='text-align: justify;'>Modern IC design relies on proprietary CAD software and third-party hardware IP cores. 
Fabrication often occurs in untrusted offshore foundries, raising concerns about security and reliability. 
Hardware Trojans (HTs) are malicious modifications to integrated circuits that can lead to functional failures or 
data leaks if undetected. While rogue agents are a known threat, studies show that compromised high-level synthesis (HLS) 
CAD tools also serve as attack vectors for HT insertion. If a design house develops an IP using a compromised CAD tool, 
the adversaries can thwart the design house’s IP to create less competitive products in the market. 
If a CAD company’s host country wants to spy on the other country, 
it can force the CAD company to create backdoors in the design using national security interest arguments. 
My research interests are in exploring possible attack vectors in HLS flow as well as development of design methodologies 
that can effectively counter these threats.
</p>

</p>

<p style='text-align: justify; font-size: 15px;'> Related Works: </p>

<p style='text-align: justify; font-size: 15px;'> 1) <strong>Rijoy Mukherjee</strong>, Archisman Ghosh, and Rajat Subhra Chakraborty, <a href='https://dl.acm.org/doi/full/10.1145/3663477'>"HLS-IRT: Hardware Trojan Insertion through Modification of Intermediate Representation During High-Level Synthesis,"</a> in ACM Transactions on Design Automation of Electronic Systems, 29, 5, Article 81 (September 2024), 23 pages.</p>

## 3. Hardware-specifc Deep Neural Network Security
<p style='text-align: justify;'>Consider the following threats:</p>
<p style='text-align: justify;'>
(i) Deep learning, powered by deep neural networks (DNNs), is widely used in smart systems such as autonomous vehicles 
and security applications like facial recognition and biometric authentication. The reliability of these systems 
directly affects safety and privacy. For instance, incorrect DNN object recognition in autonomous vehicles can result 
in fatal accidents. The use of FPGAs to deploy DNN models is growing due to their flexibility, low latency, energy 
efficiency, and easy implementation compared to GPUs and ASICs. However, FPGAs’ reprogrammable nature increases the 
risk of attacks, such as crashing systems or altering functionality 
using Hardware Trojan (HT), or stealing intellectual property (IP) through 
bitstream analysis. Features like Dynamic Partial Reconfiguration (DPR) in high-end FPGAs further expose vulnerabilities.</p>
<p style='text-align: justify;'>
(ii) Training state-of-the-art DNN architectures from scratch requires specialized and skilled effort, in conjunction with the 
deployment of considerable computational resources. The training dataset(s), DNN architecture and parameters are fine-tuned 
to the business use-case. Hence, DNNs are frequently considered as valuable Intellectual Property (IP). 
In general, a DNN IP consists of (a) the detailed architecture of the DNN including the layer connectivity information, 
and (b) the collection of individual node weight parameters. 
Several attacks have been proposed and demonstrated, whereby the DNN is reverse-engineered and the network 
is cloned through side-channel and fault attacks on hardware implementation. Hence, adversaries and competitors may 
illegally copy the models and provide DNN models unauthorized prediction services to unsuspecting users.
Thus, DNN IP protection is an important 
emerging problem, and there is increasing need to safeguard it against malicious use and piracy.</p>

My research work lies in exploring the hardware implementation-specific vulnerabilities of DNNs, 
and development of robust, low-cost, deployable solutions for them.
</p>

<p style='text-align: justify; font-size: 15px;'> Related Works: </p>

<p style='text-align: justify; font-size: 15px;'> 1) <strong>Rijoy Mukherjee</strong> and Rajat Subhra Chakraborty, <a href='https://ieeexplore.ieee.org/document/10115275'>"Attacks on Recent DNN IP Protection Techniques and Their Mitigation,"</a> in IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, vol. 42, no. 11, pp. 3642-3650, Nov. 2023.</p>

<p style='text-align: justify; font-size: 15px;'> 2) <strong>Rijoy Mukherjee</strong> and Rajat Subhra Chakraborty, <a href='https://ieeexplore.ieee.org/document/9734742'>"Novel Hardware Trojan Attack on Activation Parameters of FPGA-Based DNN Accelerators,"</a> in IEEE Embedded Systems Letters, vol. 14, no. 3, pp. 131-134, Sept. 2022.</p>
