Busybox for Windows - SSH
==========================

Scripts for managing MS Windows machines using OpenSSH.

## Help

chmod-0600

    Usage: chmod-0600 [-u USER] FILE...
    
    Make files only read and write for the current user using
    chmod(1) in UNIX and icacls in Windows (Busybox for Windows).

ssh-h-windows-set-busybox

    Usage: ssh-h-windows-set-busybox [OPTS] SSH
    
    After you configured an SSHD server in a windows machine with this
    command you can make *Busybox For Windows* it's default shell.
    
    This is done in three steps:
    
      -u 32|64 : Upload busybox (step1).
      -p       : Enable public key auth (step2).
      -c       : Link to "sh.exe" and "vi.exe" (step3).
    
    For example: ssh-h-windows-set-busybox -u 64 -pc admin@192.168.1.3

## Collaborating

For making bug reports, feature requests, support or consulting visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
