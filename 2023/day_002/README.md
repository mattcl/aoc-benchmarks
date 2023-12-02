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
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.4 | 1.06 ± 0.34 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.09 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.09 ± 0.33 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.7 | 1.10 ± 0.34 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.6 | 1.10 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.5 | 1.11 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.7 | 1.14 ± 0.33 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.4 | 1.15 ± 0.32 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.4 | 1.3 | 1.17 ± 0.32 |
| pting | input-lanjian | 16.6 ± 0.7 | 15.6 | 19.7 | 19.76 ± 4.79 |
| pting | input-chancalan | 16.6 ± 0.6 | 15.8 | 19.0 | 19.78 ± 4.78 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.6 | 19.3 | 19.81 ± 4.78 |
| pting | input-mattcl | 16.7 ± 0.7 | 15.6 | 19.7 | 19.85 ± 4.81 |
| pting | input-pting | 16.7 ± 0.7 | 15.9 | 19.6 | 19.92 ± 4.83 |
| mattcl-py | input-lanjian | 16.8 ± 0.7 | 15.4 | 20.1 | 19.93 ± 4.84 |
| pting | input-kcen | 16.8 ± 0.8 | 15.6 | 20.1 | 19.95 ± 4.86 |
| mattcl-py | input-kcen | 16.8 ± 0.8 | 15.6 | 19.8 | 19.96 ± 4.86 |
| mattcl-py | input-pting | 16.8 ± 0.7 | 16.0 | 19.8 | 20.04 ± 4.87 |
| mattcl-py | input-mattcl | 16.9 ± 2.5 | 15.5 | 48.7 | 20.12 ± 5.64 |
| chancalan | input-lanjian | 17.4 ± 0.5 | 16.7 | 20.4 | 20.74 ± 4.99 |
| chancalan | input-kcen | 17.5 ± 0.6 | 16.5 | 20.5 | 20.78 ± 5.02 |
| chancalan | input-mattcl | 17.5 ± 0.7 | 16.7 | 20.8 | 20.79 ± 5.03 |
| chancalan | input-chancalan | 17.5 ± 0.7 | 16.7 | 20.6 | 20.82 ± 5.05 |
| chancalan | input-pting | 17.6 ± 0.6 | 16.9 | 20.6 | 20.93 ± 5.05 |
| kcen | input-lanjian | 17.9 ± 0.6 | 17.0 | 21.0 | 21.23 ± 5.12 |
| kcen | input-kcen | 18.1 ± 0.9 | 17.0 | 21.6 | 21.49 ± 5.25 |
| kcen | input-chancalan | 18.1 ± 0.8 | 16.8 | 21.5 | 21.50 ± 5.23 |
| kcen | input-mattcl | 18.1 ± 0.8 | 17.0 | 21.3 | 21.52 ± 5.23 |
| kcen | input-pting | 18.2 ± 0.8 | 17.2 | 21.3 | 21.62 ± 5.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|