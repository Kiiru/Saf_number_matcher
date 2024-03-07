# Safaricom patterns test
~ This binary aims to test Safaricom and none Saf MSISDN Ranges (See bellow link).
	https://www.dignited.com/57218/safaricom-introduces-new-prefix-numbers-0110-and-0111/

* Requirements:
==================
- Download or install java 21 on your workstation
- Download this binary SafaricomPattern.jar

* Running the binary:
========================
- To run the binary navigate to its directory and run bellow command

	java -jar SafaricomPattern.jar 0778224569 0768224569 0714224569

The numbers can be more or less. 

* Sample Results
-------------------
java -jar SafaricomPattern.jar 0778224569
0778224569 does not match Safaricom MSISDN pattern

java -jar SafaricomPattern.jar 0768224569
0768224569 matches Safaricom MSISDN pattern
# Saf_number_matcher
