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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.24 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.5 | 4.7 | 2.41 ± 0.48 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.8 | 2.41 ± 0.49 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 6.0 | 2.42 ± 0.52 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.8 | 2.42 ± 0.53 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.3 | 18.3 | 13.99 ± 2.62 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.4 | 18.8 | 14.00 ± 2.63 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.6 | 18.6 | 14.04 ± 2.63 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.6 | 19.1 | 14.17 ± 2.66 |
| mattcl-py | input-kcen | 25.9 ± 0.8 | 24.5 | 28.9 | 20.78 ± 3.92 |
| mattcl-py | input-mattcl | 25.9 ± 0.7 | 24.8 | 28.9 | 20.78 ± 3.91 |
| mattcl-py | input-pting | 26.2 ± 0.8 | 25.0 | 29.4 | 20.98 ± 3.95 |
| mattcl-py | input-lanjian | 26.5 ± 1.4 | 24.8 | 37.2 | 21.26 ± 4.11 |
| pting | input-kcen | 27.0 ± 0.6 | 26.0 | 30.4 | 21.64 ± 4.06 |
| pting | input-mattcl | 27.1 ± 0.6 | 25.9 | 29.7 | 21.67 ± 4.06 |
| pting | input-pting | 27.2 ± 0.6 | 25.9 | 29.6 | 21.79 ± 4.08 |
| pting | input-lanjian | 27.5 ± 1.1 | 25.8 | 33.6 | 22.01 ± 4.18 |
| kcen | input-pting | 46.7 ± 0.8 | 44.8 | 48.6 | 37.44 ± 6.99 |
| kcen | input-lanjian | 48.6 ± 1.8 | 46.8 | 59.7 | 38.90 ± 7.37 |
| kcen | input-mattcl | 50.5 ± 1.4 | 48.3 | 56.8 | 40.44 ± 7.60 |
| kcen | input-kcen | 50.9 ± 3.5 | 48.6 | 75.8 | 40.75 ± 8.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|