# Service: BI Implementation
### Cloud business intelligence solution from source data extraction through report adoption
#### Simple | Durable | Transferable
<br>

## Pricing
#### Fixed price based on:
* Number / nature of source systems
* Landscape of desired reporting
* Complexity of transforms

## Process
#### Seven phases of development:
* Design (metrics needed, source systems, cloude infrastructure)
* Extract (attach applications / pipelines to source data)
* Load (deposit source data to data lake in SQL friendly format)
* Stabilize (optimize performance and cost, ensure successful daily runs)
* Transform (build star schema data models to support needed KPIs) (single fact if possible, for simplicity & transferability)
* Validate (confirm the intelligence is accurate)
* Present (deliver KPIs through reporting interface)

## Platform
#### Microsoft Azure family of cloud resources:
* Full toolset (extraction, staging, modeling, reporting)
* Recent integrations with many data sources / non native languages
* Reasonable / flexible costs 
<br> 


# Development Phases
### 1. Design
>* Meet with client to review current **and** desired KPIs
>* Understand in-house technical abilities and capacity to support the project
>* Review of source systems needed to drive the KPIs identified
>* Align with client on what constitutes a reasonable Phase 1
>* 20-40 hours to develop detailed roadmap and pricing **$4,000 up-front cost**
>* Meet with client to review roadmap.  Determine if the project will move forward
>* Simple (text and diagrams), Durable (should keep relevance for ~2 years), Transferrable (well-documented)

### 2. Extract
>* Obtain stable access to client source data
>* Author applications / flow required to extract data into the pipeline(s)
>* Author any processes required to reformat data into common format (CSV/JSON/SQL)
>* Simple (control tables, low code pipelines), Durable (use popular Azure tools), Transferable (best practice used and well-documented)

### 3. Load
>* Identify the newly staged data necessary to drive reporting
>* Load extracted data into cloud data lake
>* Convert extracted data to SQL friendly format as required
>* Ensure source data is replicated properly in the data lake (via row-counts if possible)
>* Simple (minimize custom code), Durable (Microsoft leading cloud technologies), Transferable (Microsoft technologies)

### 4. Stabilize
>* Study performance and cost of the extract and load processes
>* Optimize storage / processing technologies if necessary to decrease cost or increase speed
>* Set up delta loading logic if necessary (and subsequently, daily checksum & delete management procedures)
>* Set triggers to run at least once daily and monitor performance
>* Set up alert emails detailing the success/failure of the daily runs
>* Simple (match client source row for row), Durable (alerts and results stored in easily accessible tables), Transferrable (well documented)

### 5. Transform
>* Review star schema data models presented in the roadmapping phase
>* Transform staged data into required dimension sql objects
>* Transform staged data in required fact sql objects
>* Write in any additional business logic needed for reporting
>* Test the integrity of the final reporting dataset (relationships, duplication, granularity)
>* Simple (1 star schema per reporting area), Durable (clean, organized code), Transferable (star schema is widely understood)

### 6. Validate
>* Obtain any trusted client reporting that is actively used and trustworthy 
>* Match the KPI output of the reporting datasets to the client reporting
>* Make adjustments and correct errors as needed
>* Meet with client several times to review final results and discuss justification for any discrepancies
>* Obtain formal client sign off on the validation and the KPI accuracy
>* Simple (spreadsheet based comparisons), Durable (repeatable process established at start of validation), Transferrable (discrepancies well-documented)

### 7. Present
>* Build client reporting environment (licensing, workspaces, client access)
>* Work with client to agree on a design standard (colors, slicers, visual types, interactivity)
>* Attach to reporting datasets and author the necessary measures / calculations / KPI indicators
>* Meet with the client 2-3 times throughout development
>* Validate the reports against the data lake
>* Obtain client sign off
>* Relase reports