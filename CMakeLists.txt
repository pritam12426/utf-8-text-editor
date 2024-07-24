cmake_minimum_required(VERSION 3.30)

project(
	"editor" 
	VERSION 0.1.0
	DESCRIPTION "Small Utf-8 text editor"
	HOMEPAGE_URL "https://github.com/pritam12426/utf-8-text-editor"
	LANGUAGES C
)

set(SRC "src/main.c")
set(CMAKE_CXX_STANDARD 17)

add_executable(${PROJECT_NAME} ${SRC})
