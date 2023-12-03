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
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.0 | 1.2 | 1.02 ± 0.34 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.0 | 1.04 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.2 | 0.9 | 1.05 ± 0.31 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.0 | 1.2 | 1.06 ± 0.35 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.35 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.3 | 1.2 | 1.09 ± 0.33 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.0 | 1.0 | 1.09 ± 0.35 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.09 ± 0.36 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.0 | 1.6 | 1.10 ± 0.39 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.5 | 19.7 | 22.08 ± 5.52 |
| mattcl-py | input-pting | 16.4 ± 0.6 | 15.4 | 19.3 | 22.11 ± 5.52 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.3 | 19.6 | 22.12 ± 5.55 |
| mattcl-py | input-mattcl | 16.4 ± 0.7 | 15.4 | 19.6 | 22.13 ± 5.55 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.3 | 19.7 | 22.21 ± 5.56 |
| chancalan | input-chancalan | 17.2 ± 0.6 | 16.3 | 20.6 | 23.20 ± 5.79 |
| chancalan | input-lanjian | 17.2 ± 0.6 | 16.2 | 20.6 | 23.22 ± 5.80 |
| chancalan | input-kcen | 17.3 ± 0.7 | 16.2 | 20.7 | 23.30 ± 5.85 |
| chancalan | input-mattcl | 17.3 ± 0.7 | 16.1 | 20.3 | 23.30 ± 5.83 |
| chancalan | input-pting | 17.4 ± 0.7 | 16.4 | 20.5 | 23.40 ± 5.86 |
| pting | input-chancalan | 17.4 ± 0.7 | 16.3 | 20.7 | 23.40 ± 5.87 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.6 | 20.7 | 23.45 ± 5.87 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.2 | 20.2 | 23.50 ± 5.88 |
| pting | input-kcen | 17.4 ± 0.7 | 16.2 | 20.8 | 23.50 ± 5.89 |
| pting | input-pting | 17.6 ± 2.7 | 16.7 | 51.7 | 23.67 ± 6.89 |
| kcen | input-kcen | 17.6 ± 0.6 | 16.6 | 20.7 | 23.72 ± 5.92 |
| kcen | input-chancalan | 17.6 ± 0.6 | 16.7 | 20.7 | 23.75 ± 5.93 |
| kcen | input-pting | 17.7 ± 0.7 | 16.6 | 20.5 | 23.82 ± 5.96 |
| kcen | input-mattcl | 17.7 ± 0.7 | 16.7 | 20.5 | 23.86 ± 5.97 |
| kcen | input-lanjian | 17.8 ± 2.4 | 16.7 | 46.8 | 24.03 ± 6.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|