---  

### Sum Column in Tab Delimited File

**code:** `cat /Volumes/web/cnidarian/TGR_intersectbed_CDS_v9_CGmotif.txt | awk -F"\t" '{ sum+=$10} END {print sum}'`

screenshot:
<img src="http://eagle.fish.washington.edu/cnidarian/skitch/BiGo_methratio_17A2220E.png" alt="BiGo_methratio_17A2220E.png"/>

---

### Count Lines with String

**code:** `!fgrep -c "fuzznuc" /Volumes/web/cnidarian/TJGR_oyster_v9_CG.gff`   

screenshot:   
<img src="http://eagle.fish.washington.edu/cnidarian/skitch/BiGo_methratio_17A2231A.png" alt="BiGo_methratio_17A2231A.png"/>


---

### Convert csv to tab

**code:** `tr ',' "\t" </Users/sr320/Desktop/Ruphi\ Enriched\ Genes.csv> /Users/sr320/Desktop/Ruphi\ Enriched\ Genes.txt`

---

### Copy Program of Interest to Run

**code:** `cp ncbi-blast-2.2.27+/bin/* /usr/local/bin`

---


### Remove First line of file

**code:** `!tail -n +2 /Volumes/web/cnidarian/BiGo_methratio_boop.gff > /Volumes/web/cnidarian/BiGo_methratio_boop_c.gff`