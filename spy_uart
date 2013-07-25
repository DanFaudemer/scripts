#!/bin/sh

#Check argument number
EXPECTED_ARGS=2
E_BADARGS=65

if [ $# -ne $EXPECTED_ARGS ]
then
  echo "Usage: `basename $0` /dev/tty* baudrate"
  exit $E_BADARGS
fi

#configure baudrate
stty -F $1 ispeed $2
cat $1 > out 












