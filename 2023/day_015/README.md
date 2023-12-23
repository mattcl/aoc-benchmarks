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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.4 | 1.00 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 2.0 | 1.02 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 2.9 | 0.3 | 41.4 | 1.03 ± 2.41 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 2.0 | 1.05 ± 0.22 |
| pting | input-mattcl | 18.4 ± 0.7 | 17.2 | 21.3 | 15.44 ± 2.35 |
| pting | input-kcen | 18.4 ± 0.9 | 17.3 | 22.0 | 15.44 ± 2.38 |
| pting | input-pting | 18.4 ± 0.8 | 17.3 | 21.5 | 15.45 ± 2.38 |
| pting | input-lanjian | 18.4 ± 0.9 | 17.0 | 21.9 | 15.47 ± 2.39 |
| kcen | input-mattcl | 18.8 ± 0.8 | 17.6 | 21.9 | 15.75 ± 2.40 |
| kcen | input-lanjian | 18.9 ± 0.7 | 17.5 | 22.1 | 15.83 ± 2.39 |
| kcen | input-pting | 18.9 ± 0.8 | 17.7 | 22.0 | 15.83 ± 2.42 |
| kcen | input-kcen | 19.0 ± 0.7 | 17.9 | 21.5 | 15.93 ± 2.41 |
| mattcl-py | input-pting | 20.1 ± 0.7 | 19.0 | 22.6 | 16.84 ± 2.54 |
| mattcl-py | input-kcen | 20.2 ± 0.7 | 18.9 | 23.6 | 16.90 ± 2.56 |
| mattcl-py | input-lanjian | 20.2 ± 0.8 | 18.9 | 23.4 | 16.92 ± 2.57 |
| mattcl-py | input-mattcl | 21.3 ± 7.1 | 19.0 | 83.1 | 17.85 ± 6.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|