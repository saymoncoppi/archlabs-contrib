#!/usr/bin/env bash
clear; echo #clear sccreen and clean line
c1='\e[38;5;235m' # Dark Grey
c2='\e[38;5;237m' # Light Grey
c3='\e[1;38;5;235m' # Bold

# Fixing and centering Positions
splash() {
#Column
banner_width=46
indent=$(( (COLUMNS - banner_width) / 2 ))
prefix=''
for ((i=1; i<=indent; i++)) ; do
    prefix+=' '
done  

#Line
LINES=`tput lines`
line=`expr $LINES / 2 - 20`
tput cup $line

#Display 
echo -ne "                                                                                             
${prefix}${c1}                     'c'
${prefix}                    'kKk,
${prefix}                   .dKKKx.
${prefix}                  .oKXKXKd.
${prefix}                 .l0XXXXKKo.
${prefix}                 c0KXXXXKX0l.
${prefix}                :0XKKOxxOKX0l.
${prefix}               :OXKOc. .c0XX0l.
${prefix}              :OK0o. ${c2}...${c1}'dKKX0l.
${prefix}             :OX0c  ${c2};xOx'${c1}'dKXX0l.
${prefix}            :0KKo.${c2}.o0XXKd'.${c1}lKXX0l.
${prefix}           c0XKd.${c2}.oKXXXXKd..${c1}oKKX0l.
${prefix}         .c0XKk;${c2}.l0K0OO0XKd..${c1}oKXXKo.
${prefix}        .l0XXXk:${c2},dKx,.'l0XKo.${c1}.kXXXKo.
${prefix}       .o0XXXX0d,${c2}:x;   .oKKx'${c1}.dXKXXKd.
${prefix}      .oKXXXXKK0c.${c2};.    :00c'${c1}cOXXXXXKd.
${prefix}     .dKXXXXXXXXk,${c2}.     cKx'${c1}'xKXXXXXXKx'
${prefix}    'xKXXXXK0kdl:.     ${c2}.ok; ${c1}.cdk0KKXXXKx'
${prefix}   'xKK0koc,..         ${c2}'c, ${c1}    ..,cok0KKk,            
${prefix}  ,xko:'.             ${c2}.. ${c1}           .':okx;
${prefix} .,'.                                   .',.\n
${prefix}${c3}          Welcome to ArchLabs Linux${c1}


${prefix}Run:
${prefix}${c2}    archlabs-installer${c1} ( Default installer )
${prefix}${c2}                       -l${c1} Live, ${c2}-t${c1} TearFree"
}

splash

# Putting cursor at the last line
LINES=`tput lines`
line=`expr $LINES`
tput cup $line
