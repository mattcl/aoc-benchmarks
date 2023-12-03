# Day 2 benchmarks

[link to problem](https://adventofcode.com/2023/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 0.5 ± 0.3 | 0.0 | 0.9 | 1.00 |
| mattcl | input-chancalan | 0.6 ± 0.2 | 0.0 | 0.9 | 1.11 ± 0.72 |
| mattcl | input-pting | 0.6 ± 0.2 | 0.0 | 1.1 | 1.21 ± 0.69 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.2 | 1.26 ± 0.70 |
| mattcl | input-kcen | 0.7 ± 0.1 | 0.2 | 0.8 | 1.30 ± 0.70 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.3 | 1.32 ± 0.76 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.1 | 1.35 ± 0.77 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.2 | 1.36 ± 0.75 |
| lanjian | input-kcen | 0.7 ± 0.1 | 0.2 | 1.2 | 1.39 ± 0.74 |
| lanjian | input-mattcl | 0.8 ± 3.5 | 0.0 | 50.2 | 1.53 ± 6.82 |
| pting | input-mattcl | 16.5 ± 0.6 | 15.3 | 19.5 | 31.69 ± 16.19 |
| pting | input-lanjian | 16.5 ± 0.6 | 15.2 | 19.0 | 31.79 ± 16.25 |
| pting | input-pting | 16.6 ± 0.7 | 15.3 | 19.6 | 31.95 ± 16.35 |
| mattcl-py | input-pting | 16.6 ± 0.5 | 15.5 | 19.4 | 31.99 ± 16.34 |
| pting | input-chancalan | 16.7 ± 0.8 | 15.2 | 19.4 | 32.07 ± 16.41 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.8 | 20.1 | 32.10 ± 16.41 |
| mattcl-py | input-mattcl | 16.7 ± 0.6 | 15.8 | 19.9 | 32.13 ± 16.42 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.5 | 19.8 | 32.17 ± 16.43 |
| pting | input-kcen | 16.9 ± 2.9 | 15.6 | 53.0 | 32.46 ± 17.45 |
| chancalan | input-lanjian | 17.3 ± 0.6 | 16.5 | 20.2 | 33.31 ± 17.02 |
| chancalan | input-mattcl | 17.3 ± 0.6 | 16.3 | 20.1 | 33.32 ± 17.02 |
| chancalan | input-kcen | 17.3 ± 0.6 | 16.1 | 20.4 | 33.41 ± 17.07 |
| chancalan | input-pting | 17.4 ± 0.7 | 16.3 | 20.5 | 33.53 ± 17.15 |
| mattcl-py | input-chancalan | 17.4 ± 0.5 | 16.2 | 19.7 | 33.55 ± 17.13 |
| kcen | input-lanjian | 17.8 ± 0.7 | 16.8 | 20.6 | 34.36 ± 17.56 |
| kcen | input-pting | 17.9 ± 0.6 | 17.0 | 20.9 | 34.41 ± 17.58 |
| kcen | input-mattcl | 17.9 ± 0.7 | 16.8 | 21.0 | 34.43 ± 17.60 |
| kcen | input-kcen | 18.0 ± 0.7 | 16.8 | 20.8 | 34.60 ± 17.69 |
| kcen | input-chancalan | 18.7 ± 0.4 | 17.9 | 20.7 | 36.03 ± 18.38 |
| chancalan | input-chancalan | 18.9 ± 1.9 | 17.5 | 30.8 | 36.36 ± 18.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|