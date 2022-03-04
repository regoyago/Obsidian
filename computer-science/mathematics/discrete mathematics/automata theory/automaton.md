an automaton is a relatively self-operating machine or control mechanism designed to automatically follow a sequence of operations or respond to predetermined instructions

the word automaton is the latinization of the ancient greek  "αὐτόματον" "acting of one's own will"

an automaton can be formally defined as a $5-$[[tuple]] $M=(\Sigma ,\Gamma ,Q ,\delta ,\lambda)$ where:
- $\Sigma$ is a finite [[set]] of symbols, called the input of the automaton
- $\Gamma$ is another finite set of symbols, called the output alphabet of the automaton
- $Q$ is the set of states
- $\delta$ is the next-state function or transition function $\delta : Q \times \Sigma \rightarrow Q$ mapping state-input pairs to successor states
- $\lambda$ is the next-output function $\lambda : Q\times \sigma \rightarrow \Gamma$ mapping state-input pairs to outputs
if $Q$ is finite, then $M$ is a [[finite automaton]]

#automata_theory