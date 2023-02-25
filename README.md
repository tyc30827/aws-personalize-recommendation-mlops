# aws-personalize-recommendation-mlops
A repository about how to apply automatic workflow to personalized recommendation task with the usage of Amazon Personalize

## AWS service
- Personalize
- S3
- Kinesis Data Firehose
- Athena
- Lambda

## Open-source package
- Apache Airflow
- Apache Superset
- MLflow

[TO-DO]
- Upload data to Personalize
    - Interaction, Item, User data
    - source
        - real-time interaction
            - upload events directly from Kinesis Data Firehose
        - batch import
            - S3
            - Athena (SQL)
- Train model
    - (Automatic) train and fine-tune solution version (model) of Personalize
- Inference
    - Get recommendation result from Personalize
        - batch inference
        - real-time recommendation (Campaign)
- Visualization
    - Superset
