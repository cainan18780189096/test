# /bin/bash
for i in `seq 9`
  do
    for j in `seq $i`
    do
      echo -ne "$i*$j=$[i*j] \t"
    done
  done
