# this file contains the aliases used by me to get quick results of LLVM/Clang
# to use this, add these inside shell profile files such as ~/.profile, ~/.bashrc

<pre>

alias d_clang='clang -E -x c  /dev/null -dM'
alias v_clang='clang -E -x c /dev/null -v'
alias d_clang++='clang++ -E -x c++  /dev/null -dM'
alias v_clang++='clang++ -E -x c++ /dev/null -v'
alias help_cc1='clang -cc1 -analyzer-checker-help |less'
alias scan_build='scan-build --use-analyzer=$(which clang)'
alias v_cc1_o0='clang /dev/null -xc -O0 - -o /dev/null -\#\#\# 2>&1 | tr " " "\n"'
alias v_cc1_o1='clang /dev/null -xc -O1 - -o /dev/null -\#\#\# 2>&1 | tr " " "\n"'
alias v_cc1_o2='clang /dev/null -xc -O2 - -o /dev/null -\#\#\# 2>&1 | tr " " "\n"'
alias v_cc1_o3='clang /dev/null -xc -O3 - -o /dev/null -\#\#\# 2>&1 | tr " " "\n"'
alias v_cc1_os='clang /dev/null -xc -Os - -o /dev/null -\#\#\# 2>&1 | tr " " "\n"'
alias v_cc1_oz='clang /dev/null -xc -Oz - -o /dev/null -\#\#\# 2>&1 | tr " " "\n"'
alias v_cc1_ofast='clang /dev/null -xc -Ofast - -o /dev/null -\#\#\# 2>&1 | tr " " "\n"'
alias v_clang_llvm='clang -xc /dev/null -c -mllvm -print-all-options'
</pre>
# pass g++ to clang++
alias g++="clang++"
