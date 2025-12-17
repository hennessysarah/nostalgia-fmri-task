# nostalgia-fmri-task
Stimulus script for music-evoked nostalgia task in fMRI scanner (Hennessy et al., 2025).

Step 1. Compile 18 songs, labeled N1-6, C1-6, U1-6 and place them in a single folder named with subject ID. 
Step 2. Run make_runs.m. This creates run-level folders (shuffles songs, creates order, matches by triplets)
Step 3. In scanner, run task script (nostalgia_task.m). 
Step 4. Create EV files for analysis using make_EVs.py
