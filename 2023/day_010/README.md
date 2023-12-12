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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.4 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.6 | 1.00 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.9 | 1.03 ± 0.22 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.0 | 1.13 ± 0.24 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.1 | 4.6 | 2.56 ± 0.41 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 3.6 | 2.56 ± 0.39 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 4.2 | 2.57 ± 0.39 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 5.6 | 2.60 ± 0.43 |
| mattcl-ts | input-mattcl | 17.4 ± 0.5 | 16.6 | 19.0 | 15.06 ± 2.14 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.6 | 18.5 | 15.07 ± 2.13 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.0 | 18.6 | 15.10 ± 2.14 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.6 | 19.0 | 15.25 ± 2.16 |
| mattcl-py | input-kcen | 25.8 ± 0.8 | 24.5 | 28.3 | 22.23 ± 3.18 |
| mattcl-py | input-mattcl | 25.8 ± 0.8 | 24.4 | 29.5 | 22.30 ± 3.19 |
| mattcl-py | input-pting | 26.2 ± 1.0 | 24.8 | 29.5 | 22.65 ± 3.27 |
| mattcl-py | input-lanjian | 26.3 ± 1.0 | 24.7 | 29.6 | 22.66 ± 3.28 |
| pting | input-kcen | 26.9 ± 0.8 | 25.2 | 29.4 | 23.24 ± 3.32 |
| pting | input-mattcl | 27.0 ± 0.8 | 25.9 | 29.5 | 23.32 ± 3.33 |
| pting | input-lanjian | 27.1 ± 0.7 | 25.8 | 30.2 | 23.39 ± 3.33 |
| pting | input-pting | 27.2 ± 0.8 | 26.2 | 30.2 | 23.44 ± 3.35 |
| kcen | input-pting | 46.8 ± 0.9 | 45.3 | 50.0 | 40.43 ± 5.70 |
| kcen | input-lanjian | 48.0 ± 1.2 | 46.2 | 51.6 | 41.40 ± 5.88 |
| kcen | input-kcen | 50.2 ± 1.1 | 47.9 | 53.4 | 43.36 ± 6.13 |
| kcen | input-mattcl | 50.3 ± 1.4 | 48.2 | 55.9 | 43.41 ± 6.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|