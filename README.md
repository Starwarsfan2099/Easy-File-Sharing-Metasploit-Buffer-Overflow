# Easy-File-Sharing-Metasploit-Buffer-Overflow
These modules exploit the Easy File Sharing 7.2 Windows program([Download](https://www.exploit-db.com/apps/60f3ff1f3cd34dec80fba130ea481f31-efssetup.exe))
The exploits lie in the `GET` and `HEAD` requests, allowing external code to overwrite the `SEH` and get called and executed. Shellcode space is 390 bytes maximum allowing full meterpreter payloads to be used. This exploit works on any Windows version.
Place these in the `modules/exploits/winodws/ftp` directory to use in metasploit. `RHOST`, `RPORT`, `payload`, and `LHOST` options are required.
