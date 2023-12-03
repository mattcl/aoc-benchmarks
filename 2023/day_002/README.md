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
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.3 | 1.0 | 1.03 ± 0.34 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.35 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 0.9 | 1.05 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.06 ± 0.34 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.0 | 1.2 | 1.08 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.10 ± 0.35 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.5 | 1.11 ± 0.35 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.0 | 1.4 | 1.12 ± 0.39 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.3 | 1.2 | 1.12 ± 0.34 |
| pting | input-chancalan | 16.3 ± 0.6 | 15.5 | 19.6 | 22.56 ± 5.50 |
| pting | input-kcen | 16.3 ± 0.7 | 15.3 | 19.6 | 22.62 ± 5.52 |
| pting | input-lanjian | 16.4 ± 0.7 | 15.5 | 19.6 | 22.65 ± 5.54 |
| pting | input-mattcl | 16.4 ± 0.6 | 15.4 | 19.5 | 22.65 ± 5.53 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.3 | 19.4 | 22.67 ± 5.52 |
| mattcl-py | input-lanjian | 16.4 ± 0.6 | 15.8 | 19.5 | 22.67 ± 5.52 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.3 | 19.4 | 22.73 ± 5.53 |
| pting | input-pting | 16.4 ± 0.7 | 15.4 | 19.6 | 22.75 ± 5.56 |
| mattcl-py | input-pting | 16.4 ± 0.6 | 15.8 | 19.4 | 22.75 ± 5.54 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.3 | 19.4 | 22.79 ± 5.56 |
| chancalan | input-chancalan | 17.2 ± 0.6 | 16.2 | 20.3 | 23.85 ± 5.81 |
| chancalan | input-kcen | 17.3 ± 0.6 | 16.3 | 20.2 | 23.89 ± 5.81 |
| chancalan | input-lanjian | 17.3 ± 0.6 | 16.1 | 19.5 | 23.92 ± 5.82 |
| chancalan | input-pting | 17.3 ± 0.6 | 16.3 | 20.7 | 23.95 ± 5.83 |
| chancalan | input-mattcl | 17.5 ± 2.6 | 16.1 | 48.9 | 24.26 ± 6.83 |
| kcen | input-mattcl | 17.6 ± 0.6 | 16.9 | 21.2 | 24.39 ± 5.93 |
| kcen | input-pting | 17.7 ± 0.7 | 17.0 | 20.8 | 24.46 ± 5.97 |
| kcen | input-chancalan | 17.7 ± 0.7 | 16.6 | 20.3 | 24.47 ± 5.96 |
| kcen | input-kcen | 17.7 ± 0.7 | 16.9 | 21.0 | 24.47 ± 5.97 |
| kcen | input-lanjian | 17.7 ± 0.9 | 16.5 | 20.9 | 24.54 ± 6.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|