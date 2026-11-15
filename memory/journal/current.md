# Journal
- 06:13 act: {"say":"Billy here at -271,67,327, hunger 14, no food. I'll head west-south-west to the cow lake near -288,67,257 with Data. Worf, rotten flesh to Laforge first.","intent":{"goal":"travel_to_cow_lake"
- 06:13 act: {"actions":[{"do":"unstick"}],"intent":{"goal":"walk_toward_cow_lake","program":"travel","arguments":{"target":{"x":-288,"y":67,"z":257}},"wake_on":["directly_addressed","precondition_failed","unexpec
- 06:14 act: {"actions":[{"do":"goto","target":{"x":-288,"y":67,"z":260}}],"say":"Billy moving on toward the cow lake with Tommy. Still no food, hunger 14."}
- 06:14 act: {"actions":[{"do":"goto","target":{"x":-305,"y":67,"z":258}}],"say":"No cows at the lake edge. Walking west a little to look.","reasoning":"Short walk west to scan for cows, staying near Tommy."}
- 06:14 act: {"actions":[{"do":"goto","target":{"x":-313,"y":65,"z":258}}],"say":"Salmon in the water to the west. I'll try to get one; Tommy, come along."}
- 06:14 act: {"actions":[{"do":"attack","target":"salmon"}],"reasoning":"Retry the attack; the last call errored at the endpoint, not the world."}
- 06:14 act: {"actions":[{"do":"goto","target":{"x":-311,"y":64,"z":258}}],"reasoning":"I'm in deep water, drifting. Get back to the shore before anything else."}
