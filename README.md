# calabash-commands
Calabash Commands

#Install Calabash
curl -sSL https://raw.githubusercontent.com/calabash/install/master/install-osx.sh | bash

#Starting Calabash
./calabash-sandbox

#Import Android SDK
export ANDROID_HOME=/Applications/sdk
export PATH=$PATH:$ANDROID_HOME:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools:$ANDROID_HOME/add-ons

#Calabash Console Start
calabash-android console app-staging-debug.apk
start_test_server_in_background
--run query
query("*")

#Calabash Console Exit
exit

#Running on your local/emulator device
calabash-android run app-staging-debug.apk --verbose
