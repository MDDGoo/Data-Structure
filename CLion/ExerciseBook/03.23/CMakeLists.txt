# 包含公共库
include_directories(${CMAKE_SOURCE_DIR}/Status)

# 生成可执行文件
add_executable(03.23 SqStack.h SqStack.c 03.23.c)
# 链接公共库
target_link_libraries(03.23 Scanf_lib)