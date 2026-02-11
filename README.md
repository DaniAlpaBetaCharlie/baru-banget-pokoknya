=IF(OR(TRIM(INDEX(Table2[Contractor], COUNTA(Table2[Contractor])))="Other",
      TRIM(INDEX(Table2[Contractor], COUNTA(Table2[Contractor])))="PT. CENTRAL",
      TRIM(INDEX(Table2[Contractor], COUNTA(Table2[Contractor])))="PT. BATAM KARYA MANDIRI",
      TRIM(INDEX(Table2[Contractor], COUNTA(Table2[Contractor])))="PT. EASTERN"),
   "",
   CHAR(80))



=IF(ISNA(MATCH(INDEX(Table2[Type of Project], COUNTA(Table2[Type of Project])), {"Other";"Civil";"Mechanical";"Electrical"}, 0)), CHAR(80), "")
   

pakai ini, tetap aja terceklis terus dia keduanya
