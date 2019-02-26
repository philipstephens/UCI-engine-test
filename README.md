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

Update to UCI-engine-test

1. Added misses.txt to help create puzzles that given engines were unable to solve.
2. Added ability to test alternative puzzle solutions by appending letters to the
   end of the "Round" headings of pgn files.  
   
   [Round "12a"]
   [Round "12b"]
   
   or [Round "12aa"]
      [Round "12ab"]

