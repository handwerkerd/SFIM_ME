meica-figure
============

Report generator for meica.py from https://bitbucket.org/prantikk/me-ica

Use meica_report.py to generate the report.  The report will appear in the specified directory in html format and also latex format.  To open the html format, just open the Report directory and then the html directory and open index.html file.

use 'meica_report.py -h' for help

example input '~/meica_report/meica_report.py -anat "MPRAGE_ns.nii.gz" -TED TED -setname meica.WE_TE1234label -sag -ax'

Please use the anatomical generated by meica with the name *_ns* for best results
if you use *_ns_at or *_od, the alignemnt may be off
