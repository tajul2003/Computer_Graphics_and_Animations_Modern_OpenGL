win:
	g++ -fdiagnostics-color=always -I./include ./src/main.cpp ./src/glad.c -o ./build/main.exe -Llib -lglfw3 -lopengl32 -lgdi32
	./build/main.exe

run:
	./build/main.exe

clean:
	del /Q build\*.exe
