# Agent Design

The Agent is designed as a research workflow coordinator for complex engineering modelling tasks.

## Design Philosophy

The system follows a human-in-the-loop strategy. It does not autonomously determine scientific conclusions. Instead, it helps the researcher organize tasks, coordinate repeatable procedures, document decisions, and prepare structured outputs for review.

## Main Modules

### 1. Task Planning Module

Interprets the research objective and decomposes it into smaller subtasks, such as model checking, data processing, figure preparation, manuscript revision, or final reporting.

### 2. Modelling Support Module

Organizes model assumptions, physical interpretation, parameter roles, validation logic, and comparison strategies.

### 3. Computational Coordination Module

Connects analysis steps, generated outputs, documentation, and manuscript content. Its main purpose is to improve consistency across the research pipeline.

### 4. Documentation Module

Summarizes objectives, decisions, changes, generated outputs, problems encountered, and final conclusions in a structured run log.

### 5. Review and Sanitization Module

Before public sharing, the Agent helps remove sensitive details such as local paths, raw data, unpublished numerical values, personal information, and complete private source code.

## Researcher Control

All scientific decisions remain under researcher control. The Agent provides structure, execution support, consistency checking, and documentation assistance, but the researcher reviews and validates assumptions, results, and final interpretation.
