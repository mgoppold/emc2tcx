emc2tcx
=======

ergo_memo_card to tcx

emc2tcx -p PATH [-x [NUM|ALL]]

List trainings of DAUM ergo_memo_card or export your training(s) to tcx.

wget http://www.garmin.com/xmlschemas/TrainingCenterDatabasev2.xsd
xmllint --noout --schema TrainingCenterDatabasev2.xsd test.tcx
test.tcx validates

