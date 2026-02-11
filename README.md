=IF(AND(ISNA(SEARCH("Civil";INDEX('Contractor Survei.xlsx'!Table2[Type of Project];COUNTA('Contractor Survei.xlsx'!Table2[Type of Project]))));ISNA(SEARCH("Mechanical";INDEX('Contractor Survei.xlsx'!Table2[Type of Project];COUNTA('Contractor Survei.xlsx'!Table2[Type of Project]))));ISNA(SEARCH("Electrical";INDEX('Contractor Survei.xlsx'!Table2[Type of Project];COUNTA('Contractor Survei.xlsx'!Table2[Type of Project])))));CHAR(80);"")



=IF(AND(ISNA(SEARCH("PT CENTRAL";INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))));ISNA(SEARCH("PT BATAM KARYA MANDIRI";INDEX(Table2[Contractor];COUNTA(Table[Contractor]))));ISNA(SEARCH("PT EASTERN";INDEX(Table2[Contractor];COUNTA(Table2[Contractor])))));CHAR(80);"")
