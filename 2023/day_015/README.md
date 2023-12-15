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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.0 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 2.1 | 1.01 ± 0.22 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.4 | 1.9 | 1.02 ± 0.22 |
| lanjian | input-pting | 1.4 ± 0.2 | 0.6 | 1.9 | 1.07 ± 0.21 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.9 | 1.07 ± 0.21 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.6 | 1.9 | 1.08 ± 0.21 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 1.9 | 1.08 ± 0.22 |
| pting | input-kcen | 18.4 ± 0.6 | 17.7 | 21.8 | 13.91 ± 2.21 |
| pting | input-pting | 18.7 ± 0.8 | 17.7 | 21.8 | 14.09 ± 2.27 |
| pting | input-mattcl | 18.7 ± 0.9 | 17.8 | 21.8 | 14.13 ± 2.30 |
| pting | input-lanjian | 18.8 ± 0.8 | 17.6 | 21.8 | 14.20 ± 2.30 |
| kcen | input-mattcl | 18.9 ± 0.7 | 17.9 | 21.9 | 14.26 ± 2.28 |
| kcen | input-pting | 18.9 ± 0.7 | 18.0 | 21.9 | 14.27 ± 2.28 |
| kcen | input-lanjian | 19.0 ± 0.8 | 18.0 | 22.3 | 14.30 ± 2.31 |
| kcen | input-kcen | 19.1 ± 3.7 | 17.6 | 63.7 | 14.38 ± 3.56 |
| mattcl-py | input-kcen | 19.8 ± 0.5 | 19.1 | 22.5 | 14.96 ± 2.37 |
| mattcl-py | input-mattcl | 20.0 ± 0.8 | 18.6 | 23.1 | 15.09 ± 2.42 |
| mattcl-py | input-pting | 20.0 ± 0.7 | 18.9 | 22.7 | 15.09 ± 2.40 |
| mattcl-py | input-lanjian | 20.0 ± 0.8 | 18.9 | 23.2 | 15.09 ± 2.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|