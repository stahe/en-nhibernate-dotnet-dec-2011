# Introduction to the NHibernate Framework for the .NET Platform

[Introduction to the NHibernate Framework for the .NET Platform (2011)](https://stahe.github.io/en-nhibernate-dotnet-dec-2011/)

This repository accompanies an introductory course on **NHibernate**, presented as the .NET equivalent of the Java **Hibernate** framework. The document provides a concise overview of using an **ORM** (*Object Relational Mapper*) in the .NET ecosystem.

## Overview

An ORM is a set of libraries that allows a database-driven application to manipulate the database **without explicitly writing SQL queries** and **without depending on the specifics of the DBMS used**.

This material serves as a **brief introduction** to NHibernate. For a more in-depth study, the document recommends the following book:

- **NHibernate in Action**
- **Author**: Pierre-Henri Kuaté
- **Publisher**: Manning
- **ISBN-13**: 978-1932394924

## Level and Prerequisites

On a **beginner / intermediate / advanced** scale, this document is at the **intermediate** level.

Understanding it requires several prerequisites, including:

1. **C# 2008**  
   *Learning the C# 3.0 language with the .NET 3.5 Framework*

2. **Spring IoC for .NET**  
   Introduction to the basics of **Inversion of Control (IoC)** and **Dependency Injection** with **Spring.NET**

The document also includes, at the beginning of certain paragraphs, recommended reading references to these prerequisite resources.

## Tools Used

The case study relies on tools freely available on the web, in the versions listed as of **December 2011**:

- **NHibernate 3.2**
- **Spring.NET 1.3.2**  
  Used here for libraries that facilitate the use of NHibernate
- **log4net 1.2.10**  
  Logging framework used by NHibernate
- **NUnit 2.5**  
  Unit testing framework, the .NET equivalent of JUnit
- **ADO.NET Driver 6.4.4 for MySQL 5**

## Course Objective

This course aims to introduce the basics of **NHibernate** in a .NET context, demonstrating how to simplify data access through an object-oriented approach, while leveraging complementary configuration, logging, and testing tools.

