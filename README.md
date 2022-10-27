# plus
ng () {       echo NG at Line $1       res=1 } 　 res=0out=$(seq 5 | ./plus) [ "${out}" = 14 ] || ng ${LINENO} 　 [ "$rexit $reses" = 0 ] &amp;&amp; echo OK 
