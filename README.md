# SQL Data Warehouse Project

An end-to-end Data Warehouse project built with SQL Server, focusing on ETL development, data cleansing, data modeling, and analytics.

The project follows a Medallion Architecture with three layers:

- Bronze Layer – Raw data ingestion from source systems
- Silver Layer – Data cleansing, standardization, and transformation
- Gold Layer – Business-ready data modeled using a Star Schema

## Architecture

Source Systems
      ↓
Bronze Layer
      ↓
Silver Layer
      ↓
Gold Layer
      ↓
Analytics & Reporting

## Key Concepts

- Data Warehouse Architecture
- ETL Pipeline
- Medallion Architecture
- Data Cleaning & Transformation
- SQL Server
- Stored Procedures
- Data Modeling
- Star Schema
- Fact & Dimension Tables
- Data Quality
- Data Documentation

## Project Structure

datasets/
├── source datasets

docs/
├── data architecture
├── data flow
├── data catalog

scripts/
├── bronze
├── silver
└── gold

tests/
├── data quality checks

README.md
