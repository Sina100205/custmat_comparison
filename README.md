# custmat_comparison
A browser-based tool for reconciling BITZER Product IDs between the SAP reports (e.g. from ZSD_VA05N ) and ZSD_CUSTMAT (customer material master). 
It identifies missing entries and conflicts without requiring any installation or data upload to external servers.
Results are grouped into three categories: 
✅ Present & correctEntry exists in CUSTMAT and Customer Material matches
🔴 MissingThe Customer + BITZER Product ID combination is not in CUSTMAT at all
🟠 ConflictThe combination exists in CUSTMAT, but the Customer Material number differs

How to use
Open CUSTMAT_Abgleich_Tool.html in any modern browser (Chrome, Edge, Firefox).
Upload your exports:
ZSD_CUSTMAT – customer material master export from SAP
ZSD_VA05N – open sales order report export from SAP
The analysis runs automatically once both files are loaded.
Review results in the Fehlende Einträge and Konflikte tabs.
Download the results as Excel using the buttons on the respective stat cards.
