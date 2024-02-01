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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 2.0 | 1.00 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.5 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.6 | 1.03 ± 0.21 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.5 | 1.04 ± 0.19 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.3 | 2.1 | 1.04 ± 0.22 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 1.7 | 1.06 ± 0.19 |
| pting | input-mattcl | 18.3 ± 0.8 | 17.1 | 21.6 | 14.85 ± 2.17 |
| pting | input-pting | 18.4 ± 0.9 | 17.4 | 21.6 | 14.95 ± 2.22 |
| pting | input-lanjian | 18.4 ± 0.7 | 17.5 | 21.1 | 14.96 ± 2.18 |
| pting | input-kcen | 18.5 ± 0.8 | 17.6 | 21.7 | 15.04 ± 2.20 |
| kcen | input-pting | 18.8 ± 0.6 | 17.8 | 21.5 | 15.32 ± 2.21 |
| kcen | input-mattcl | 18.9 ± 0.7 | 17.4 | 21.5 | 15.35 ± 2.22 |
| kcen | input-lanjian | 18.9 ± 0.7 | 17.9 | 21.8 | 15.39 ± 2.22 |
| kcen | input-kcen | 19.0 ± 0.8 | 18.2 | 22.2 | 15.44 ± 2.25 |
| mattcl-py | input-pting | 20.0 ± 0.6 | 18.9 | 22.9 | 16.28 ± 2.34 |
| mattcl-py | input-kcen | 20.1 ± 0.6 | 18.9 | 22.8 | 16.31 ± 2.33 |
| mattcl-py | input-mattcl | 20.1 ± 0.7 | 18.8 | 22.9 | 16.33 ± 2.35 |
| mattcl-py | input-lanjian | 20.3 ± 0.8 | 18.8 | 23.6 | 16.52 ± 2.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|