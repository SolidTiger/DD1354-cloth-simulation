# Blog 1/3-21
## Forces on the mass spring system.
### What's the deal with cloth?
We found a labb instruction from the University of California where they explained how to connect the nodes in the mass spring system with springs. [Ling to the labb](https://www.ics.uci.edu/~shz/courses/cs114/docs/proj3/index.html). We then used that as a basis to implement the mass spring system with a kind of forward euler method. We just updated the forces on the nodes in **FixedUpdate** and scaled them with the **FixedUpdate** time step. This produced a simulation! However as in the toppe lab the stiffness of the springs could not be so high without the system going bananas so later we will move to the RK4 method.
![Cloth](./img/Screenshot from 2021-03-06 15-22-30.png)