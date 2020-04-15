# Volatility

## Description
This tool takes as input a memory file, captured from a live system. Volatility takes that memory file and helps index the items and analyze it. Different plugins help to view different aspects of what was in memory.
<br />
<br />

## Personal Review
I didn't 
use everything that Volatility had and I was amazed at how awesome it was. Definitely a nice DF/Malware Analysis tool
<br />
<br />

## Usage
Volatility is already installed on Kali Linux by default. This can be used. Begin with this command

```volatility -f file.vmem imageinfo```

After running this command, Use suggested profiles to execute more commands. For example:

```volatility -f file.vmem --profile WinXPSP3x86 psscan```

There are plenty of plugins to use besides psscan
<br />
<br />

## Resources
https://www.volatilityfoundation.org/

https://github.com/volatilityfoundation/volatility
