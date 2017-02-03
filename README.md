# impression
A simple script to register a page impression on a set of URLs with a specific referrer

## Rationale
To iteratively hit a page with the referrer of an aggregation page to increase the measured click through rate of links, which should be reflected in the relavent portal analytics dashboard. This was needed by a friend to determine if underused links were being reported correctly. 

I really did not think that it be as simple as adding the referrer to a curl request and hitting it a couple of times, but apparently this did work better than expected. I'm dubious of this working on high volume services or sites that rely solely on JavaScript to measure analytics.