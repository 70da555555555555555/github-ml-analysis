## Ethics Reflection
Question 1: Why is it important to verify data collected from public APIs?
Answer:

Public APIs provide raw data from external systems, which means the data can contain unexpected errors, missing values, or network corruption. Verifying public API data is important because:

Accuracy: Network dropouts or rate limits can cause incomplete data downloads.

Schema Updates: API developers often update field names or data formats, which can break analysis scripts if not verified.

Bias & Timeliness: API data may be cached or reflect specific sampling biases that need to be identified before drawing conclusions.

Question 2: Why should data analysts document the source of their data?
Answer:

Documenting data sources is essential for establishing transparency, credibility, and reproducibility:

Reproducibility: Recording the exact API endpoints, parameters, and access timestamps allows other analysts to re-run the pipeline and verify the results.

Credibility: Clear documentation builds trust with stakeholders by proving where the information originated.

Auditability: If questions arise about data licensing or accuracy, documentation provides a clear audit trail.

Question 3: How can missing or inaccurate data affect data analysis and decision-making?
Answer:

Working with missing or inaccurate data undermines the entire analytical workflow:

Skewed Results: Unaddressed missing values or incorrect data types alter key statistics like averages, correlations, and machine learning model predictions.

Bad Decisions: Businesses or researchers rely on analytical outputs to make real-world decisions. Flawed data can lead to wrong strategy choices and wasted resources.

Loss of Trust: Stakeholders lose confidence in an analyst's work if reports contain uncorrected errors or unsupported claims.
