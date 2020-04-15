# Yara

## Description
Yara is used mostly for signature matching. This helps to identify whether a file is malicious by running yara rules on it and seeing if the signatures set in the rules match.
<br />
<br />

## Personal Review
Yara is simple to use and works well. It is widely used by a lot of other tools and antivirus software. There are a lot of web resources for Yara.
<br />
<br />

## Usage
Basic usage for yara is as follows:

```yara <rulesfile> <filetosearch>```

Rules have the following basic syntax:

```
rule <rulename>
{
  strings:
    $str1 = "hello"
    $str2 = "world"
  condition:
    $str1 and $str2
}
```

You can also search with regex, hex, etc.
<br />
<br />

## Resources
https://yara.readthedocs.io/en/v3.4.0/writingrules.html

https://github.com/VirusTotal/yara
