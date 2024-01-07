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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 2.0 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.19 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.1 | 0.7 | 1.7 | 1.02 ± 0.18 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.1 | 1.06 ± 0.22 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 2.1 | 1.08 ± 0.23 |
| pting | input-pting | 18.3 ± 0.6 | 17.5 | 21.5 | 14.74 ± 2.19 |
| pting | input-kcen | 18.3 ± 0.6 | 17.3 | 21.2 | 14.76 ± 2.18 |
| pting | input-lanjian | 18.4 ± 0.6 | 17.7 | 22.0 | 14.86 ± 2.21 |
| pting | input-mattcl | 18.5 ± 0.8 | 17.3 | 22.1 | 14.88 ± 2.24 |
| kcen | input-mattcl | 18.9 ± 0.8 | 18.0 | 22.2 | 15.26 ± 2.29 |
| kcen | input-pting | 19.0 ± 0.8 | 17.9 | 21.8 | 15.28 ± 2.29 |
| kcen | input-kcen | 19.0 ± 0.7 | 17.9 | 22.3 | 15.30 ± 2.28 |
| kcen | input-lanjian | 19.1 ± 0.9 | 17.7 | 22.0 | 15.38 ± 2.33 |
| mattcl-py | input-mattcl | 20.1 ± 0.8 | 18.7 | 23.2 | 16.22 ± 2.44 |
| mattcl-py | input-pting | 20.2 ± 0.7 | 19.1 | 22.9 | 16.24 ± 2.42 |
| mattcl-py | input-lanjian | 20.2 ± 0.6 | 19.3 | 23.0 | 16.25 ± 2.40 |
| mattcl-py | input-kcen | 20.2 ± 0.7 | 19.4 | 23.8 | 16.30 ± 2.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|