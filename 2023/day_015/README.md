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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.19 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.5 | 2.1 | 1.05 ± 0.22 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.06 ± 0.20 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.6 | 1.06 ± 0.19 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.08 ± 0.22 |
| mattcl | input-pting | 1.5 ± 4.9 | 0.3 | 70.3 | 1.21 ± 4.06 |
| pting | input-kcen | 18.4 ± 0.8 | 17.4 | 21.5 | 15.24 ± 2.19 |
| pting | input-pting | 18.4 ± 0.8 | 17.4 | 21.4 | 15.24 ± 2.17 |
| pting | input-mattcl | 18.4 ± 0.7 | 17.4 | 21.6 | 15.27 ± 2.16 |
| pting | input-lanjian | 18.8 ± 2.5 | 17.2 | 48.3 | 15.56 ± 2.96 |
| kcen | input-mattcl | 18.8 ± 0.6 | 17.9 | 21.7 | 15.58 ± 2.17 |
| kcen | input-lanjian | 19.0 ± 0.8 | 17.6 | 22.2 | 15.71 ± 2.24 |
| kcen | input-kcen | 19.0 ± 0.8 | 17.8 | 22.2 | 15.74 ± 2.24 |
| kcen | input-pting | 19.0 ± 1.8 | 17.7 | 39.2 | 15.74 ± 2.60 |
| mattcl-py | input-kcen | 20.1 ± 0.6 | 19.0 | 23.3 | 16.66 ± 2.33 |
| mattcl-py | input-mattcl | 20.2 ± 0.7 | 18.8 | 23.6 | 16.71 ± 2.35 |
| mattcl-py | input-lanjian | 20.2 ± 0.7 | 19.3 | 23.1 | 16.73 ± 2.34 |
| mattcl-py | input-pting | 20.2 ± 0.7 | 19.1 | 23.1 | 16.74 ± 2.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|