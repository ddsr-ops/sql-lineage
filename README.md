# Unified SQL Lineage Analysis Platform

## Overview

This platform aims to provide the functionality of analyzing dataset lineage of SQL statement. The engines of the platform manipulate SQL events which are produced by restful emitter or kafka emitter, then deliver lineage result to various sinks, such as DataHub, Neo4j graph database.

This is a tool platform, such capabilities like retrieve, search, scan, even modification are not considerable for me. It is for integrate with data platforms, with the extensible capability of sql lineage analysis. Yes, It is a supplement, not a substitution for some components of data platform.  

## Features 

1. Multiple database dialects support, MySQL(Doris) as firstly considerable
2. Easy to Use: provide a visualization endpoint where users can observe the relationship of datasets 
3. Easy to integrate: Kafka as the communication channel that connects other systems easily
