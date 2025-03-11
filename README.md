# ETL Pipeline for Analyzing YouTube Video Data

## Project Overview
This project is an ETL (Extract, Transform, Load) pipeline designed to analyze YouTube video statistics. The pipeline extracts data from the YouTube API, processes it using Pandas, and stores it in a database for further analysis.

## Workflow
1. **Extract**: Fetch video statistics (views, likes, comments) from the YouTube API.
2. **Transform**: Clean and process the data using Pandas (e.g., formatting timestamps, handling missing values).
3. **Load**: Store the transformed data into an SQLite or PostgreSQL database.
4. **Analyze**: Perform basic analytics and visualize trends using Matplotlib.
5. **Automate**: Schedule and manage the ETL pipeline using Apache Airflow.

## Technologies Used
- **Python**: Core programming language for data processing.
- **Pandas**: Data manipulation and transformation.
- **YouTube API**: Extracting video statistics.
- **SQLite/PostgreSQL**: Database for storing processed data.
- **Matplotlib**: Visualization of video trends.
- **Apache Airflow**: Automating and managing the pipeline workflow.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/akashavcoewala/ETL-pipeline-project
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up API credentials for YouTube API.
4. Configure database connection (SQLite or PostgreSQL).
5. Run the ETL pipeline script:
   ```sh
   python etl_pipeline.py
   ```

## Future Enhancements
- Implement real-time streaming with Kafka.
- Deploy the pipeline using Docker and Kubernetes.
- Add more advanced analytics and machine learning models for trend prediction.

## Author
Akash Raut

