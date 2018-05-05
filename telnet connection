
import telnetlib
import getpass

host =  raw_input("Enter switch Ip address: ")
user = raw_input("Enter your telnet username: ")
password = getpass.getpass()

tn = telnetlib.Telnet(host)

tn.write("conf t\n")
tn.write("vlan "number"")
tn.write("name Pythonvlan10\n")
tn.write("vlan "number"")
tn.write("name Pythonvlan20\n")
tn.write("end\n")
tn.write("exit\n")

print tn.read_all()
