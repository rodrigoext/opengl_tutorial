CC=clang++
PARAM=-std=c++11 -lGL -lGLEW -lglfw -fcxx-exceptions -Wno-deprecated-register
OUTPUT=window

all: clang

clang: *.cpp
	${CC} -o ${OUTPUT} *.cpp ${LLVMPARAM} ${PARAM}

clean:
	rm ${OUTPUT}