# Netcat

## Description
Netcat is a simple program that provisions a listener and a sender. It makes an easy way for things to be sent from one location to another (i.e. messages or files).
<br />
<br />

## Personal Review
Super nifty little tool. It is not complicated and does what it is supposed to do well. This could be used for remote acquisition or just getting things from one place to another quickly.
<br />
<br />

## Usage
1. Download from site (See `Resources` Section) if using Windows. If on Linux, it might be installed already. If not, use `sudo apt install netcat` to install.
2. Set up the Listener on Windows

```nc -L -p 5555 > filename.txt```

3. Run a file and pipe it to netcat on the other machine (Linux in this case)

```cat /etc/passwd | nc <IP address> 5555```

This will send the /etc/passwd file from the Linux machine and write it into a file on the Windows machine called filename.txt
<br />
<br />

## Resources
https://joncraton.org/blog/46/netcat-for-windows/
