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
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 1.7 | 1.00 ± 0.20 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.1 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.02 ± 0.21 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.4 | 5.7 | 2.26 ± 0.38 |
| lanjian | input-kcen | 3.2 ± 0.3 | 2.3 | 6.2 | 2.28 ± 0.40 |
| lanjian | input-lanjian | 3.2 ± 0.2 | 2.5 | 4.9 | 2.28 ± 0.37 |
| lanjian | input-mattcl | 3.2 ± 0.3 | 2.7 | 5.9 | 2.29 ± 0.41 |
| mattcl-ts | input-mattcl | 17.3 ± 0.3 | 16.3 | 18.2 | 12.48 ± 1.91 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.3 | 18.6 | 12.53 ± 1.92 |
| mattcl-ts | input-kcen | 17.4 ± 0.4 | 16.3 | 18.6 | 12.54 ± 1.92 |
| mattcl-ts | input-lanjian | 18.2 ± 5.3 | 16.7 | 69.6 | 13.11 ± 4.28 |
| mattcl-py | input-kcen | 25.4 ± 0.7 | 24.4 | 28.3 | 18.32 ± 2.82 |
| mattcl-py | input-mattcl | 25.6 ± 0.7 | 24.7 | 28.5 | 18.42 ± 2.84 |
| mattcl-py | input-lanjian | 25.9 ± 0.8 | 24.7 | 29.9 | 18.61 ± 2.88 |
| mattcl-py | input-pting | 26.0 ± 0.8 | 24.7 | 28.6 | 18.69 ± 2.90 |
| pting | input-kcen | 26.7 ± 0.8 | 25.6 | 29.6 | 19.21 ± 2.97 |
| pting | input-pting | 27.0 ± 0.8 | 26.0 | 30.0 | 19.46 ± 3.01 |
| pting | input-lanjian | 27.1 ± 0.9 | 25.8 | 30.2 | 19.53 ± 3.03 |
| pting | input-mattcl | 27.1 ± 1.0 | 25.8 | 29.6 | 19.54 ± 3.05 |
| kcen | input-pting | 46.8 ± 1.2 | 45.4 | 52.5 | 33.69 ± 5.19 |
| kcen | input-lanjian | 47.7 ± 1.4 | 46.1 | 56.0 | 34.37 ± 5.31 |
| kcen | input-mattcl | 49.8 ± 1.1 | 48.1 | 52.8 | 35.85 ± 5.49 |
| kcen | input-kcen | 50.0 ± 1.2 | 48.4 | 54.3 | 35.99 ± 5.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|