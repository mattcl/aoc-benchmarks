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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.5 | 1.03 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.05 ± 0.36 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.36 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.4 | 1.2 | 1.06 ± 0.35 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.4 | 1.09 ± 0.37 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.11 ± 0.37 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.1 | 1.5 | 1.11 ± 0.38 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.4 | 1.11 ± 0.37 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.4 | 1.11 ± 0.39 |
| pting | input-lanjian | 16.5 ± 0.5 | 15.4 | 18.2 | 20.76 ± 5.80 |
| pting | input-chancalan | 16.7 ± 0.7 | 15.3 | 19.7 | 21.01 ± 5.89 |
| pting | input-kcen | 16.7 ± 0.8 | 15.5 | 20.4 | 21.06 ± 5.93 |
| pting | input-mattcl | 16.8 ± 0.8 | 15.4 | 19.9 | 21.11 ± 5.94 |
| pting | input-pting | 16.8 ± 0.7 | 15.8 | 19.7 | 21.20 ± 5.95 |
| mattcl-py | input-lanjian | 16.8 ± 0.6 | 15.7 | 20.4 | 21.20 ± 5.94 |
| mattcl-py | input-chancalan | 16.9 ± 0.8 | 15.5 | 19.8 | 21.31 ± 6.00 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 15.7 | 19.7 | 21.32 ± 5.98 |
| mattcl-py | input-mattcl | 17.0 ± 0.7 | 16.0 | 20.1 | 21.38 ± 6.00 |
| mattcl-py | input-kcen | 17.0 ± 2.2 | 16.0 | 43.8 | 21.43 ± 6.54 |
| chancalan | input-chancalan | 17.5 ± 0.6 | 16.3 | 20.4 | 22.00 ± 6.16 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.5 | 20.8 | 22.01 ± 6.18 |
| chancalan | input-kcen | 17.5 ± 0.6 | 16.2 | 20.7 | 22.01 ± 6.17 |
| chancalan | input-mattcl | 17.5 ± 0.7 | 16.5 | 21.1 | 22.04 ± 6.19 |
| chancalan | input-pting | 17.6 ± 0.8 | 16.4 | 20.7 | 22.16 ± 6.24 |
| kcen | input-lanjian | 18.0 ± 0.7 | 16.7 | 21.0 | 22.70 ± 6.38 |
| kcen | input-chancalan | 18.0 ± 0.7 | 17.1 | 21.3 | 22.71 ± 6.37 |
| kcen | input-kcen | 18.1 ± 0.8 | 17.0 | 21.4 | 22.76 ± 6.40 |
| kcen | input-mattcl | 18.1 ± 0.7 | 16.8 | 20.8 | 22.77 ± 6.38 |
| kcen | input-pting | 18.2 ± 0.8 | 17.1 | 21.3 | 22.97 ± 6.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|