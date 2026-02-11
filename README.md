=IF(COUNTIF({"Other";"PT. CENTRAL";"PT. BATAM KARYA MANDIRI";"PT. EASTERN"}, INDEX(Table2[Contractor], COUNTA(Table2[Contractor])))=0, CHAR(80), "")
