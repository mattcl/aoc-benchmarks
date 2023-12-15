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


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.6 | 1.03 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.6 | 1.6 | 1.03 ± 0.22 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.8 | 1.03 ± 0.25 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 1.7 | 1.06 ± 0.25 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.06 ± 0.25 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.6 | 1.06 ± 0.26 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.07 ± 0.26 |
| kcen | input-lanjian | 19.1 ± 0.6 | 18.0 | 21.7 | 17.86 ± 3.09 |
| kcen | input-pting | 19.1 ± 0.7 | 18.0 | 22.0 | 17.87 ± 3.10 |
| kcen | input-mattcl | 19.1 ± 0.7 | 18.2 | 22.1 | 17.91 ± 3.11 |
| kcen | input-kcen | 19.2 ± 0.8 | 18.4 | 22.1 | 18.01 ± 3.14 |
| mattcl-py | input-mattcl | 19.7 ± 0.6 | 18.7 | 22.4 | 18.40 ± 3.17 |
| mattcl-py | input-kcen | 19.7 ± 0.9 | 18.7 | 22.8 | 18.46 ± 3.24 |
| mattcl-py | input-pting | 19.7 ± 0.7 | 18.3 | 22.6 | 18.47 ± 3.21 |
| mattcl-py | input-lanjian | 19.8 ± 0.8 | 18.6 | 23.1 | 18.52 ± 3.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|