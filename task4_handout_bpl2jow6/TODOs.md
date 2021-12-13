- [x] Read the section below on rewards-to-go and the use of a baseline.
- [x] Read the original paper introducing Generalized Advantage Estimation.
- [x] Read the skeleton code care- fully.
- [x] Implement the TODOS, testing after each one.

## TODO's
### Stage 1
- [x] **TODO1**: Implement the ‘step‘ function in the ‘MLPActorCritic‘ class.
	- [x] Where should the no_grad be included? 
- [x] **TODO2**: Update the policy neural networks at the end of each epoch
- [x] **TODO3**: Implement ‘get action‘
- [x] Run

### Stage 2, rewards-to-go
- [x] **TODO4**: Implement the computation of rewards-to-go in the `ret buf`.
- [x] Run

### Stage 3, GAE
- [x] Update the value function at the end of each epoch.
- [x] Implement the estimation of the advantage at each timestep (called phi in the code).
- [x] Normalize the advantage values.
- [x] Change the update rule for the policy to make use of the advantage function as a baseline.
