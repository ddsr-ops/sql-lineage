# Unified DataSet Lineage Analysis Platform
## Overview

This platform aims to provide the functionality of analyzing dataset lineage of SQL statement. The engines of the platform manipulate SQL events which are produced by restful emitter or kafka emitter, then deliver lineage result to various sink, such as DataHub, Neo4j graph database.
This is a tool platform, capabilities such as retrieve, search, scan, even modification are not considerable for me. It is for integrate with

## Features 

1. Multiple database dialects support, MySQL(Doris) as first
2. Easy to Use: provide a visualization endpoint where users can observe the relationship of datasets 
3. Easy to integrate: Kafka as the communication channel that connects other systems easily
