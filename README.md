# Unexpected Null Handling in Addition Function

This repository demonstrates an issue with null handling in a simple JavaScript addition function. The `foo` function attempts to add two numbers but does not correctly handle null input values. The provided solution improves the null handling to return 0 in case of null values. 

## Bug Description
The `foo` function is expected to add two numbers, but it produces unexpected `null` outputs when one or both input values are null. The expected behavior is a more robust handling of null values, either returning 0, throwing an error or explicitly handling the situation.