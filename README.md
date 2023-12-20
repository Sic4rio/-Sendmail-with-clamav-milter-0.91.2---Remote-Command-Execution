# -Sendmail-with-clamav-milter-0.91.2---Remote-Command-Execution
 Sendmail with clamav-milter &lt; 0.91.2 - Remote Command Execution Python Exploit 
 
# Clam AntiVirus 'clamav-milter' Remote Code Execution Exploit

This Python script exploits a vulnerability in the Clam AntiVirus suite 'clamav-milter' (Sendmail mail filter). The vulnerability exists in versions prior to v0.92.2, allowing remote code execution when implemented with black hole mode enabled, due to an insecure `popen` call.

## Usage

### Prerequisites

- Python 3.x

### Running the Exploit

1. Clone the repository:

```
   git clone https://github.com/yourusername/clamav-milter-exploit.git
   cd clamav-milter-exploit
```

2. Run the script with the target host as a command-line argument:
```
 python exploit.py 192.168.1.2
```
## Module Information

- **Module Name**: clamav-milter Remote Code Execution
- **Author**: Patrick x Sic4rio
- **License**: MIT_LICENSE
- **Version**: $Revision: 10617 $
- **Disclosure Date**: Aug 24 2007

## References

- [CVE-2007-4560](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-4560)
- [OSVDB-36909](https://www.osvdb.org/show/osvdb/36909)
- [BID-25439](https://www.securityfocus.com/bid/25439)
- [Milw0rm Exploit](http://www.milw0rm.com/exploits/4761)

## Options

- `MAILTO`: TO address of the e-mail (default: `nobody@localhost`)

## Disclaimer

This exploit is provided for educational purposes only. Unauthorized use against systems you do not own or have explicit permission to test is illegal.

## Author

- Sic4rio

## License

This project is licensed under the [MIT License](LICENSE).
   
