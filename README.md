# a matter of time
A Matter of Time is a stereo recorder with granular synthesis playback based on Raspberry Pi, Pure Data and a MIDIMIX controller. 
It has a 3-in by 2-out matrix mixer with 2 external inputs and 2 outputs with feedback. The recorder can make 10 min long recordings at 44.1Khz sampling frequency, and the buffer can be accessed for playback simultaneously with the recording process. 
Each output channel has 10 parameters for playback manipulation and one for panning control, with 8 buttons for specific functions as recording, playback, plus some extra control over the playback parameters.

# amot is the main patch. 
All other files (.pd, .gif, and libs) are necessary for its use.
Include an "empty.wav" (use that name) file of the lenght you desire in the folder (I use a 10 min empty.waw)
