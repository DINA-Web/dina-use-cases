# 07. Add a PCR reaction

## Background/Motivationn

A user wants to enter a new PCR reaction for a sample.

## Actors
Lab technician

## Preconditions
- [01. Add a sample](01-Add_a_sample.md)
- [03. Add a PCR batch](03-Add_a_PCR_batch.md)

## Course of events
1. The user selects the sample to which the PCR reaction will be applied
1. The user selects the PCR Batch
1. If required, the user overides values of the gene region and primers from the PCR batch

## Alternative paths


## Success post-conditions

1. A unique identifier is assigned to the PCR reaction information
1. The PCR reaction information is saved in the database
1. The PCR reaction is linked to the sample
1. The PCR batch is linked to the PCR reaction

## Notes

## Model treatment