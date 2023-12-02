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

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.0 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.4 | 1.00 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.0 | 1.6 | 1.01 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.0 | 1.5 | 1.03 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.4 | 1.04 ± 0.36 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.0 | 1.2 | 1.07 ± 0.31 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.0 | 1.4 | 1.08 ± 0.33 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.0 | 1.3 | 1.10 ± 0.33 |
| pting | input-mattcl | 16.5 ± 0.7 | 15.3 | 19.7 | 20.54 ± 4.87 |
| pting | input-lanjian | 16.6 ± 0.7 | 15.3 | 19.6 | 20.60 ± 4.88 |
| pting | input-kcen | 16.6 ± 0.7 | 15.4 | 19.9 | 20.64 ± 4.90 |
| pting | input-pting | 16.6 ± 0.6 | 15.8 | 19.7 | 20.66 ± 4.88 |
| mattcl-py | input-kcen | 16.8 ± 0.6 | 15.7 | 19.8 | 20.87 ± 4.94 |
| mattcl-py | input-lanjian | 16.8 ± 0.7 | 15.5 | 20.4 | 20.92 ± 4.96 |
| mattcl-py | input-pting | 16.8 ± 0.7 | 15.9 | 20.1 | 20.95 ± 4.97 |
| mattcl-py | input-mattcl | 16.9 ± 0.7 | 16.0 | 20.3 | 21.02 ± 5.00 |
| kcen | input-mattcl | 17.9 ± 0.7 | 16.6 | 21.1 | 22.30 ± 5.28 |
| kcen | input-lanjian | 18.0 ± 0.8 | 17.0 | 21.6 | 22.34 ± 5.32 |
| kcen | input-kcen | 18.0 ± 0.8 | 17.0 | 21.0 | 22.39 ± 5.33 |
| kcen | input-pting | 18.1 ± 0.7 | 17.1 | 21.1 | 22.53 ± 5.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|