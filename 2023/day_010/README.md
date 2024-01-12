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
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.0 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.2 | 1.00 ± 0.19 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.6 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 0.6 | 2.3 | 1.03 ± 0.23 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.6 | 2.19 ± 0.35 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.4 | 4.9 | 2.20 ± 0.34 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.7 | 2.20 ± 0.38 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.5 | 5.6 | 2.21 ± 0.36 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.5 | 18.7 | 12.36 ± 1.71 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.7 | 18.6 | 12.40 ± 1.71 |
| mattcl-ts | input-kcen | 17.7 ± 0.5 | 16.3 | 19.4 | 12.43 ± 1.73 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.6 | 18.9 | 12.49 ± 1.73 |
| mattcl-py | input-mattcl | 26.0 ± 1.0 | 24.7 | 29.8 | 18.26 ± 2.59 |
| mattcl-py | input-kcen | 26.1 ± 1.0 | 24.6 | 29.1 | 18.33 ± 2.60 |
| mattcl-py | input-pting | 26.3 ± 0.8 | 25.1 | 29.4 | 18.49 ± 2.59 |
| mattcl-py | input-lanjian | 26.6 ± 1.1 | 25.2 | 30.2 | 18.68 ± 2.66 |
| pting | input-kcen | 27.2 ± 0.8 | 25.8 | 30.0 | 19.10 ± 2.67 |
| pting | input-mattcl | 27.3 ± 0.9 | 26.2 | 30.2 | 19.20 ± 2.70 |
| pting | input-lanjian | 27.3 ± 0.7 | 26.1 | 30.0 | 19.20 ± 2.67 |
| pting | input-pting | 27.3 ± 0.8 | 26.1 | 30.0 | 19.22 ± 2.68 |
| kcen | input-pting | 47.6 ± 1.1 | 45.7 | 51.4 | 33.44 ± 4.63 |
| kcen | input-lanjian | 48.4 ± 1.0 | 46.7 | 51.3 | 33.99 ± 4.69 |
| kcen | input-mattcl | 50.5 ± 1.3 | 48.4 | 53.7 | 35.49 ± 4.92 |
| kcen | input-kcen | 50.6 ± 1.2 | 49.0 | 54.9 | 35.57 ± 4.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|