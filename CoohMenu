#!/bin/bash

pkg install util-linux

gem install lolcat

pkg install cowsay

pkg install figlet

pkg install python

pkg install python2

pkg install git

pkg install queue

setterm -foreground blue -store

clear

figlet CoohMenu | lolcat
echo "Hackeando Tudo!"


#Menu
echo '\n'
echo '\n'
echo "[1] DDoS"
read ops

if [ "$ops" = "1" ]
   then
	clear
	figlet CoohDDoS | lolcat
	echo '\n'
        echo '\n'
	echo "[1] DDoS-Attack"
	echo "[2] Hammer"
	read ddos
	#DDos-Attack
	if [ "$ddos" = "1" ]
	   then
		 clear
       		 pkg update
       		 pkg upgrade -y
       		 mkdir tmp
       		 cd tmp
       		 git clone https://github.com/Ha3MrX/DDos-Attack
	         clear
		chmod +x $HOME/CoohMenu/tmp/DDos-Attack/*
	         python2 $HOME/CoohMenu/tmp/DDos-Attack/ddos-attack.py
	fi

	if [ "$ddos" = "2" ]
	   then
		clear
		pkg update
		pkg upgrade -y
		mkdir tmp
		cd tmp
		git clone https://github.com/cyweb/hammer
		clear
		chmod +x $HOME/CoohMenu/tmp/hammer/*
		python2 $HOME/CoohMenu/tmp/hammer/hammer.py
	fi

fi
