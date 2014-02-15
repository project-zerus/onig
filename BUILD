cc_library(
    name = 'onig',
    warning = 'no',
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
        'enc/ascii.c',
        'enc/big5.c',
        'enc/cp1251.c',
        'enc/euc_jp.c',
        'enc/euc_kr.c',
        'enc/euc_tw.c',
        'enc/gb18030.c',
        'enc/iso8859_10.c',
        'enc/iso8859_11.c',
        'enc/iso8859_13.c',
        'enc/iso8859_14.c',
        'enc/iso8859_15.c',
        'enc/iso8859_16.c',
        'enc/iso8859_1.c',
        'enc/iso8859_2.c',
        'enc/iso8859_3.c',
        'enc/iso8859_4.c',
        'enc/iso8859_5.c',
        'enc/iso8859_6.c',
        'enc/iso8859_7.c',
        'enc/iso8859_8.c',
        'enc/iso8859_9.c',
        'enc/koi8.c',
        'enc/koi8_r.c',
        'enc/sjis.c',
        'enc/unicode.c',
        'enc/utf16_be.c',
        'enc/utf16_le.c',
        'enc/utf32_be.c',
        'enc/utf32_le.c',
        'enc/utf8.c',
    ],
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

cc_binary(
    name = 'mktable',
    warning = 'no',
    srcs = [
        'enc/mktable.c',
    ]
)
