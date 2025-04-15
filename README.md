# CBT600
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 600 is from Paul Wells, and contains C Language programs  *   FILE 600
//*           which format SMF TCP/IP records (types 118 and 119).  *   FILE 600
//*                                                                 *   FILE 600
//*           Name      : Paul Wells                                *   FILE 600
//*                                                                 *   FILE 600
//*           Address   : Saudi Aramco Box 12959                    *   FILE 600
//*                       Dhahran 31311                             *   FILE 600
//*                       Saudi Arabia                              *   FILE 600
//*                                                                 *   FILE 600
//*           Telephone : +966 3 873 3155 (Work - direct line)      *   FILE 600
//*                                                                 *   FILE 600
//*           Fax       : +966 3 873 8958 (Work)                    *   FILE 600
//*                                                                 *   FILE 600
//*           Email     : Paul.Wells@aramco.com                     *   FILE 600
//*                                                                 *   FILE 600
//*           Yahoo     : paulwells_technogold                      *   FILE 600
//*                                                                 *   FILE 600
//*      Contained herein are two programs (FTPC118 and FTPC119)    *   FILE 600
//*      written in the C language to process SMF type 118/119      *   FILE 600
//*      records from the FTP component of TCPIP on IBM's OS/390    *   FILE 600
//*      and z/OS operating systems.  A minimum operating system    *   FILE 600
//*      level of OS/390 2.5 is required.                           *   FILE 600
//*                                                                 *   FILE 600
//*      The programs operate in two modes: SMF exit mode and       *   FILE 600
//*      TEST mode.                                                 *   FILE 600
//*                                                                 *   FILE 600
//*      In SMF exit mode the programs are installed as             *   FILE 600
//*      operating system SMF exits and invoked by the system       *   FILE 600
//*      each time an SMF record is written. In this mode the       *   FILE 600
//*      programs select FTP SMF records and issue formatted WTO    *   FILE 600
//*      (Write to Operator) messages for each FTP related          *   FILE 600
//*      record.                                                    *   FILE 600
//*                                                                 *   FILE 600
//*      In TEST mode the programs run in batch against an input    *   FILE 600
//*      file of SMF data and print FTP related records to a        *   FILE 600
//*      file.                                                      *   FILE 600
//*                                                                 *   FILE 600
//*      The primary motivation for the creation of these           *   FILE 600
//*      programs was to enable an installation to log FTP          *   FILE 600
//*      activity in real-time for tracking, audit and              *   FILE 600
//*      automation purposes and also to report on historical       *   FILE 600
//*      FTP activity. The secondary motivation was to show that    *   FILE 600
//*      the C language could be used for operating system exits    *   FILE 600
//*      on OS/390.                                                 *   FILE 600
//*                                                                 *   FILE 600
//*      There are a few other programs in this file as follows.    *   FILE 600
//*                                                                 *   FILE 600
//*      RXMAILER (REXX) - A REXX bulk emailer which opens a        *   FILE 600
//*                        socket connection to an SMTP server      *   FILE 600
//*                        and transmits SMTP format input data.    *   FILE 600
//*                        It is similar in function to UDSMTP,     *   FILE 600
//*                        but RXMAILER has many additional         *   FILE 600
//*                        features.                                *   FILE 600
//*      HPNSTST (ASM)   - A program to exercise to TCP/IP HPNS     *   FILE 600
//*                        API.                                     *   FILE 600
//*         NOTE:  Fixed by Mike Tomkins (2006/Feb)                 *   FILE 600
//*         ----   email: mjt6@daimlerchrysler.com                  *   FILE 600
//*                                                                 *   FILE 600
//*      ANFUXMSG (ASM)  - A message exit for IBM's Infoprint       *   FILE 600
//*                        Server which generates formatted single  *   FILE 600
//*                        or multi-line WTOs.                      *   FILE 600
//*      NICKNC (C)      - A fun program which generates combines   *   FILE 600
//*                        common English language phonetic sounds  *   FILE 600
//*                        to generate random nicknames.            *   FILE 600
//*                                                                 *   FILE 600
```
