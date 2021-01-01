User Account: cat kerberos.log | zeek-cut id.orig_h client service | awk '$3~"krbtgt"' | grep -vi "<computer name>" 
