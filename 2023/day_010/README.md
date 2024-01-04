# Day 10 benchmarks

[link to problem](https://adventofcode.com/2023/day/10)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 10)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.22 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.2 | 5.5 | 2.38 ± 0.41 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 5.6 | 2.38 ± 0.41 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.5 | 5.6 | 2.40 ± 0.41 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.9 | 2.41 ± 0.40 |
| mattcl-ts | input-pting | 17.2 ± 0.3 | 16.4 | 18.2 | 13.33 ± 2.04 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.4 | 18.6 | 13.44 ± 2.06 |
| mattcl-ts | input-lanjian | 17.3 ± 0.4 | 16.3 | 18.5 | 13.45 ± 2.07 |
| mattcl-ts | input-mattcl | 17.7 ± 5.1 | 16.0 | 76.8 | 13.75 ± 4.46 |
| mattcl-py | input-kcen | 25.6 ± 0.9 | 24.6 | 28.8 | 19.84 ± 3.08 |
| mattcl-py | input-mattcl | 25.8 ± 1.9 | 24.5 | 44.3 | 20.00 ± 3.36 |
| mattcl-py | input-pting | 26.0 ± 0.7 | 24.8 | 29.1 | 20.16 ± 3.11 |
| mattcl-py | input-lanjian | 26.1 ± 0.9 | 25.2 | 30.1 | 20.28 ± 3.16 |
| pting | input-kcen | 26.6 ± 0.8 | 25.5 | 29.2 | 20.65 ± 3.20 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.7 | 30.3 | 20.76 ± 3.21 |
| pting | input-pting | 26.8 ± 0.7 | 25.8 | 30.2 | 20.81 ± 3.20 |
| pting | input-lanjian | 26.9 ± 0.8 | 25.9 | 29.7 | 20.84 ± 3.22 |
| kcen | input-pting | 46.6 ± 1.0 | 45.3 | 49.4 | 36.16 ± 5.54 |
| kcen | input-lanjian | 47.8 ± 1.3 | 46.3 | 55.4 | 37.07 ± 5.72 |
| kcen | input-mattcl | 49.9 ± 1.0 | 48.2 | 52.8 | 38.72 ± 5.92 |
| kcen | input-kcen | 50.1 ± 1.1 | 48.5 | 53.0 | 38.84 ± 5.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|