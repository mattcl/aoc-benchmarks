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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.24 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.05 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 2.9 | 0.3 | 42.1 | 1.07 ± 2.58 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.08 ± 0.25 |
| lanjian | input-mattcl | 1.3 ± 0.1 | 0.6 | 1.8 | 1.10 ± 0.23 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 1.7 | 1.11 ± 0.23 |
| pting | input-pting | 18.0 ± 0.7 | 17.1 | 21.5 | 15.84 ± 2.79 |
| pting | input-lanjian | 18.1 ± 0.6 | 17.4 | 21.3 | 15.85 ± 2.78 |
| pting | input-kcen | 18.1 ± 0.7 | 17.0 | 21.4 | 15.89 ± 2.81 |
| pting | input-mattcl | 18.1 ± 0.9 | 17.1 | 21.3 | 15.92 ± 2.84 |
| kcen | input-pting | 18.7 ± 0.8 | 17.4 | 22.0 | 16.42 ± 2.90 |
| kcen | input-lanjian | 18.8 ± 0.8 | 17.6 | 21.7 | 16.47 ± 2.91 |
| kcen | input-kcen | 18.8 ± 0.8 | 17.6 | 22.3 | 16.48 ± 2.92 |
| kcen | input-mattcl | 18.8 ± 0.8 | 17.7 | 21.9 | 16.50 ± 2.92 |
| mattcl-py | input-pting | 19.8 ± 0.6 | 18.5 | 22.6 | 17.36 ± 3.03 |
| mattcl-py | input-kcen | 19.9 ± 0.7 | 18.8 | 22.8 | 17.45 ± 3.05 |
| mattcl-py | input-mattcl | 20.0 ± 0.8 | 18.9 | 23.3 | 17.52 ± 3.10 |
| mattcl-py | input-lanjian | 20.8 ± 7.0 | 18.8 | 95.5 | 18.22 ± 6.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|