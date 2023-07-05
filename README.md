# Service-Function-Chaining 
SFC, or Service Function Chaining 📶  is a concept used in network architecture and virtualization to define the order and sequence of network services through which packets or flows should traverse. It enables the creation of logical service chains by linking multiple network functions or service functions together to achieve a specific goal or service requirement.
## Purpose 🧐
The purpose of SFC is to provide a flexible and scalable way to define and manage the flow of network traffic through a series of network functions. By chaining together multiple services, such as firewalls, load balancers, intrusion detection systems, and deep packet inspection, SFC allows for the implementation of complex network services and policies.

* Key Features <br />
  -> Service Chain Definition: SFC allows network administrators or orchestrators to define the sequence and order of network functions to be traversed by packets or flows. <br />
  -> Dynamic Service Insertion: SFC supports the dynamic insertion or removal of service functions based on policy or network conditions. <br />
  -> Traffic Steering: SFC enables the intelligent steering of network traffic to appropriate service functions based on specific criteria, such as packet header information or policy rules.<br />
  -> Service Function Virtualization: SFC is often used in conjunction with Network Function Virtualization (NFV) to virtualize network functions and deploy them as software-based instances.<br />
  -> Policy Enforcement: SFC enables the enforcement of specific policies or rules on network traffic by directing it through designated service functions.

### 💪🏼 What is implemented? 
 Designed an algorithm for deriving the minimum delay path for an SFC by using Q-learning method of Reinforcement Machine learning.
 MECs load is computed for each time the SFC is requested, thus creating dynamic scenario. The reward matrix stores how early the MEC will process
the VNF, thus maximum the processing rate of MEC leads to maximum reward. Q-value is computed based on Bellman equation which pushes the MEC with a minimum delay
to the largest value possible. So that if the next time the same request comes, the computed Q-value is
referred to make a decision.
