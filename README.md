# Cilk Docker Image

## Usage

* `docker build -t cilk .`

* `docker run -v ${PWD}/test:/test -it cilk`

* Compile `clang -fcilkplus -o test test.c`

* Run `time CILK_NWORKERS=2 ./test`