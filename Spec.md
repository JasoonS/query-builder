# HyperSync Query Builder

## Requirements

The idea is to build a query builder that should be used for HyperSync. It should give an intuitive flow and UI to create these queries.

First the user will have to define filters in filters for logs, transactions and blocks. 

We will start this process with the creation of a simple query initially defining the filters for logs, transactions and blocks and determining which fields to be selected.

The user will select drop downs and construct a query which will be then represented in memory by the code. Then there will be options to view the constructed query either as JSON (curl query)or as it would look in the various languages from Python, Rust, and TypeScript.

