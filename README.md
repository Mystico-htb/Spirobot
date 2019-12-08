############################################################################
###                               Spirobot                               ###
###    Dumps dns records from dnsdumpster, pings results to identify     ###
### valid servers, then crawls through the robots.txt file of main host  ###
###      looking for any misconfigured or exposed endpoints.             ###
### Finally outputs endpoints and response codes. Grep for 200 for fun!  ###
###    Use only for education and authorized research -- MrBreadcrumbs   ###
############################################################################

# Dependencies: 

Curl

# Todo: 

Add threading capabilities, potentially add screenshot of any 200 response code, 
add more dns services to get more output

script may be tuned by editing segments of the ping commands and the timeout flag on the final
curl loop. For slower connections, increase the value of the ping -W flag to reduce the chance
of missing valid hosts.

As with all of my work, I am always learning and open to feedback and improvements!

Hack the Planet!
