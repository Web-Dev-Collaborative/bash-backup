ls
sudo apt install npm

#!/bin/bash
source ./helpers/colors.sh
source ./helpers/utils.sh
IS_MACOS=$(uname -a | awk '{ print $1 }' | grep -c Darwin 2> /dev/null)
IS_WINDOWS=$(which cmd.exe | grep -c -v 'not found' 2> /dev/null)
LSB_RELEASE=$(which lsb_release | grep -c -v 'not found' 2> /dev/null)
if [ $LSB_RELEASE = 1 ]; then     IS_UBUNTU=$(lsb_release -s -i | grep -c "Ubuntu" 2> /dev/null);     IS_DEBIAN=$(lsb_release -s -i | grep -c "Debian" 2> /dev/null);     IS_RASPBIAN=$(lsb_release -s -i | grep -c "Raspbian" 2> /dev/null); fi
success() {     hr;     c_green "Congratulations, you have everything installed properly!";     hr; }
if [ $IS_MACOS = 1 ]; then     $SHELL -l ./helpers/macos-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_WINDOWS = 1 ]; then     $SHELL -l ./helpers/windows-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_UBUNTU = 1 ]; then     $SHELL ./helpers/ubuntu-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_DEBIAN = 1 ]; then     $SHELL ./helpers/debian-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_RASPBIAN = 1 ]; then     $SHELL ./helpers/raspbian-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ -e /etc/fedora-release ]; then     $SHELL ./helpers/fedora-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; else     c_red "Unknown Operating System, checker script not supported"; fi
#!/bin/bash
source ./helpers/colors.sh
source ./helpers/utils.sh
IS_MACOS=$(uname -a | awk '{ print $1 }' | grep -c Darwin 2> /dev/null)
IS_WINDOWS=$(which cmd.exe | grep -c -v 'not found' 2> /dev/null)
LSB_RELEASE=$(which lsb_release | grep -c -v 'not found' 2> /dev/null)
if [ $LSB_RELEASE = 1 ]; then     IS_UBUNTU=$(lsb_release -s -i | grep -c "Ubuntu" 2> /dev/null);     IS_DEBIAN=$(lsb_release -s -i | grep -c "Debian" 2> /dev/null);     IS_RASPBIAN=$(lsb_release -s -i | grep -c "Raspbian" 2> /dev/null); fi
success() {     hr;     c_green "Congratulations, you have everything installed properly!";     hr; }
if [ $IS_MACOS = 1 ]; then     $SHELL -l ./helpers/macos-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_WINDOWS = 1 ]; then     $SHELL -l ./helpers/windows-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_UBUNTU = 1 ]; then     $SHELL ./helpers/ubuntu-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_DEBIAN = 1 ]; then     $SHELL ./helpers/debian-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_RASPBIAN = 1 ]; then     $SHELL ./helpers/raspbian-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ -e /etc/fedora-release ]; then     $SHELL ./helpers/fedora-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; else     c_red "Unknown Operating System, checker script not supported"; fi
#!/bin/bash
source ./helpers/colors.sh
source ./helpers/utils.sh
IS_MACOS=$(uname -a | awk '{ print $1 }' | grep -c Darwin 2> /dev/null)
IS_WINDOWS=$(which cmd.exe | grep -c -v 'not found' 2> /dev/null)
LSB_RELEASE=$(which lsb_release | grep -c -v 'not found' 2> /dev/null)
if [ $LSB_RELEASE = 1 ]; then     IS_UBUNTU=$(lsb_release -s -i | grep -c "Ubuntu" 2> /dev/null);     IS_DEBIAN=$(lsb_release -s -i | grep -c "Debian" 2> /dev/null);     IS_RASPBIAN=$(lsb_release -s -i | grep -c "Raspbian" 2> /dev/null); fi
success() {     hr;     c_green "Congratulations, you have everything installed properly!";     hr; }
if [ $IS_MACOS = 1 ]; then     $SHELL -l ./helpers/macos-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_WINDOWS = 1 ]; then     $SHELL -l ./helpers/windows-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_UBUNTU = 1 ]; then     $SHELL ./helpers/ubuntu-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_DEBIAN = 1 ]; then     $SHELL ./helpers/debian-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ $IS_RASPBIAN = 1 ]; then     $SHELL ./helpers/raspbian-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; elif [ -e /etc/fedora-release ]; then     $SHELL ./helpers/fedora-checker.sh;     if [ $? -eq 1 ]; then         exit 1;     fi;     success;     exit 0; else     c_red "Unknown Operating System, checker script not supported"; fi
npm i 
npm run start
sudo apt install npm
npm i 
sudo apt update && sudo apt upgrade
npm init
sudo apt install npm
find . -type f -exec sed -i '/copy/d' ./* {} \;
find . -type f -exec sudo  sed -i '/copy/d' ./* {} \;
find . -type d -exec sudo  sed -i '/copy/d' ./* {} \;
find . -type f -exec sed -i '/copy/d' ./* {} \;
find . -name *copy -type f -exec rm -rf {} \;
find . -name *copy*  -type f -exec rm -rf {} \;
find . -type f -exec sed -i '/copy/d' ./* {} \;
fdupes -r -f . | grep -v '^$' | xargs rm -v 
find . -type f -exec sed -i '/copy/d' ./* {} \;
find . -type f -exec sed -i '/-copy/d' ./* {} \;
sudo apt install fdupes
find . -name "* *" -type d | rename 's/ /_/g'   
find . -name "* *" -type f | rename 's/ /_/g'
sudo apt install rename
find . -name "* *" -type f | rename 's/ /_/g'
find . -type f -exec sed -i '/copy/d' ./* {} \;
find -type f -name '*copy*' -delete
cd ..
find -type f -name '*copy*' -delete
find . | xargs grep -l copy | awk '{print "rm "$1}' > doit.sh
find -type f -name '*copy*' -delete
find -type f -name '*copy*' -delete
cd ..
fdupes -r -f . | grep -v '^$' | xargs rm -v 
git pull
git add .
make
make
cd ..
cd ../../../../
pwd
code .
curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh -o install_nvm.sh
bash install_nvm.sh
export NVM_DIR="$HOME/.nvm"
source ~/.bash_profile
code .
sudo apt install && sudo apt update
npm config edit
sudo apt install nvm
//lists all versions
nvm ls-remote
//installs the version you want (in this case version 14.0.0)
nvm install v14.0.0
//use the version that you installed as the default
nvm use v14.0.0
sudo apt install npm
sudo apt install nvm
nvm install v14.0.0
nvm use v14.0.0
nvm install v14.19.2
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
nvm install v14.19.2
nvm use v14.19.2
npm i -f
$ npm config get proxynpm config get proxy
make
npm install -g npm-reinstall
npm install -g npm-reinstall
git pull
ls
cd ..
ls
update
npm i
npm i --legacy-peer-deps
npm i 
npm i 
code .
fdupes -r -f . | grep -v '^$' | xargs rm -v 
firebase login --no-localhost
curl -sL https://firebase.tools | bash
curl -sL https://firebase.tools | bash
firebase login --no-localhost
firebase login --no-localhost
npm install -g firebase-tools
4/0AX4XfWiuhS1IdJ4tkd07wJPFCBjYkIx9Av3mAQT8_J7SK-rS8IlAy18N9iYr1v6syLSTTA
npm install -g firebase-tools
sudo 4/0AX4XfWiuhS1IdJ4tkd07wJPFCBjYkIx9Av3mAQT8_J7SK-rS8IlAy18N9iYr1v6syLSTTA~
sudo npm install -g firebase-tools
sudo npm install -g firebase-tools --force
npm install -g firebase-tools
sudo npm install -g firebase-tools
npm i autofix -g
sudo npm i autofix -g
autofix
sudo npm install netlify-cli -g
sudo apt install build-essential
sudo apt update && sudo apt upgrade
netlify login
netlify login
cd no
cd notes/
prettier --write .
npm i prettier -g
sudo npm i prettier -g
prettier --write .
netlify login
sudo npm install netlify-cli -g
cd ..
npm run start
netlify login
make
code .
npm run start
sudo apt install tree
sudo apt install tree
sudo apt install pandoc -y
sudo apt install tree
npm install netlify-cli --save-dev
make
netlify --login
export LT_USERNAME=bryan.guner
export LT_ACCESS_KEY=sFA2TI1V3nytHbaPn4iJI8wypnT8jOnse0Vg8v5l4uFLlNJCYY
git clone https://github.com/LambdaTest/jest-selenium-webdriver-sample.git
LT  --user bryan.guner@gmail.com --key sFA2TI1V3nytHbaPn4iJI8wypnT8jOnse0Vg8v5l4uFLlNJCYY --dir E:\lambda
LT  --user bryan.guner@gmail.com --key sFA2TI1V3nytHbaPn4iJI8wypnT8jOnse0Vg8v5l4uFLlNJCYY --dir E:\lambda
npm install -g sass
nvm i v12.1.0
sudo apt install nodejs
sudo apt install pandoc -y
git checkout -preview
git checkout preview
npm run start
nvm i v12.1.0
sudo apt update -y
sudo apt update -y
sudo apt upgrade -y
#!/usr/bin/env bash
{ # this ensures the entire script is downloaded # nvm_has() {   type "$1" > /dev/null 2>&1; } nvm_default_install_dir() {   [ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm"; } nvm_install_dir() {   if [ -n "$NVM_DIR" ]; then     printf %s "${NVM_DIR}";   else     nvm_default_install_dir;   fi; } nvm_latest_version() {   echo "v0.35.0"; } nvm_profile_is_bash_or_zsh() {   local TEST_PROFILE;   TEST_PROFILE="${1-}";   case "${TEST_PROFILE-}" in     *"/.bashrc" | *"/.bash_profile" | *"/.zshrc")       return;     ;;     *)       return 1;     ;;   esac; }
nvm_source() {   local NVM_METHOD;   NVM_METHOD="$1";   local NVM_SOURCE_URL;   NVM_SOURCE_URL="$NVM_SOURCE";   if [ "_$NVM_METHOD" = "_script-nvm-exec" ]; then     NVM_SOURCE_URL="https://raw.githubusercontent.com/nvm-sh/nvm/$(nvm_latest_version)/nvm-exec";   elif [ "_$NVM_METHOD" = "_script-nvm-bash-completion" ]; then     NVM_SOURCE_URL="https://raw.githubusercontent.com/nvm-sh/nvm/$(nvm_latest_version)/bash_completion";   elif [ -z "$NVM_SOURCE_URL" ]; then     if [ "_$NVM_METHOD" = "_script" ]; then       NVM_SOURCE_URL="https://raw.githubusercontent.com/nvm-sh/nvm/$(nvm_latest_version)/nvm.sh";     elif [ "_$NVM_METHOD" = "_git" ] || [ -z "$NVM_METHOD" ]; then       NVM_SOURCE_URL="https://github.com/nvm-sh/nvm.git";     else       echo >&2 "Unexpected value \"$NVM_METHOD\" for \$NVM_METHOD";       return 1;     fi;   fi;   echo "$NVM_SOURCE_URL"; }
nvm_node_version() {   echo "$NODE_VERSION"; } nvm_download() {   if nvm_has "curl"; then     curl --compressed -q "$@";   elif nvm_has "wget"; then
    ARGS=$(echo "$*" | command sed -e 's/--progress-bar /--progress=bar /' \
                            -e 's/-L //' \
                            -e 's/--compressed //' \
                            -e 's/-I /--server-response /' \
                            -e 's/-s /-q /' \
                            -e 's/-o /-O /' \
                            -e 's/-C - /-c /')
    eval wget $ARGS;   fi; } install_nvm_from_git() {   local INSTALL_DIR;   INSTALL_DIR="$(nvm_install_dir)"   if [ -d "$INSTALL_DIR/.git" ]; then     echo "=> nvm is already installed in $INSTALL_DIR, trying to update using git";     command printf '\r=> ';     command git --git-dir="$INSTALL_DIR"/.git --work-tree="$INSTALL_DIR" fetch origin tag "$(nvm_latest_version)" --depth=1 2> /dev/null || {       echo >&2 "Failed to update nvm, run 'git fetch' in $INSTALL_DIR yourself.";       exit 1;     };   else
    echo "=> Downloading nvm from git to '$INSTALL_DIR'";     command printf '\r=> ';     mkdir -p "${INSTALL_DIR}";     if [ "$(ls -A "${INSTALL_DIR}")" ]; then       command git init "${INSTALL_DIR}" || {         echo >&2 'Failed to initialize nvm repo. Please report this!';         exit 2;       };       command git --git-dir="${INSTALL_DIR}/.git" remote add origin "$(nvm_source)" 2> /dev/null         || command git --git-dir="${INSTALL_DIR}/.git" remote set-url origin "$(nvm_source)" || {         echo >&2 'Failed to add remote "origin" (or set the URL). Please report this!';         exit 2;       };       command git --git-dir="${INSTALL_DIR}/.git" fetch origin tag "$(nvm_latest_version)" --depth=1 || {         echo >&2 'Failed to fetch origin with tags. Please report this!';         exit 2;       };     else       command git -c advice.detachedHead=false clone "$(nvm_source)" -b "$(nvm_latest_version)" --depth=1 "${INSTALL_DIR}" || {         echo >&2 'Failed to clone nvm repo. Please report this!';         exit 2;       };     fi;   fi;   command git -c advice.detachedHead=false --git-dir="$INSTALL_DIR"/.git --work-tree="$INSTALL_DIR" checkout -f --quiet "$(nvm_latest_version)";   if [ -n "$(command git --git-dir="$INSTALL_DIR"/.git --work-tree="$INSTALL_DIR" show-ref refs/heads/master)" ]; then     if command git --git-dir="$INSTALL_DIR"/.git --work-tree="$INSTALL_DIR" branch --quiet 2>/dev/null; then       command git --git-dir="$INSTALL_DIR"/.git --work-tree="$INSTALL_DIR" branch --quiet -D master >/dev/null 2>&1;     else       echo >&2 "Your version of git is out of date. Please update it!";       command git --git-dir="$INSTALL_DIR"/.git --work-tree="$INSTALL_DIR" branch -D master >/dev/null 2>&1;     fi;   fi   echo "=> Compressing and cleaning up git repository";   if ! command git --git-dir="$INSTALL_DIR"/.git --work-tree="$INSTALL_DIR" reflog expire --expire=now --all; then     echo >&2 "Your version of git is out of date. Please update it!";   fi;   if ! command git --git-dir="$INSTALL_DIR"/.git --work-tree="$INSTALL_DIR" gc --auto --aggressive --prune=now ; then     echo >&2 "Your version of git is out of date. Please update it!";   fi;   return; }
nvm_install_node() {   local NODE_VERSION_LOCAL;   NODE_VERSION_LOCAL="$(nvm_node_version)"   if [ -z "$NODE_VERSION_LOCAL" ]; then     return 0;   fi   echo "=> Installing Node.js version $NODE_VERSION_LOCAL";   nvm install "$NODE_VERSION_LOCAL";   local CURRENT_NVM_NODE   CURRENT_NVM_NODE="$(nvm_version current)";   if [ "$(nvm_version "$NODE_VERSION_LOCAL")" == "$CURRENT_NVM_NODE" ]; then     echo "=> Node.js version $NODE_VERSION_LOCAL has been successfully installed";   else     echo >&2 "Failed to install Node.js $NODE_VERSION_LOCAL";   fi; } install_nvm_as_script() {   local INSTALL_DIR;   INSTALL_DIR="$(nvm_install_dir)";   local NVM_SOURCE_LOCAL;   NVM_SOURCE_LOCAL="$(nvm_source script)";   local NVM_EXEC_SOURCE;   NVM_EXEC_SOURCE="$(nvm_source script-nvm-exec)";   local NVM_BASH_COMPLETION_SOURCE;   NVM_BASH_COMPLETION_SOURCE="$(nvm_source script-nvm-bash-completion)"
  mkdir -p "$INSTALL_DIR";   if [ -f "$INSTALL_DIR/nvm.sh" ]; then     echo "=> nvm is already installed in $INSTALL_DIR, trying to update the script";   else     echo "=> Downloading nvm as script to '$INSTALL_DIR'";   fi;   nvm_download -s "$NVM_SOURCE_LOCAL" -o "$INSTALL_DIR/nvm.sh" || {     echo >&2 "Failed to download '$NVM_SOURCE_LOCAL'";     return 1;   } &   nvm_download -s "$NVM_EXEC_SOURCE" -o "$INSTALL_DIR/nvm-exec" || {     echo >&2 "Failed to download '$NVM_EXEC_SOURCE'";     return 2;   } &   nvm_download -s "$NVM_BASH_COMPLETION_SOURCE" -o "$INSTALL_DIR/bash_completion" || {     echo >&2 "Failed to download '$NVM_BASH_COMPLETION_SOURCE'";     return 2;   } &   for job in $(jobs -p | command sort);   do     wait "$job" || return $?;   done;   chmod a+x "$INSTALL_DIR/nvm-exec" || {     echo >&2 "Failed to mark '$INSTALL_DIR/nvm-exec' as executable";     return 3;   }; } nvm_try_profile() {   if [ -z "${1-}" ] || [ ! -f "${1}" ]; then     return 1;   fi;   echo "${1}"; }
nvm_detect_profile() {   if [ "${PROFILE-}" = '/dev/null' ]; then
    return;   fi   if [ -n "${PROFILE}" ] && [ -f "${PROFILE}" ]; then     echo "${PROFILE}";     return;   fi   local DETECTED_PROFILE;   DETECTED_PROFILE=''   if [ -n "${BASH_VERSION-}" ]; then     if [ -f "$HOME/.bashrc" ]; then       DETECTED_PROFILE="$HOME/.bashrc";     elif [ -f "$HOME/.bash_profile" ]; then       DETECTED_PROFILE="$HOME/.bash_profile";     fi;   elif [ -n "${ZSH_VERSION-}" ]; then     DETECTED_PROFILE="$HOME/.zshrc";   fi   if [ -z "$DETECTED_PROFILE" ]; then     for EACH_PROFILE in ".profile" ".bashrc" ".bash_profile" ".zshrc";     do       if DETECTED_PROFILE="$(nvm_try_profile "${HOME}/${EACH_PROFILE}")"; then         break;       fi;     done;   fi   if [ -n "$DETECTED_PROFILE" ]; then     echo "$DETECTED_PROFILE";   fi; }
nvm_check_global_modules() {   command -v npm >/dev/null 2>&1 || return 0   local NPM_VERSION;   NPM_VERSION="$(npm --version)";   NPM_VERSION="${NPM_VERSION:--1}";   [ "${NPM_VERSION%%[!-0-9]*}" -gt 0 ] || return 0   local NPM_GLOBAL_MODULES;   NPM_GLOBAL_MODULES="$(
    npm list -g --depth=0 |
    command sed -e '/ npm@/d' -e '/ (empty)$/d'
  )"   local MODULE_COUNT;   MODULE_COUNT="$(
    command printf %s\\n "$NPM_GLOBAL_MODULES" |
    command sed -ne '1!p' |                     # Remove the first line
    wc -l | command tr -d ' '                   # Count entries
  )"   if [ "${MODULE_COUNT}" != '0' ]; then
    echo '=> You currently have modules installed globally with `npm`. These will no'
    echo '=> longer be linked to the active version of Node when you install a new node'
    echo '=> with `nvm`; and they may (depending on how you construct your `$PATH`)'
    echo '=> override the binaries of modules installed with `nvm`:';     echo     command printf %s\\n "$NPM_GLOBAL_MODULES";     echo '=> If you wish to uninstall them at a later point (or re-install them under your'
    echo '=> `nvm` Nodes), you can remove them from the system Node as follows:';     echo;     echo '     $ nvm use system';     echo '     $ npm uninstall -g a_module';     echo;   fi; } nvm_do_install() {   if [ -n "${NVM_DIR-}" ] && ! [ -d "${NVM_DIR}" ]; then     if [ -e "${NVM_DIR}" ]; then       echo >&2 "File \"${NVM_DIR}\" has the same name as installation directory.";       exit 1;     fi     if [ "${NVM_DIR}" = "$(nvm_default_install_dir)" ]; then       mkdir "${NVM_DIR}";     else       echo >&2 "You have \$NVM_DIR set to \"${NVM_DIR}\", but that directory does not exist. Check your profile files and environment.";       exit 1;     fi;   fi;   if [ -z "${METHOD}" ]; then
    if nvm_has git; then       install_nvm_from_git;     elif nvm_has nvm_download; then       install_nvm_as_script;     else       echo >&2 'You need git, curl, or wget to install nvm';       exit 1;     fi;   elif [ "${METHOD}" = 'git' ]; then     if ! nvm_has git; then       echo >&2 "You need git to install nvm";       exit 1;     fi;     install_nvm_from_git;   elif [ "${METHOD}" = 'script' ]; then     if ! nvm_has nvm_download; then       echo >&2 "You need curl or wget to install nvm";       exit 1;     fi;     install_nvm_as_script;   else     echo >&2 "The environment variable \$METHOD is set to \"${METHOD}\", which is not recognized as a valid installation method.";     exit 1;   fi   echo   local NVM_PROFILE;   NVM_PROFILE="$(nvm_detect_profile)";   local PROFILE_INSTALL_DIR;   PROFILE_INSTALL_DIR="$(nvm_install_dir | command sed "s:^$HOME:\$HOME:")"   SOURCE_STR="\\nexport NVM_DIR=\"${PROFILE_INSTALL_DIR}\"\\n[ -s \"\$NVM_DIR/nvm.sh\" ] && \\. \"\$NVM_DIR/nvm.sh\"  # This loads nvm\\n"
  COMPLETION_STR='[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion\n';   BASH_OR_ZSH=false   if [ -z "${NVM_PROFILE-}" ] ; then     local TRIED_PROFILE;     if [ -n "${PROFILE}" ]; then       TRIED_PROFILE="${NVM_PROFILE} (as defined in \$PROFILE), ";     fi;     echo "=> Profile not found. Tried ${TRIED_PROFILE-}~/.bashrc, ~/.bash_profile, ~/.zshrc, and ~/.profile.";     echo "=> Create one of them and run this script again";     echo "   OR";     echo "=> Append the following lines to the correct file yourself:";     command printf "${SOURCE_STR}";     echo;   else     if nvm_profile_is_bash_or_zsh "${NVM_PROFILE-}"; then       BASH_OR_ZSH=true;     fi;     if ! command grep -qc '/nvm.sh' "$NVM_PROFILE"; then       echo "=> Appending nvm source string to $NVM_PROFILE";       command printf "${SOURCE_STR}" >> "$NVM_PROFILE";     else       echo "=> nvm source string already in ${NVM_PROFILE}";     fi
    if ${BASH_OR_ZSH} && ! command grep -qc '$NVM_DIR/bash_completion' "$NVM_PROFILE"; then       echo "=> Appending bash_completion source string to $NVM_PROFILE";       command printf "$COMPLETION_STR" >> "$NVM_PROFILE";     else       echo "=> bash_completion source string already in ${NVM_PROFILE}";     fi;   fi;   if ${BASH_OR_ZSH} && [ -z "${NVM_PROFILE-}" ] ; then     echo "=> Please also append the following lines to the if you are using bash/zsh shell:";     command printf "${COMPLETION_STR}";   fi
  \. "$(nvm_install_dir)/nvm.sh"   nvm_check_global_modules   nvm_install_node   nvm_reset   echo "=> Close and reopen your terminal to start using nvm or run the following to use it now:";   command printf "${SOURCE_STR}";   if ${BASH_OR_ZSH} ; then     command printf "${COMPLETION_STR}";   fi; }
nvm_reset() {   unset -f nvm_has nvm_install_dir nvm_latest_version nvm_profile_is_bash_or_zsh     nvm_source nvm_node_version nvm_download install_nvm_from_git nvm_install_node     install_nvm_as_script nvm_try_profile nvm_detect_profile nvm_check_global_modules     nvm_do_install nvm_reset nvm_default_install_dir; } [ "_$NVM_ENV" = "_testing" ] || nvm_do_install } # this ensures the entire script is downloaded #
sudo apt-get install -y build-essential libssl-dev
sudo apt-get install -y build-essential libssl-dev
nvm i v12.0.0
nvm i v12.1.0
sudo apt-get install -y build-essential libssl-dev
sudo nvm install 12.0.0
su
    sudo apt-get install -y vim curl python-software-properties
    sudo apt-get install -y python-dev, python-pip
    sudo apt-get install -y python-dev, python-pip3
    sudo apt-get install -y pip3
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
sudo apg update
nvm i v12.0.0
sudo apt install nodejs && npm -y 
nvm i v12.0.0
sudo apt update
    sudo nvm install 12.0.0
    curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
    source ~/.profile
nvm i v12.0.0
npm i 
npm run start
npm install --save gatsby-transformer-remark
npm run start
 Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
# Installing build essentials
sudo apt-get install -y build-essential libssl-dev
# Installing build essentials
sudo apt-get install -y build-essential libssl-dev
# Nodejs and NVM
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
source ~/.profile
npm run build
ls
bash install_nvm.sh 
code .
sudo apt install 
sudo apt update
sudo apt upgrade
sudo apt install zip
 sudo apt-get install openssh-client
 sudo apt-get install openssh-server
sudo apt-get install sshfs
code .
nvm i v12.1.0
sudo apt-get update -y
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash
. ./.bashrc
~/.bashrc
sudo ~/.bashrc
sudo apt install unzip
sudo apt install build-essential
nvm install --lts
~/.bashrc
sudo ~/.bashrc
sudo ~/.bashrc
 ~/.bashrc
nvm i v14.5.0
sudo apt-get install git -y
sudo apt-get install curl
curl -sL https://deb.nodesource.com/setup | sudo bash -
sudo apt-get install -y nodejs
vim ~./.bashrc
vim ~./.bashrc
 ~./.bashrc
 ~/.bashrc
su
 ~/.bashrc
# Create a folder
mkdir actions-runner && cd actions-runner
# Download the latest runner package
curl -o actions-runner-linux-x64-2.292.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.292.0/actions-runner-linux-x64-2.292.0.tar.gz
# Optional: Validate the hash
echo "14839ba9f3da01abdd51d1eae0eb53397736473542a8fae4b7618d05a5af7bb5  actions-runner-linux-x64-2.292.0.tar.gz" | shasum -a 256 -c
# Extract the installer
tar xzf ./actions-runner-linux-x64-2.292.0.tar.gz
Configure
# Create the runner and start the configuration experience
./config.sh --url https://github.com/bgoonz/BGOONZ_BLOG_2.0 --token AP4RFILTCBLJPS56IK2IA5LCUWI6S
bgoonz
./config.sh --url https://github.com/bgoonz/BGOONZ_BLOG_2.0 --token AP4RFILTCBLJPS56IK2IA5LCUWI6S
./config.sh --url https://github.com/bgoonz/BGOONZ_BLOG_2.0 --token AP4RFILTCBLJPS56IK2IA5LCUWI6S
sudo ./config.sh --url https://github.com/bgoonz/BGOONZ_BLOG_2.0 --token AP4RFILTCBLJPS56IK2IA5LCUWI6S
sudo ./config.sh --url https://github.com/bgoonz/BGOONZ_BLOG_2.0 --token AP4RFILTCBLJPS56IK2IA5LCUWI6S
./config.sh --url https://github.com/bgoonz/BGOONZ_BLOG_2.0 --token AP4RFILTCBLJPS56IK2IA5LCUWI6S
nvm i v14.5.0
nvm i v14.5.0
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
source ~/.profile
nvm i v14.5.0
npm i 
npm run build
ubuntu
linux
wsl
sudo apt install wsl
wsl
sudo apt install npm 
sudo apt install nvm
nvm i v14.5.0
sudo apt install npm 
sudo apt install nodejs
node
~/.bashrc
sudo ~/.bashrc
. ./.bashrc
 ./.bashrc
../.bashrc
~/.bashrc
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash 
 sudo apt install build-essential
nvm i v14.5.0
# Create a folder
mkdir actions-runner && cd actions-runner
# Download the latest runner package
curl -o actions-runner-linux-x64-2.292.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.292.0/actions-runner-linux-x64-2.292.0.tar.gz
# Optional: Validate the hash
echo "14839ba9f3da01abdd51d1eae0eb53397736473542a8fae4b7618d05a5af7bb5  actions-runner-linux-x64-2.292.0.tar.gz" | shasum -a 256 -c
# Extract the installer
tar xzf ./actions-runner-linux-x64-2.292.0.tar.gz
Configure
# Create the runner and start the configuration experience
./config.sh --url https://github.com/bgoonz/BGOONZ_BLOG_2.0 --token AP4RFILTCBLJPS56IK2IA5LCUWI6S
curl   -H "Accept: application/vnd.github.v3+json"   https://api.github.com/repos/bgoonz/BGOONZ_BLOG_2.0/commits
curl   -H "Accept: application/vnd.github.v3+json"   https://api.github.com/repos/bgoonz/BGOONZ_BLOG_2.0/commits >commits.md
code .
sudo apt install chrome
sudo apt install google-chrome
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb --fix-missing
sudo dpkg -i google-chrome-stable_current_amd64.deb
ls
cd ../../../../..
ls
cd mnt
cd c
ls
MY-WEB-DEV/
ls
cd MY-WEB-DEV/
ls
cd blog-march/
code-insiders
source ~/.profile
cd docs
prettier --write .
source ~/.profile
git pul
git pull
make
