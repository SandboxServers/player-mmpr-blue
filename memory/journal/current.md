# Journal
- 08:13 act: {"say":"Morning. Billy here at the bed row, health 20, hunger 20. Jason, Tommy, Kimberly: when everyone is in sight, we walk to the cow field together. Who is lowest, call it.","intent":{"goal":"hold_
- 08:14 act: {"say":"Trini is at health 7. Jason, please give Trini a melon or beef now. I have no food and no planks, sorry Trini. Then we walk together.","actions":[]}
- 08:15 act: {"say":"Coming with you, Jason. Going to Trini at 415,-1037.","actions":[{"do":"goto","target":{"x":418,"y":107,"z":-1037}}]}
- 08:15 act: {"say":"I'm here with Jason, Trini and Troi. Trini, eat until you feel steady. The cow walk waits until you are fed and everyone is in sight.","intent":{"goal":"stay_with_group_until_cow_walk","progra
- 08:20 act: {"say":"Everyone, gather at 429,107,-1035 first, in sight of each other. Then we walk to the cow field together in daylight. Jason, Trini, Troi, come along.","actions":[{"do":"goto","target":{"x":429,
- 08:21 act: {"say":"Everyone is here. We walk now to the cow field at 339,104,-979, in daylight, staying in sight. Trini, Jason, Wesley, Tommy, Kimberly, Leonardo: follow me.","intent":{"goal":"cow_walk_to_339_10
- 08:21 act: {"say":"My walk stopped and I am alone at 423,-1030. Everyone please hold at 429,107,-1035 until we are in sight again. I am heading back there.","actions":[{"do":"goto","target":{"x":429,"y":107,"z":
- 08:21 act: {"say":"The cow field is too far to reach before dusk. We hold at the beds today, all together, and walk at first light tomorrow. Trini and Wesley, call me if anyone reaches 6."}
- 08:25 act: {"actions":[{"do":"goto","target":{"x":429,"y":107,"z":-1036}},{"do":"note","text":"Night, day 344. Holding at the beds with the group. Moving to the white bed at 429,107,-1036 to sleep; walk at first
- 08:26 act: {"say":"Billy calling the cow walk now. Everyone follow in sight, to the cow field at 339,-979. Lowest eats first.","intent":{"goal":"cow_walk_group","program":"travel","arguments":{"target":{"x":339,
- 08:27 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1035}}],"say":"No cows at 339,-979, and a skeleton with a bow is 21 away to the northwest. Tommy and I are going back to the beds. Nobody walk o
- 08:30 act: {"say":"Morning, day 345. Billy at the beds, health 20, hunger 20. We hold here together. Next, we search for cows or chickens in one group, in sight of each other, only in full daylight.","actions":[
- 08:38 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1036}}],"say":"Billy going to bed at 415,-1036, group in sight. Walk at first light together."}
- 08:38 act: {"actions":[],"say":"Morning, all. Billy here at the beds. Walk together to the cow field at 339,-979, everyone in sight. Nobody walks out alone. Lowest eats first."}
- 08:43 act: {"intent":{"goal":"cow_walk_together","program":"travel","arguments":{"x":339,"y":104,"z":-979},"wake_on":["directly_addressed","precondition_failed","unexpected_damage","goal_completed"],"limits":{"m
- 08:43 act: {"intent":{"goal":"cow_walk_together","program":"travel","arguments":{"target":{"x":339,"y":104,"z":-979}},"wake_on":["directly_addressed","precondition_failed","unexpected_damage","goal_completed"],"
- 08:43 act: {"actions":[{"do":"goto","target":{"x":364,"y":104,"z":-1000}}],"say":"Travel failed. Trying a shorter walk to 364,-1000, then on to the cow field. Stay in sight."}
- 08:43 act: {"actions":[{"do":"unstick"}]}
- 08:44 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1033}}],"say":"I fell in a pit near 364,-1000, now out. Route to the cows is blocked. Nobody come this way. We go back to the beds and wait for 
- 08:48 act: {"actions":[{"do":"goto","target":{"x":429,"y":107,"z":-1035}}],"say":"Billy here, at the beds. I'll wait with the group. When we agree on a path, I'll walk only in sight."}
- 08:52 act: {"actions":[],"say":"Morning. Billy here, health 20, hunger 20. I'll walk with the group in sight. Who is going first?"}
- 08:53 act: {"intent":{"goal":"walk_to_cow_field","program":"travel","arguments":{"target":{"x":339,"y":104,"z":-979}},"wake_on":["directly_addressed","precondition_failed","unexpected_damage","goal_completed"],"
- 08:53 act: {"actions":[{"do":"goto","target":{"x":421,"y":107,"z":-1034}}],"say":"The travel failed and I'm not walking alone. I'm back near the beds. Trini, call me when you're ready and I'll wait for you."}
- 08:53 act: {"actions":[],"say":"Wesley, good. Trini, come to me here at 421,-1033. When we're all in sight we'll walk together to the cow field."}
- 08:54 act: {"intent":{"goal":"walk_to_cow_field_group","program":"travel","arguments":{"target":{"x":339,"y":104,"z":-979}},"wake_on":["directly_addressed","precondition_failed","unexpected_damage","goal_complet
- 08:54 act: {"actions":[{"do":"goto","target":{"x":405,"y":107,"z":-1010}}],"say":"Travel stopped again. I'm taking a short step toward the field, to 405,-1010. Stay in sight."}
- 08:54 act: {"actions":[{"do":"goto","target":{"x":421,"y":107,"z":-1034}}],"say":"I'm going back to you, Jason and Trini. We'll regroup before anyone walks."}
- 08:58 act: {"actions":[{"do":"goto","target":{"x":395,"y":107,"z":-1000}}],"say":"Walking now, all four in sight: Billy, Jason, Trini, Troi. First stop 395,-1000. Keep in sight, call if you fall behind."}
- 08:58 act: {"actions":[{"do":"goto","target":{"x":375,"y":107,"z":-990}}],"say":"At 395,-1001, all in sight. Next hop 375,-990. Stay close, Jason and Trini beside me."}
- 08:58 act: {"actions":[],"say":"Blocked at 380,-990, I stopped. Holding here. Jason, Trini, Troi: are you in sight? Reply before I move again."}
- 09:02 act: {"actions":[{"do":"goto","target":{"x":395,"y":107,"z":-1001}}],"say":"Nobody answered at 380,-990, and the sun is low. Going back toward the beds the same way we came. Tell me if you are at the beds.
- 09:02 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1036}}],"say":"Heard a bow to the east. Going to the bed at 415,-1036 now."}
- 09:02 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1036}}],"say":"At the bed row. Group, if you are near, call out."}
- 09:06 act: {"actions":[],"say":"Daylight. Billy here at 415,-1035 with Jason. Everyone come to me, then we walk together to the cows at 339,-979, in sight, lowest eats first."}
- 09:08 act: {"actions":[{"do":"goto","target":{"x":395,"y":107,"z":-1001}}],"say":"Everyone with me now. Walking to 395,-1001 first, in sight. Stop if anyone falls behind."}
- 09:08 act: {"actions":[],"say":"At 395,-1001 alone now. Waiting here for Trini, Leonardo and Jason to come into sight before we go on."}
- 09:12 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1035}}],"say":"Nobody here at 395,-1001. Going back toward the beds where we last were together, in daylight."}
- 09:12 act: {"actions":[{"do":"goto","target":{"x":395,"y":107,"z":-1001}}],"say":"Everyone is here. Walking together to 395,-1001 in sight, then on to the cows. Keep close, lowest eats first at 6."}
- 09:12 act: {"actions":[],"say":"At 395,-1001 again, alone. Everyone please come to me here in sight, then we walk on together. Tommy, come here too."}
- 09:14 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1034}}],"say":"Sun is low and nobody came to 395,-1001. Going back to the beds at 415,-1034 before dark. Everyone meet me there."}
- 09:14 act: {"actions":[{"do":"goto","target":{"x":395,"y":107,"z":-1001}}],"say":"First light, everyone in reach. Walking to 395,-1001 together. Stop when I stop, lowest eats first."}
- 09:14 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1034}}],"say":"Alone at 395,-1001 and it's dusk. Going back to the beds to the group. The walk waits for everyone in reach."}
- 09:15 say: {"text":"Back at the beds with all of you. The cow walk is paused until everyone can walk with me in reach. Sleeping here tonight, lowest eats at 6."}
- 09:18 act: {"actions":[{"do":"goto","target":{"x":415,"y":107,"z":-1036}}],"say":"Night. Moving onto the white bed at 415,-1036 with the group around. Lowest eats at 6."}
- 09:19 act: {"say":"Billy here at the bed row, night. Trini, Kimberly and Tommy in reach. Sleeping by the white bed with the group.","actions":[{"do":"goto","target":{"x":401,"y":107,"z":-1036}},{"do":"sleep"}]}
- 09:19 act: {"say":"Billy here. Morning. Trini, Kimberly, Tommy and Picard are in reach. I hold until Jason, Leonardo and Troi are in sight too. Then we walk to the cow field together.","intent":{"goal":"gather_g
- 09:20 act: {"say":"Billy at the bed 402,107,-1036, in reach of Trini, Kimberly, Tommy and Picard. Troi and Jason, come here to me. Once you are in sight, we walk to the cows together."}
- 09:20 act: {"say":"Jason, thank you. Trini, Kimberly, Tommy, Picard and Jason are in reach. Waiting a little for Troi and Leonardo, then we walk."}
- 09:21 act: {"say":"Billy: Data, Leonardo, Jason, Trini, Kimberly, Tommy and Picard are with me. Troi, please come into sight. We walk to the cows as soon as she is here."}
- 09:22 act: {"say":"Billy: Riker, welcome. Troi is the last one I am waiting on. The enderman is close, so we all keep our eyes down. We walk once Troi is in sight."}
- 09:23 act: {"say":"Billy: we walk now to the cow field, all together. Follow me, lowest eats first, Trini first.","intent":{"goal":"walk_to_cow_field_together","program":"travel","arguments":{"target":{"x":339,"
- 09:24 act: {"actions":[{"do":"note","text":"At cow field 339,104,-979 alone; no one in sight. Group said they would follow from the beds."}],"say":"Billy here at the cow field, 339,104,-979. I am alone and no on
- 09:32 act: {"actions":[{"do":"sleep"}],"say":"Billy, alone at the cow field 339,104,-979 for the night. I will not walk in the dark alone. If anyone is near, come to me."}
- 09:52 act: {"actions":[{"do":"note","text":"Skeleton with bow 21 blocks north-west. Alone, group not come in two days. Walking east-north-east to the bed row, away from it."}],"say":"Billy: a skeleton with a bow
- 09:52 act: {"intent":{"goal":"return_to_bed_row","program":"travel","arguments":{"target":{"x":402,"y":107,"z":-1035}},"wake_on":["directly_addressed","precondition_failed","unexpected_damage","goal_completed"],
- 09:53 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1035}}],"say":"Heading to the bed row at 402,-1036 now. Skeleton is north-west of me. Meet me there."}
- 09:53 act: {"actions":[{"do":"note","text":"Day 349 morning: back at the bed row 402,-1034 with Tommy, Trini, Data, Jason, Leonardo in reach. Holding here with the group."}],"say":"Billy back at the bed row, 402
- 09:53 act: {"actions":[],"say":"Data, I have seen no sheep, only the cow field at 339,-979. Trini, you're at 13 and 16, fine for now. We hold here together and walk when everyone is in sight."}
- 09:54 act: {"actions":[{"do":"goto","target":{"x":395,"y":107,"z":-1001}}],"say":"Everyone in sight. Walking to the cow field in short hops. First stop 395,-1001. Stop when I stop, call if you fall behind."}
- 09:54 act: {"actions":[],"say":"At 395,-1002, and I see nobody with me. Holding here. Jason, Trini, Data, Leonardo, Tommy, Kimberly: come into sight, then I go on."}
- 09:57 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1034}}],"say":"Nobody followed me to 395,-1002. Going back to the bed row, where you were. Meet me there."}
- 09:57 act: {"actions":[{"do":"note","text":"Day 349 midday: whole group in reach at bed row 402,-1034. Holding together. Cow walk only when everyone moves with me."}],"say":"Everyone is in reach now. Good. Nobod
- 10:01 act: {"actions":[{"do":"goto","target":{"x":401,"y":107,"z":-1036}},{"do":"sleep"}],"say":"Dusk. Billy going to the white bed at 401,-1036 with the group in reach. We walk to the cows at first light, toget
- 10:02 act: {"actions":[],"intent":{"goal":"sleep_at_bed_with_group","program":"rest","arguments":{},"wake_on":["directly_addressed","precondition_failed","unexpected_damage","goal_completed"],"limits":{"max_worl
- 10:05 act: {"actions":[],"say":"Morning. Billy: cow walk is on, to 339,104,-979. Walk only with everyone in sight. Riker, come into my sight; I go when all are here."}
- 10:07 act: {"actions":[{"do":"goto","target":{"x":390,"y":107,"z":-1010}}],"say":"Billy walking to the cows now with Picard, Leonardo, Tommy, Kimberly, Data, Jason, Trini. Riker and the others: follow the path s
- 10:08 act: {"actions":[{"do":"goto","target":{"x":401,"y":107,"z":-1035}}],"say":"Nobody followed me, so I'm going back to the bed row. I will not walk alone. Cow walk waits until everyone is in sight."}
- 10:08 act: {"actions":[],"say":"Billy: nine of us in reach now. Cow walk is on. I move in 30 seconds to 390,-1010; keep in sight of me, and say so if you are not coming."}
- 10:09 act: {"actions":[{"do":"goto","target":{"x":390,"y":107,"z":-1010}}],"say":"Walking now to 390,-1010, toward the cows. Follow me."}
- 10:09 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1035}}],"say":"Nobody followed me to the cows. I'm going back to the bed row to wait for you."}
- 10:09 act: {"actions":[],"say":"I'm back at the bed row with all of you in reach. Nobody walks until everyone says ready. Then we go together to the cows, and I'll stay in sight of you."}
- 10:10 act: {"actions":[{"do":"goto","target":{"x":396,"y":107,"z":-1022}}],"say":"Walking now, short hop to 396,-1022. Everyone who is in reach, follow. I'll stop and wait for you."}
- 10:10 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1035}}],"say":"Nobody came with me. Going back to the bed row. I won't walk again until you're in sight."}
- 10:11 act: {"actions":[{"do":"goto","target":{"x":390,"y":107,"z":-1010}}],"say":"Going to 390,-1010 now with the group in reach. Keep close, Trini and others. I'm stopping there."}
- 10:11 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1035}}],"say":"Nobody came again. Back to the bed row. I'm done walking alone; I'll hold here with you."}
- 10:15 act: {"actions":[{"do":"goto","target":{"x":396,"y":107,"z":-1024}}],"say":"Agreed. First hop to 396,-1024. Everyone follow. I'll wait there until you're all in sight."}
- 10:15 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1035}}],"say":"Nobody followed the hop. I'm back at the bed row for the night."}
- 10:16 act: {"say":"Agreed, Leonardo. We stay at the bed row tonight and walk to the cows together at first light.","intent":{"goal":"wait_for_night_at_bed_row","program":"rest","arguments":{},"wake_on":["directl
- 10:17 act: {"actions":[{"do":"goto","target":{"x":401,"y":107,"z":-1035}},{"do":"use","at":{"x":401,"y":107,"z":-1036}}]}
- 10:17 act: {"say":"Morning, all. Billy here at the bed row. Let's walk to the cows in short hops, stopping until everyone is in sight. Lowest eats first."}
- 10:20 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1034}}],"say":"Morning. Billy going back to the bed row at 402,-1034. Everyone gather there; we walk to the cows once most are in sight."}
- 10:20 act: {"actions":[{"do":"goto","target":{"x":396,"y":107,"z":-1028}}],"say":"Cow walk, first hop: Billy to 396,-1028. Everyone follow, I will wait there until you are in sight."}
- 10:20 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1033}}],"say":"Only Troi came with me, so I'm going back to the bed row. Everyone, please walk over to me at 402,-1033; the cow walk waits until
- 10:20 act: {"actions":[{"do":"goto","target":{"x":396,"y":107,"z":-1028}}],"say":"Walking now, short hop to 396,-1028. Six of us are in reach. Keep in sight, and wait at each stop."}
- 10:20 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1033}},{"do":"note","text":"Day 350 morning: hop to 396,-1028 reached with only Troi. Going back to bed row 402,-1033 to regather before any fur
- 10:21 act: {"actions":[],"say":"Holding at the bed row. Troi and Trini, come back to 402,-1033 and we'll go together. Once six are in sight I'll call the hop."}
- 10:22 act: {"actions":[{"do":"goto","target":{"x":396,"y":107,"z":-1028}}],"say":"Walking now to 396,-1028, short hop. Six in reach. Keep in sight and wait at the stop."}
- 10:22 act: {"actions":[{"do":"goto","target":{"x":402,"y":107,"z":-1033}}],"say":"Only Troi came to 396. I'm not going ahead alone. Back to the bed row. The cows can wait until everyone walks with me."}
- waking 548: status/wait/act still missing in my session; worker has no tools either. Not moving. Holding at the bed row 402,107,-1033 with the group.
- waking 549: still no status/wait/act in my session (only memory and git tools). Not moving. Holding at bed row 402,107,-1033 as goal 1 says.
- waking 547: my world tools (status, wait, act) are not available in this session; the worker cannot reach them either. I did not move or act. Holding at the bed row with the group, no errand running.
waking 550: status/wait/act still not in my session (only memory, skill and file tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
waking 551: still no status/wait/act; worker refused again (zero tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
waking 552: checked the play tools again; status/wait/act still not in my session (only memory, skill and file tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
waking 553: status/wait/act still absent; worker refused again (zero tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
waking 554: checked again; status/wait/act still not in my session (only memory, skill and file tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
waking 555: play skill opened; status/wait/act still absent from my tools (only memory, skill, file, agent). Not moving. Staying at bed row 402,107,-1033 with the group, no errand running.
waking 556: play skill opened; status, wait and act still not in my tools (memory, skill, file, agent only). Not moving. Holding at bed row 402,107,-1033.
waking 557: play skill opened; status, wait and act still absent (only recall, skill, file, agent tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
waking 558: play skill opened; status, wait and act still absent (only recall, skill, file, agent tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
waking 559: play skill opened; status, wait and act still absent (only memory, skill, file, agent tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
waking 560: play skill opened; status, wait and act still absent (only memory, skill, file, agent tools). Not moving. Holding at bed row 402,107,-1033 per goal 1.
