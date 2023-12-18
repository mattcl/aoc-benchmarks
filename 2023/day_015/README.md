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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 2.0 | 1.02 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.19 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.8 | 1.6 | 1.04 ± 0.19 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.8 | 1.7 | 1.04 ± 0.18 |
| mattcl | input-lanjian | 1.3 ± 0.1 | 0.4 | 1.7 | 1.05 ± 0.18 |
| lanjian | input-lanjian | 1.3 ± 0.1 | 0.7 | 1.7 | 1.06 ± 0.18 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.0 | 1.06 ± 0.23 |
| pting | input-mattcl | 18.3 ± 0.6 | 17.5 | 21.6 | 15.11 ± 2.04 |
| pting | input-pting | 18.4 ± 0.8 | 17.3 | 21.6 | 15.14 ± 2.08 |
| pting | input-lanjian | 18.5 ± 0.8 | 17.4 | 22.1 | 15.22 ± 2.09 |
| pting | input-kcen | 18.5 ± 0.8 | 17.5 | 22.1 | 15.27 ± 2.10 |
| kcen | input-pting | 18.8 ± 0.7 | 17.5 | 22.0 | 15.51 ± 2.11 |
| kcen | input-lanjian | 18.8 ± 0.7 | 17.8 | 21.9 | 15.54 ± 2.11 |
| kcen | input-mattcl | 18.9 ± 0.8 | 18.0 | 21.7 | 15.60 ± 2.14 |
| kcen | input-kcen | 19.0 ± 0.9 | 17.6 | 22.0 | 15.69 ± 2.19 |
| mattcl-py | input-pting | 20.0 ± 0.7 | 18.6 | 22.7 | 16.53 ± 2.24 |
| mattcl-py | input-lanjian | 20.0 ± 0.5 | 19.3 | 22.9 | 16.53 ± 2.20 |
| mattcl-py | input-mattcl | 20.1 ± 0.7 | 18.9 | 22.9 | 16.55 ± 2.23 |
| mattcl-py | input-kcen | 20.2 ± 0.8 | 19.1 | 23.2 | 16.64 ± 2.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|