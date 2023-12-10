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
| mattcl | input-lanjian | 0.5 ± 0.0 | 0.4 | 0.6 | 1.00 |
| lanjian | input-lanjian | 0.5 ± 0.1 | 0.4 | 1.0 | 1.05 ± 0.14 |
| mattcl | input-kcen | 0.6 ± 0.1 | 0.4 | 1.0 | 1.18 ± 0.20 |
| lanjian | input-kcen | 0.6 ± 0.1 | 0.4 | 1.1 | 1.20 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.4 | 2.34 ± 0.43 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.4 | 2.36 ± 0.50 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.4 | 2.45 ± 0.45 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.5 | 2.50 ± 0.45 |
| mattcl-ts | input-pting | 15.5 ± 0.8 | 14.3 | 19.2 | 31.59 ± 3.08 |
| mattcl-ts | input-lanjian | 17.2 ± 0.6 | 16.2 | 20.5 | 35.06 ± 3.18 |
| mattcl-ts | input-mattcl | 17.3 ± 9.3 | 14.3 | 91.5 | 35.14 ± 19.19 |
| mattcl-py | input-mattcl | 17.6 ± 0.5 | 16.6 | 20.1 | 35.86 ± 3.21 |
| pting | input-mattcl | 17.6 ± 0.5 | 16.6 | 19.9 | 35.86 ± 3.16 |
| mattcl-py | input-pting | 18.0 ± 2.6 | 16.3 | 31.9 | 36.54 ± 6.11 |
| pting | input-pting | 18.4 ± 1.0 | 16.9 | 23.2 | 37.36 ± 3.80 |
| mattcl-ts | input-kcen | 18.7 ± 1.2 | 16.8 | 27.4 | 37.94 ± 4.03 |
| mattcl-py | input-lanjian | 20.3 ± 0.5 | 19.3 | 21.9 | 41.24 ± 3.61 |
| pting | input-lanjian | 21.6 ± 3.0 | 17.0 | 29.4 | 43.86 ± 7.16 |
| kcen | input-mattcl | 21.8 ± 0.7 | 20.5 | 24.2 | 44.32 ± 3.97 |
| mattcl-py | input-kcen | 22.1 ± 0.3 | 21.0 | 22.8 | 44.91 ± 3.85 |
| kcen | input-pting | 22.1 ± 5.7 | 19.9 | 70.2 | 45.05 ± 12.28 |
| pting | input-kcen | 23.4 ± 2.7 | 19.5 | 35.7 | 47.51 ± 6.76 |
| kcen | input-lanjian | 25.3 ± 0.6 | 24.2 | 27.0 | 51.55 ± 4.52 |
| kcen | input-kcen | 27.5 ± 2.7 | 19.9 | 36.5 | 56.04 ± 7.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|