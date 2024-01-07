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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 ± 0.24 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.4 | 1.3 | 1.03 ± 0.21 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.6 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.24 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.4 | 1.6 | 1.04 ± 0.22 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.9 | 15.7 | 12.90 ± 2.29 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.7 | 15.8 | 12.90 ± 2.29 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.7 | 15.9 | 12.90 ± 2.29 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 14.0 | 15.8 | 12.92 ± 2.29 |
| mattcl-ts | input-lanjian | 15.2 ± 3.8 | 14.1 | 60.6 | 13.24 ± 4.05 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.6 | 19.4 | 14.34 ± 2.58 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.7 | 19.9 | 14.37 ± 2.58 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.7 | 20.0 | 14.39 ± 2.58 |
| mattcl-py | input-chancalan | 16.6 ± 0.7 | 15.4 | 20.2 | 14.41 ± 2.61 |
| mattcl-py | input-mattcl | 16.6 ± 0.8 | 15.5 | 19.4 | 14.46 ± 2.63 |
| pting | input-chancalan | 16.9 ± 0.7 | 15.9 | 19.7 | 14.72 ± 2.66 |
| pting | input-kcen | 16.9 ± 0.6 | 16.0 | 20.3 | 14.72 ± 2.64 |
| pting | input-lanjian | 17.0 ± 0.6 | 15.8 | 19.6 | 14.80 ± 2.66 |
| pting | input-mattcl | 17.1 ± 0.7 | 16.2 | 20.2 | 14.86 ± 2.68 |
| pting | input-pting | 17.1 ± 0.8 | 16.1 | 20.5 | 14.88 ± 2.72 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.2 | 22.8 | 17.57 ± 3.14 |
| kcen | input-chancalan | 20.3 ± 0.8 | 19.3 | 23.1 | 17.67 ± 3.18 |
| kcen | input-mattcl | 20.3 ± 0.8 | 19.3 | 23.9 | 17.67 ± 3.18 |
| kcen | input-lanjian | 20.5 ± 1.2 | 19.3 | 30.7 | 17.81 ± 3.30 |
| kcen | input-pting | 20.5 ± 3.5 | 19.1 | 61.1 | 17.86 ± 4.35 |
| chancalan | input-mattcl | 24.3 ± 0.7 | 23.4 | 27.4 | 21.16 ± 3.77 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.4 | 28.1 | 21.18 ± 3.80 |
| chancalan | input-chancalan | 24.4 ± 0.8 | 23.2 | 27.4 | 21.23 ± 3.80 |
| chancalan | input-pting | 24.5 ± 0.7 | 23.5 | 27.4 | 21.28 ± 3.79 |
| chancalan | input-lanjian | 24.6 ± 1.0 | 23.4 | 27.7 | 21.42 ± 3.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|