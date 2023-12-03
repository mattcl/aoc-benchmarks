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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.35 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.3 | 1.08 ± 0.33 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.08 ± 0.35 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.10 ± 0.36 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.5 | 1.11 ± 0.37 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.4 | 1.4 | 1.11 ± 0.35 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.4 | 1.13 ± 0.35 |
| pting | input-mattcl | 16.3 ± 0.5 | 15.8 | 18.8 | 19.95 ± 5.32 |
| pting | input-pting | 16.4 ± 0.5 | 15.3 | 19.5 | 20.03 ± 5.35 |
| pting | input-lanjian | 16.5 ± 0.7 | 15.6 | 19.2 | 20.13 ± 5.40 |
| pting | input-chancalan | 16.5 ± 0.7 | 15.2 | 19.4 | 20.14 ± 5.40 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.6 | 19.3 | 20.14 ± 5.39 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.5 | 19.3 | 20.16 ± 5.40 |
| mattcl-py | input-kcen | 16.5 ± 0.7 | 15.5 | 19.5 | 20.18 ± 5.41 |
| pting | input-kcen | 16.6 ± 0.8 | 15.4 | 19.7 | 20.23 ± 5.45 |
| mattcl-py | input-lanjian | 16.6 ± 0.8 | 15.4 | 19.7 | 20.30 ± 5.46 |
| mattcl-py | input-pting | 16.7 ± 0.8 | 15.6 | 19.7 | 20.39 ± 5.50 |
| chancalan | input-chancalan | 17.3 ± 0.6 | 16.3 | 20.2 | 21.17 ± 5.66 |
| chancalan | input-lanjian | 17.4 ± 0.5 | 16.2 | 20.2 | 21.20 ± 5.66 |
| chancalan | input-kcen | 17.4 ± 0.7 | 16.5 | 20.4 | 21.27 ± 5.70 |
| chancalan | input-mattcl | 17.4 ± 0.7 | 16.2 | 20.6 | 21.27 ± 5.71 |
| chancalan | input-pting | 17.6 ± 2.4 | 16.2 | 47.6 | 21.44 ± 6.40 |
| kcen | input-chancalan | 17.7 ± 0.7 | 16.8 | 20.9 | 21.65 ± 5.81 |
| kcen | input-pting | 17.8 ± 0.7 | 16.7 | 20.7 | 21.75 ± 5.83 |
| kcen | input-mattcl | 17.8 ± 0.7 | 17.1 | 20.8 | 21.76 ± 5.84 |
| kcen | input-lanjian | 17.8 ± 0.8 | 17.0 | 20.9 | 21.78 ± 5.86 |
| kcen | input-kcen | 18.0 ± 3.5 | 16.8 | 60.9 | 22.00 ± 7.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|