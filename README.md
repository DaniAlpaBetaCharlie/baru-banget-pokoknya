=IF(OR(INDEX(Table2[Contractor],COUNTA(Table2[Contractor]))="",ISNUMBER(MATCH(INDEX(Table2[Contractor],COUNTA(Table2[Contractor])),{"Mechanical","Electrical","Civil"},0))),"",CHAR(80))
=IF(OR(INDEX(Table2[Type of Project],COUNTA(Table2[Type of Project]))="",ISNUMBER(MATCH(INDEX(Table2[Type of Project],COUNTA(Table2[Type of Project])),{"Mechanical","Electrical","Civil"},0))),"",CHAR(80))
