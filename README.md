## DBREI - Defensive Back Reactive Execution Index

### DBREI Background

In the NFL, the defensive back position is one of the most challenging positions in an offense-oriented league where DBs require patience, quick reaction, and strategic execution to prevent completions, but many metrics do not isolate what happens after the ball is released. Traditional metrics only cover statistics such as completions allowed by DBs without uncovering true DB movement and tracking.

DBREI (Defensive Back Reactive Execution Index)  quantifies DB reaction and execution efficiency while the ball is in the air. Through isolation of post-release movement from pre-release context, DBREI reflects which DBs excel when the race to the catch point begins.

### Instructions to Run Code

The source code can be found in the src folder with the notebook **NFL_BDB_DBREI_Code.ipynb** uploaded in this folder. There are two required changes to ensure that the code is functional for outside users.

1) Download the data for the NFL BDB 2026 Analytics (instructions will be found in the data section of the competition): https://www.kaggle.com/competitions/nfl-big-data-bowl-2026-analytics/data
2) Download the NFL_BDB_DBREI_Code notebook and navigate to the DATA FETCHING AND CLEANING section of the notebook
     - Here, change path_to_data to the path where the training data folder is stored
     - Also, change the path for the line sup_df_final = pd.read_csv("ENTER YOUR PATH TO SUPPLEMENTARY DATA")
3) Now, you should be able to run through the entire notebook. For any questions please feel free to reach out through linkedin: https://www.linkedin.com/in/sarveshg30/

