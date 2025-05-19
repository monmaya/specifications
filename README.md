Data-related referential management service - Specifications
============================================================

# Table of Content (ToC)
* [Overview](#overview)
* [References](#references)
  * [Data products](#data-products)
  * [Data contracts](#data-contracts)
* [Test the API](#test-the-api)

# Overview
[This project](https://github.com/monmaya/specifications) aims at specifying,
in a open and transparent way, services to manage a referential for data-related
objects, like for instance data products, data contracts, data quality specifications,
data quality reports, data metrics, Service Level Objectives (SLO) and, more generally,
any type or concept appearing at a high level in data contracts.

Reference implementation: https://github.com/monmaya/base-impl

Even though the members of the GitHub organization may be employed by some companies,
they speak on their personal behalf and do not represent these companies.


# References

## Data products
* Linux Foundation's Open Data Product Specification (ODPS): https://opendataproducts.org/
* Innoq's specification for Data Products: https://dataproduct-specification.com/
* Open Data Mesh (ODM)'s Data Product Descriptor Specification (DPDS): https://github.com/opendatamesh-initiative/odm-specification-dpdescriptor

## Data contracts
* Open Data Contract Specification (ODCS)
  * Reader-friendly, dedicated site: https://bitol-io.github.io/open-data-contract-standard/latest/
  * GitHub home page: https://github.com/bitol-io/open-data-contract-standard
* Innoq's Data Contract specification: https://datacontract.com/
* [Andrew Jones' Git repository supporting his book about data contracts](https://github.com/PacktPublishing/Driving-Data-Quality-with-Data-Contracts)
  * [Andrew Jones' Git repository supporting his book about data contracts - Chapter 08: samples of contracts for customer profiles](https://github.com/PacktPublishing/Driving-Data-Quality-with-Data-Contracts/tree/main/Chapter08/contracts)
  * [Andrew Jones' Git repository supporting his book about data contracts - Chapter 03: samples of contracts for order events](https://github.com/PacktPublishing/Driving-Data-Quality-with-Data-Contracts/blob/main/Chapter03/order_events.yaml)

 
 # Test the API
 You can test the API using Docker Compose from the base-impl project.
 <br/>Checkout this project then:
 - create a virtual environnement
 - install the libraires (base-impl/requirements.txt file)
 - run the "docker compose up" command
 - The project Swagger is available at the URL http://localhost:8020/docs


## Other repositories of Data Engineering helpers
* [Data Engineering Helpers - Knowledge Sharing - Data products](https://github.com/data-engineering-helpers/data-products)
* [Data Engineering Helpers - Knowledge Sharing - Data contracts](https://github.com/data-engineering-helpers/data-contracts)
* [Data Engineering Helpers - Knowledge Sharing - Data quality](https://github.com/data-engineering-helpers/data-quality)
* [Data Engineering Helpers - Knowledge Sharing - Semantic layer](https://github.com/data-engineering-helpers/semantic-layer)
* [Data Engineering Helpers - Knowledge Sharing - Architecture principles](https://github.com/data-engineering-helpers/architecture-principles)
* [Data Engineering Helpers - Knowledge Sharing - Data life cycle](https://github.com/data-engineering-helpers/data-life-cycle)
* [Data Engineering Helpers - Knowledge Sharing - Data management](https://github.com/data-engineering-helpers/data-management)
* [Data Engineering Helpers - Knowledge Sharing - Data lakehouse](https://github.com/data-engineering-helpers/data-lakehouse)
* [Data Engineering Helpers - Knowledge Sharing - Metadata](https://github.com/data-engineering-helpers/metadata)
* [Data Engineering Helpers - Knowledge Sharing - Data pipeline deployment](https://github.com/data-engineering-helpers/data-pipeline-deployment)


