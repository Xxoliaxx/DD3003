## Report for lab on OpenMP

1. I simply modified the two existing print statements in the
source file so that they read `printf("Starting on %i threads\n", omp_get_max_threads());`
and `printf("Hello World from thread %i!\n", omp_get_thread_num());`, respectively.

2. 