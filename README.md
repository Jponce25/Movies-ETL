# Movies-ETL

We use the ETL (Extract, Transform, Load) method to Collect, Import, and Process Data in order to clean and move information between databases. The objective was to create a data pipelines that transform and moves data from a source to a destination. Usually create data pipelines is often the first step before any analysis can be performed.

## ETL process is divided into three phases: Extract, Transform, and Load. 

- In the Extract phase, data is pulled from external or internal sources, the sources could be flat files, scraped webpages in HTML or JavaScript Object Notation (JSON) format, SQL tables, or even streams of sensor data.

- In the Transform phase, te data may need to be filtered, parsed, translated, sorted, interpolated, pivoted, summarized, aggregated, merged, or more. The goal is to create a consistent structure in the data. The transformation phase can be accomplished with Python and Pandas and even using regular expressions (Regex) to parse data and to transform text into numbers.

- Finally, after the data is transformed into a consistent structure, it's loaded into the data target. The data target can be a relational database like PostgreSQL. This final phase is called the Load.

The project requires us to gather data from both Wikipedia and Kaggle, combine them, and save them into a SQL in order to have a usable database for a hackathon. Our information needs to be cleaned and put in a structured format to be used, having a data-cleaning strategy based on three key steps: plan, inspect, execute will help us to solve de problem. 

When our data are cleaned up and is in tabular formats with the right data types for each column, we can join them together. Finally we need a way to make the data accessible for the hackathon, we choose to provide a SQL database to the participants. 
