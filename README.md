# dp-700-lab-5-Work-with-data-in-a-Microsoft-Fabric-eventhouse


https://github.com/user-attachments/assets/f5ce3b06-898b-48e0-8459-6c76e285dad7



🧭 Lab Title: Work with data in a Microsoft Fabric eventhouse
🎯 Goal:
Learn how to store and analyze real-time event data using Microsoft Fabric’s Eventhouse feature with KQL and Transact-SQL.

✅ Steps Performed
Workspace Setup

Created a Fabric-enabled workspace in Microsoft Fabric.

Create Eventhouse with Sample Data

Used the “Explore Real-Time Intelligence Sample” option to generate an Eventhouse with a Bikestream table inside a KQL database.

Query Data with KQL

Queried the first 100 records using take.

Selected specific columns using project.

Renamed columns using aliases.

Used summarize to aggregate data like total bikes by neighbourhood.

Handled missing neighbourhood values with case, isempty, and isnull.

Sorted and filtered results using sort by, order by, and where.

Query Data with Transact-SQL

Queried data using SQL syntax via the T-SQL endpoint (read-only).

Performed similar steps as with KQL: column selection, aliases, aggregation, sorting, filtering, and handling nulls using CASE.

Cleanup

Deleted the workspace after the exercise.

💡 Key Learnings
Eventhouses store real-time event data in KQL databases.

KQL is powerful for querying streaming data with real-time insight.

T-SQL can be used for compatibility but is limited in functionality.

Handling nulls, aliases, grouping, and filtering are essential in both query languages.

🌍 Real-Life Use Cases
Smart cities: Monitoring shared bike availability in real-time.

Transportation: Tracking taxi or delivery vehicle activity.

Retail: Analyzing point-of-sale events instantly.

IoT: Visualizing and alerting on live sensor data.
<img width="1440" alt="Screenshot 2025-05-07 at 16 36 54" src="https://github.com/user-attachments/assets/f9592a4c-953e-4f45-9d17-060e24addba1" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 36 28" src="https://github.com/user-attachments/assets/8da14251-424f-4ccb-a381-914d5f77c2d4" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 36 01" src="https://github.com/user-attachments/assets/1b358e83-a3ca-4155-a77b-d67064b40bab" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 35 39" src="https://github.com/user-attachments/assets/9ae041b2-05ec-41a3-bec7-c76d8bd90765" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 33 56" src="https://github.com/user-attachments/assets/7278a9ff-f786-4919-881b-1c7547174f05" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 33 12" src="https://github.com/user-attachments/assets/cd45d993-0af1-40c3-a06d-335b231ace4e" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 33 06" src="https://github.com/user-attachments/assets/75b05877-7734-4b1f-9954-0cf93b5b86c5" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 32 30" src="https://github.com/user-attachments/assets/8c905c64-ad4c-4397-958b-4b0c0a979749" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 31 45" src="https://github.com/user-attachments/assets/aa97db2e-14cd-43f7-9b72-51c3f850e273" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 31 23" src="https://github.com/user-attachments/assets/b552db51-7dd6-442f-8ccf-3a6a96bd1b6d" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 30 58" src="https://github.com/user-attachments/assets/2dc4d62a-efb6-49d4-b59b-96edaa5ef91e" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 30 17" src="https://github.com/user-attachments/assets/d8a3a814-a4b4-456b-b359-74048ad06955" />
<img width="1440" alt="Screenshot 2025-05-07 at 16 29 06" src="https://github.com/user-attachments/assets/c4364630-02ee-4ada-9279-c30b56b1f017" />

