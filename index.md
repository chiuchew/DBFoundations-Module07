# Title
**Dev:** HChew

**Date:** 2021-08-13

## Introduction
This paper will walk through when to use a SQL User Defined Function (UDF) and the differences and similarities between the various UDFs: Scalar, Inline, and Multi-Statement Functions.  

## When To Use SQL UDF
A UDF accepts parameters and returns the result as an output. UDFs are used in programming SQL code and it allows writing up queries fast. 

## Differences & Similarities Between Scalar, Inline, and Multi-Statement Functions
Scalar user-defined functions return a single value. They will always contain a RETURNS clause in it. Multi-Statement Functions syntax is like the scalar user-defined function but instead provides multi-values as the output. Inline table values functions are performance optimized functions. They do not contain table definitions. Instead, the subquery within the inline table value function is a single statement, therefore, it does not provide any performance issues when we use it batches or in loops.

## Summary
A SQL UDF has three different types of functions: scalar, inline and multi-statement functions. For an optimal performance, it is best to use the inline function because an inline table-valued function returns a variable of data type table whose value is derived from a single SELECT statement. There is no need to specify the table variable name because the structure of the returned value is generated from the columns that compose the SELECT statement.


```
--*************************************************************************--
-- Title: Assignment07
-- Author: Helena
-- Desc: This file demonstrates how to use Functions
-- Change Log: 2021-08-13,Helena Chew, How to Use Functions
-- 2021-08-13,Helena Chew,Created File
--**************************************************************************--

print("Built-In Python error info: ")
    print(e, e.__doc__, type(e), sep='\n')
```
#### Question 8

                        
![Results of Question 8](https://github.com/chiuchew/DBFoundations-Module07/blob/main/Assignment07_image.JPG "Results of Question 8")#### Question 8. The results of Question 8
