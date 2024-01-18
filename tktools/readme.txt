tk目的是为了在沉浸模式下定时提醒(macos版本，linux需要调整date参数)。
可以通过在命令下模式下输入tk 10[h|m|s] describe 或者 tk 18:00:00 describe达到定时提醒的效果。
前提： 将tk文件放入PATH路径下，方便执行。 

printf "\tUsage:   %s 10[h|m|s] default add suffix s means seconds\n " "$0"
echo -e "\tExample: $0 10[h|m|s] default no sufiix,indicate seconds"
echo -e "\tExample: $0 18:00:00"
