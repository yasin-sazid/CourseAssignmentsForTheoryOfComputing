# Theory of Computing: Automata and Strings

C and C++ coursework translating formal-language ideas into executable programs. The repository brings together deterministic finite automata, nondeterministic-to-deterministic conversion, and foundational string operations.

## Programs

| Source | Focus |
| --- | --- |
| [DFA.cpp](DFA.cpp) | Deterministic finite automaton simulation |
| [nfadfa.cpp](nfadfa.cpp) | Construction of deterministic state representations from nondeterministic transitions |
| [string.c](string.c) | Interactive comparison, length, reversal, concatenation, and palindrome checking |

The automata programs expose the state and transition processing behind language recognition. The string exercise implements operations explicitly, making character-level algorithms visible rather than hiding them behind library calls.

## Compile and explore

Use GCC and G++ on a system providing the GNU C++ headers used by the DFA implementation:

```bash
g++ DFA.cpp -o /tmp/dfa
/tmp/dfa

g++ nfadfa.cpp -o /tmp/nfadfa
/tmp/nfadfa

gcc string.c -o /tmp/string-exercises
/tmp/string-exercises
```

Follow the console prompts in the selected program. For the string application, enter two strings and choose an operation from its menu; the menu supports repeated operations until exit.

## Technical contributions

The project connects mathematical models to procedural representations: states and transitions become indexed data, automaton processing becomes a sequence of transitions, and string properties become direct character comparisons. Separate programs make each topic straightforward to inspect and experiment with independently.
