=IF(AND(INDEX(Table2[Type of Project],COUNTA(Table2[Type of Project]))<>"",ISNA(MATCH(INDEX(Table2[Type of Project],COUNTA(Table2[Type of Project])),{"other","Mechanical","Electrical","Civil"},0))),CHAR(80),"")



=IF(AND(INDEX(Table2[Contractor],COUNTA(Table2[Contractor]))<>"",ISNA(MATCH(INDEX(Table2[Contractor],COUNTA(Table2[Contractor])),{"other","PT CENTRAL","PT BATAM KARYA MANDIRI","PT EASTERN"},0))),CHAR(80),"")
