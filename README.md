# People Data Labs API Specifications

This repository contains the specification file for [People Data Labs APIs](https://docs.peopledatalabs.com/).

In order to use the APIs, you need to have an API key. You can get the API key by signing up on the [People Data Labs Website](https://dashboard.peopledatalabs.com/).

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/32867294-ef278c05-d32d-47a1-b147-b819bc96238a?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D32867294-ef278c05-d32d-47a1-b147-b819bc96238a%26entityType%3Dcollection%26workspaceId%3Dbbcb7a7c-1696-4864-8cb7-5163c79dd459)

## API Endpoints

### Person

[Person Enrichment API](https://docs.peopledatalabs.com/docs/person-enrichment-api)

The Person Enrichment API enables you to enrich data on a person by performing a one-to-one match of this person with the nearly three billion individual profiles that are hosted in our dataset.

[Person Search API](https://docs.peopledatalabs.com/docs/person-search-api)

The Person Search API gives you access to every profile in our full Person Dataset, which you can filter and segment using a search query.

[Person Identify API](https://docs.peopledatalabs.com/docs/person-identify-api)

The Person Identify API allows you to use broad search inputs to retrieve multiple records from our person dataset. In particular, this endpoint enables functionality such as searching through a single identifying attribute, such as name, email, phone number, company, school or location, in addition to using any combination of these attributes and more. The API then scores and sorts all matching records that it returns based on the strength of their association with the input parameters.

### Company

[Company Enrichment API](https://docs.peopledatalabs.com/docs/company-enrichment-api)

The Company Enrichment API lets you enrich data on a company by performing a one-to-one match of this company with the numerous company profiles that are hosted on our site.

[Company Search API](https://docs.peopledatalabs.com/docs/company-search-api)

The Company Search API gives you access to every record in our full Company Dataset, which you can filter and segment using a search query.

### IP

[IP Enrichment API](https://docs.peopledatalabs.com/docs/ip-enrichment-api)

The IP Enrichment API enables you to enrich data on a IP by performing a one-to-one match of this IP with the nearly 2 Billion IPs hosted in our dataset. Once matched, you can view the location, company, and metadata info associated with the IP address.

### Supplemental

[Autocomplete API](https://docs.peopledatalabs.com/docs/autocomplete-api)

The Autocomplete API allows you to get suggestions for Search API query values along with the number of available records for each suggestion. For example, schools starting with "stanf".

[Job Title Enrichment API](https://docs.peopledatalabs.com/docs/job-title-enrichment-api)

The Job Title Enrichment API lets you enrich data on a job title by performing a one-to-one match of this job title with those included in our Job Title Dataset.

[Skill Enrichment API](https://docs.peopledatalabs.com/docs/skill-enrichment-api)

The Skill Enrichment API lets you enrich data on a skill by performing a one-to-one match of this skill with those included in our Skill Dataset.

[Company Cleaner API](https://docs.peopledatalabs.com/docs/cleaner-apis-reference)

Clean input data can make a big difference when it comes to retrieving the best results from your queries. With our Company Cleaner API, you can clean the company data that you employ in your API queries.

[Location Cleaner API](https://docs.peopledatalabs.com/docs/cleaner-apis-reference)

Clean input data can make a big difference when it comes to retrieving the best results from your queries. With our Location Cleaner API, you can clean the location data that you employ in your API queries.

[School Cleaner API](https://docs.peopledatalabs.com/docs/cleaner-apis-reference)

Clean input data can make a big difference when it comes to retrieving the best results from your queries. With our School Cleaner API, you can clean the school data that you employ in your API queries.
