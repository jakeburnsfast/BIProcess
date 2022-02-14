## Cloud BI Service: Full Implementation
---
### Source data extraction through report delivery 
##### Simple | Durable | Transferable
<br>

## Pricing
#### Fixed price based on:
* Number / nature of source systems
* Landscape of desired reporting
* Complexity of transforms

## Process
#### Seven phases of development:
* Design (metrics needed, source systems, cloud infrastructure)
* Extract (attach applications / pipelines to source data)
* Load (replicate source data in data lake)
* Stabilize (optimize performance/cost, ensure daily synchronization)
* Transform (build simple star schema data models to enable reporting)
* Validate (confirm the data models produce accurate metrics)
* Present (deliver metrics through reporting interface)

## Platform
#### Microsoft Azure family of resources:
* Full toolset (extraction, staging, modeling, reporting)
* Integration friendly  (data sources / non native languages)
* Reasonable / flexible cost options 
<br> <br>


# Implementation Phases
### 1. Design
>* Meet with client to review desired metrics
>* Guage in-house technical skill and capacity to support the project
>* Review source systems needed to produce the metrics
>* Align with client on what constitutes a reasonable Phase 1
>* Develop detailed roadmap and pricing (20-40 hours, **$4,000 up-front cost**)
>* Meet with client to review and determine next steps
>* Simple (text and diagrams), Durable (should keep relevance for ~2 years), Transferrable (well-documented)

### 2. Extract
>* Obtain access to client networks / source data
>* Author applications required to extract data into the pipeline(s)
>* Set up pipeline(s) to move the data from source into a data lake
>* Reformat data (if necessary) into common format (CSV/JSON/SQL)
>* Simple (control tables, low code pipelines), Durable (use core Azure tools), Transferable (best practice used and well-documented)

### 3. Load
>* Identify the newly staged data necessary to drive reporting
>* Load extracted data into cloud data lake
>* Convert extracted data to SQL friendly format as required
>* Ensure source data is replicated properly in the data lake
>* Simple (minimize custom code), Durable (Microsoft leading cloud technologies), Transferable (Microsoft technologies)

### 4. Stabilize
>* Study performance and cost of the extract and load processes
>* Optimize storage / processing technologies if necessary
>* Set up delta loading logic if necessary (for larger datasets)
>* Set triggers to run at least once daily and monitor performance
>* Set up alert emails detailing the success/failure of the daily runs
>* Simple (match client source row for row), Durable (alerts and results stored in easily accessible tables), Transferrable (well documented)

### 5. Transform
>* Review star schema data models presented in the roadmapping phase
>* Transform staged data into required dimension SQL objects
>* Transform staged data in required fact SQL objects
>* Write in any additional business logic needed for reporting
>* Test the integrity of the final reporting dataset (duplication, granularity)
>* Simple (1 star schema per reporting area), Durable (clean, organized code), Transferable (star schema is widely understood)

### 6. Validate
>* Obtain client reporting that is trustworthy 
>* Match the output of the new data model to the client reporting
>* Meet with client several times to discuss discrepancies
>* Obtain formal client sign off on accuracy of the data models
>* Simple (spreadsheet based comparisons), Durable (repeatable process established at start of validation), Transferrable (discrepancies well-documented)

### 7. Present
>* Build reporting environment (licensing, workspaces, client access)
>* Agree on a design standard (colors, slicers, visuals, etc.)
>* Attach to data model(s) and author final calculations and KPIs
>* Meet with the client 2-3 to collaborate
>* Validate the reports
>* Obtain sign off
>* Relase reports and documentation

Test image
![](https://github.com/jakeburnsfast/BIProcess/blob/main/Test%20Image.png "Okey Dokey")