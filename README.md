=LET(x; LOOKUP(2; 1/(Table2[Contractor]<>""); Table2[Contractor]);
IF(AND(ISERR(SEARCH("PT. CENTRAL"; x)); ISERR(SEARCH("PT. BATAM KARYA MANDIRI"; x)); ISERR(SEARCH("PT. EASTERN"; x))); CHAR(80); ""))

=LET(x; LOOKUP(2; 1/(Table2[Type of Project]<>""); Table2[Type of Project]);
IF(AND(ISERR(SEARCH("Electrical"; x)); ISERR(SEARCH("Civil"; x)); ISERR(SEARCH("Mechanical"; x))); CHAR(80); ""))
