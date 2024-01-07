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
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.8 | 2.0 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 2.0 | 1.05 ± 0.24 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.10 ± 0.23 |
| lanjian | input-kcen | 3.0 ± 0.1 | 2.3 | 3.9 | 2.32 ± 0.37 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 3.7 | 2.32 ± 0.37 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.7 | 2.34 ± 0.42 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.8 | 5.8 | 2.35 ± 0.40 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.3 | 18.4 | 13.20 ± 2.03 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.4 | 13.26 ± 2.04 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.4 | 18.4 | 13.30 ± 2.04 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.5 | 18.6 | 13.32 ± 2.05 |
| mattcl-py | input-kcen | 25.5 ± 1.1 | 24.5 | 31.3 | 19.53 ± 3.08 |
| mattcl-py | input-mattcl | 25.7 ± 0.9 | 24.6 | 28.9 | 19.68 ± 3.06 |
| mattcl-py | input-pting | 25.9 ± 0.7 | 25.2 | 29.2 | 19.83 ± 3.06 |
| mattcl-py | input-lanjian | 26.0 ± 0.8 | 24.7 | 28.8 | 19.88 ± 3.09 |
| pting | input-kcen | 26.6 ± 0.7 | 25.8 | 29.1 | 20.36 ± 3.14 |
| pting | input-mattcl | 26.7 ± 0.7 | 25.8 | 30.5 | 20.42 ± 3.16 |
| pting | input-lanjian | 26.9 ± 0.8 | 25.9 | 29.8 | 20.57 ± 3.18 |
| pting | input-pting | 27.0 ± 0.6 | 26.0 | 30.0 | 20.64 ± 3.18 |
| kcen | input-pting | 47.1 ± 1.1 | 45.7 | 51.4 | 36.01 ± 5.54 |
| kcen | input-lanjian | 47.8 ± 1.1 | 46.6 | 50.9 | 36.62 ± 5.63 |
| kcen | input-kcen | 50.1 ± 1.2 | 48.3 | 53.2 | 38.33 ± 5.90 |
| kcen | input-mattcl | 50.3 ± 1.3 | 48.0 | 54.8 | 38.47 ± 5.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|