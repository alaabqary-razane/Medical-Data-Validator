This project validates structured patient records by enforcing data format rules, required keys, and value constraints.

Features:

-Validates that medical records are provided as a list of dictionaries

-Ensures each record contains all required fields with no missing or extra keys

-Checks data types and value constraints (IDs, age, gender, medications, etc.)

-Uses regular expressions to validate patient and visit identifiers

-Identifies and reports unexpected or invalid field values with precise record indexing

-Returns detailed feedback to help detect and debug malformed medical data
