# kavlan-tester

Tool to test kavlan robustness.

Basic usage:

reserve a VLAN and nodes:
oarsub -t deploy -l {"type='kavlan'"}/vlan=1,walltime=5 'sleep 1d'
oarsub -t deploy -p "ethnb>1" -l nodes=5,walltime=4 'sleep 1d'

Edit script to set VLAN id and list of nodes, and number of iterations

Run. Debug issues.
