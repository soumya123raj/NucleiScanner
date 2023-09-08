# NucleiFuzzer = Nuclei + Paramspider
`NucleiFuzzer` is an automation tool that combines `ParamSpider` and `Nuclei` to enhance web application security testing. It uses `ParamSpider` to identify potential entry points and `Nuclei's` templates to scan for vulnerabilities. `NucleiFuzzer` streamlines the process, making it easier for security professionals and web developers to detect and address security risks efficiently. Download `NucleiFuzzer` to protect your web applications from vulnerabilities and attacks.

**Note:** `Nuclei` + `Paramspider` = `NucleiFuzzer`

### Tools included:
[ParamSpider](https://github.com/0xKayala/ParamSpider) `git clone https://github.com/0xKayala/ParamSpider.git`<br><br>
[Nuclei](https://github.com/projectdiscovery/nuclei) `git clone https://github.com/projectdiscovery/nuclei.git`

### Templates:
[Fuzzing Templates](https://github.com/projectdiscovery/fuzzing-templates) `git clone https://github.com/projectdiscovery/fuzzing-templates.git`

# Screenshot
![image](https://github.com/0xKayala/NucleiFuzzer/assets/16838353/d3e6466c-8716-45bd-9bac-51f388ef8179)


# Output
![image](https://github.com/0xKayala/NucleiFuzzer/assets/16838353/4bc2998b-b48d-4705-8ba7-16ff4c0aace7)
![image](https://github.com/0xKayala/NucleiFuzzer/assets/16838353/bf911936-1eed-42bc-b81f-35d71a8ebf49)

## Usage

```sh
nucleifuzzer -h
```

This will display help for the tool. Here are the options it supports.


```console
NucleiFuzzer is a Powerful Automation tool for detecting XSS, SQLi, SSRF, Open-Redirect, etc. vulnerabilities in Web Applications

Usage: /usr/local/bin/nucleifuzzer [options]

Options:
  -h, --help              Display help information
  -d, --domain <domain>   Domain to scan for XSS, SQLi, SSRF, Open-Redirect..etc vulnerabilities
```  

### Steps to Install:
1. git clone https://github.com/soumya123raj/NucleiScanner
2. cd NucleiFuzzer
3. sudo chmod +x install.sh
4. ./install.sh <br>
5. nucleifuzzer -h

Made by
`Soumya Mohanty` \

A `Security Researcher` and `Bug Hunter` \

