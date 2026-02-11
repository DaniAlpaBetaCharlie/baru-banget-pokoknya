=IF(AND(
INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))<>"";
ISNA(SEARCH("PT CENTRAL";INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))));
ISNA(SEARCH("PT BATAM KARYA MANDIRI";INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))));
ISNA(SEARCH("PT EASTERN";INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))))
);
CHAR(80);
"")




=IF(AND(
INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))<>"";
ISNA(SEARCH("PT CENTRAL";INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))));
ISNA(SEARCH("PT BATAM KARYA MANDIRI";INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))));
ISNA(SEARCH("PT EASTERN";INDEX(Table2[Contractor];COUNTA(Table2[Contractor]))))
);
CHAR(80);
"")

