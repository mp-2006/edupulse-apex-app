# 📊 EduPulse Insights: Student Analytics Dashboard

### 1. Objective 
[cite_start]Implementing a data model and interactive dashboards using **Oracle APEX** for analyzing student performance[cite: 18]. [cite_start]The project focuses on converting raw data into interactive reports and dashboards[cite: 20].

### 2. Database Structure (Data Model)
[cite_start]The following tables were implemented to manage the analytics system[cite: 22]:
* [cite_start]**`EP_BATCHES`**: Stores batch information and academic streams[cite: 22].
* **`EP_STUDENTS`**: Contains student details linked to specific batches[cite: 22].
* **`EP_ATTENDANCE`**: Tracks student attendance status (Present/Absent)[cite: 22, 23].
* **`EP_ASSESSMENTS`**: Logs subject-wise scores for performance tracking[cite: 22, 23].

### 3. Key Features & Analytics
[cite_start]The application utilizes optimized SQL queries and views to provide real-time insights[cite: 40]:
* [cite_start]**Interactive Reports**: Features for sorting, filtering, and searching student data[cite: 32].
* **Bar Charts**: Student score comparison and performance trends[cite: 34].
* [cite_start]**Donut Charts**: Visual representation of attendance distribution[cite: 34].
* [cite_start]**Dashboards**: A centralized view with navigation between charts and reports[cite: 35, 36].

### 4. Setup Instructions
1. Run the `EduPulse_Setup.sql` script in your Oracle SQL workshop to create tables and views.
2. [cite_start]The script includes sample data population for immediate testing and visualization[cite: 24, 25].
