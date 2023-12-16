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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.19 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 1.8 | 1.02 ± 0.18 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.4 | 3.0 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.6 | 5.7 | 2.33 ± 0.37 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.4 | 4.8 | 2.33 ± 0.34 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.0 | 2.34 ± 0.36 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 6.1 | 2.35 ± 0.39 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.5 | 18.9 | 13.27 ± 1.76 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.4 | 18.7 | 13.29 ± 1.76 |
| mattcl-ts | input-kcen | 17.7 ± 0.5 | 16.9 | 19.1 | 13.33 ± 1.77 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.8 | 19.0 | 13.40 ± 1.77 |
| mattcl-py | input-kcen | 25.7 ± 0.6 | 24.6 | 28.4 | 19.42 ± 2.57 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.9 | 29.0 | 19.72 ± 2.65 |
| mattcl-py | input-pting | 26.3 ± 1.0 | 25.2 | 29.5 | 19.87 ± 2.69 |
| mattcl-py | input-lanjian | 26.4 ± 1.0 | 25.0 | 30.1 | 19.95 ± 2.71 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.0 | 30.1 | 20.55 ± 2.74 |
| pting | input-kcen | 27.3 ± 1.0 | 25.9 | 30.4 | 20.57 ± 2.78 |
| pting | input-lanjian | 27.3 ± 0.6 | 26.3 | 29.8 | 20.61 ± 2.73 |
| pting | input-pting | 27.3 ± 0.7 | 26.3 | 30.3 | 20.63 ± 2.75 |
| kcen | input-pting | 47.3 ± 0.9 | 45.8 | 49.9 | 35.68 ± 4.70 |
| kcen | input-lanjian | 48.6 ± 1.1 | 46.9 | 51.5 | 36.66 ± 4.85 |
| kcen | input-mattcl | 50.4 ± 1.3 | 48.6 | 56.2 | 37.99 ± 5.04 |
| kcen | input-kcen | 50.5 ± 1.3 | 48.7 | 54.4 | 38.12 ± 5.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|