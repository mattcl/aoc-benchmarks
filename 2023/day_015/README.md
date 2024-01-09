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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.6 | 1.04 ± 0.21 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 2.6 | 1.06 ± 0.27 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.6 | 1.06 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.09 ± 0.24 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.7 | 2.0 | 1.11 ± 0.27 |
| pting | input-lanjian | 18.3 ± 0.7 | 17.1 | 21.5 | 16.36 ± 3.01 |
| pting | input-mattcl | 18.3 ± 0.7 | 16.9 | 21.8 | 16.36 ± 3.01 |
| pting | input-kcen | 18.4 ± 0.8 | 16.9 | 21.8 | 16.45 ± 3.05 |
| pting | input-pting | 18.5 ± 2.0 | 16.9 | 40.5 | 16.53 ± 3.47 |
| kcen | input-mattcl | 18.8 ± 0.7 | 17.8 | 22.1 | 16.80 ± 3.09 |
| kcen | input-pting | 18.9 ± 0.7 | 18.0 | 21.6 | 16.85 ± 3.09 |
| kcen | input-lanjian | 19.0 ± 0.7 | 17.7 | 22.2 | 16.92 ± 3.11 |
| kcen | input-kcen | 19.0 ± 0.8 | 17.9 | 22.3 | 16.97 ± 3.13 |
| mattcl-py | input-kcen | 20.1 ± 0.7 | 19.3 | 23.7 | 17.95 ± 3.29 |
| mattcl-py | input-lanjian | 20.1 ± 0.8 | 18.8 | 23.5 | 17.98 ± 3.32 |
| mattcl-py | input-pting | 20.4 ± 1.9 | 19.2 | 36.5 | 18.18 ± 3.70 |
| mattcl-py | input-mattcl | 20.6 ± 4.5 | 19.4 | 73.8 | 18.42 ± 5.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|