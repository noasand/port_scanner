# python port scanner

simple python port scanner 


# Usage

	Usage: ./scanner.py -H <Target Host> -p <Target Port>

	Options:
	        -H         [Target_Host]                   
        	-p         [Target_Port]  

	Examples:
	        ./scanner.py -H 127.0.0.1 -p 22,23,80,443
          
          
# Example Output

>python3 scanner.py -H 127.0.0.1 -p 22,23,80,443                                                                                                                                               

          [+] Scan Result For : 1
          Scanning Port
          22
          Scanning Port
          23
          Scanning Port
          80
          Scanning Port
          443
          [+] 443 / TCP OPEN
          
          [-] 22 TCP CLosed
          [-] 23 TCP CLosed
          [-] 80 TCP CLosed
          
