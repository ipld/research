The most important problems/technologies relevant to PL that will/should exist 5-10 years from now

- How to do better secure computation in distributed systems
	- moving & proving computation
	- languages and typesystems that allow you to reason about those computations
	- a distributed typesystem on WASM
		- standard for sending type definitions and functions/methods/programs
		- a compact structured data object that can be shared between multiple computers
		- (sounds like IPLD)
	- indistinguishability Obfuscation
- Witness encryption
	- have a problem, encrypt with the problem where the decryption key is the solution to the problem
	- Nicola has a list of things you could do with it
		- no need for trusted hardware
- Selectors, accumulators, transformations, queries
- Writing an actual database
	- distributed, authenticated, private search
- Deniability/undeniability
	- be able to have plausible deniability on commitments
- Authenticated data structures
- "the last file extension"
	- objects have data and code on how to interpret them or what to do with them
- Programming language for distributed systems
	- objects have data and code and they are dispersed and executed across multiple computers collaboratively
	- sometimes called "transparent networking"
	- move compute to the data
	- move networking (error handling, routing, etc) out of the programming language
	- semitrusted environment (different trust levels and different reliabilities)


--- 
This began as notes from a conversation on 2017-12-15 with @jbenet, @stebalien, @nicola, and @miyazono, but this list should grow and evolve. Please directly edit this to add additional items, submit issues to propose clarifications or removal of items, and convert these to more complete and formalized open problem statements.
