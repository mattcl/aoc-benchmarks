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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.0 | 1.02 ± 0.20 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.18 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.18 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.03 ± 0.20 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.5 | 1.9 | 1.04 ± 0.18 |
| mattcl | input-pting | 1.3 ± 0.1 | 0.8 | 1.8 | 1.04 ± 0.15 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.8 | 1.5 | 1.04 ± 0.17 |
| pting | input-mattcl | 18.0 ± 0.8 | 17.0 | 21.5 | 14.39 ± 1.84 |
| pting | input-kcen | 18.1 ± 0.7 | 17.0 | 21.3 | 14.43 ± 1.82 |
| pting | input-lanjian | 18.1 ± 0.6 | 17.0 | 21.0 | 14.43 ± 1.80 |
| pting | input-pting | 18.2 ± 0.8 | 16.9 | 21.7 | 14.49 ± 1.87 |
| kcen | input-pting | 18.6 ± 0.8 | 17.3 | 22.0 | 14.88 ± 1.91 |
| kcen | input-mattcl | 18.7 ± 0.8 | 17.7 | 21.8 | 14.88 ± 1.89 |
| kcen | input-lanjian | 18.7 ± 0.8 | 17.7 | 21.8 | 14.96 ± 1.91 |
| kcen | input-kcen | 18.8 ± 0.6 | 17.5 | 21.4 | 14.97 ± 1.86 |
| mattcl-py | input-lanjian | 19.9 ± 0.8 | 18.7 | 23.2 | 15.90 ± 2.01 |
| mattcl-py | input-pting | 20.0 ± 0.7 | 18.9 | 23.9 | 15.94 ± 2.01 |
| mattcl-py | input-mattcl | 20.0 ± 0.8 | 18.7 | 23.1 | 15.99 ± 2.04 |
| mattcl-py | input-kcen | 20.1 ± 0.8 | 19.0 | 23.2 | 16.01 ± 2.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|