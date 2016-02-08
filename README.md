# Plesk database schemas

## About

This repository contains Plesk database schemas, explaining the structure of Plesk database and relations between tables.

## Contents

The three files contain the database schema in three different formats:

- `psadb.xml` - XML description of the database structure.
- `psadb.svg` - SVG file depicting general structure and relations inside the Plesk database.
- `psadb.mwb` - MySQL Workbench project file for Plesk database.

## How to view .mwb file

To view the MySQL Workbench project file:

1. [Download](https://www.mysql.com/products/workbench/) and install MySQL Workbench (free).
2. Download the `psadb.mwb` file from this repository.
3. Open the `psadb.mwb` in MySQL Workbench: **File > Open Model**.

Using MySQL Workbench is a recommended way to view Plesk database schema, since it allows you interacting with the schema, 
hiding unnecessary tables, view additional information, and better track links between two tables.

