import os
import platform
from colorama import Fore, Style, init

init(autoreset=True)

def clear(self):
    os.system("cls" if "indows" in platform.system() else "clear")
    print(f"""{Fore.GREEN}
                                        .n
                                  .dP         .9b.                  ,n.
             4      .qXb         .dP           Xb         .dKb.    .t      .xb
         dx.   9Xb       .dKb   dXXObbo.      .odXXXXb  dOOXXP.   _.xb
       9XXXXXXXP'XXXXXXXXXXXXXXXXO.   .o0OOOXXXXXXXXXXP` {Fore.YELLOW} v1.0 {Fore.GREEN}
        `9XXXXXXXXXXP'  `9XX'   `98v8P' LAB   `XXP'  `9XXXXXXXP'
          `~~~~~~~    9X.         .db|db.         .XP          ~~~~~~~
                        jb.   .dbo.DP`v`9b.odb.  .dX(
                        ,dXXXXXXXXXXXXXXXXb   dXXXXXXXXXXXXXXb.
                      dXXXXXXXXXXXXXXXXP'   `9XXXXXXXP'
                   dXXXXXXXXXXXXXXXXb  d|b   dXXXXXXXXXXXXXXXXb
                   9XXb'   `XXXXXb.dX|Xb.dXXXXX'   `dXXP'
                             9XXXXXX(   )XXXXXXP
                             XXXX X. v` .X XXXX
                             XP`X`b   d`X`XX
                             X. 9   ' P`X
                             `b   .   d'

                     {Fore.GREEN}LazyWare - Simple Lab Generator

{Fore.BLUE}Disclaimer {Fore.WHITE}: {Fore.RED}This tool is for educational lab purposes only!
{Fore.BLUE}Author {Fore.WHITE}    : {Fore.RED}Justakazh / https://github.com/justakazh
{Style.RESET_ALL}""")
