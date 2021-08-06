# Warping Reality - creating and countering the next generation of Linux rootkits using eBPF
Presentation given at [DEF CON 29](https://defcon.org/html/defcon-29/dc-29-speakers.html#path).

## Abstract
With complete access to a system, Linux kernel rootkits are perfectly placed to hide malicious access and activity. However, running code in the kernel comes with the massive risk that any change to a kernel version or configuration can mean the difference between running successfully and crashing the entire system. This talk will cover how to use extended Berkley Packet Filters (eBPF) to create kernel rootkits that are safe, stable, stealthy, and portable.

eBPF is one of the newest additions to the Linux kernel, designed to easily load safe, constrained, and portable programs into the kernel to observe and make decisions about network traffic, syscalls, and more. But that’s not it’s only use: by creating eBPF programs that target specific processes we can warp reality, presenting a version of a file to one program and a different version to another, all without altering the real file on disk. This enables techniques such as presenting a backdoor user to ssh while hiding from sysadmins, or smuggling data inside connections from legitimate programs. This talk will also cover how to use these same techniques in malware analysis to fool anti-sanbox checks.

These ideas and more are explored in this talk alongside practical methods to detect and prevent this next generation of Linux rootkits.

## Video:
https://www.youtube.com/watch?v=g6SKWT7sROQ

## Slides
[https://github.com/pathtofile/Presentations/blob/master/2021_defcon/path-defcon29-ebpf.pdf](https://github.com/pathtofile/Presentations/blob/master/2021_defcon/path-defcon29-ebpf.pdf)

## Code
[https://github.com/pathtofile/bad-bpf](https://github.com/pathtofile/bad-bpf)

## Blog
[https://blog.tofile.dev/2021/08/01/bad-bpf.html](https://blog.tofile.dev/2021/08/01/bad-bpf.html)
