# Binary-Addition-with-Liquid-State-Machine

## Aim of this project:
 To observe the behavior of Echo State Network (ESM) or Liquid State Machine (LSM) via building and training a binary digit addition network.
 
## Something well-known:
- Consider the binary digit addition network as finite state machine. 
  - ref: https://www.cs.toronto.edu/~hinton/csc2535/notes/lec10new.pdf  
- The manifold of LSM reservoir has to be (at least?) equivalent to the aforementioned finite state machine. And the readout network will learn to translate the state of reservoir to binary digit.

## Expected outcomes:
- The performance of this network increased as the size of reservoir scaled up.
  - What happened if I want to add three more binary digits?
  - From binary digit to three-/four-digit problem?
- Is there a good pair of parameters (degree and mean and std of adjacent matrix) that produce a good reservoir? 
  - Plot: degree and the performance of LSM? 
  - Dissipation of information when the degree of LSM increased.
- How does initial status of reservoir impacts the performance.
  - Visualization?
