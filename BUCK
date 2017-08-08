cxx_library(
    name = 'bar',
    srcs = ['bar.c'],
    headers = ['bar.h'],
    exported_headers = ['bar.h']
)

cxx_binary(
    name = 'foo',
    srcs = ['foo.c'],
    deps = [':bar'],
    link_style = 'SHARED'
)
