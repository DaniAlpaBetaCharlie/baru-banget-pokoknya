=IF(AND(
INDEX(Table2[@[Contractor]];COUNTA(Table2[[@Contractor]]))<>"";
ISNA(SEARCH("PT CENTRAL";INDEX(Table2[@[Contractor]];COUNTA(Table2[@[Contractor]]))));
ISNA(SEARCH("PT BATAM KARYA MANDIRI";INDEX(Table2[@[Contractor]];COUNTA(Table2[@[Contractor]]))));
ISNA(SEARCH("PT EASTERN";INDEX(Table2[@[Contractor]];COUNTA(Table2[@[Contractor]]))))
);
CHAR(80);
"")




=IF(AND(
INDEX(Table2[@[Type of Project]];COUNTA(Table2[@[Type of Project]]))<>"";
ISNA(SEARCH("Mechanical";INDEX(Table2[@[Type of Project]];COUNTA(Table2[@[Type of Project]]))));
ISNA(SEARCH("Civil";INDEX(Table2[@[Type of Project]];COUNTA(Table2[@[Type of Project]]))));
ISNA(SEARCH("Electrical";INDEX(Table2[@[Type of Project]];COUNTA(Table2[@[Type of Project]]))))
);
CHAR(80);
"")

