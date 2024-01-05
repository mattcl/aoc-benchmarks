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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.26 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.07 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.7 | 1.08 ± 0.23 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.0 | 1.13 ± 0.27 |
| pting | input-pting | 17.9 ± 0.7 | 16.9 | 20.9 | 15.57 ± 2.99 |
| pting | input-kcen | 17.9 ± 0.7 | 16.9 | 21.3 | 15.57 ± 3.00 |
| pting | input-lanjian | 18.0 ± 0.8 | 17.1 | 21.3 | 15.66 ± 3.03 |
| pting | input-mattcl | 18.3 ± 3.3 | 16.8 | 58.7 | 15.88 ± 4.15 |
| kcen | input-pting | 18.4 ± 0.6 | 17.3 | 21.5 | 16.03 ± 3.07 |
| kcen | input-mattcl | 18.5 ± 0.7 | 17.4 | 21.8 | 16.06 ± 3.08 |
| kcen | input-lanjian | 18.6 ± 0.6 | 17.6 | 21.6 | 16.14 ± 3.09 |
| kcen | input-kcen | 18.7 ± 0.6 | 17.7 | 21.3 | 16.22 ± 3.10 |
| mattcl-py | input-pting | 19.8 ± 0.6 | 18.6 | 22.4 | 17.20 ± 3.29 |
| mattcl-py | input-lanjian | 19.8 ± 0.7 | 18.8 | 22.9 | 17.22 ± 3.31 |
| mattcl-py | input-kcen | 20.0 ± 0.9 | 18.8 | 22.9 | 17.37 ± 3.36 |
| mattcl-py | input-mattcl | 20.3 ± 4.2 | 18.7 | 61.9 | 17.65 ± 4.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|