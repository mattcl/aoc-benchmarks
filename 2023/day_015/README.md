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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.23 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 1.5 | 1.05 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.06 ± 0.24 |
| lanjian | input-mattcl | 1.3 ± 0.1 | 0.7 | 1.7 | 1.07 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 2.0 | 1.07 ± 0.24 |
| pting | input-pting | 18.0 ± 0.8 | 16.9 | 21.3 | 15.10 ± 2.71 |
| pting | input-lanjian | 18.1 ± 0.7 | 17.2 | 21.2 | 15.13 ± 2.70 |
| pting | input-mattcl | 18.1 ± 0.8 | 17.1 | 21.0 | 15.15 ± 2.72 |
| pting | input-kcen | 18.2 ± 0.8 | 17.2 | 21.4 | 15.22 ± 2.73 |
| kcen | input-pting | 18.5 ± 0.5 | 17.4 | 21.6 | 15.54 ± 2.74 |
| kcen | input-lanjian | 18.6 ± 0.5 | 17.5 | 21.2 | 15.58 ± 2.75 |
| kcen | input-mattcl | 18.6 ± 0.6 | 17.7 | 21.6 | 15.58 ± 2.77 |
| kcen | input-kcen | 18.8 ± 0.8 | 17.6 | 22.1 | 15.73 ± 2.81 |
| mattcl-py | input-pting | 19.8 ± 0.7 | 19.0 | 22.5 | 16.62 ± 2.95 |
| mattcl-py | input-mattcl | 19.9 ± 0.7 | 18.7 | 22.6 | 16.69 ± 2.97 |
| mattcl-py | input-lanjian | 19.9 ± 0.7 | 19.0 | 22.8 | 16.70 ± 2.96 |
| mattcl-py | input-kcen | 20.1 ± 0.8 | 19.1 | 23.0 | 16.81 ± 3.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|