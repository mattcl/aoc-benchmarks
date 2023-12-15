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
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.23 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.07 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.08 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.7 | 1.09 ± 0.23 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.8 | 1.9 | 1.11 ± 0.24 |
| pting | input-lanjian | 18.4 ± 0.7 | 17.5 | 21.8 | 16.19 ± 2.84 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.4 | 22.0 | 16.20 ± 2.86 |
| pting | input-kcen | 18.4 ± 0.8 | 17.4 | 21.9 | 16.20 ± 2.85 |
| pting | input-pting | 18.4 ± 0.7 | 17.5 | 21.3 | 16.20 ± 2.85 |
| kcen | input-lanjian | 19.1 ± 0.6 | 18.0 | 22.0 | 16.79 ± 2.92 |
| kcen | input-kcen | 19.1 ± 0.8 | 17.9 | 22.2 | 16.83 ± 2.95 |
| kcen | input-pting | 19.2 ± 0.8 | 18.0 | 22.1 | 16.89 ± 2.97 |
| mattcl-py | input-kcen | 19.7 ± 0.7 | 18.5 | 22.7 | 17.30 ± 3.02 |
| mattcl-py | input-lanjian | 19.7 ± 0.6 | 18.9 | 22.2 | 17.37 ± 3.01 |
| mattcl-py | input-pting | 19.8 ± 0.6 | 18.7 | 22.3 | 17.39 ± 3.03 |
| kcen | input-mattcl | 19.8 ± 4.7 | 18.2 | 60.1 | 17.43 ± 5.06 |
| mattcl-py | input-mattcl | 19.8 ± 0.9 | 18.9 | 22.9 | 17.44 ± 3.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|