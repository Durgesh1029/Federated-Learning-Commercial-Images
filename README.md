# Federated Learning for Commercial Image Sources

## Overview
[cite_start]This project addresses the "Averaging Dilemma" in traditional Federated Learning[cite: 73]. 
[cite_start]It implements two robust algorithms to handle domain shift in commercial datasets[cite: 235].

## Dataset
[cite_start]Based on 23,326 images from 8 commercial sources: [cite: 233, 234]
* [cite_start]Adobe Stock, Getty Images, Shutterstock, Alamy, and others[cite: 291, 330, 348, 300].

## [cite_start]Comparative Results 
| Method | Accuracy | Global Rounds |
| :--- | :--- | :--- |
| **FedAvg** | 89.11% | 250 |
| **Fed-Cyclic** | 91.15% | 150 |
| **Fed-Star** | **91.72%** | **50** |

[cite_start]*Fed-Star outperforms local models and standard FedAvg while using 5x fewer rounds[cite: 275, 278].*
