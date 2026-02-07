# education-board-intervention-and-cost-forecasting
📌 Business Understanding
Background

Fort Vermilion School Division (FVSD) is a public education organization responsible for managing multiple schools across academic years and semesters. To support data-driven planning, FVSD collects standardized assessment data to evaluate student performance and determine the level of academic support required.

Each academic year is divided into three semesters: Fall, Winter, and Spring. During each semester, students complete multiple standardized assessments that generate performance scores and associated testing costs. These assessment results are used not only to monitor educational outcomes but also to inform staffing and budget decisions.

Stakeholders

School Board Members: Monitor overall student performance and educational quality

Finance & Operations Managers: Plan teacher allocation and manage testing and intervention costs

Business Objectives

Analyze student assessment performance across schools, semesters, and academic years

Identify students requiring additional academic intervention

Estimate the number of teachers needed for intervention programs

Forecast testing and intervention-related costs for upcoming semesters

Support proactive resource allocation and long-term planning

Assessment & Intervention Logic

Students are evaluated using standardized assessments each semester

Assessment results are classified into performance levels and grouped into broader categories

Students requiring additional support are assigned to intervention tiers based on their scores

Intervention Rules

Scores between 80 and 90 → Tier 2 intervention

Scores below 80 → Tier 3 intervention

Tier 2: 10 students per teacher

Tier 3: 5 students per teacher

Analytical Approach

Assessment results are analyzed at the student and semester level

Historical performance data is used to project future intervention needs

Teacher and cost forecasts for a semester are estimated using results from the previous semester

Performance trends are evaluated across time to support strategic decision-making

Key Questions Addressed

How are students distributed across assessment performance levels?

What proportion of students fall below expected performance benchmarks?

How many teachers are required for Tier 2 and Tier 3 intervention groups?

What are the projected testing and intervention costs for upcoming semesters?

How is student performance changing over time?

Tools & Skills Demonstrated

Data modeling and star schema design

Business logic translation into analytical metrics

Time-based analysis using academic calendars

Power BI dashboard design for decision support

⚠️ Assumptions & Limitations
Assumptions

Assessment results accurately reflect student academic performance at the time of testing

Each assessment record represents a valid and complete assessment event for a student

Students participate in all required assessments within each semester unless otherwise indicated in the data

Intervention tier classification is based solely on assessment score thresholds and does not account for qualitative factors such as teacher observations or individual learning needs

Teacher allocation rules (students per teacher per intervention tier) are fixed and consistently applied across all schools

Testing and intervention cost values remain constant within the same academic period

Teacher and cost forecasts for a semester are estimated using assessment outcomes from the previous semester

Student enrollment is assumed to remain stable between consecutive semesters unless reflected in the data

Limitations

The analysis does not account for student movement between schools during an academic year

External factors influencing student performance (e.g., socio-economic conditions, attendance, or special education needs) are not included

Intervention effectiveness is not measured; the model estimates resource needs but does not evaluate outcomes of interventions

Teacher availability, contract constraints, and workload variations are not considered in staffing forecasts

Cost estimates do not include indirect expenses such as training, administration, or infrastructure

Forecasting logic is rule-based and does not incorporate statistical or machine learning prediction models

Results are sensitive to data quality; missing or inaccurate assessment records may impact counts and projections
