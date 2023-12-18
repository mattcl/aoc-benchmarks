# Day 15 benchmarks

[link to problem](https://adventofcode.com/2023/day/15)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 15)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.1 ± 1.8 | 0.3 | 25.9 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.4 | 1.01 ± 1.60 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.6 | 1.03 ± 1.64 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.3 | 1.4 | 1.05 ± 1.67 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.5 | 1.06 ± 1.68 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.08 ± 1.71 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.8 | 1.4 | 1.10 ± 1.73 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.4 | 1.11 ± 1.76 |
| pting | input-kcen | 18.0 ± 0.6 | 17.2 | 20.8 | 15.90 ± 25.10 |
| pting | input-pting | 18.0 ± 0.7 | 17.0 | 21.0 | 15.94 ± 25.15 |
| pting | input-lanjian | 18.1 ± 0.6 | 17.1 | 21.1 | 15.96 ± 25.19 |
| pting | input-mattcl | 18.1 ± 0.7 | 17.0 | 21.2 | 15.99 ± 25.23 |
| kcen | input-mattcl | 18.5 ± 0.6 | 17.7 | 21.4 | 16.39 ± 25.86 |
| kcen | input-pting | 18.6 ± 0.8 | 17.3 | 21.8 | 16.45 ± 25.97 |
| kcen | input-lanjian | 18.6 ± 0.6 | 17.6 | 21.6 | 16.46 ± 25.97 |
| kcen | input-kcen | 18.7 ± 0.7 | 17.8 | 22.0 | 16.53 ± 26.09 |
| mattcl-py | input-pting | 19.8 ± 0.7 | 18.8 | 23.3 | 17.54 ± 27.69 |
| mattcl-py | input-kcen | 19.9 ± 0.7 | 18.7 | 22.7 | 17.57 ± 27.73 |
| mattcl-py | input-lanjian | 19.9 ± 2.0 | 18.8 | 42.6 | 17.62 ± 27.86 |
| mattcl-py | input-mattcl | 20.0 ± 0.8 | 18.9 | 23.8 | 17.70 ± 27.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|