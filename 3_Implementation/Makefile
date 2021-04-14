# comments
# Target : dependency
# <TAB>Command

PROJECT_NAME= calculator.exe

SRC=main.c\
src\calculator_operations.c\
src\addition.c\
src\division.c\
src\factorial.c\
src\modulus.c\
src\multiplication.c\
src\power.c\
src\subtraction.c

INC=inc

$(PROJECT_NAME):$(SRC)
	gcc -I $(INC) $(SRC) -o calculator.exe
	
run:$(PROJECT_NAME)
	$(PROJECT_NAME)
	
clean:
	del /q *.exe
	
doc: Doxyfile
	doxygen ./Doxyfile
	
