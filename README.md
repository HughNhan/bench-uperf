# bench-uperf
Helper scripts to aid the execution and post-processing of uperf network performance tool.

## Scripts

Name | Description
-----|------------
uperf-base | Checks if the bench-base library can be sourced from the ${TOOLBOX_HOME}/bash/library/ directory. If the library cannot be sourced, the script prints an error message and exits with an exit status of 1.
uperf-client | Runs a network benchmark using uperf, a network performance tool. The script has several command-line options that can be used to customize the benchmark run, including the number of threads, protocol, packet sizes, and duration.
uperf-get-runtime | Outputs the duration of a benchmark run.
uperf-post-process | Perl script that processes results from the uPerf benchmark tool and outputs a JSON file containing performance metrics.
uperf-server-start | Bash script that runs the uperf network performance benchmarking tool as a server. The script sets up the environment for running the tool and starts the server process with the specified parameters.
uperf-server-stop | Stop a uperf server process. The script redirects standard output and standard error to a file named "uperf-server-stop-stderrout.txt".
