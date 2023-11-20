# Compiler Construction
CSE4035 Compiler Construction, Undergraduate School

Home works and Lab. Materials

*언어 변경 가능. 원본 코드는 C
Scanner-(token)->Parser[hw2 구현부 여기까지]+SDT-(AST)->Ucode Translater-(UCode *u.c *u.c.o)
->UCode Interpreter(input: Data, output: Execution result)

minic.gr->PGS->(parsing table->Parser)

*Scanner file 제공(파서에 포함)
*Parser에 parsing table include

스캐너, 테이블, 파서 모듈들을 합쳐서 동작시킬수 있는 main프로그램 하나 만들어서 파서 동작시키기.

.mc파일 가져다 input으로 넣게되면 right parse 출력할 수 있음.
right parse 출력까지가 hw2 과제

.uco -> Interpreter의 input으로 넣기

[U-code Program 마방진 과제]


2차원 배열로 표기된 알고리즘을 1차원 배열로 읽어 처리하는 알고리즘이 필요함.
mat[M][N] 사이즈
mat[i][j]

->mat+i*Mj

