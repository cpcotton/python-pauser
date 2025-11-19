## Problem during python debug - error message does not show
### Import and Add a pauser 
pz = Pauser()
#### in your code to pause console put
pz.z30 now pauses for 3 seconds and reports the code line
#### you get a console message ie: Pausing for 3 seconds at s_4_page_make_cards.py, line 518

#### at the end of your code put
pz.info 
#### displays the pause list - great for finding those debug statments you now want to remove if you oput a pz.z1 next to debugs
At the end ot your code report
Paused for 20 seconds at s_4_page_make_cards.py, line 1063
Paused for 0.1 seconds at s_4_page_make_cards.py, line 518

