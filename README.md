# Deep-Neural-Network

The data set represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria
a. It is an inpatient encounter (a hospital admission).
b. It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.
c. The length of stay was at least 1 day and at most 14 days.
d. Laboratory tests were performed during the encounter.
e. Medications were administered during the encounter.

**Output**
In this database, you have 3 different outputs:

No readmission;
A readmission in less than 30 days (this situation is not good, because maybe your treatment was not appropriate);
A readmission in more than 30 days (this one is not so good as well the last one, however, the reason can be the state of the patient.
In this context, you can see different objective functions for the problem. You can try to figure out situations where the patient will not be readmitted, or if their are going to be readmitted in less than 30 days (because the problem can the the treatment), etc... Make your choice and let's help them creating new approaches for the problem.

**Original Source of Dataset**
https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008

**Source**
The data are submitted on behalf of the Center for Clinical and Translational Research, Virginia Commonwealth University, a recipient of NIH CTSA grant UL1 TR00058 and a recipient of the CERNER data. John Clore (jclore '@' vcu.edu), Krzysztof J. Cios (kcios '@' vcu.edu), Jon DeShazo (jpdeshazo '@' vcu.edu), and Beata Strack (strackb '@' vcu.edu). This data is a de-identified abstract of the Health Facts database (Cerner Corporation, Kansas City, MO).
