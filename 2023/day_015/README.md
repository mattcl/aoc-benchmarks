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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.7 | 1.7 | 1.04 ± 0.19 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 2.1 | 1.04 ± 0.21 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 1.5 | 1.05 ± 0.20 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.1 | 1.06 ± 0.21 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.7 | 1.7 | 1.06 ± 0.20 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 2.1 | 1.09 ± 0.23 |
| pting | input-pting | 18.0 ± 0.6 | 17.1 | 21.3 | 15.02 ± 2.22 |
| pting | input-mattcl | 18.0 ± 0.7 | 16.9 | 21.2 | 15.04 ± 2.25 |
| pting | input-lanjian | 18.1 ± 0.8 | 17.0 | 20.8 | 15.10 ± 2.26 |
| pting | input-kcen | 18.1 ± 0.7 | 17.0 | 21.2 | 15.13 ± 2.26 |
| kcen | input-mattcl | 18.6 ± 0.7 | 17.8 | 21.9 | 15.51 ± 2.30 |
| kcen | input-pting | 18.6 ± 0.9 | 17.5 | 21.4 | 15.57 ± 2.36 |
| kcen | input-lanjian | 18.7 ± 0.7 | 17.5 | 21.6 | 15.58 ± 2.31 |
| kcen | input-kcen | 18.7 ± 0.8 | 17.7 | 22.0 | 15.64 ± 2.35 |
| mattcl-py | input-mattcl | 19.8 ± 0.6 | 18.9 | 22.3 | 16.52 ± 2.42 |
| mattcl-py | input-pting | 19.8 ± 0.7 | 18.4 | 22.6 | 16.54 ± 2.45 |
| mattcl-py | input-lanjian | 19.8 ± 0.7 | 18.8 | 22.6 | 16.56 ± 2.45 |
| mattcl-py | input-kcen | 20.0 ± 0.8 | 18.7 | 22.8 | 16.67 ± 2.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|