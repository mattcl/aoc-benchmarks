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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.8 | 1.6 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.4 | 1.03 ± 0.24 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.8 | 2.36 ± 0.39 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 4.0 | 2.38 ± 0.36 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.9 | 2.39 ± 0.39 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.9 | 2.40 ± 0.39 |
| mattcl-ts | input-mattcl | 17.4 ± 0.4 | 16.0 | 19.3 | 13.26 ± 1.91 |
| mattcl-ts | input-kcen | 17.4 ± 0.4 | 16.5 | 18.4 | 13.28 ± 1.90 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.5 | 18.6 | 13.29 ± 1.90 |
| mattcl-ts | input-lanjian | 17.5 ± 0.3 | 16.6 | 18.6 | 13.37 ± 1.91 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.4 | 29.3 | 19.47 ± 2.84 |
| mattcl-py | input-mattcl | 25.7 ± 0.8 | 24.7 | 28.8 | 19.60 ± 2.84 |
| mattcl-py | input-lanjian | 26.0 ± 0.7 | 24.6 | 30.2 | 19.82 ± 2.86 |
| mattcl-py | input-pting | 26.3 ± 1.0 | 24.9 | 29.4 | 20.04 ± 2.94 |
| pting | input-kcen | 26.8 ± 0.8 | 25.9 | 29.7 | 20.45 ± 2.96 |
| pting | input-mattcl | 27.0 ± 0.7 | 25.8 | 30.3 | 20.60 ± 2.97 |
| pting | input-pting | 27.2 ± 0.8 | 26.1 | 30.0 | 20.80 ± 3.01 |
| pting | input-lanjian | 28.0 ± 6.6 | 26.1 | 83.4 | 21.36 ± 5.88 |
| kcen | input-pting | 47.4 ± 1.1 | 45.8 | 51.8 | 36.18 ± 5.19 |
| kcen | input-lanjian | 48.0 ± 1.0 | 46.6 | 51.3 | 36.65 ± 5.25 |
| kcen | input-mattcl | 50.2 ± 1.1 | 48.3 | 52.9 | 38.30 ± 5.49 |
| kcen | input-kcen | 50.2 ± 1.2 | 48.7 | 54.3 | 38.36 ± 5.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|