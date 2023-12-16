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
| lanjian | input-kcen | 0.9 ± 2.3 | 0.4 | 32.9 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.3 | 0.3 | 2.0 | 1.21 ± 3.15 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.41 ± 3.66 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.8 | 1.42 ± 3.67 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.42 ± 3.68 |
| lanjian | input-mattcl | 1.3 ± 0.1 | 0.8 | 1.5 | 1.48 ± 3.82 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.48 ± 3.84 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 2.0 | 1.49 ± 3.86 |
| pting | input-kcen | 18.3 ± 0.8 | 17.4 | 21.4 | 20.71 ± 53.57 |
| pting | input-mattcl | 18.4 ± 0.7 | 17.1 | 21.3 | 20.76 ± 53.71 |
| pting | input-pting | 18.4 ± 0.7 | 17.6 | 21.7 | 20.82 ± 53.85 |
| pting | input-lanjian | 18.6 ± 2.1 | 17.4 | 43.0 | 21.04 ± 54.46 |
| kcen | input-pting | 18.8 ± 0.6 | 17.6 | 22.1 | 21.21 ± 54.85 |
| kcen | input-lanjian | 18.8 ± 0.6 | 17.8 | 21.4 | 21.21 ± 54.85 |
| kcen | input-mattcl | 18.8 ± 0.8 | 17.7 | 22.1 | 21.26 ± 54.99 |
| kcen | input-kcen | 19.2 ± 3.0 | 17.6 | 54.7 | 21.73 ± 56.29 |
| mattcl-py | input-mattcl | 20.1 ± 0.8 | 19.1 | 23.7 | 22.73 ± 58.80 |
| mattcl-py | input-kcen | 20.1 ± 0.7 | 18.7 | 22.7 | 22.74 ± 58.80 |
| mattcl-py | input-pting | 20.2 ± 0.8 | 18.8 | 23.4 | 22.80 ± 58.98 |
| mattcl-py | input-lanjian | 20.4 ± 3.8 | 19.1 | 65.0 | 23.06 ± 59.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|