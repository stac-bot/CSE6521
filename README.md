# CSE6521
Problem 1: A* Graph Search (15+2 points)

1) Implement A* graph search with the default heuristic (15 points)

Extension (2 extra points): Implement a better ("tighter") heuristic and submit a report that compares the two heuristics and the resulted difference in efficiency, number of paths explored / added to the frontier etc. 

Deliverable for Problem 1:  A complete `search.py` file with the default heuristic function and the A* search implementation. For extension, submit a separate file (e.g., `search_extension.py`) with the alternative heuristic and the report (in a PDF/Word file). Compress everything in a .zip file and submit.

Evaluation: We will use `pytest` for automated evaluation. The accompanying `test_search.py` file contains two exemplar public test cases for the A* search function. Make sure your program can pass both. After submission, it will be evaluated against 5 hidden tests, which determines the final score.

To run `pytest` on the public test cases, first install `pytest` by `pip install -r requirements.txt`, then run `py.test` in a terminal under the same folder as the code files.

Note: Please use Python 3.7+. please implement A* graph search, not tree search. Tree search may lead to less optimal solutions that will fail the hidden tests.
