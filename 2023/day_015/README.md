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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.04 ± 0.24 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.2 | 1.06 ± 0.24 |
| mattcl | input-lanjian | 1.3 ± 0.1 | 0.8 | 1.8 | 1.06 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 2.3 | 1.07 ± 0.26 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.08 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.1 | 0.9 | 1.8 | 1.09 ± 0.22 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 1.9 | 1.12 ± 0.25 |
| pting | input-pting | 18.1 ± 0.7 | 17.0 | 21.5 | 14.72 ± 2.69 |
| pting | input-kcen | 18.1 ± 0.7 | 17.3 | 22.1 | 14.74 ± 2.69 |
| pting | input-mattcl | 18.4 ± 3.0 | 17.4 | 54.5 | 14.95 ± 3.64 |
| kcen | input-pting | 18.6 ± 0.7 | 17.4 | 21.7 | 15.14 ± 2.77 |
| kcen | input-mattcl | 18.6 ± 0.6 | 17.7 | 21.7 | 15.16 ± 2.75 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.6 | 21.4 | 15.18 ± 2.76 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.8 | 21.7 | 15.25 ± 2.78 |
| pting | input-lanjian | 18.8 ± 4.9 | 17.2 | 67.9 | 15.26 ± 4.80 |
| mattcl-py | input-mattcl | 19.8 ± 0.6 | 18.7 | 22.4 | 16.11 ± 2.92 |
| mattcl-py | input-pting | 19.8 ± 0.7 | 18.7 | 22.8 | 16.14 ± 2.93 |
| mattcl-py | input-lanjian | 19.9 ± 0.6 | 19.0 | 22.4 | 16.18 ± 2.93 |
| mattcl-py | input-kcen | 20.0 ± 0.7 | 19.0 | 22.9 | 16.24 ± 2.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|