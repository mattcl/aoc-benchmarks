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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.6 | 1.01 ± 0.19 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.6 | 1.7 | 1.04 ± 0.19 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.22 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.20 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.19 |
| pting | input-pting | 18.2 ± 0.7 | 17.2 | 21.4 | 15.97 ± 2.28 |
| pting | input-mattcl | 18.3 ± 0.8 | 17.3 | 21.6 | 16.04 ± 2.32 |
| pting | input-lanjian | 18.3 ± 0.6 | 17.0 | 21.1 | 16.09 ± 2.29 |
| pting | input-kcen | 18.4 ± 0.8 | 17.2 | 21.4 | 16.12 ± 2.33 |
| kcen | input-pting | 18.7 ± 0.7 | 17.7 | 21.8 | 16.42 ± 2.33 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.8 | 21.8 | 16.44 ± 2.33 |
| kcen | input-mattcl | 18.8 ± 0.8 | 17.5 | 21.8 | 16.49 ± 2.38 |
| kcen | input-kcen | 19.0 ± 0.9 | 17.8 | 22.4 | 16.66 ± 2.42 |
| mattcl-py | input-pting | 19.9 ± 0.7 | 18.8 | 23.4 | 17.48 ± 2.48 |
| mattcl-py | input-mattcl | 20.0 ± 0.7 | 18.9 | 23.5 | 17.54 ± 2.50 |
| mattcl-py | input-lanjian | 20.0 ± 0.7 | 18.7 | 23.1 | 17.58 ± 2.49 |
| mattcl-py | input-kcen | 20.1 ± 0.6 | 19.0 | 22.8 | 17.62 ± 2.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|