cc_library(
    name = 'onig',
    srcs = [
        'regcomp.c',
        'regenc.c',
        'regerror.c',
        'regexec.c',
        'regext.c',
        'reggnu.c',
        'regparse.c',
        'regposerr.c',
        'regposix.c',
        'regsyntax.c',
        'regtrav.c',
        'regversion.c',
        'st.c',
    ],
    deps = [
        '//essence/onig/enc:enc',
    ]
)

cc_binary(
    name = 'testu',
    warning = 'no',
    srcs = [
        'testu.c',
    ],
    deps = [
        ':onig',
    ]
)

cc_binary(
    name = 'testc',
    warning = 'no',
    srcs = [
        'testc.c',
    ],
    deps = [
        ':onig',
    ]
)