=IF(ISNA(MATCH(INDEX('Contractor Survei.xlsx'!Table2[Type of Project];COUNTA('Contractor Survei.xlsx'!Table2[Type of Project]));{"Other";"Civil";"Mechanical";"Electrical"};0));CHAR(80);"")

=IF(ISNA(MATCH(INDEX('Contractor Survei.xlsx'!Table2[Contractor];COUNTA('Contractor Survei.xlsx'!Table2[Contractor]));{"Other";"PT. CENTRAL";"PT. BATAM KARYA MANDIRI";"PT. EASTERN"};0));CHAR(80);"")
