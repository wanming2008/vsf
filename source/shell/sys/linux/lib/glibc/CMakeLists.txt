# CMakeLists head

target_sources(${VSF_LIB_NAME} INTERFACE
    vsf_linux_glibc.c
    vsf_linux_glibc_pthread.c
    vsf_linux_glibc_sem.c
    vsf_linux_glibc_stdio.c
    vsf_linux_glibc_stdlib.c
    vsf_linux_glibc_string.c
    vsf_linux_glibc_time.c
    vsf_linux_glibc_ctype.c

    3rd-party/getopt_long.c
)
