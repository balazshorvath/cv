## Contact

|                                  Name                                   |                      **Balázs** Péter Horváth                       |
|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|
|                                Location                                 |                              Budapest                               | 
|                                Languages                                |                           English, German                           | 
|                                  Email                                  |                   balazs.peter.horvath@gmail.com                    | 


_[LinkedIn](https://www.linkedin.com/in/balazs-peter-horvath-275121110/) - [Github](https://github.com/balazshorvath)_

Latest version of this CV is also available on _[Github](https://github.com/balazshorvath/cv)_.

## Introduction
I am a Software Engineer who specializes in server development. I have expertise in multithreaded applications, networking, and web APIs.

I am a versatile developer, usually using multiple programming languages and tools, but here is a list of technologies I am most familiar with:

|                              Go                              |                                Containerization                       |                                   SQL                                    |                            AWS/GCP                            |
|:------------------------------------------------------------:|:---------------------------------------------------------------------:|:------------------------------------------------------------------------:|:-------------------------------------------------------------:|
| Most recent and up-to-date experience (also preferred/loved) | I feel like containerization of a service has become a default by now | Primarily worked with PSQL recently | Have always been using either platform in the past years |

I usually have some sort of a hobby project to test new technologies, ideas.
In recent years I have been working on a trading system, tested some design ideas for an event sourcing ledger.
As part of that project learned about TigerBeetle and for fun, implemented a message queue using TigerBeetle for this event sourced ledger. 
As maybe a slightly less exciting hobby, I also like to build computers (home servers, or just for personal use).

## Employment/Project History

### Alpaca, Budapest 2024 -
Working as part of the clearing and settlements team. 

- Maintenance of:
  - Existing self clearing systems (DTC)
  - Services supporting stock lending programs
- Implementation of new partner integrations for:
  - Fully Paid Securities Lending program
  - Self clearing options (OCC)
- Implementation of other supporting systems:
  - File/Report processing system to improve monitoring and maintenance needs
  - Generic trade matching system

###### Technologies: Go, Containers, Postgres, GCP, Redpanda, DTC, OCC, FIS

### Odum Research, London 2021 - 2024
I helped building an end-to-end trading platform with many supporting systems.

Responsibilities included:
- Integration with various crypto exchanges (rest, websocket, FIX) in Go.
- Implementation of 
  - Internal monitoring, benchmarking, automated testing, simulation systems.
  - Automated exchange connectivity/latency testing (ip hunting, testing various machine types, etc.).
  - Position monitoring and alerting system.
  - Semi-automated cash balancing system between exchanges.
- Optimization of parts of the High Frequency Trading code like networking, zero alloc message parsing (a notable example is a DPDK wrapper for Go with custom built AWS VM image)

###### Technologies: Go, Python, MongoDB, BigQuery, Dataflow, Gitlab CI, Docker, Kubernetes, GCloud, AWS, Grafana, DPDK

### Pressenger Kft., Budapest 2021 - 2021
Complete modernization of the infrastructure, codebase of multiple separate software components.
Development of CI/CD pipelines.

###### Technologies: Java, Go, Php, MySQL, Gitlab CI, Docker, AWS

### Splendex Kft., Budapest 2018 - 2021
Worked as a contractor, or directly with the team on various projects.

- Developed a social idea sharing web application using Spring Boot, Java 8. The platform’s main feature is the organization of idea competitions, where employees may submit solutions to problems and can collaborate with the organizers to win the competition.

  ###### Technologies: Docker, Jenkins pipeline, SQL Server, Liquibase, ADFS SAML.
- Supported and developed features for a web application written in Java 8, Spring boot.
  The product is a company search platform for investors providing detailed information/analysis about said companies.

  ###### Technologies: Docker, Jenkins pipeline, AWS CodeDeploy, AWS S3, Elasticsearch, Postgres, Flyway.
- Supported an enterprise application for a multinational company.
  The application is used by big telecommunication companies, 
  it allows for their support team to analyze anomalies with their mobile network.

  ###### Technologies: Java EE, GWT, Postgres, Jboss, HBase
- Developed a dashboard application for management for a multinational company in Go.
  The application collects and reports about the development processes, statuses of various teams.

  ###### Technologies: Go, Docker, Postgres, Jira API, Jenkins API, Elasticsearch
- Developed a web service for a delivery company, with integration to multiple eCommerce apis.
  
  ###### Technologies: Dotnet Core, C#, SQL Server.
    
  ###### APIs: Shopify, Shoprenter, WooCommerce, UNAS, eMag.

### Toptal, 2018 -
Became a member of the Toptal community as a developer.

### Nuance-Recognita  Ltd., Budapest 2017 - 2018
Developed a printer management software in Java EE.
Built the front-end on web based multifunction printers.

###### Technologies: Java EE, MSSQL, JavaScript

### Software Integrator, BOSCH, Budapest 2016 - 2017
Created a C library interface definition in AUTOSAR.

###### Technologies: C, AUTOSAR, DOORS

### Java Programmer, MI Software, Budapest 2016 - 2016
- Developed features for a management/financial application.
- Created an application for tracking company and people relationships.
- Supported a back-end for a mobile application for a mobile service provider.
###### Technologies: Spring, IceFaces, MySQL, Oracle, Neo4j

### Java Programmer, Black Horse Group, Budapest 2015 - 2016
Developed the back-end for an online educational application.
Configured Ubuntu servers (VPN, DNS, firewall, etc.).

###### Technologies: Scala, Spring, MongoDB, Redis, Neo4j

### Web Developer, 365Solutions, Pécs 2014 - 2014
Built a website using an internal PHP framework. Supported a legacy eCommerce website.

###### Technologies: PHP, HTML, JavaScript, jQuery, CSS, MySQL, SVN

## Education

### Bachelor's Degree - Computer Engineering - University of Pécs (2012 - 2016)
My thesis project was an MMORPG server which was completed in collaboration with another developer.
The server was developed over the course of 1.5 years and included building the application from the ground up three times.
We originally used C/C++ and later decided to use Unity and Java.

This project taught me a lot about networking and multithreading. 

The result was pretty simple: a user could log in, create a character, and find and kill other players.

###### Technologies: C/C++, Java, TCP/UDP

### Master's Degree - Computer Engineering - University of Pécs (2017 - 2019)
My thesis for my master's degree was to develop a classification method for recognizing limb movement from EMG signals collected specifically with a MyoArmband.

Based on available studies, I compared various neural network configurations with different features of EMG signals.

###### Technologies: Go (data parsing/processing), Python (MLP training - Tensorflow)


