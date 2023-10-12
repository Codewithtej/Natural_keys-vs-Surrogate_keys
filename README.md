# Natural_keys-vs-Surrogate_keys
This is for the Communications final Project.

# Exploring Database Key Controversy: Surrogate vs. Natural Keys 
## Table of Contents
Overview
Surrogate Keys
Natural Keys
Use Case
Resources

## Overview
This repository contains materials used for a presentation and public debate exploring the differences between natural keys and surrogate keys – with an emphasis on benefits and disadvantages of each approach.

## Surrogate Keys
Definition: Surrogate keys are automatically generated identifiers, often assigned without considering the actual data within a row. They are particularly useful when designing databases with data that lacks unique and consistent attributes suitable for a primary key.
Characteristics: While the scope of this project limits analysis of all characteristics of surrogate keys, focus is centered on the fact that keys are automatically generated, unique, immutable, and non-descriptive.

## Natural Keys
Definition: Natural keys are derived from the actual data within a table's attributes. They are employed when a single attribute or a combination of attributes can uniquely identify each record in the table.
Characteristics: Similar to surrogate keys, the scope of this project prohibits a deep dive into all characteristics of natural keys. However, particular attention is paid to the fact that natural keys are derived from data, unique, and descriptive.

## Use Case
A story is additionally shared in this presentation to introduce the audience to the concept of surrogate keys– and emphasize their situational usefulness. Data from United States Office of Personnel Management payroll records (with artificial values and authentic structure) are presented in a table with attributes not suitable for a natural key. In practice, this issue prohibited a group member from implementing a database at their former job!

A brief coding demonstration following the use case teaches the audience how to generate UUID surrogate keys and assign them as a primary key to existing data.

## Conclusion
The choice between surrogate keys and natural keys depends on the specific requirements of your database. Surrogate keys are a good choice when data integrity and performance are critical. Natural keys are suitable when meaningful, human-readable data representation is a priority, but they may require additional effort to maintain data integrity. In some cases, a combination of both approaches may be used, with a surrogate key for internal management and a natural key for reference and readability.

## Resources
Presentation slides are uploaded to the reprository
MSSQLTips’ Surrogate Key vs Natural Key Differences and When to Use in SQL Server(https://www.mssqltips.com/sqlservertip/5431/surrogate-key-vs-natural-key-differences-and-when-to-use-in-sql-server/) was especially helpful in preparation for this project

