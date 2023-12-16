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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.9 | 1.02 ± 0.25 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.4 | 1.08 ± 0.23 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.09 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.5 | 1.7 | 1.10 ± 0.22 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.11 ± 0.23 |
| pting | input-mattcl | 17.9 ± 0.5 | 16.8 | 19.9 | 16.14 ± 2.74 |
| pting | input-pting | 18.0 ± 0.6 | 17.2 | 21.0 | 16.21 ± 2.78 |
| pting | input-kcen | 18.1 ± 0.7 | 17.3 | 21.8 | 16.24 ± 2.80 |
| pting | input-lanjian | 18.5 ± 3.6 | 17.1 | 63.0 | 16.67 ± 4.28 |
| kcen | input-pting | 18.7 ± 0.8 | 17.6 | 22.0 | 16.79 ± 2.90 |
| kcen | input-lanjian | 18.7 ± 0.5 | 17.9 | 21.1 | 16.79 ± 2.85 |
| kcen | input-kcen | 18.7 ± 0.6 | 17.7 | 21.4 | 16.83 ± 2.88 |
| kcen | input-mattcl | 18.7 ± 0.6 | 18.0 | 21.5 | 16.84 ± 2.88 |
| mattcl-py | input-mattcl | 19.8 ± 0.7 | 18.8 | 22.8 | 17.83 ± 3.06 |
| mattcl-py | input-pting | 20.0 ± 0.8 | 18.7 | 24.4 | 18.00 ± 3.12 |
| mattcl-py | input-lanjian | 20.1 ± 1.4 | 18.9 | 33.8 | 18.04 ± 3.27 |
| mattcl-py | input-kcen | 20.4 ± 3.2 | 19.2 | 51.4 | 18.39 ± 4.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|