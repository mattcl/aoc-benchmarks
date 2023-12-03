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
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.2 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.0 | 1.3 | 1.09 ± 0.43 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.10 ± 0.40 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.3 | 1.11 ± 0.43 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.6 | 1.11 ± 0.45 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.2 | 1.5 | 1.12 ± 0.40 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.2 | 1.12 ± 0.40 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.1 | 1.3 | 1.14 ± 0.40 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.6 | 1.17 ± 0.42 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.1 | 1.1 | 1.22 ± 0.42 |
| pting | input-mattcl | 16.5 ± 0.6 | 15.3 | 19.4 | 23.44 ± 7.12 |
| pting | input-pting | 16.7 ± 0.6 | 15.6 | 19.4 | 23.60 ± 7.18 |
| pting | input-kcen | 16.7 ± 0.7 | 15.5 | 19.6 | 23.61 ± 7.19 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.8 | 19.0 | 23.62 ± 7.18 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.7 | 19.6 | 23.70 ± 7.20 |
| mattcl-py | input-pting | 16.7 ± 0.5 | 15.9 | 19.7 | 23.73 ± 7.20 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.9 | 20.3 | 23.78 ± 7.25 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.7 | 20.4 | 23.79 ± 7.25 |
| pting | input-chancalan | 17.3 ± 0.6 | 16.0 | 18.9 | 24.57 ± 7.46 |
| chancalan | input-mattcl | 17.4 ± 0.7 | 16.4 | 20.5 | 24.72 ± 7.52 |
| chancalan | input-pting | 17.5 ± 0.6 | 16.6 | 20.4 | 24.74 ± 7.52 |
| mattcl-py | input-chancalan | 17.5 ± 0.4 | 16.6 | 19.2 | 24.74 ± 7.49 |
| chancalan | input-kcen | 17.5 ± 0.7 | 16.5 | 20.5 | 24.75 ± 7.53 |
| chancalan | input-lanjian | 17.5 ± 0.8 | 16.2 | 20.7 | 24.78 ± 7.56 |
| kcen | input-lanjian | 17.8 ± 0.7 | 17.0 | 21.4 | 25.27 ± 7.69 |
| kcen | input-mattcl | 18.0 ± 0.7 | 16.7 | 21.1 | 25.45 ± 7.75 |
| kcen | input-pting | 18.0 ± 0.7 | 16.6 | 21.0 | 25.49 ± 7.75 |
| kcen | input-kcen | 18.3 ± 4.2 | 16.9 | 70.6 | 25.94 ± 9.79 |
| chancalan | input-chancalan | 18.7 ± 2.3 | 16.8 | 25.1 | 26.51 ± 8.64 |
| kcen | input-chancalan | 19.0 ± 0.6 | 18.3 | 22.1 | 26.94 ± 8.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|