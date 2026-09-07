# AuditAgent
Multi-agent audit pipeline analyzing real Oklahoma state P-Card spending data. SQL flags anomalies (duplicate payments, threshold-skirting, statistical outliers); an Investigator agent writes its own SQL to gather evidence; a Reviewer agent independently verifies findings before they reach the final exception report. Alteryx handles data prep.
