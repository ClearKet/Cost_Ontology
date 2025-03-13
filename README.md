# Cost Estimation Ontology

This repository contains a basic RDF ontology structure for modeling cost estimation in construction.

## Structure

- **Classes**:
  - `CostItem`: Represents a cost-related item.
  - `Work`: Defines construction work, including construction, demolition, and consolidation.
  - `Activity`: Defines activities related to each work type.

- **Properties**:
  - `hasWork`: Links a `CostItem` to its `Work`.
  - `hasActivity`: Links a `CostItem` to an `Activity`.
  - `hasMaterial`: Specifies the material used in the work.
  - `hasDimensions`: Indicates the wall thickness.
  - `hasObject`: Represents the object type (e.g., Wall).

## Usage
This ontology can be imported into **Protégé** for visualization and reasoning.

## Example Data
The ontology contains example instances for:
- Load-bearing wall **construction** using reinforced concrete and a human resource group of 3 labourers.
- Load-bearing wall **demolition** using demolition equipment and a human resource group of 3 labourers.
- Load-bearing wall **consolidation** using FRP material and a human resource group of 3 labourers.
