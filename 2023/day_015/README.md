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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.01 ± 0.22 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.19 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.5 | 1.5 | 1.01 ± 0.21 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.1 | 0.7 | 1.8 | 1.02 ± 0.19 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 2.1 | 1.03 ± 0.21 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.05 ± 0.22 |
| pting | input-pting | 18.4 ± 0.7 | 17.1 | 21.6 | 14.51 ± 2.24 |
| pting | input-kcen | 18.4 ± 0.9 | 17.0 | 21.6 | 14.52 ± 2.28 |
| pting | input-lanjian | 18.4 ± 0.7 | 17.4 | 21.5 | 14.54 ± 2.25 |
| pting | input-mattcl | 18.5 ± 0.8 | 17.4 | 21.8 | 14.56 ± 2.26 |
| kcen | input-lanjian | 18.8 ± 0.5 | 17.7 | 21.8 | 14.82 ± 2.25 |
| kcen | input-pting | 18.8 ± 0.8 | 17.4 | 22.1 | 14.87 ± 2.31 |
| kcen | input-kcen | 18.9 ± 0.6 | 17.7 | 21.7 | 14.88 ± 2.27 |
| kcen | input-mattcl | 19.0 ± 0.7 | 17.5 | 22.1 | 14.95 ± 2.30 |
| mattcl-py | input-lanjian | 20.0 ± 0.5 | 18.9 | 22.8 | 15.82 ± 2.39 |
| mattcl-py | input-mattcl | 20.1 ± 0.6 | 18.6 | 23.3 | 15.85 ± 2.42 |
| mattcl-py | input-kcen | 20.1 ± 0.7 | 18.6 | 23.1 | 15.87 ± 2.43 |
| mattcl-py | input-pting | 20.1 ± 0.6 | 19.0 | 22.4 | 15.88 ± 2.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|