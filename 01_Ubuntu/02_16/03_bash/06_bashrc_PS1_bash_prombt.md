# bash prombt in ~/.bashrc
```{bash}
vi ~/.bashrc
...
if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]\n\$ '
else
    PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\n\$ '
fi
...
```

# option code
```{text}
d - the date in "Weekday Month Date" format (e.g., "Tue May 26")
e - an ASCII escape character (033)
h - the hostname up to the first .
H - the full hostname
j - the number of jobs currently run in background
l - the basename of the shells terminal device name
n - newline
r - carriage return
s - the name of the shell, the basename of $0 (the portion following the final slash)
t - the current time in 24-hour HH:MM:SS format
T - the current time in 12-hour HH:MM:SS format
@ - the current time in 12-hour am/pm format
A - the current time in 24-hour HH:MM format
u - the username of the current user
v - the version of bash (e.g., 4.00)
V - the release of bash, version + patch level (e.g., 4.00.0)
w - Complete path of current working directory
W - the basename of the current working directory
! - the history number of this command
# - the command number of this command
$ - if the effective UID is 0, a #, otherwise a $
nnn - the character corresponding to the octal number nnn
```
