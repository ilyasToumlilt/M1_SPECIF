# Projet Lustre - Modélisation et vérification en Lustre
#
# @author Massine BITAM  <massine.bitam@etu.upmc.fr>
# @author Ilyas Toumlilt <toumlilt.ilyas@gmail.com>
# 
# @version 1.0
# @package toumlilt/M1/SPECIF

CC=gcc -Wall -ansi
BIN=bin
INC=include
LIB=lib
OBJ=obj
SRC=src


all: directories


directories: ${OBJ} ${BIN} ${LIB}

${OBJ}:
	mkdir ${OBJ}
${BIN}:
	mkdir ${BIN}
${LIB}:
	mkdir ${LIB}


clean:
	rm -f ${OBJ}/* ${BIN}/* ${LIB}/*

cleanall:
	rm -rf ${OBJ} ${BIN} ${LIB}
	rm -f ${INC}/*~ ${SRC}/*~ *~

