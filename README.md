=IF(OR(TRIM(INDEX(Table2[Contractor], COUNTA(Table2[Contractor])))="Other"),"",CHAR(80))



=IF(ISNA(MATCH(INDEX(Table2[Type of Project], COUNTA(Table2[Type of Project])), {"Other"}, 0)), CHAR(80), "")
   

pakai ini, tetap aja terceklis terus dia keduanya
