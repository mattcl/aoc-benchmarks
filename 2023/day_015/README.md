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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.9 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.03 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.06 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.5 | 2.0 | 1.06 ± 0.21 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.3 | 1.9 | 1.08 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 1.08 ± 0.23 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.4 | 21.5 | 15.62 ± 2.47 |
| pting | input-lanjian | 18.5 ± 0.8 | 17.4 | 21.9 | 15.70 ± 2.49 |
| pting | input-kcen | 18.6 ± 0.8 | 17.4 | 22.1 | 15.76 ± 2.49 |
| pting | input-pting | 18.6 ± 0.9 | 17.5 | 22.2 | 15.78 ± 2.54 |
| kcen | input-mattcl | 18.8 ± 0.6 | 17.9 | 22.0 | 16.01 ± 2.50 |
| kcen | input-lanjian | 18.9 ± 0.6 | 17.6 | 21.5 | 16.03 ± 2.51 |
| kcen | input-pting | 19.0 ± 0.9 | 17.6 | 21.9 | 16.18 ± 2.58 |
| kcen | input-kcen | 19.1 ± 0.9 | 17.8 | 22.8 | 16.26 ± 2.59 |
| mattcl-py | input-pting | 20.0 ± 0.8 | 18.5 | 23.4 | 17.03 ± 2.68 |
| mattcl-py | input-mattcl | 20.1 ± 0.7 | 19.0 | 23.1 | 17.04 ± 2.67 |
| mattcl-py | input-lanjian | 20.1 ± 0.7 | 19.0 | 22.7 | 17.11 ± 2.68 |
| mattcl-py | input-kcen | 20.4 ± 1.9 | 19.2 | 40.2 | 17.35 ± 3.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|