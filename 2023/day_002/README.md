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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.5 | 1.00 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.27 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.27 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.3 | 1.1 | 1.04 ± 0.25 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.26 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.5 | 1.04 ± 0.26 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.5 | 1.05 ± 0.27 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.4 | 1.06 ± 0.26 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.27 |
| pting | input-kcen | 16.7 ± 0.6 | 15.7 | 19.5 | 18.64 ± 3.60 |
| pting | input-mattcl | 16.7 ± 0.6 | 15.8 | 19.7 | 18.68 ± 3.61 |
| pting | input-chancalan | 16.8 ± 0.6 | 15.8 | 19.5 | 18.70 ± 3.63 |
| pting | input-lanjian | 16.8 ± 0.5 | 16.0 | 20.5 | 18.72 ± 3.62 |
| pting | input-pting | 16.8 ± 0.7 | 15.4 | 19.8 | 18.78 ± 3.67 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.6 | 20.2 | 18.79 ± 3.67 |
| mattcl-py | input-lanjian | 16.9 ± 0.7 | 15.8 | 20.0 | 18.81 ± 3.67 |
| mattcl-py | input-kcen | 16.9 ± 0.7 | 15.6 | 20.5 | 18.88 ± 3.69 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 15.9 | 20.3 | 18.91 ± 3.68 |
| mattcl-py | input-mattcl | 17.0 ± 0.7 | 15.9 | 20.2 | 18.95 ± 3.70 |
| chancalan | input-lanjian | 17.5 ± 0.6 | 16.7 | 20.9 | 19.58 ± 3.80 |
| chancalan | input-chancalan | 17.6 ± 0.7 | 16.6 | 20.7 | 19.61 ± 3.81 |
| chancalan | input-mattcl | 17.6 ± 0.6 | 16.8 | 20.6 | 19.61 ± 3.79 |
| chancalan | input-kcen | 17.6 ± 0.7 | 16.6 | 21.3 | 19.62 ± 3.82 |
| chancalan | input-pting | 17.6 ± 0.8 | 16.6 | 21.0 | 19.68 ± 3.85 |
| kcen | input-lanjian | 18.0 ± 0.8 | 17.1 | 21.2 | 20.13 ± 3.94 |
| kcen | input-pting | 18.1 ± 0.5 | 16.9 | 21.0 | 20.19 ± 3.89 |
| kcen | input-kcen | 18.1 ± 0.7 | 16.9 | 21.2 | 20.20 ± 3.93 |
| kcen | input-mattcl | 18.1 ± 0.8 | 17.1 | 21.8 | 20.24 ± 3.95 |
| kcen | input-chancalan | 18.2 ± 0.8 | 17.3 | 21.3 | 20.26 ± 3.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|