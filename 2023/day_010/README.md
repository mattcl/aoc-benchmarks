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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.8 | 1.00 ± 0.20 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.0 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.6 | 1.9 | 1.01 ± 0.22 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 5.7 | 2.32 ± 0.41 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.5 | 4.8 | 2.32 ± 0.41 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.3 | 6.2 | 2.33 ± 0.47 |
| lanjian | input-lanjian | 3.2 ± 0.3 | 2.9 | 4.3 | 2.38 ± 0.43 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.3 | 18.8 | 13.05 ± 2.01 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.7 | 18.6 | 13.07 ± 2.01 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.3 | 19.0 | 13.08 ± 2.01 |
| mattcl-ts | input-lanjian | 17.7 ± 0.5 | 16.7 | 19.5 | 13.16 ± 2.03 |
| mattcl-py | input-mattcl | 25.8 ± 0.8 | 24.7 | 29.5 | 19.17 ± 2.97 |
| mattcl-py | input-kcen | 26.0 ± 0.9 | 24.5 | 29.5 | 19.34 ± 3.02 |
| mattcl-py | input-pting | 26.3 ± 0.8 | 25.1 | 29.1 | 19.56 ± 3.04 |
| mattcl-py | input-lanjian | 26.4 ± 1.0 | 25.1 | 30.0 | 19.66 ± 3.08 |
| pting | input-kcen | 27.0 ± 1.2 | 25.5 | 36.3 | 20.12 ± 3.18 |
| pting | input-mattcl | 27.1 ± 0.8 | 26.1 | 30.4 | 20.19 ± 3.12 |
| pting | input-lanjian | 27.2 ± 0.8 | 25.8 | 30.3 | 20.26 ± 3.14 |
| pting | input-pting | 27.2 ± 0.9 | 25.7 | 31.1 | 20.27 ± 3.15 |
| kcen | input-pting | 47.1 ± 1.5 | 45.3 | 55.2 | 35.08 ± 5.45 |
| kcen | input-lanjian | 48.5 ± 1.3 | 46.3 | 53.0 | 36.07 ± 5.58 |
| kcen | input-mattcl | 50.3 ± 1.0 | 48.3 | 52.8 | 37.46 ± 5.74 |
| kcen | input-kcen | 50.6 ± 1.0 | 48.6 | 53.1 | 37.63 ± 5.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|