# API4XMLSRV
API used by XMLSERVICE

## PLUGCONF\_H.RPGLE     

* [ftok](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/p0zftok.htm)

```
     D ftok            PR            10I 0 extproc('ftok')
```

* [mkdir](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/mkdir.htm)

```
     D mkdir           PR            10I 0 extproc('mkdir')
```

* [open](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/open.htm)

```
     D openIFS         PR            10I 0 extproc('open')
```

* [close](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/close.htm)

```
     D closeIFS        PR            10I 0 extproc('close')
```

* [shmat](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/ipcshmat.htm)

```
     D shmat           PR              *   extproc('shmat')
```

* [shmctl](https://www.ibm.com/docs/it/i/7.4?topic=ssw_ibm_i_74/apis/ipcshmct.htm)

```
     D shmctl          PR            10I 0 extproc('shmctl')
```

* [shmdt](https://www.ibm.com/docs/it/i/7.4?topic=ssw_ibm_i_74/apis/ipcshmdt.htm)

```
     D shmdt           PR            10I 0 extproc('shmdt')
```

* [shmget](https://www.ibm.com/docs/it/i/7.4?topic=ssw_ibm_i_74/apis/ipcshmgt.htm)

```
     D shmget          PR            10I 0 extproc('shmget')
```

* [semget](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/ipcsemgt.htm)

```
     D semget          PR            10I 0 extproc('semget')
```

* [semctl](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/ipcsemct.htm)

```
     D semctl          PR            10I 0 extproc('semctl')
```

* [semop](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/ipcsemop.htm)

```
     D semop           PR            10I 0 extproc('semop')
```

* [_CALLPGMV](https://www.ibm.com/docs/en/i/7.4?topic=instructions-call-program-variable-length-argument-list-callpgmv)

```
     D callpgmv        PR                  extproc('_CALLPGMV')
```

* [_CPYBWP](https://www.ibm.com/docs/en/i/7.4?topic=instructions-copy-bytes-pointers-cpybwp)

```
     D cpybwp          PR                  extproc('_CPYBWP')
```

* [_CMPSWP4](https://www.ibm.com/docs/en/i/7.4?topic=instructions-compare-swap-cmpsw)


```
     D CMPSWP4         PR            10I 0 extproc('_CMPSWP4')
```

```
     D iconvOpen       PR                  extproc('QtqIconvOpen')
```

```
     D iconvClose      PR                  extproc('iconv_close')
```

## PLUGPASE.RPGLE     


* [Qp2RunPase](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2runpase.htm)       

```
     D Qp2RunPase      PR            10I 0 extproc('Qp2RunPase')
```

* [Qp2malloc](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2malloc.htm)    

```
     D Qp2malloc       PR              *   extproc('Qp2malloc')
```

* [Qp2free](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2free.htm)       

```
     D Qp2free         PR                  extproc('Qp2free')
```

* [Qp2dlopen](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2dlopen.htm) 

```
     D Qp2dlopen       PR            20U 0 extproc('Qp2dlopen')
```

* [Qp2dlsym](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2dlsym.htm)

```
     D Qp2dlsym        PR              *   extproc('Qp2dlsym')
```

* [Qp2CallPase](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2callpase.htm)

```
     D Qp2CallNow      PR            10I 0 extproc('Qp2CallPase')
```

* [Qp2EndPase](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2endpase.htm)    

```
     D Qp2EndPase      PR            10I 0 extproc('Qp2EndPase')
```

* [Qp2SignalPase](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2signalpase.htm)  

```
     D                 PR            10I 0 extproc('Qp2SignalPase')
```

* [Qp2errnop](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2errnop.htm) 

```
     D Qp2errnop       PR              *   extproc('Qp2errnop')
```

* [Qp2paseCCSID](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2paseccsid.htm)   

```
     D                 PR            10I 0 extproc('Qp2paseCCSID')
```

* [Qp2jobCCSID](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2jobccsid.htm)      

```
     D                 PR            10I 0 extproc('Qp2jobCCSID')
```

* [Qp2ptrsize](https://www.ibm.com/docs/en/i/7.4?topic=ssw_ibm_i_74/apis/qp2ptrsize.htm)         

```
     D Qp2ptrsize      PR            10I 0 extproc('Qp2ptrsize')
```



## PLUGSIG_H.RPGLE

```
     D alarm           PR            10U 0 extproc('alarm')
```

```
     D                 PR            10I 0 extproc('Qp0sEnableSignals')
```

```
     D                 PR            10I 0 extproc('Qp0sEnableSignals')
```

```
     D C_sig_err       PR                  extproc('_C_sig_err')
```

```
     D C_sig_dfl       PR                  extproc('_C_sig_dfl')
```

```
     D C_sig_ign       PR                  extproc('_C_sig_ign')
```

```
     D sigaction       PR                  extproc('sigaction')
```

```
     D sigaddset       PR            10I 0 extproc('sigaddset')
```

```
     D sigdelset       PR            10I 0 extproc('sigdelset')
```

```
     D sigemptyset     PR            10I 0 extproc('sigemptyset')
```

```
     D sigfillset      PR            10I 0 extproc('sigfillset')
```

```
     D sigismember     PR            10I 0 extproc('sigismember')
```

```
     D                                     extproc('signal')
```

```
     D sigpending      PR            10I 0 extproc('sigpending')
```

```
     D sigprocmask     PR            10I 0 extproc('sigprocmask')
```

```
     D sigsuspend      PR            10I 0 extproc('sigsuspend')
```

```
     D sigwait         PR            10I 0 extproc('sigwait')
```

```
     D setitimer       PR            10I 0 extproc('setitimer')
```

```
     D getitimer       PR            10I 0 extproc('getitimer')
```

```
     D sigtimedwait    PR            10I 0 extproc('sigtimedwait')
```
