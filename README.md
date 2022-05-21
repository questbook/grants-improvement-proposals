# Grants Improvements Proposals
This repository determines all the interfaces and specifications that must be implemented for showing up on UIs that are implementing this _Grants Protocol_.

# New Proposals
New proposals must be made in the [issues section](https://github.com/questbook/grants-improvement-proposals/issues) of this repository. The GIP number should be the same as the issue number. 
```
# Summary
  2-3 sentences about what this proposal is about
# Abstract
  1 sentence about describing the solution space
# Motivation
  3-5 sentences on why this proposal is being made, what problem will it solve
# Specification
  Include as much detail as possible, including code
```
## What are valid proposals
We want to be pushing the limits on what is possible using the grants program for the betterment of web3 as a whole.
- Things that improve the efficiency of the grants program
- Better aligns incentives of the stakeholders in the grants ecosystem 
- Better implementation design principles

# Stages
Every GIP goes through the 3 phases
- Discussion
- Implemented in `Beta`
- Implemented in `Main`

## Discussion
Once someone creates a proposal, discussions can start directly on the issues tab of Github.
Once the discussions have matured, the discussion will be tagged as `beta-ready`

## Beta implemetation
Once the discussions have matured, and is _beta ready_, the interfaces can be updated in accordance to the discussion in `src/interfaces`.
All UIs that implement this interface must update the UI to reflect the changes to their beta branch.

The UI will show all the chains that have implemented the interface in their `beta` branch. 
All the chains that have not implemented the interfaces in beta, will get dropped. 

## Main implementation
Once the beta branch is stable and tested, the issue will move to `main-ready`
Once the interface is updated in the `main` branch `src/interfaces`, the UIs must update their `main` branch to reflect the changes. The UI will honor only the chains who have made the implementation on the `main` branch of the UI repository.
