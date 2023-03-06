* [[01 Why this book?]]
* [[02 Who this book is for]]
* [[03 How this book is organized]]
* Part 1. Introduction to Nix
	* [[Chapter 1. What Nix is all about]]
	* [[Chapter 2. Taste of Nix]]
	* [[Chapter 3. Why Nix was created]]
		* 3.1. What software deployment is
		* 3.1. Traditional approaches to deployment
		* 3.2. Limitations and problems
			* 3.2.1. Dependency hell
			* 3.2.2. Retaining dependencies
			* 3.2.3. Other shortcomings
			* 3.2.2. Can I survive without Nix?
* Part 2. Nix fundamentals
	* Chapter 4. Keys to grasping the core idea of Nix
		* 4.1 Memory Model in Programming Languages
			* 4.1.1. Pointers
			* 4.1.2. Immutability
			* 4.1.3. Garbage Collection
		* 4.2 Grounds of Functional Languages
			* 4.2.2. Purity and Referential Transparency
			* 4.2.3. Memoisation
			* 4.2.4. Lazy Evaluation
			* 4.2.5. Sharing
			* 4.2.5. Side Effects
	* Chapter 5. Nix: Pursuing Reproducibility
		* 5.1. Imposing Addressing using Cryptographic Hashes
			* 5.1.1. Immutability for Free
			* 5.1.2. Automatic Dependency Discovery
			* 5.1.3. Closures
		* 5.1. Taming Side Effects
		* 5.2. Isolation and Hermeticity
		* 5.3. Laziness and Sharing with Store Derivations
			* 5.3.1. Deferring Evaluations
			* 5.3.2. Memoisation and Substitution
		* 5.4. Additional Goals
			* 5.4.1. Traceability
	* Chapter 6. Nix Components
		* 6.1. Nix Store
		* 6.2. Nix Daemon
		* 6.3. Nix Language
		* 6.4. Nix CLI
	* Chapter 7. Learning Nix Language
	* Chapter 8. Nix language shortcomings and extensions
		* 8.1. Bringing Types and Composability with NixOS Modules
			* 8.1.1. Laziness and Mutual Recursion
* Part 3. Nix as Package Manager
	* Chapter 9. Nixpkgs Collection
	* Chapter 10. Using Flakes
	* Chapter 11. User Profile Management
	* Chapter 12. Working with Nix Store
		* 6.2. Storing File Objects
		* 6.3. Working With Derivations
		* 5.4. Optimizing and Cleaning
* Part 4. Nix for Developers
	* Nixpkgs Tools
		* Autoconf Packages
		* Language-specific Packages
	* Development Environments
	* Speed Up with Binary Caches
	* Nix and Haskell
	* Testing with Nix
* Part 5. Nix in DevOps
	* Packaging Software
		* Creating Bundles
		* Building OCI Containers
		* NixOS Modules
	* Building Software
		* Remote Builds
		* Building Farms
		* Using Hydra
		* Setting Up Binary Caches
	* Deploying
		* Deployment Strategies
	* Configuration Management
	* Rolling Out Cloud Infrastructure
* Part 6. Advanced Nix
	* Modular Flakes
* Part 7. Nix Toolkit for Haskell
	* haskell.nix
* Part 8. NixOS