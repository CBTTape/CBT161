# CBT161
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 161 IS FROM JIM MARSHALL (AIR FORCE RETIREE) AND CONTAINS *   FILE 161
//*           VARIOUS ISPF/PDF MENUS, PANELS, SKELETONS, CLISTS,    *   FILE 161
//*           ETC. SEE MEMBER $$PROSE FOR ADDITIONAL INFORMATION.   *   FILE 161
//*           THE FILE IS IN IEBUPDTE SYSIN FORMAT.                 *   FILE 161
//*                                                                 *   FILE 161
//*           JIM HAS RETIRED FROM THE AIR FORCE.  HIS ADDRESS IS:  *   FILE 161
//*                                                                 *   FILE 161
//*                 JIM MARSHALL, US TREASURY                       *   FILE 161
//*                 FINANCIAL MANAGEMENT SERVICE                    *   FILE 161
//*                 PRINCE GEORGES PLAZA II - ROOM 400B             *   FILE 161
//*                 3700 EAST-WEST HIGHWAY                          *   FILE 161
//*                 HYATTSVILLE, MD  20782                          *   FILE 161
//*                 202-874-8353                                    *   FILE 161
//*                                                                 *   FILE 161
//*              email:  jim.marshall@fms.treas.gov                 *   FILE 161
//*                                                                 *   FILE 161
//*       RELEASE  18   -  01 Oct 99                                *   FILE 161
//*                                                                 *   FILE 161
//*                                                                 *   FILE 161
//*       SUMMARY OF THE MODULES CONTAINED. HINT: MEMBER MEANS      *   FILE 161
//*       ALL MEMBERS NEEDED FOR PANELS, SKELS, ETC TO USE A        *   FILE 161
//*       PARTICULAR FUNCTION.                                      *   FILE 161
//*                                                                 *   FILE 161
//*                                                                 *   FILE 161
//*       MEMBER   REL              DESCRIPTION                     *   FILE 161
//*       PREFIX                                                    *   FILE 161
//*                                                                 *   FILE 161
//*       @PNL#CI   1  CLIST USED TO DETERMINE IF YOU ARE A         *   FILE 161
//*                    SYSPROG SO YOU CAN GET 'TOOL BOX' PANEL.     *   FILE 161
//*                    YOU NEVER TELL USER THEY CAN NOT HAVE        *   FILE 161
//*                    SOMETHING BECAUSE THEY MAY COMPLAIN &        *   FILE 161
//*                    BOSS BOWS TO PRESSURE (THE WHIMP). SO YOU    *   FILE 161
//*                    GIVE THE USER SOMETHING, YOU GIVE THEM       *   FILE 161
//*                    SOMETHING OF LITTLE VAULE (LIKE PANEL        *   FILE 161
//*                    '@PNL#PI')                                   *   FILE 161
//*                                                                 *   FILE 161
//*       @PNL#PI   1  THE WORTHLESS PANEL SPECIFIED ABOVE.         *   FILE 161
//*                                                                 *   FILE 161
//*       @PNL#PK   1  PANEL OF TSO COMMANDS FOR USERS.             *   FILE 161
//*                                                                 *   FILE 161
//*       @PNL#PM   1  MY CURRENT MASTER MENU.                      *   FILE 161
//*                                                                 *   FILE 161
//*       @PNL#PX   1  THE SYSTEM PROGRAMMER'S 'TOOL BOX'           *   FILE 161
//*                                                                 *   FILE 161
//*       $TOOL#..  1  USER "TOOL CHEST" INVOKED VIA POPUP MENUS.   *   FILE 161
//*                    GIVES OUR USER THE ILLUSION WE USE PC'S      *   FILE 161
//*                    AND ARE NOT ALL OLD MAINFRAMERS.             *   FILE 161
//*                                                                 *   FILE 161
//*       ABND#     1  MEMBERS FOR USING THE ABEND TSO COMMAND.     *   FILE 161
//*                    THIS WILL PROVIDE A FURTHER EXPLANATION OF   *   FILE 161
//*                    SOME OF THE MORE COMMON ABEND.               *   FILE 161
//*                                                                 *   FILE 161
//*       ACC#      3  MEMBERS FOR USING THE TSO ACCOUNT CMD FOR    *   FILE 161
//*                    FMS.                                         *   FILE 161
//*                                                                 *   FILE 161
//*       ADM#      1  TOOK INSPIRATION FROM BILL SMITH, SYNTEX     *   FILE 161
//*                    TO MAKE PANEL FOR GDDM PRESENTATION          *   FILE 161
//*                    GRAPHICS.GOT AN IBM 3279 AND WANTED TO DO    *   FILE 161
//*                    SOME PGF.  BILL MADE IT EASY BY MAKING       *   FILE 161
//*                    PANELS (LOVE IT).                            *   FILE 161
//*                                                                 *   FILE 161
//*       AMB#      1  MEMBERS FOR INTERACTIVELY INVOKE "AMBLIST".  *   FILE 161
//*                                                                 *   FILE 161
//*       ASMH#     3  MEMBERS FOR USING TSO ASMH CMD. ASMH IS TO   *   FILE 161
//*                    INTERACTIVE COMPILES. THESE SERIES OF        *   FILE 161
//*                    SCREENS ETC, ACTUALLY LIMITS THE USER TO     *   FILE 161
//*                    ONLY RECEIVE THEIR ERRORS TO A SYSTERM DD    *   FILE 161
//*                    CARD. SINCE NO LISTINGS, OBJ MODULES, ETC    *   FILE 161
//*                    CAN BE GENERATED, I CALL IT A 'CHEAP         *   FILE 161
//*                    CHECKER'. UPDATED USING "POPUPS".            *   FILE 161
//*                                                                 *   FILE 161
//*       CALC#     1  MEMBERS FOR USING CALC CMD.                  *   FILE 161
//*                    CALC IS A TSO CALCULATOR.                    *   FILE 161
//*                                                                 *   FILE 161
//*       CALEND#   1  MEMBERS FOR POPUP CALENDAR.                  *   FILE 161
//*                                                                 *   FILE 161
//*       CNTI#     1  MEMBERS FOR ISPF VERSION OF THE COUNT TSO    *   FILE 161
//*                    CMD.  USE THE SUPPLIED "COUNTI" TSO CP.      *   FILE 161
//*                                                                 *   FILE 161
//*       COBMVS#   1  MEMBERS FOR COBOL-FOR-MVS CHEAP CHECKER      *   FILE 161
//*                    UPDATED USING "POPUPS".  TSOCP COBMVS IS     *   FILE 161
//*                    FOUND IN FILE 300.                           *   FILE 161
//*                                                                 *   FILE 161
//*       COBOL#    3  MEMBERS FOR USING COBOLCHK. COBOLCHK IS TO   *   FILE 161
//*                    INTERACTIVE COMPILES. THESE SERIES OF        *   FILE 161
//*                    SCREENS ETC, ACTUALLY LIMITS THE USER TO     *   FILE 161
//*                    ONLY RECEIVE THEIR ERRORS TO A SYSTERM DD    *   FILE 161
//*                    CARD. SINCE NO LISTINGS, OBJ MODULES, ETC    *   FILE 161
//*                    CAN BE GENERATED, I CALL IT A 'CHEAP         *   FILE 161
//*                    CHECKER'.                                    *   FILE 161
//*                                                                 *   FILE 161
//*       COB2#     3  MEMBERS FOR COBOL II VERSION OF CHEAP        *   FILE 161
//*                    CHECKER UPDATED USING "POPUPS".              *   FILE 161
//*                                                                 *   FILE 161
//*       COMPR#    3  MEMBERS FOR USING THE TSO COMPARE CMD.       *   FILE 161
//*                    UPDATED USING "POPUPS".                      *   FILE 161
//*                                                                 *   FILE 161
//*       COPYS#    2  MEMBERS FOR USING TSO COPYSDS CMD. COPYSDS   *   FILE 161
//*                    IS A SEQUENTIAL DATASET COPY. UPDATED        *   FILE 161
//*                    USING "POPUPS".                              *   FILE 161
//*                                                                 *   FILE 161
//*       COUNT#    2  MEMBERS FOR USING THE TSO COUNT COMMAND.     *   FILE 161
//*                    COUNT THE NUMBER OF RECORDS IN A FILE.       *   FILE 161
//*                                                                 *   FILE 161
//*       CUT...    1  BILL GODFREY'S 'CUT' AND 'PASTE' MACROS IN   *   FILE 161
//*                    ALCCODE VERSUS CLIST (IMPRESSIVE). SEE       *   FILE 161
//*                    CUTDOC                                       *   FILE 161
//*                                                                 *   FILE 161
//*       CVDI      1  ISPF VERSION OF CVD TSOCP.                   *   FILE 161
//*                                                                 *   FILE 161
//*       CVDI#     2  MEMBERS FOR CVD TSOCP (CONVERTS HEX TO       *   FILE 161
//*                    DEC). ADDED "POPUP" SUPPORT.                 *   FILE 161
//*                                                                 *   FILE 161
//*       CVXI      1  ISPF VERSION OF CVX TSOCP.                   *   FILE 161
//*                                                                 *   FILE 161
//*       CVXI#     2  MEMBERS FOR CVX TSOCP (CONVERTS DEC TO       *   FILE 161
//*                    HEX). ADDED "POPUP" SUPPORT.                 *   FILE 161
//*                                                                 *   FILE 161
//*       DEFA#     1  MEMBERS FOR USING DEFINING AN ALIAS IN       *   FILE 161
//*                    YOUR MASTER CATALOG.                         *   FILE 161
//*                                                                 *   FILE 161
//*       DELA#     2  MEMBERS FOR USING DELETING AN ALIAS FROM     *   FILE 161
//*                    THE MASTER  CATALOG.                         *   FILE 161
//*                                                                 *   FILE 161
//*       FORT#     1  MEMBERS FOR USING THE FORT CMD. FORT IS TO   *   FILE 161
//*                    DO INTERACTIVE COMPILES WITH FORTRAN G1.     *   FILE 161
//*                    THESE SERIES OF SCREENS, ETC, ACTUALLY       *   FILE 161
//*                    LIMITS THE THE USER TO ONLY RECEIVE THEIR    *   FILE 161
//*                    ERRORS TO A SYSTERM DD CARD. SINCE NO        *   FILE 161
//*                    LISTINGS, OR OBJECT CAN BE GENERATED, I      *   FILE 161
//*                    CALL IT A 'CHEAP CHECKER'                    *   FILE 161
//*                                                                 *   FILE 161
//*       FORTX#    1  MEMBERS FOR USING THE FORTX CMD. FORTX IS    *   FILE 161
//*                    TO DO INTERACTIVE COMPILES, FORTRAN-HX.      *   FILE 161
//*                    THESE SERIES OF SCREENS, ETC, ACTUALLY       *   FILE 161
//*                    LIMITS THE THE USER TO ONLY RECEIVE THEIR    *   FILE 161
//*                    ERRORS TO A SYSTERM DD CARD. SINCE NO        *   FILE 161
//*                    LISTINGS, OBJECT CAN BE GENERATED, I CALL    *   FILE 161
//*                    IT A 'CHEAP CHECKER'                         *   FILE 161
//*                                                                 *   FILE 161
//*       FREEA#    1  MEMBERS FOR USING FREEALL CMD.               *   FILE 161
//*                                                                 *   FILE 161
//*       HLASM#    1  DIALOG FOR USING "HLASM" INVOKING OF HIGH    *   FILE 161
//*                    LEVEL ASSEMBLER, USING "POPUPS".  TSOCP      *   FILE 161
//*                    HLASM IS FOUND IN FILE 300.                  *   FILE 161
//*                                                                 *   FILE 161
//*       IDT#      1  PANELS SUPPORT TSO/E TRANSMIT-RECEIVE. OUR   *   FILE 161
//*                    USERS ARE NOVICES AND NEEDED A WAY OF USING  *   FILE 161
//*                    FUNCTIONS. SEE THE TSO FILE FOR THE RELATED  *   FILE 161
//*                    MODULES CALLED 'INMXPARM' AND 'INMXZ02'      *   FILE 161
//*                    EXIT.  THIS CONTAINS AN UPDATED VERSION OF   *   FILE 161
//*                    WHAT WAS CONTAINED IN THE MEMBERS TRC#.      *   FILE 161
//*                                                                 *   FILE 161
//*       ISG@MSTR  2  IS THE PRIMARY PANEL THAT YOUR GET WITH      *   FILE 161
//*                    YOU GET INTO ISPF/PDF FOR 2ISG SYSTEM        *   FILE 161
//*                    PROGRAMMERS BE CONCATENATED AHEAD OF         *   FILE 161
//*                    IBM'S (ISPPLIB).                             *   FILE 161
//*                                                                 *   FILE 161
//*       ISR@PRIM  2  IS THE PRIMARY PANEL THAT YOUR GET WITH      *   FILE 161
//*                    YOU GET INTO ISPF/PDF. PANEL LIB YOU USE     *   FILE 161
//*                    SHOULD BE CONCATENATED AHEAD OF IBM'S        *   FILE 161
//*                    (ISPPLIB).                                   *   FILE 161
//*                                                                 *   FILE 161
//*       JUL#      2  MEMBERS FOR JULISPF TSO CMD USING            *   FILE 161
//*                    "POPUPS".                                    *   FILE 161
//*                                                                 *   FILE 161
//*       JULISPF   1  ISPF VERSION OF JULIAN TSO CMD.              *   FILE 161
//*                                                                 *   FILE 161
//*       LASTI#    1  LASTIPL TSOCP DIALOG USING "POPUPS".         *   FILE 161
//*                                                                 *   FILE 161
//*       LASTIPL   1  ISPF VERSION OF LASTIPL TSOCP.               *   FILE 161
//*                                                                 *   FILE 161
//*       LISTC#    1  MEMBERS FOR USING LISTCAT CMD.               *   FILE 161
//*                                                                 *   FILE 161
//*       LSTSU#    1  MEMBERS FOR 'LISTSU' TSO CMD                 *   FILE 161
//*                                                                 *   FILE 161
//*       MEMB#     1  MEMBERS FOR USING MEMBER  CMD.               *   FILE 161
//*                                                                 *   FILE 161
//*       NEWS#     1  MEMBERS FOR USING 2ISG NEWS FACILITY.  NOT   *   FILE 161
//*                    TOO APPLICABLE TO OTHER INSTALLATIONS BUT    *   FILE 161
//*                    IT SHOWS ONE HOW TO SELECTIVELY INVOKE       *   FILE 161
//*                    'BROWSE' SERVICE FROM YOUR  OWN PANELS,      *   FILE 161
//*                    ETC.                                         *   FILE 161
//*                                                                 *   FILE 161
//*       NFLE#     1  EL-CHEAPO FILE TRANSFER TO VM VIA NJE.       *   FILE 161
//*                                                                 *   FILE 161
//*       NPRT#     1  EL-CHEAPO FILE TRANSFER TO VM VIA NJE.       *   FILE 161
//*                                                                 *   FILE 161
//*       NPUN#     1  EL-CHEAPO FILE TRANSFER TO VM VIA NJE.       *   FILE 161
//*                                                                 *   FILE 161
//*       OBSL#     1  MEMBER FOR INVOKING 'OBS' WYLBUR PROGRAM     *   FILE 161
//*                    TO DECOMPRESS WYLBUR FILE, THEN INVOKE       *   FILE 161
//*                    ISPF/PDF BROWSE SERVICE TO BROWSE IT.        *   FILE 161
//*                                                                 *   FILE 161
//*       OMEG#     1  MEMBERS FOR INVOKING OMEGAMON IN TSO.        *   FILE 161
//*                                                                 *   FILE 161
//*       PHIX#     1  CLIST FOR INVOKING PHOENIX COMPUTER BASE     *   FILE 161
//*                    TRAINING SYSTEM. INVOKES A FRONT-END TSO     *   FILE 161
//*                    CP TO THE PHOENIX TSO CP (LIMITS WHO CAN     *   FILE 161
//*                    GET INTO PHOENIX AND WHO CAN NOT).           *   FILE 161
//*                                                                 *   FILE 161
//*       PRT#      3  MEMBERS FOR USING PRINTOFF CMD.  THIS IS     *   FILE 161
//*                    THE FAMOUS 'PRINTOFF' FROM MY TSO FILE.      *   FILE 161
//*                                                                 *   FILE 161
//*       SADSYSP   2  THIS IS THE '2ISG'  PANEL MEMBER THAT GOES   *   FILE 161
//*                    IN YOUR PANEL LIBRARY FOR PROGRAM PRODUCTS.  *   FILE 161
//*                    NEEDED ANOTHER PANEL TO ADD THINGS. LOOK     *   FILE 161
//*                    AT ISR@PRIM  AND THIS MEMBER AND IT WILL     *   FILE 161
//*                    WILL MAKE MORE SENSE.                        *   FILE 161
//*                                                                 *   FILE 161
//*       SADTSOP   2  THIS IS THE '2ISG' PANEL MEMBER THAT GOES    *   FILE 161
//*                    IN YOUR PANEL LIBRARY FOR TSO COMMANDS.      *   FILE 161
//*                    LOOK AT ISR@PRIM  AND THIS MEMBER AND IT     *   FILE 161
//*                    IT WILL MAKE MORE SENSE.                     *   FILE 161
//*                                                                 *   FILE 161
//*       SADUTLP   2  THIS IS THE '2ISG' PANEL MEMBER THAT GOES    *   FILE 161
//*                    IN YOUR PANEL LIB FOR UTILITY FUNCTIONS      *   FILE 161
//*                    AND 'CHEAP CHECKERS'. LOOK AT ISR@PRIM AND   *   FILE 161
//*                    THIS MEMBER AND IT WILL MAKE MORE SENSE.     *   FILE 161
//*                                                                 *   FILE 161
//*       SEND#     2  MEMBERS FOR USING SEND TSO CMD.  'SEND'      *   FILE 161
//*                    A MSG TO ANOTHER USER.                       *   FILE 161
//*                                                                 *   FILE 161
//*       SLSS#     2  A MODIFICATION OF THE SLSS ISPF/PDF PANELS   *   FILE 161
//*                    ON THE MODS TAPE. EXCEPT THIS ONE HAS        *   FILE 161
//*                    COBOL PGM AS THE DRIVER. JIM PETERSON        *   FILE 161
//*                    REWROTE THE ISPF APPLICATION MAKING IT       *   FILE 161
//*                    MORE EFFICIENT (I'M IMPRESSED. I TOOK ALL    *   FILE 161
//*                    THE CODE AND REWROTE IT MYSELF WHEN I        *   FILE 161
//*                    TRIED TO IMPLEMENT IT. IT ALL WORKS NOW.     *   FILE 161
//*                    SEE MEMBER SLSS##PR FOR DOC.                 *   FILE 161
//*                                                                 *   FILE 161
//*       SORT#     3  DO A SMALL SORT INACTIVELY.                  *   FILE 161
//*                                                                 *   FILE 161
//*       SORTLNK   2  ALC PGM TO "LINK EP=SORT', ELIMINATES        *   FILE 161
//*                    "CALL".  UPDATED TO USE "POPUPS".            *   FILE 161
//*                                                                 *   FILE 161
//*       SYSLG#    1  MEMBERS FOR USING BROWSING THE SPOOLED TO    *   FILE 161
//*                    DISK, OPERATOR CONSOLE LOGS. PUT IT INTO     *   FILE 161
//*                    DISK FILES FOR THE PAST 3 WEEKS FOR          *   FILE 161
//*                    BROWSING.                                    *   FILE 161
//*                                                                 *   FILE 161
//*       SYSPR#P   1  SECONDAY PANEL FOR GETTING INTO 2ISG         *   FILE 161
//*                    SYSTEM PROG FUNCTIONS. LOOK AT CLIST THAT    *   FILE 161
//*                    IS INVOKED OUT OF ISR@PRIM WHEN ENTER 'S'.   *   FILE 161
//*                    CLIST INVOKED CHECKS TO SEE IF 1ST CHAR      *   FILE 161
//*                    OF USERID BEGINS WITH 'S'. SO YOU ARE ONE    *   FILE 161
//*                    OF SYSTEMS, IF NOT, YOU ARE A BAD GUY AND    *   FILE 161
//*                    RETURNED TO ISR@PRIM.                        *   FILE 161
//*                                                                 *   FILE 161
//*       TMS#      1  MEMBERS FOR USING TMS CMD (INVOKE UCC1 PGM   *   FILE 161
//*                    FOR INTERACTIVE TMS ACCESS). SEE DOC MEMBER  *   FILE 161
//*                    CALLED  TMS##PR.                             *   FILE 161
//*                                                                 *   FILE 161
//*       ULX...    1  BILL GODFREY'S ISPF DISK SPACE INFO PGM.     *   FILE 161
//*                    INDEXED VTOCS ARE SUPPORTED. USER CAN OPT    *   FILE 161
//*                    DISPLAY A LIST OF FREE SPACE.  SEE ULXDOC.   *   FILE 161
//*                                                                 *   FILE 161
//*       USR#      1  USER INTERFACE USING LIBDEF FACS. DON'T      *   FILE 161
//*                    WANT USERS MESSING WITH MY LOGON PROCS.      *   FILE 161
//*                                                                 *   FILE 161
//*       VFORT#    3  MEMBERS FOR USING VSFORT CMD. VSFORT IS TO   *   FILE 161
//*                    DO INTERACTIVE COMPILES WITH VS FORTRAN.     *   FILE 161
//*                    SERIES OF SCREENS, ETC, ACTUALLY LIMITS      *   FILE 161
//*                    THE THE USER TO ONLY RECEIVE THEIR ERRORS    *   FILE 161
//*                    TO A SYSTERM DD CARD. SINCE NO LISTINGS,     *   FILE 161
//*                    OBJECT CAN BE GENERATED, I CALL IT A         *   FILE 161
//*                    'CHEAP CHECKER' UPDATED TO USE "POPUPS".     *   FILE 161
//*                                                                 *   FILE 161
//*       XBE...    1  BILL GODFREY'S PGM TO SET UP ISPF,  CAN      *   FILE 161
//*                    HAVE SHORT CODE WORDS FOR DSNS YOU           *   FILE 161
//*                    FREQUENTLY EDIT OR BROWSE. SEE XBEDOC FOR    *   FILE 161
//*                    DETAILS.                                     *   FILE 161
//*                                                                 *   FILE 161
//*       ZAP#      1  MEMBERS FOR USING ZAP CMD.                   *   FILE 161
//*                                                                 *   FILE 161
```
