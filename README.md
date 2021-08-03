# VLDB Summer School 2021 Labs

## Introduction

This is the labs of VLDB Summer School 2021. The main target of is implementation of the distributed transaction.

There are several modules in a distributed database.

- TinyKV, the storage engine of the system.
- TinyScheduler, it is used to manager and schedule TinyKV cluster.
- TinySQL, the SQL layer of TinyKV engine.

## Labs

There are 4 labs in this course.

- [Lab1](./tinykv/doc_ss/lab1.md), implement the storage and log layer in TinyKV.
- [Lab2](./tinykv/doc_ss/lab2.md), implement the transaction layer in TinyKV.
- [Lab3](./tinysql/doc_ss/lab3-README-zh_CN.md), implement the Percolator protocol.
- Lab4, implement the SQL execution layer.
    - [Lab4 A](./tinysql/doc_ss/lab4a-README-zh_CN.md), implement SQL protocol.
    - [Lab4 B](./tinysql/doc_ss/lab4b-README-zh_CN.md), implement update executor.
    - [Lab4 C](./tinysql/doc_ss/lab4c-README-zh_CN.md), implement select and projection executor.
