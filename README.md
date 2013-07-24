yarn-mr-state-diagrams
======================

State machines for YARN and MR

To generate these files, do

mvn compile -Pvisualize
for i in *.gv; do dot -Tpng $i > $.png; done
