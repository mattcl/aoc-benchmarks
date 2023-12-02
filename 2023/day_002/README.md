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
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.5 | 1.04 ± 0.42 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.39 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.42 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.0 | 1.2 | 1.08 ± 0.42 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.6 | 1.16 ± 0.43 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.0 | 1.5 | 1.16 ± 0.45 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.3 | 1.19 ± 0.39 |
| pting | input-kcen | 16.5 ± 0.7 | 15.6 | 19.6 | 22.96 ± 6.78 |
| pting | input-lanjian | 16.5 ± 0.6 | 15.8 | 19.5 | 23.00 ± 6.77 |
| pting | input-mattcl | 16.6 ± 0.6 | 15.3 | 19.2 | 23.06 ± 6.79 |
| pting | input-pting | 16.7 ± 0.8 | 15.5 | 20.2 | 23.26 ± 6.89 |
| mattcl-py | input-lanjian | 16.7 ± 0.7 | 15.5 | 19.6 | 23.28 ± 6.87 |
| mattcl-py | input-mattcl | 16.8 ± 0.5 | 15.5 | 19.4 | 23.36 ± 6.87 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.9 | 20.4 | 23.41 ± 6.91 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 16.1 | 19.9 | 23.59 ± 6.96 |
| kcen | input-kcen | 17.9 ± 0.7 | 16.7 | 21.4 | 24.89 ± 7.33 |
| kcen | input-mattcl | 18.0 ± 0.8 | 17.1 | 21.4 | 25.00 ± 7.38 |
| kcen | input-pting | 18.0 ± 0.7 | 17.0 | 21.4 | 25.05 ± 7.39 |
| kcen | input-lanjian | 18.2 ± 4.9 | 16.6 | 80.0 | 25.34 ± 10.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|