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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.00 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.24 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.1 | 1.03 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 2.0 | 1.05 ± 0.27 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.06 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 2.0 | 1.08 ± 0.26 |
| pting | input-mattcl | 18.3 ± 0.6 | 17.3 | 21.1 | 16.00 ± 2.92 |
| pting | input-pting | 18.3 ± 0.6 | 17.0 | 21.0 | 16.01 ± 2.93 |
| pting | input-kcen | 18.4 ± 0.7 | 17.2 | 22.4 | 16.13 ± 2.96 |
| pting | input-lanjian | 18.5 ± 0.8 | 17.3 | 21.9 | 16.22 ± 3.00 |
| kcen | input-pting | 18.7 ± 0.7 | 17.7 | 22.0 | 16.39 ± 3.01 |
| kcen | input-mattcl | 18.7 ± 0.6 | 17.5 | 21.5 | 16.41 ± 3.00 |
| kcen | input-kcen | 18.9 ± 0.7 | 17.7 | 21.8 | 16.54 ± 3.03 |
| kcen | input-lanjian | 18.9 ± 0.7 | 17.8 | 21.9 | 16.54 ± 3.04 |
| mattcl-py | input-pting | 19.9 ± 0.6 | 18.7 | 22.3 | 17.44 ± 3.18 |
| mattcl-py | input-mattcl | 20.1 ± 0.8 | 19.1 | 22.9 | 17.60 ± 3.24 |
| mattcl-py | input-kcen | 20.2 ± 0.7 | 18.6 | 23.2 | 17.70 ± 3.25 |
| mattcl-py | input-lanjian | 21.0 ± 5.9 | 18.4 | 64.8 | 18.39 ± 6.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|