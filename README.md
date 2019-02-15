# UCI-engine-test
Tool for testing chess engines written in Python using PGN files

Before you can use the engine_test.py file some configuration is needed.

1.  Back-up the engines.json file to engines_bak.json .
2.  Change or add the appropriate chess engines including the path of the engines in the engines.json file.
3.  Change or add the puzzle pgn files in the engines.json file.
4.  After everything has been setup type:
    python engine_test.py
    for the default test.
5.  engine_test takes 1 parameter which is the time in seconds an engine is given to think.
    python engine_test.py 2
    gives each engine 2 seconds to think before submitting a move.
