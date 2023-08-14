Linux with tcsh installed

set environment variable ENTPRISE to where  scan_genfea3_pred.job is 

cd  $ENTPRISE


test:
cd test

$ENTPRISE/scan_genfea3_pred.job test.lst 

see  test.lst for input format

output: test.lst_pred.out (column 5 is the prediction score, column 6 is the mutationi frequency in the 1k genomes project )
