# Day 7 benchmarks

[link to problem](https://adventofcode.com/2023/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 0.7 ± 0.0 | 0.6 | 0.9 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.0 | 0.6 | 0.9 | 1.03 ± 0.10 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.5 | 1.3 | 1.17 ± 0.37 |
| lanjian | input-pting | 0.8 ± 0.3 | 0.5 | 1.3 | 1.26 ± 0.40 |
| lanjian | input-lanjian | 1.2 ± 1.3 | 0.5 | 14.6 | 1.87 ± 1.94 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.5 | 2.03 ± 0.34 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.7 | 2.07 ± 0.28 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 0.6 | 1.6 | 2.07 ± 0.26 |
| mattcl-ts | input-mattcl | 15.4 ± 0.4 | 14.5 | 17.0 | 23.46 ± 1.50 |
| mattcl-ts | input-lanjian | 15.5 ± 0.4 | 14.5 | 16.7 | 23.73 ± 1.51 |
| mattcl-ts | input-pting | 15.8 ± 0.8 | 14.6 | 19.1 | 24.13 ± 1.86 |
| mattcl-ts | input-kcen | 15.9 ± 0.3 | 15.0 | 16.8 | 24.36 ± 1.53 |
| mattcl-py | input-mattcl | 17.2 ± 0.6 | 16.2 | 20.1 | 26.29 ± 1.77 |
| mattcl-py | input-lanjian | 17.3 ± 0.4 | 16.2 | 19.6 | 26.45 ± 1.70 |
| mattcl-py | input-pting | 17.9 ± 0.9 | 16.9 | 22.7 | 27.40 ± 2.15 |
| pting | input-kcen | 18.4 ± 2.8 | 17.0 | 53.1 | 28.13 ± 4.60 |
| pting | input-lanjian | 18.9 ± 3.2 | 16.9 | 28.4 | 28.83 ± 5.13 |
| pting | input-mattcl | 19.1 ± 2.7 | 17.2 | 29.5 | 29.23 ± 4.47 |
| mattcl-py | input-kcen | 20.7 ± 3.1 | 16.7 | 28.4 | 31.64 ± 5.09 |
| pting | input-pting | 20.7 ± 4.9 | 17.3 | 40.3 | 31.67 ± 7.76 |
| kcen | input-mattcl | 21.1 ± 0.6 | 19.9 | 23.6 | 32.17 ± 2.13 |
| kcen | input-pting | 22.0 ± 1.3 | 20.7 | 28.7 | 33.65 ± 2.80 |
| kcen | input-lanjian | 22.6 ± 3.3 | 20.6 | 34.9 | 34.58 ± 5.45 |
| kcen | input-kcen | 25.5 ± 1.1 | 24.4 | 34.5 | 38.94 ± 2.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|