=IF(COUNTIF({"Other";"PT. CENTRAL";"PT. BATAM KARYA MANDIRI";"PT. EASTERN"}; INDEX(Table2[Contractor], COUNTA(Table2[Contractor])))=0, CHAR(80), "")

=IF(ISNA(MATCH(INDEX(Table2[Type of Project]; COUNTA(Table2[Type of Project])); {"Other";"Civil";"Mechanical";"Electrical"}, 0)), CHAR(80), "")

