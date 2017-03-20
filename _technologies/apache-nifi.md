---
title: "Apache NiFi"
description: "General purpose technology for the movement of data between systems, including the ingestion of data into an analytical platform. Based on directed acyclic graph of Processors and Connections, with the unit of work being a FlowFile (a blob of data plus a set of key/value pair attributes).  Supports guaranteed delivery of FlowFiles, with NiFi resiliently storing state (by default to a local write ahead log) and data blobs (by default a set of local partitions on disk), with all transformation logic executed via a thread pool within the NiFi instance (with the option to deploy multiple NiFi instances as a cluster). All flows are configured in a graphical user interface, which is also used for management and operations (starting/stopping individual Processors and viewing real time statuses, statistics and other information).  Also supports data provenance (reporting on the processing events and lineage of individual FlowFiles), scheduling of Processor execution (based on periodic execution timers or cron specifications), multi-threaded Processor execution, configuration of Processor batch sizes (to enable low latency or high throughput), prioritised queues within Connections (allowing FlowFiles to be processed based on their age or a priority attribute as an alternative to FIFO), back pressure (based on counts or data volume against individual Connections) and pressure release (automatic discarding of FlowFiles based on their age), the ability to stream data to and from other NiFi instances and other streaming technologies, the ability to import and export flows as XML (flow templates), an expression language for setting Processor configuration and populating FlowFile attributes, Controller Services to provide shared services to processors (e.g. access to credentials, shared state), Reporting Tasks to output status and statistics information and a user security model.  Extensible through the addition of custom Processors, Controller Services, Reporting Tasks and Prioritizers, and integrates with Apache Ranger and Apache Ambari. Originally developed at the NSA as \"Niagara Files\", before being donated to the Apache Foundation in November 2014, graduating in July 2015. Java based, with development lead by Hortonworks after their aquisition of Onyara (which was set up by original NiFi developers to provide commercial support and services)."
alt-titles: [NiFi]
vendors: [Apache]
type: "Commercial Open Source"
date: 2017-03-15 07:30
version: "v1.1"
---
## Links

* <http://nifi.apache.org/> - home page
* <http://nifi.apache.org/docs.html> - documentation
* <https://hortonworks.com/apache/nifi/> - Hortonworks information, including tutorials and blog posts
* <http://docs.hortonworks.com/HDPDocuments/HDF2/HDF-2.1.0/index.html> - Hortonworks documentation (as part of HDF)
* <https://cwiki.apache.org/confluence/display/NIFI/Release+Notes> - release notes

## News

* Blog updates via the Hortonworks blog