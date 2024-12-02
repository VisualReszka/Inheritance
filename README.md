# Inheritance

## Overview

This project is part of the **Inheritance Exercise** from the Base Learn documentation. It demonstrates Solidity inheritance concepts using **Foundry**.

## Features

- **Salesperson Contract**:  
  Implements an employee paid hourly with specific details like `idNumber`, `managerId`, and `hourlyRate`.

- **EngineeringManager Contract**:  
  Combines salaried employee features with managerial functionalities.

- **InheritanceSubmission Contract**:  
  Links deployed `Salesperson` and `EngineeringManager` contracts.

## Contracts

This project contains the following contracts:
1. **Employee.sol**: Abstract base contract defining employee structure.
2. **Salaried.sol**: Employee contract for salaried workers.
3. **Hourly.sol**: Employee contract for hourly workers.
4. **Manager.sol**: Adds manager functionality to an employee.
5. **Salesperson.sol**: Inherits from `Hourly`.
6. **EngineeringManager.sol**: Inherits from `Salaried` and `Manager`.
7. **InheritanceSubmission.sol**: Combines `Salesperson` and `EngineeringManager` deployments.

## Setup

**Framework**: Foundry

**Contracts**:  
- Salesperson.sol  
- EngineeringManager.sol  
- InheritanceSubmission.sol  

**Network**: Base Sepolia

## Notes

This project is for educational purposes as part of the Base Learn course.

## Progress

Badges Earned: 7 out of 13

