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
| mattcl | input-pting | 0.7 ± 0.3 | 0.1 | 1.1 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.13 ± 0.47 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.3 | 1.0 | 1.15 ± 0.45 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.15 ± 0.49 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.16 ± 0.49 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.17 ± 0.46 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.4 | 1.20 ± 0.46 |
| lanjian | input-pting | 0.9 ± 2.7 | 0.1 | 38.5 | 1.22 ± 3.75 |
| pting | input-lanjian | 16.3 ± 0.6 | 15.7 | 19.5 | 22.67 ± 8.03 |
| pting | input-kcen | 16.4 ± 0.7 | 15.3 | 19.6 | 22.76 ± 8.08 |
| pting | input-mattcl | 16.4 ± 0.6 | 15.4 | 19.4 | 22.79 ± 8.08 |
| mattcl-py | input-kcen | 16.5 ± 0.7 | 15.5 | 20.2 | 22.84 ± 8.10 |
| pting | input-pting | 16.5 ± 0.7 | 15.4 | 19.1 | 22.85 ± 8.10 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.4 | 19.3 | 22.90 ± 8.12 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.5 | 19.7 | 22.91 ± 8.12 |
| mattcl-py | input-pting | 16.6 ± 0.7 | 15.4 | 20.1 | 23.00 ± 8.16 |
| kcen | input-mattcl | 17.7 ± 0.6 | 16.9 | 20.6 | 24.49 ± 8.67 |
| kcen | input-lanjian | 17.7 ± 0.7 | 17.0 | 20.7 | 24.52 ± 8.70 |
| kcen | input-pting | 17.8 ± 0.8 | 16.6 | 21.1 | 24.72 ± 8.79 |
| kcen | input-kcen | 17.8 ± 0.9 | 17.0 | 20.8 | 24.75 ± 8.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|