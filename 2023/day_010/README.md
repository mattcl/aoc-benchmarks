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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.0 | 1.05 ± 0.24 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.9 | 1.05 ± 0.24 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 2.0 | 1.06 ± 0.22 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 3.5 | 2.42 ± 0.40 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.4 | 3.8 | 2.46 ± 0.40 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.5 | 2.46 ± 0.44 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.4 | 5.9 | 2.53 ± 0.50 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.6 | 18.6 | 14.38 ± 2.24 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.9 | 19.1 | 14.39 ± 2.24 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.2 | 19.0 | 14.40 ± 2.24 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.6 | 19.1 | 14.51 ± 2.26 |
| mattcl-py | input-kcen | 25.9 ± 0.8 | 24.8 | 29.2 | 21.18 ± 3.33 |
| mattcl-py | input-mattcl | 26.0 ± 0.8 | 24.8 | 29.7 | 21.27 ± 3.34 |
| mattcl-py | input-pting | 26.4 ± 0.9 | 25.0 | 29.3 | 21.58 ± 3.40 |
| mattcl-py | input-lanjian | 26.5 ± 0.9 | 25.2 | 29.3 | 21.69 ± 3.42 |
| pting | input-kcen | 27.0 ± 0.7 | 25.8 | 29.5 | 22.07 ± 3.45 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.2 | 30.9 | 22.29 ± 3.49 |
| pting | input-pting | 27.2 ± 0.7 | 25.7 | 30.2 | 22.30 ± 3.48 |
| pting | input-lanjian | 27.3 ± 0.8 | 26.4 | 29.6 | 22.36 ± 3.50 |
| kcen | input-pting | 47.4 ± 1.0 | 45.5 | 51.3 | 38.77 ± 6.03 |
| kcen | input-lanjian | 48.5 ± 2.0 | 46.4 | 62.0 | 39.70 ± 6.34 |
| kcen | input-kcen | 50.6 ± 1.4 | 48.7 | 57.3 | 41.40 ± 6.48 |
| kcen | input-mattcl | 50.7 ± 1.3 | 49.1 | 54.3 | 41.47 ± 6.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|