# amfiquery

`amfiquery` is simple utility for anyone investing in Indian Mutual
Funds, and who interested in tracking their Net Asset Values. 

It just periodically reads and parses
<http://www.portal.amfiindia.com/spages/NAV0.txt>, and provides an API to query
the current NAV of any mutual fund you're interested in.

Just hit the URL:

<http://navchecker.appspot.com/nav?code=105628>

to get the NAV of the fund with that scheme code. That URL is for `SBI
MAGNUM TAXGAIN SCHEME 1993 - GROWTH`, for example.

Changes:

 - JSON response to get mutual fund meta-info that is stored (name,
   NAV, repurchase price, sale price, etc).
 - Corrected amfindia mutualfund dump link.
 - Changed python runtime to 2.7 and set threadsafe parameter to false in app.yaml.

The application runs on the Google App Engine, and is open-source (under
the GPL v3 license). 

You can find the source code on github, at 

<https://github.com/solancer/amfiquery>

----------------------------------------------------------------------

— Ankit Solanki • <http://ankitsolanki.com/> • <http://simulacra.in>
----------------------------------------------------------------------

Changes by — Srinivas Gowda • <http://solancer.com/> • <http://solancer.com>

