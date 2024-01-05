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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.5 | 1.5 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.20 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.20 |
| mattcl | input-pting | 1.3 ± 2.2 | 0.4 | 31.5 | 1.04 ± 1.75 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.5 | 1.06 ± 0.20 |
| lanjian | input-lanjian | 1.3 ± 0.1 | 0.7 | 1.6 | 1.06 ± 0.19 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.8 | 1.8 | 1.08 ± 0.20 |
| pting | input-pting | 18.0 ± 0.7 | 17.2 | 21.4 | 14.49 ± 2.25 |
| pting | input-mattcl | 18.1 ± 0.7 | 17.1 | 20.9 | 14.56 ± 2.27 |
| pting | input-kcen | 18.1 ± 0.7 | 17.1 | 21.3 | 14.58 ± 2.27 |
| pting | input-lanjian | 18.2 ± 0.7 | 17.4 | 21.8 | 14.62 ± 2.28 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.6 | 21.2 | 15.03 ± 2.32 |
| kcen | input-mattcl | 18.7 ± 0.8 | 17.9 | 22.3 | 15.07 ± 2.36 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.8 | 21.7 | 15.10 ± 2.34 |
| kcen | input-pting | 19.0 ± 3.4 | 17.6 | 60.1 | 15.31 ± 3.57 |
| mattcl-py | input-mattcl | 19.9 ± 0.7 | 19.0 | 22.4 | 15.98 ± 2.48 |
| mattcl-py | input-pting | 19.9 ± 0.8 | 19.1 | 23.3 | 16.06 ± 2.50 |
| mattcl-py | input-lanjian | 20.0 ± 0.7 | 19.1 | 23.8 | 16.09 ± 2.49 |
| mattcl-py | input-kcen | 20.1 ± 0.8 | 19.0 | 22.9 | 16.17 ± 2.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|