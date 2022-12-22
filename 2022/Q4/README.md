---
visibility: PUBLIC
---


#  Osmosis Phase 2 Audit performed in 2022/Q4

[Scoping document](https://github.com/informalsystems/partnership-osmosis/blob/trunk/2022/Q4/Osmosis%20Phase2%20Project%20Plan.docx) can be found in the auditing repository.

MoMs of the sync meetings are found in the folder: [SyncMoMs](https://github.com/informalsystems/partnership-osmosis/tree/trunk/2022/Q4/SyncMoMs)

#  Deliverables:

 ## PRs: ##
 
**TWAP module**
 - TWAP spec and code comments improvements [#3216](https://github.com/osmosis-labs/osmosis/pull/3216)
 - TWAP code improvements [#3231](https://github.com/osmosis-labs/osmosis/pull/3231)
 
**GAMM module & Balancer style pools**
 - GAMM module spec improvements [#3654 ](https://github.com/osmosis-labs/osmosis/pull/3654)
 - Gamm code improvements [#3657](https://github.com/osmosis-labs/osmosis/pull/3657)
 - x/gamm module minor code improvements [#3704](https://github.com/osmosis-labs/osmosis/pull/3704) 
 
 
**TLA Spec for GAMM module**
- *TODO: explain what is modeled with TLA spec, links*
 
**Osmosis Atomkraft**
- *TODO: short explanation, links*

**Issues** reported on Osmosis Lab github repositories:
- ValidateFutureGovernor() needs some polishing [#3664](https://github.com/osmosis-labs/osmosis/issues/3664)
- JoinPoolNoSwap contains diff in calculation of the expected shares out and calculated shares out [#3705](https://github.com/osmosis-labs/osmosis/issues/3705)
- GAMM module and balancer pool model spec improvements [#3706](https://github.com/osmosis-labs/osmosis/issues/3706)
- Atomkraft findings:
  - x/gamm: Exiting balancer pool with zero assets and low share [#3828](https://github.com/osmosis-labs/osmosis/issues/3828)
  - x/gamm: Panics in SwapExactAmountOut and SwapExactAmountIn for balancer pool[#3829](https://github.com/osmosis-labs/osmosis/issues/3829)
  - x/gamm: Panic “division by zero” in SwapExactAmountOut for balancer pool [#3831](https://github.com/osmosis-labs/osmosis/issues/3831)
  - x/gamm: Unexpected error in MaximalExactRatioJoin for balancer JoinPoolNoSwap [#3834](https://github.com/osmosis-labs/osmosis/issues/3834)
 

 



