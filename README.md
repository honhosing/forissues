# forissues
This repository is to store the text for issues

Collecting wordcloud
  Using cached https://files.pythonhosted.org/packages/bc/e8/cab8479b25297b3847cfb55e85a5014e8c53b80e513eaf1ba58c7b3a6acd/wordcloud-1.4.1.tar.gz
Requirement already satisfied: matplotlib in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from wordcloud) (2.2.2)
Requirement already satisfied: numpy>=1.6.1 in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from wordcloud) (1.14.5)
Requirement already satisfied: pillow in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from wordcloud) (5.2.0)
Requirement already satisfied: six>=1.10 in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from matplotlib->wordcloud) (1.11.0)
Requirement already satisfied: pyparsing!=2.0.4,!=2.1.2,!=2.1.6,>=2.0.1 in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from matplotlib->wordcloud) (2.2.0)
Requirement already satisfied: kiwisolver>=1.0.1 in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from matplotlib->wordcloud) (1.0.1)
Requirement already satisfied: python-dateutil>=2.1 in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from matplotlib->wordcloud) (2.7.3)
Requirement already satisfied: cycler>=0.10 in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from matplotlib->wordcloud) (0.10.0)
Requirement already satisfied: pytz in /Users/hanhaoxing/Library/Python/3.7/lib/python/site-packages (from matplotlib->wordcloud) (2018.5)
Requirement already satisfied: setuptools in /usr/local/lib/python3.7/site-packages (from kiwisolver>=1.0.1->matplotlib->wordcloud) (39.2.0)
Building wheels for collected packages: wordcloud
  Running setup.py bdist_wheel for wordcloud: started
  Running setup.py bdist_wheel for wordcloud: finished with status 'error'
  Complete output from command /usr/local/opt/python/bin/python3.7 -u -c "import setuptools, tokenize;__file__='/private/var/folders/bl/4dsqzdws0dsbq7s8_wntttkm0000gp/T/pycharm-packaging/wordcloud/setup.py';f=getattr(tokenize, 'open', open)(__file__);code=f.read().replace('\r\n', '\n');f.close();exec(compile(code, __file__, 'exec'))" bdist_wheel -d /private/var/folders/bl/4dsqzdws0dsbq7s8_wntttkm0000gp/T/pip-wheel-oim68xiv --python-tag cp37:
  running bdist_wheel
  running build
  running build_py
  creating build
  creating build/lib.macosx-10.13-x86_64-3.7
  creating build/lib.macosx-10.13-x86_64-3.7/wordcloud
  copying wordcloud/wordcloud_cli.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
  copying wordcloud/__init__.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
  copying wordcloud/tokenization.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
  copying wordcloud/wordcloud.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
  copying wordcloud/color_from_image.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
  copying wordcloud/stopwords -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
  copying wordcloud/DroidSansMono.ttf -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
  warning: build_py: byte-compiling is disabled, skipping.
  
  running build_ext
  building 'wordcloud.query_integral_image' extension
  creating build/temp.macosx-10.13-x86_64-3.7
  creating build/temp.macosx-10.13-x86_64-3.7/wordcloud
  clang -Wno-unused-result -Wsign-compare -Wunreachable-code -fno-common -dynamic -DNDEBUG -g -fwrapv -O3 -Wall -I/usr/local/include -I/usr/local/opt/openssl/include -I/usr/local/opt/sqlite/include -I/usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m -c wordcloud/query_integral_image.c -o build/temp.macosx-10.13-x86_64-3.7/wordcloud/query_integral_image.o
  wordcloud/query_integral_image.c:2039:134: warning: code will never be executed [-Wunreachable-code]
      __pyx_t_7 = PyTuple_GET_ITEM(__pyx_t_3, __pyx_t_1); __Pyx_INCREF(__pyx_t_7); __pyx_t_1++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 145; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                       ^~~~~~~
  wordcloud/query_integral_image.c:3876:138: warning: code will never be executed [-Wunreachable-code]
          __pyx_t_5 = PyTuple_GET_ITEM(__pyx_t_2, __pyx_t_3); __Pyx_INCREF(__pyx_t_5); __pyx_t_3++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 350; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                           ^~~~~~~
  wordcloud/query_integral_image.c:3869:137: warning: code will never be executed [-Wunreachable-code]
          __pyx_t_5 = PyList_GET_ITEM(__pyx_t_2, __pyx_t_3); __Pyx_INCREF(__pyx_t_5); __pyx_t_3++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 350; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                          ^~~~~~~
  wordcloud/query_integral_image.c:6312:140: warning: code will never be executed [-Wunreachable-code]
            __pyx_t_3 = PyTuple_GET_ITEM(__pyx_t_4, __pyx_t_5); __Pyx_INCREF(__pyx_t_3); __pyx_t_5++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 554; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                             ^~~~~~~
  wordcloud/query_integral_image.c:6305:139: warning: code will never be executed [-Wunreachable-code]
            __pyx_t_3 = PyList_GET_ITEM(__pyx_t_4, __pyx_t_5); __Pyx_INCREF(__pyx_t_3); __pyx_t_5++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 554; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                            ^~~~~~~
  wordcloud/query_integral_image.c:7264:138: warning: code will never be executed [-Wunreachable-code]
          __pyx_t_7 = PyTuple_GET_ITEM(__pyx_t_4, __pyx_t_5); __Pyx_INCREF(__pyx_t_7); __pyx_t_5++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 635; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                           ^~~~~~~
  wordcloud/query_integral_image.c:7257:137: warning: code will never be executed [-Wunreachable-code]
          __pyx_t_7 = PyList_GET_ITEM(__pyx_t_4, __pyx_t_5); __Pyx_INCREF(__pyx_t_7); __pyx_t_5++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 635; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                          ^~~~~~~
  wordcloud/query_integral_image.c:7831:138: warning: code will never be executed [-Wunreachable-code]
          __pyx_t_9 = PyTuple_GET_ITEM(__pyx_t_3, __pyx_t_7); __Pyx_INCREF(__pyx_t_9); __pyx_t_7++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 703; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                           ^~~~~~~
  wordcloud/query_integral_image.c:7824:137: warning: code will never be executed [-Wunreachable-code]
          __pyx_t_9 = PyList_GET_ITEM(__pyx_t_3, __pyx_t_7); __Pyx_INCREF(__pyx_t_9); __pyx_t_7++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 703; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                          ^~~~~~~
  wordcloud/query_integral_image.c:14910:21: error: no member named 'exc_type' in 'struct _ts'
      *type = tstate->exc_type;
              ~~~~~~  ^
  wordcloud/query_integral_image.c:14911:22: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
      *value = tstate->exc_value;
                       ^~~~~~~~~
                       curexc_value
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
      PyObject *curexc_value;
                ^
  wordcloud/query_integral_image.c:14912:19: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
      *tb = tstate->exc_traceback;
                    ^~~~~~~~~~~~~
                    curexc_traceback
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
      PyObject *curexc_traceback;
                ^
  wordcloud/query_integral_image.c:14924:24: error: no member named 'exc_type' in 'struct _ts'
      tmp_type = tstate->exc_type;
                 ~~~~~~  ^
  wordcloud/query_integral_image.c:14925:25: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
      tmp_value = tstate->exc_value;
                          ^~~~~~~~~
                          curexc_value
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
      PyObject *curexc_value;
                ^
  wordcloud/query_integral_image.c:14926:22: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
      tmp_tb = tstate->exc_traceback;
                       ^~~~~~~~~~~~~
                       curexc_traceback
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
      PyObject *curexc_traceback;
                ^
  wordcloud/query_integral_image.c:14927:13: error: no member named 'exc_type' in 'struct _ts'
      tstate->exc_type = type;
      ~~~~~~  ^
  wordcloud/query_integral_image.c:14928:13: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
      tstate->exc_value = value;
              ^~~~~~~~~
              curexc_value
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
      PyObject *curexc_value;
                ^
  wordcloud/query_integral_image.c:14929:13: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
      tstate->exc_traceback = tb;
              ^~~~~~~~~~~~~
              curexc_traceback
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
      PyObject *curexc_traceback;
                ^
  wordcloud/query_integral_image.c:14972:24: error: no member named 'exc_type' in 'struct _ts'
      tmp_type = tstate->exc_type;
                 ~~~~~~  ^
  wordcloud/query_integral_image.c:14973:25: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
      tmp_value = tstate->exc_value;
                          ^~~~~~~~~
                          curexc_value
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
      PyObject *curexc_value;
                ^
  wordcloud/query_integral_image.c:14974:22: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
      tmp_tb = tstate->exc_traceback;
                       ^~~~~~~~~~~~~
                       curexc_traceback
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
      PyObject *curexc_traceback;
                ^
  wordcloud/query_integral_image.c:14975:13: error: no member named 'exc_type' in 'struct _ts'
      tstate->exc_type = local_type;
      ~~~~~~  ^
  wordcloud/query_integral_image.c:14976:13: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
      tstate->exc_value = local_value;
              ^~~~~~~~~
              curexc_value
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
      PyObject *curexc_value;
                ^
  wordcloud/query_integral_image.c:14977:13: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
      tstate->exc_traceback = local_tb;
              ^~~~~~~~~~~~~
              curexc_traceback
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
      PyObject *curexc_traceback;
                ^
  wordcloud/query_integral_image.c:14999:24: error: no member named 'exc_type' in 'struct _ts'
      tmp_type = tstate->exc_type;
                 ~~~~~~  ^
  wordcloud/query_integral_image.c:15000:25: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
      tmp_value = tstate->exc_value;
                          ^~~~~~~~~
                          curexc_value
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
      PyObject *curexc_value;
                ^
  wordcloud/query_integral_image.c:15001:22: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
      tmp_tb = tstate->exc_traceback;
                       ^~~~~~~~~~~~~
                       curexc_traceback
  /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
      PyObject *curexc_traceback;
                ^
  wordcloud/query_integral_image.c:15002:13: error: no member named 'exc_type' in 'struct _ts'
      tstate->exc_type = *type;
      ~~~~~~  ^
  fatal error: too many errors emitted, stopping now [-ferror-limit=]
  9 warnings and 20 errors generated.
  error: command 'clang' failed with exit status 1
  
  ----------------------------------------
  Running setup.py clean for wordcloud
Failed to build wordcloud
Installing collected packages: wordcloud
  Running setup.py install for wordcloud: started
    Running setup.py install for wordcloud: finished with status 'error'
    Complete output from command /usr/local/opt/python/bin/python3.7 -u -c "import setuptools, tokenize;__file__='/private/var/folders/bl/4dsqzdws0dsbq7s8_wntttkm0000gp/T/pycharm-packaging/wordcloud/setup.py';f=getattr(tokenize, 'open', open)(__file__);code=f.read().replace('\r\n', '\n');f.close();exec(compile(code, __file__, 'exec'))" install --record /private/var/folders/bl/4dsqzdws0dsbq7s8_wntttkm0000gp/T/pip-record-wdr3g60r/install-record.txt --single-version-externally-managed --compile --user --prefix=:
    running install
    running build
    running build_py
    creating build
    creating build/lib.macosx-10.13-x86_64-3.7
    creating build/lib.macosx-10.13-x86_64-3.7/wordcloud
    copying wordcloud/wordcloud_cli.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
    copying wordcloud/__init__.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
    copying wordcloud/tokenization.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
    copying wordcloud/wordcloud.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
    copying wordcloud/color_from_image.py -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
    copying wordcloud/stopwords -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
    copying wordcloud/DroidSansMono.ttf -> build/lib.macosx-10.13-x86_64-3.7/wordcloud
    warning: build_py: byte-compiling is disabled, skipping.
    
    running build_ext
    building 'wordcloud.query_integral_image' extension
    creating build/temp.macosx-10.13-x86_64-3.7
    creating build/temp.macosx-10.13-x86_64-3.7/wordcloud
    clang -Wno-unused-result -Wsign-compare -Wunreachable-code -fno-common -dynamic -DNDEBUG -g -fwrapv -O3 -Wall -I/usr/local/include -I/usr/local/opt/openssl/include -I/usr/local/opt/sqlite/include -I/usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m -c wordcloud/query_integral_image.c -o build/temp.macosx-10.13-x86_64-3.7/wordcloud/query_integral_image.o
    wordcloud/query_integral_image.c:2039:134: warning: code will never be executed [-Wunreachable-code]
        __pyx_t_7 = PyTuple_GET_ITEM(__pyx_t_3, __pyx_t_1); __Pyx_INCREF(__pyx_t_7); __pyx_t_1++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 145; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                         ^~~~~~~
    wordcloud/query_integral_image.c:3876:138: warning: code will never be executed [-Wunreachable-code]
            __pyx_t_5 = PyTuple_GET_ITEM(__pyx_t_2, __pyx_t_3); __Pyx_INCREF(__pyx_t_5); __pyx_t_3++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 350; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                             ^~~~~~~
    wordcloud/query_integral_image.c:3869:137: warning: code will never be executed [-Wunreachable-code]
            __pyx_t_5 = PyList_GET_ITEM(__pyx_t_2, __pyx_t_3); __Pyx_INCREF(__pyx_t_5); __pyx_t_3++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 350; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                            ^~~~~~~
    wordcloud/query_integral_image.c:6312:140: warning: code will never be executed [-Wunreachable-code]
              __pyx_t_3 = PyTuple_GET_ITEM(__pyx_t_4, __pyx_t_5); __Pyx_INCREF(__pyx_t_3); __pyx_t_5++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 554; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                               ^~~~~~~
    wordcloud/query_integral_image.c:6305:139: warning: code will never be executed [-Wunreachable-code]
              __pyx_t_3 = PyList_GET_ITEM(__pyx_t_4, __pyx_t_5); __Pyx_INCREF(__pyx_t_3); __pyx_t_5++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 554; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                              ^~~~~~~
    wordcloud/query_integral_image.c:7264:138: warning: code will never be executed [-Wunreachable-code]
            __pyx_t_7 = PyTuple_GET_ITEM(__pyx_t_4, __pyx_t_5); __Pyx_INCREF(__pyx_t_7); __pyx_t_5++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 635; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                             ^~~~~~~
    wordcloud/query_integral_image.c:7257:137: warning: code will never be executed [-Wunreachable-code]
            __pyx_t_7 = PyList_GET_ITEM(__pyx_t_4, __pyx_t_5); __Pyx_INCREF(__pyx_t_7); __pyx_t_5++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 635; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                            ^~~~~~~
    wordcloud/query_integral_image.c:7831:138: warning: code will never be executed [-Wunreachable-code]
            __pyx_t_9 = PyTuple_GET_ITEM(__pyx_t_3, __pyx_t_7); __Pyx_INCREF(__pyx_t_9); __pyx_t_7++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 703; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                             ^~~~~~~
    wordcloud/query_integral_image.c:7824:137: warning: code will never be executed [-Wunreachable-code]
            __pyx_t_9 = PyList_GET_ITEM(__pyx_t_3, __pyx_t_7); __Pyx_INCREF(__pyx_t_9); __pyx_t_7++; if (unlikely(0 < 0)) {__pyx_filename = __pyx_f[1]; __pyx_lineno = 703; __pyx_clineno = __LINE__; goto __pyx_L1_error;}
                                                                                                                                            ^~~~~~~
    wordcloud/query_integral_image.c:14910:21: error: no member named 'exc_type' in 'struct _ts'
        *type = tstate->exc_type;
                ~~~~~~  ^
    wordcloud/query_integral_image.c:14911:22: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
        *value = tstate->exc_value;
                         ^~~~~~~~~
                         curexc_value
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
        PyObject *curexc_value;
                  ^
    wordcloud/query_integral_image.c:14912:19: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
        *tb = tstate->exc_traceback;
                      ^~~~~~~~~~~~~
                      curexc_traceback
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
        PyObject *curexc_traceback;
                  ^
    wordcloud/query_integral_image.c:14924:24: error: no member named 'exc_type' in 'struct _ts'
        tmp_type = tstate->exc_type;
                   ~~~~~~  ^
    wordcloud/query_integral_image.c:14925:25: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
        tmp_value = tstate->exc_value;
                            ^~~~~~~~~
                            curexc_value
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
        PyObject *curexc_value;
                  ^
    wordcloud/query_integral_image.c:14926:22: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
        tmp_tb = tstate->exc_traceback;
                         ^~~~~~~~~~~~~
                         curexc_traceback
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
        PyObject *curexc_traceback;
                  ^
    wordcloud/query_integral_image.c:14927:13: error: no member named 'exc_type' in 'struct _ts'
        tstate->exc_type = type;
        ~~~~~~  ^
    wordcloud/query_integral_image.c:14928:13: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
        tstate->exc_value = value;
                ^~~~~~~~~
                curexc_value
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
        PyObject *curexc_value;
                  ^
    wordcloud/query_integral_image.c:14929:13: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
        tstate->exc_traceback = tb;
                ^~~~~~~~~~~~~
                curexc_traceback
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
        PyObject *curexc_traceback;
                  ^
    wordcloud/query_integral_image.c:14972:24: error: no member named 'exc_type' in 'struct _ts'
        tmp_type = tstate->exc_type;
                   ~~~~~~  ^
    wordcloud/query_integral_image.c:14973:25: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
        tmp_value = tstate->exc_value;
                            ^~~~~~~~~
                            curexc_value
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
        PyObject *curexc_value;
                  ^
    wordcloud/query_integral_image.c:14974:22: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
        tmp_tb = tstate->exc_traceback;
                         ^~~~~~~~~~~~~
                         curexc_traceback
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
        PyObject *curexc_traceback;
                  ^
    wordcloud/query_integral_image.c:14975:13: error: no member named 'exc_type' in 'struct _ts'
        tstate->exc_type = local_type;
        ~~~~~~  ^
    wordcloud/query_integral_image.c:14976:13: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
        tstate->exc_value = local_value;
                ^~~~~~~~~
                curexc_value
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
        PyObject *curexc_value;
                  ^
    wordcloud/query_integral_image.c:14977:13: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
        tstate->exc_traceback = local_tb;
                ^~~~~~~~~~~~~
                curexc_traceback
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
        PyObject *curexc_traceback;
                  ^
    wordcloud/query_integral_image.c:14999:24: error: no member named 'exc_type' in 'struct _ts'
        tmp_type = tstate->exc_type;
                   ~~~~~~  ^
    wordcloud/query_integral_image.c:15000:25: error: no member named 'exc_value' in 'struct _ts'; did you mean 'curexc_value'?
        tmp_value = tstate->exc_value;
                            ^~~~~~~~~
                            curexc_value
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:237:15: note: 'curexc_value' declared here
        PyObject *curexc_value;
                  ^
    wordcloud/query_integral_image.c:15001:22: error: no member named 'exc_traceback' in 'struct _ts'; did you mean 'curexc_traceback'?
        tmp_tb = tstate->exc_traceback;
                         ^~~~~~~~~~~~~
                         curexc_traceback
    /usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/include/python3.7m/pystate.h:238:15: note: 'curexc_traceback' declared here
        PyObject *curexc_traceback;
                  ^
    wordcloud/query_integral_image.c:15002:13: error: no member named 'exc_type' in 'struct _ts'
        tstate->exc_type = *type;
        ~~~~~~  ^
    fatal error: too many errors emitted, stopping now [-ferror-limit=]
    9 warnings and 20 errors generated.
    error: command 'clang' failed with exit status 1
    
    ----------------------------------------

  Failed building wheel for wordcloud
Command "/usr/local/opt/python/bin/python3.7 -u -c "import setuptools, tokenize;__file__='/private/var/folders/bl/4dsqzdws0dsbq7s8_wntttkm0000gp/T/pycharm-packaging/wordcloud/setup.py';f=getattr(tokenize, 'open', open)(__file__);code=f.read().replace('\r\n', '\n');f.close();exec(compile(code, __file__, 'exec'))" install --record /private/var/folders/bl/4dsqzdws0dsbq7s8_wntttkm0000gp/T/pip-record-wdr3g60r/install-record.txt --single-version-externally-managed --compile --user --prefix=" failed with error code 1 in /private/var/folders/bl/4dsqzdws0dsbq7s8_wntttkm0000gp/T/pycharm-packaging/wordcloud/
