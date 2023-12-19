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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.0 | 1.03 ± 0.22 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.6 | 2.42 ± 0.43 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 4.6 | 2.42 ± 0.41 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 5.6 | 2.43 ± 0.44 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.4 | 6.0 | 2.44 ± 0.44 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.4 | 18.5 | 14.11 ± 2.20 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.3 | 19.2 | 14.13 ± 2.21 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.8 | 19.0 | 14.15 ± 2.21 |
| mattcl-ts | input-lanjian | 17.9 ± 3.2 | 16.7 | 58.4 | 14.46 ± 3.42 |
| mattcl-py | input-kcen | 25.7 ± 1.0 | 24.5 | 29.0 | 20.76 ± 3.31 |
| mattcl-py | input-mattcl | 25.8 ± 0.8 | 24.7 | 28.6 | 20.86 ± 3.29 |
| mattcl-py | input-pting | 26.1 ± 1.0 | 24.8 | 29.4 | 21.12 ± 3.37 |
| mattcl-py | input-lanjian | 26.2 ± 0.8 | 24.9 | 30.2 | 21.15 ± 3.34 |
| pting | input-mattcl | 27.1 ± 0.9 | 26.0 | 30.2 | 21.87 ± 3.45 |
| pting | input-pting | 27.1 ± 0.7 | 25.9 | 29.8 | 21.91 ± 3.43 |
| pting | input-kcen | 27.1 ± 1.0 | 25.4 | 29.9 | 21.91 ± 3.48 |
| pting | input-lanjian | 27.3 ± 0.9 | 25.7 | 30.2 | 22.03 ± 3.48 |
| kcen | input-pting | 46.9 ± 1.0 | 45.5 | 49.9 | 37.89 ± 5.91 |
| kcen | input-lanjian | 48.4 ± 1.1 | 46.5 | 51.2 | 39.09 ± 6.12 |
| kcen | input-mattcl | 50.4 ± 1.2 | 48.5 | 53.7 | 40.68 ± 6.37 |
| kcen | input-kcen | 50.5 ± 1.1 | 48.5 | 53.8 | 40.79 ± 6.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|