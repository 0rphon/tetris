# tetris
tetris clone with custom AI.\
built in rust using my game engine Untitled_Engine and my error handling crate Dynerr.\
\
i havent updated the UI yet, but hit P to activate the AI. its still in training but should do pretty well. --auto-loop to let the ai restart games on its own.\
if youre interested in training your own AI, pass the arg --train.\
i have plans to set up config files for the AI so it can be trained and changed without recompiling, but for now look at the constants in train.rs to change how the evolutionary alg works.\
