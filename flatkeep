#!/bin/bash
for folder in $(find . -type d -links 2)
do
  if [ "$(ls -A $folder)" ]; then
  	continue
  else
  	echo "Creating .keep file in $folder!"
  	touch $folder/.keep
  fi
done

