# Compiler Construction
CSE4035 Compiler Construction, Undergraduate School

Home works and Lab. Materials


Scanner-(token)->Parser[hw2 구현부 여기까지]+SDT-(AST)->Ucode Translater-(UCode *u.c *u.c.o)
->UCode Interpreter(input: Data, output: Execution result)

minic.gr->PGS->(parsing table->Parser)

*Scanner file 제공(파서에 포함)
*Parser에 parsing table include

스캐너, 테이블, 파서 모듈들을 합쳐서 동작시킬수 있는 main프로그램 하나 만들어서 파서 동작시키기.

.mc파일 가져다 input으로 넣게되면 right parse 출력할 수 있음.
right parse 출력까지가 hw2 과제

.uco -> Interpreter의 input으로 넣기

