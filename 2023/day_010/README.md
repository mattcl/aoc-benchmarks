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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.1 | 1.03 ± 0.21 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.5 | 2.2 | 1.03 ± 0.23 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 3.8 | 2.30 ± 0.37 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 4.0 | 2.31 ± 0.37 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.5 | 2.34 ± 0.41 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.5 | 5.8 | 2.39 ± 0.46 |
| mattcl-ts | input-mattcl | 16.3 ± 0.4 | 15.1 | 17.8 | 12.17 ± 1.86 |
| mattcl-ts | input-kcen | 16.4 ± 0.4 | 15.3 | 17.4 | 12.25 ± 1.87 |
| mattcl-ts | input-pting | 16.5 ± 0.4 | 15.1 | 17.7 | 12.26 ± 1.87 |
| mattcl-ts | input-lanjian | 16.6 ± 0.5 | 15.3 | 17.8 | 12.37 ± 1.89 |
| mattcl-py | input-kcen | 25.6 ± 0.9 | 24.1 | 29.2 | 19.11 ± 2.95 |
| mattcl-py | input-mattcl | 26.0 ± 0.9 | 24.6 | 29.2 | 19.36 ± 2.99 |
| mattcl-py | input-pting | 26.2 ± 0.8 | 25.0 | 29.5 | 19.52 ± 3.00 |
| mattcl-py | input-lanjian | 26.3 ± 0.9 | 25.0 | 29.1 | 19.60 ± 3.03 |
| pting | input-kcen | 27.1 ± 0.8 | 25.9 | 30.7 | 20.18 ± 3.09 |
| pting | input-lanjian | 27.1 ± 0.8 | 25.6 | 29.9 | 20.19 ± 3.09 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.1 | 30.5 | 20.26 ± 3.11 |
| pting | input-pting | 27.3 ± 0.8 | 26.2 | 30.4 | 20.31 ± 3.12 |
| kcen | input-pting | 47.6 ± 1.3 | 45.2 | 51.0 | 35.49 ± 5.43 |
| kcen | input-lanjian | 48.5 ± 1.1 | 46.9 | 52.2 | 36.12 ± 5.50 |
| kcen | input-kcen | 50.4 ± 1.2 | 48.7 | 53.8 | 37.54 ± 5.72 |
| kcen | input-mattcl | 50.5 ± 1.7 | 48.4 | 59.5 | 37.63 ± 5.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|