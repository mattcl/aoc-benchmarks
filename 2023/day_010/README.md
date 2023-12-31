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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.0 | 1.03 ± 0.20 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.1 | 1.03 ± 0.20 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.1 | 1.07 ± 0.21 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 2.32 ± 0.38 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.5 | 2.33 ± 0.38 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.5 | 6.3 | 2.33 ± 0.41 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.4 | 5.8 | 2.37 ± 0.43 |
| mattcl-ts | input-pting | 17.6 ± 0.5 | 16.3 | 20.0 | 13.23 ± 1.82 |
| mattcl-ts | input-mattcl | 17.6 ± 0.5 | 16.4 | 18.7 | 13.24 ± 1.82 |
| mattcl-ts | input-kcen | 17.7 ± 0.4 | 16.7 | 18.9 | 13.32 ± 1.82 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.7 | 19.0 | 13.36 ± 1.83 |
| mattcl-py | input-kcen | 25.7 ± 0.9 | 24.2 | 29.1 | 19.36 ± 2.70 |
| mattcl-py | input-mattcl | 26.1 ± 2.4 | 24.5 | 50.2 | 19.66 ± 3.23 |
| mattcl-py | input-pting | 26.2 ± 0.9 | 24.9 | 29.4 | 19.67 ± 2.74 |
| mattcl-py | input-lanjian | 26.2 ± 0.8 | 24.8 | 30.0 | 19.69 ± 2.73 |
| pting | input-kcen | 27.1 ± 0.8 | 26.0 | 31.0 | 20.40 ± 2.82 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.1 | 30.1 | 20.44 ± 2.83 |
| pting | input-lanjian | 27.3 ± 0.9 | 26.0 | 29.9 | 20.55 ± 2.85 |
| pting | input-pting | 27.5 ± 0.9 | 26.0 | 30.3 | 20.66 ± 2.88 |
| kcen | input-pting | 47.4 ± 1.3 | 45.3 | 51.1 | 35.65 ± 4.90 |
| kcen | input-lanjian | 49.1 ± 5.1 | 46.5 | 85.5 | 36.97 ± 6.30 |
| kcen | input-mattcl | 50.3 ± 1.2 | 48.4 | 53.4 | 37.87 ± 5.19 |
| kcen | input-kcen | 50.7 ± 1.3 | 48.7 | 54.4 | 38.11 ± 5.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|