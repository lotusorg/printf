project('printf',
        'c')

printf_inc = include_directories('.')
printf_lib = static_library('printf',
                            'printf.c',
                            include_directories: printf_inc)

printf_dep = declare_dependency(include_directories: [printf_inc], link_with: [printf_lib])