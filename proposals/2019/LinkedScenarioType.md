# LinkedScenarioType - BRICR Support

## Overview

Link ScenarioTypes to ResourceUses and AllResourceTotals to support the BRICR Use Case.

## Justification

There exists a need to link ScenarioType to ResourceUses and AllResourceTotals, in order to identify which scenario the results belong to.  CalculationMethod can also be retrieved via the LinkedScenarioType (to determine modeled vs. actual results). An 'ID' attribute will be added to each ScenarioType to make the linking possible. This is to support BRICR and other use cases.

## Implementation

1. Add 'ID' attribute to path: BuildingSync/Facilities/Facility/Reports/Report/Scenarios/Scenario/ScenarioType	

1. 				


## References

N/A
