# BARE_METAL
	└─a modular tracker framework by deformat.records

## What Is It?
	BARE_METAL is a modular tracker system written in Python, designed with both versatility and minimalism in mind. Inspired by the philosophy and workflow of classic trackers such as FastTracker and Impulse Tracker, as well as more modern approaches like Renoise, BARE_METAL also draws heavy conceptual influence from Jeskola Buzz, especially in its modularity and signal routing principles.

	The core goal of BARE_METAL is to create a tracker ecosystem that can operate seamlessly across multiple environments—including command-line interfaces (CLI), embedded hardware platforms, and standard desktop systems—without compromising on compositional depth or creative control.

	Unlike many trackers, which are built with a fixed structure of tracks and instruments, BARE_METAL introduces a fully modular approach:
		- Every track type is an independent unit, capable of serving a specific purpose: MIDI output, sampler playback, control voltage sequencing, parameter automation, or even procedural generation.
		- Tracks can be added, removed, or reconfigured at runtime, giving composers the power to tailor their working environment to the specific needs of a project or performance.
		- Track behavior and parameters are not hardcoded—instead, they are defined via reusable and extendable modules, encouraging experimentation and future expansion.

	The system is intended to support composition using both MIDI and audio-based workflows, with an emphasis on real-time control, tight timing, and deep customization. Whether you want to write lo-fi chiptune music for a Game Boy, sequence analog synths with MIDI, or build complex generative compositions, BARE_METAL aims to be a capable and adaptable solution. I just pray you use it to make breakcore and not any of the affermentioned garbage.

	Designed to run lean, BARE_METAL avoids unnecessary bloat in favor of stability, transparency, and control. It favors readable formats, accessible design, and user-defined workflows over prescriptive ones.

	Eventually, the project may include:
		A native UI for editing and playback on low-resource hardware or handheld devices
		Integration with external hardware (via MIDI, GPIO, I2C, etc.)
		A scripting API for algorithmic composition
		A file format that’s both human- and machine-readable, making project files easy to inspect, edit, and version control

	Whether you're a retro music enthusiast, a circuit bender, or an experimental composer, BARE_METAL is being built to serve as a flexible foundation for the most unconventional workflows without ever losing the raw, mechanical intimacy that made trackers special to begin with.

 ## More Coming Soon
  Currently being local dev'd, this is placeholder until first major commit.
