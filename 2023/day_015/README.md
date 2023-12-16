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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.6 | 1.00 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.1 | 1.04 ± 0.25 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.5 | 1.07 ± 0.24 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.09 ± 0.25 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.9 | 1.09 ± 0.26 |
| pting | input-mattcl | 17.9 ± 0.8 | 17.0 | 21.2 | 15.84 ± 2.79 |
| pting | input-pting | 18.0 ± 0.7 | 17.1 | 21.1 | 15.85 ± 2.79 |
| pting | input-lanjian | 18.0 ± 0.8 | 17.0 | 21.2 | 15.90 ± 2.80 |
| pting | input-kcen | 18.1 ± 2.3 | 16.8 | 46.8 | 15.98 ± 3.43 |
| kcen | input-mattcl | 18.7 ± 0.7 | 17.7 | 21.8 | 16.47 ± 2.89 |
| kcen | input-pting | 18.7 ± 0.8 | 17.6 | 21.9 | 16.53 ± 2.93 |
| kcen | input-kcen | 18.8 ± 0.8 | 17.4 | 21.8 | 16.58 ± 2.92 |
| kcen | input-lanjian | 18.8 ± 0.8 | 17.8 | 21.8 | 16.60 ± 2.93 |
| mattcl-py | input-pting | 19.8 ± 0.8 | 18.8 | 22.8 | 17.48 ± 3.07 |
| mattcl-py | input-kcen | 19.8 ± 0.8 | 18.7 | 22.7 | 17.50 ± 3.07 |
| mattcl-py | input-mattcl | 19.9 ± 0.8 | 18.8 | 23.0 | 17.54 ± 3.09 |
| mattcl-py | input-lanjian | 19.9 ± 0.8 | 18.5 | 22.4 | 17.55 ± 3.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|