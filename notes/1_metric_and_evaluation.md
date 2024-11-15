1. performance
	- latency
	- throughput
2. x is N times faster than y,means:
	- speedup = N
	- N = speed(x) / speed(y)
	- N = latency(y) / latency(x)
	- N = throughput(x) / throughput(y)
3. speedup
	-  > 1， improved performance：short execution time or higher throughput
	-  < 1，worse performance
	- performance ~ throughput or ~ 1/throughput
4. how to measure performance?
	- performance $\approx$  1 / execution time 
	- on what workload? its hard to use actual user workload because: many programs/cannot representative of other users/how do we get workload data
	- solution: benchmark
5. benchmark：
	- programs and input data agreed upon for performance measurements
	- benchmark suite: multiple programs, each representative of some type of apps
6. types of benchmark
	- real applications: most representative/ most difficult to set up
	- kernels(prototype):find most time-consuming part of app
	- synthetic benchmarks(design suites): behave similarly to kernels but simple to compile
	- peak performance(marketing)
7. benchmark standards: 
	- TPC
	- EEMBC:for embed device
	- SPEC: for high performance processor
		- GCC:compiler workload
		- BWAVES/LBM:fluid dynamic workload
		- perl: string processing applications
		- CACTUS ADM:physic simulation related to relativity
		- XALANCBMK: parser for XML
		- CALCULIX/DEALL: solvers of differential equations
		- BZIP: a compression application
		- GO/SJENNG: game ai application
		-  ....





























