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
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.02 ± 0.27 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.3 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.5 | 1.4 | 1.03 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.5 | 1.04 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.28 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.6 | 1.7 | 1.07 ± 0.26 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.9 | 1.08 ± 0.30 |
| kcen | input-kcen | 19.2 ± 0.5 | 18.4 | 21.9 | 16.70 ± 3.59 |
| kcen | input-lanjian | 19.3 ± 0.6 | 18.5 | 22.3 | 16.78 ± 3.61 |
| kcen | input-mattcl | 19.3 ± 0.6 | 18.5 | 22.2 | 16.79 ± 3.62 |
| kcen | input-pting | 19.5 ± 0.8 | 18.2 | 22.4 | 16.90 ± 3.67 |
| mattcl-py | input-kcen | 19.8 ± 0.7 | 18.8 | 22.4 | 17.18 ± 3.70 |
| mattcl-py | input-pting | 19.9 ± 0.8 | 18.7 | 22.7 | 17.27 ± 3.74 |
| mattcl-py | input-mattcl | 20.0 ± 0.8 | 18.8 | 22.7 | 17.33 ± 3.75 |
| mattcl-py | input-lanjian | 20.0 ± 0.8 | 18.9 | 23.0 | 17.35 ± 3.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|