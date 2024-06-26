## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| src/TroveManager.sol | [object Promise] |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **TroveManager** | Implementation | LiquityBase, Ownable, CheckContract, ITroveManager |||
| └ | setAddresses | External ❗️ | 🛑  | onlyOwner |
| └ | getTroveOwnersCount | External ❗️ |   |NO❗️ |
| └ | getTroveFromTroveOwnersArray | External ❗️ |   |NO❗️ |
| └ | liquidate | External ❗️ | 🛑  |NO❗️ |
| └ | _liquidateNormalMode | Internal 🔒 | 🛑  | |
| └ | _liquidateRecoveryMode | Internal 🔒 | 🛑  | |
| └ | _getOffsetAndRedistributionVals | Internal 🔒 |   | |
| └ | _getCappedOffsetVals | Internal 🔒 |   | |
| └ | liquidateTroves | External ❗️ | 🛑  |NO❗️ |
| └ | _getTotalsFromLiquidateTrovesSequence_RecoveryMode | Internal 🔒 | 🛑  | |
| └ | _getTotalsFromLiquidateTrovesSequence_NormalMode | Internal 🔒 | 🛑  | |
| └ | batchLiquidateTroves | Public ❗️ | 🛑  |NO❗️ |
| └ | _getTotalFromBatchLiquidate_RecoveryMode | Internal 🔒 | 🛑  | |
| └ | _getTotalsFromBatchLiquidate_NormalMode | Internal 🔒 | 🛑  | |
| └ | _addLiquidationValuesToTotals | Internal 🔒 |   | |
| └ | _sendGasCompensation | Internal 🔒 | 🛑  | |
| └ | _movePendingTroveRewardsToActivePool | Internal 🔒 | 🛑  | |
| └ | _redeemCollateralFromTrove | Internal 🔒 | 🛑  | |
| └ | _redeemCloseTrove | Internal 🔒 | 🛑  | |
| └ | _isValidFirstRedemptionHint | Internal 🔒 |   | |
| └ | redeemCollateral | External ❗️ | 🛑  |NO❗️ |
| └ | getNominalICR | Public ❗️ |   |NO❗️ |
| └ | getCurrentICR | Public ❗️ |   |NO❗️ |
| └ | _getCurrentTroveAmounts | Internal 🔒 |   | |
| └ | applyPendingRewards | External ❗️ | 🛑  |NO❗️ |
| └ | _applyPendingRewards | Internal 🔒 | 🛑  | |
| └ | updateTroveRewardSnapshots | External ❗️ | 🛑  |NO❗️ |
| └ | _updateTroveRewardSnapshots | Internal 🔒 | 🛑  | |
| └ | getPendingETHReward | Public ❗️ |   |NO❗️ |
| └ | getPendingLUSDDebtReward | Public ❗️ |   |NO❗️ |
| └ | hasPendingRewards | Public ❗️ |   |NO❗️ |
| └ | getEntireDebtAndColl | Public ❗️ |   |NO❗️ |
| └ | removeStake | External ❗️ | 🛑  |NO❗️ |
| └ | _removeStake | Internal 🔒 | 🛑  | |
| └ | updateStakeAndTotalStakes | External ❗️ | 🛑  |NO❗️ |
| └ | _updateStakeAndTotalStakes | Internal 🔒 | 🛑  | |
| └ | _computeNewStake | Internal 🔒 |   | |
| └ | _redistributeDebtAndColl | Internal 🔒 | 🛑  | |
| └ | closeTrove | External ❗️ | 🛑  |NO❗️ |
| └ | _closeTrove | Internal 🔒 | 🛑  | |
| └ | _updateSystemSnapshots_excludeCollRemainder | Internal 🔒 | 🛑  | |
| └ | addTroveOwnerToArray | External ❗️ | 🛑  |NO❗️ |
| └ | _addTroveOwnerToArray | Internal 🔒 | 🛑  | |
| └ | _removeTroveOwner | Internal 🔒 | 🛑  | |
| └ | getTCR | External ❗️ |   |NO❗️ |
| └ | checkRecoveryMode | External ❗️ |   |NO❗️ |
| └ | _checkPotentialRecoveryMode | Internal 🔒 |   | |
| └ | _updateBaseRateFromRedemption | Internal 🔒 | 🛑  | |
| └ | getRedemptionRate | Public ❗️ |   |NO❗️ |
| └ | getRedemptionRateWithDecay | Public ❗️ |   |NO❗️ |
| └ | _calcRedemptionRate | Internal 🔒 |   | |
| └ | _getRedemptionFee | Internal 🔒 |   | |
| └ | getRedemptionFeeWithDecay | External ❗️ |   |NO❗️ |
| └ | _calcRedemptionFee | Internal 🔒 |   | |
| └ | getBorrowingRate | Public ❗️ |   |NO❗️ |
| └ | getBorrowingRateWithDecay | Public ❗️ |   |NO❗️ |
| └ | _calcBorrowingRate | Internal 🔒 |   | |
| └ | getBorrowingFee | External ❗️ |   |NO❗️ |
| └ | getBorrowingFeeWithDecay | External ❗️ |   |NO❗️ |
| └ | _calcBorrowingFee | Internal 🔒 |   | |
| └ | decayBaseRateFromBorrowing | External ❗️ | 🛑  |NO❗️ |
| └ | _updateLastFeeOpTime | Internal 🔒 | 🛑  | |
| └ | _calcDecayedBaseRate | Internal 🔒 |   | |
| └ | _minutesPassedSinceLastFeeOp | Internal 🔒 |   | |
| └ | _requireCallerIsBorrowerOperations | Internal 🔒 |   | |
| └ | _requireTroveIsActive | Internal 🔒 |   | |
| └ | _requireLUSDBalanceCoversRedemption | Internal 🔒 |   | |
| └ | _requireMoreThanOneTroveInSystem | Internal 🔒 |   | |
| └ | _requireAmountGreaterThanZero | Internal 🔒 |   | |
| └ | _requireTCRoverMCR | Internal 🔒 |   | |
| └ | _requireAfterBootstrapPeriod | Internal 🔒 |   | |
| └ | _requireValidMaxFeePercentage | Internal 🔒 |   | |
| └ | getTroveStatus | External ❗️ |   |NO❗️ |
| └ | getTroveStake | External ❗️ |   |NO❗️ |
| └ | getTroveDebt | External ❗️ |   |NO❗️ |
| └ | getTroveColl | External ❗️ |   |NO❗️ |
| └ | setTroveStatus | External ❗️ | 🛑  |NO❗️ |
| └ | increaseTroveColl | External ❗️ | 🛑  |NO❗️ |
| └ | decreaseTroveColl | External ❗️ | 🛑  |NO❗️ |
| └ | increaseTroveDebt | External ❗️ | 🛑  |NO❗️ |
| └ | decreaseTroveDebt | External ❗️ | 🛑  |NO❗️ |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
