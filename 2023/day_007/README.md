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
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 ± 0.19 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.9 | 1.01 ± 0.18 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.17 |
| lanjian | input-chancalan | 1.3 ± 0.1 | 0.7 | 2.1 | 1.02 ± 0.16 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 2.1 | 1.02 ± 0.18 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 1.3 ± 0.1 | 0.8 | 1.5 | 1.03 ± 0.14 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.17 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.1 | 16.2 | 11.57 ± 1.38 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.2 | 16.4 | 11.58 ± 1.39 |
| mattcl-ts | input-kcen | 15.2 ± 0.3 | 14.4 | 16.1 | 11.62 ± 1.38 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 13.9 | 16.1 | 11.64 ± 1.40 |
| mattcl-ts | input-lanjian | 15.7 ± 4.1 | 14.1 | 56.3 | 11.99 ± 3.45 |
| mattcl-py | input-kcen | 16.9 ± 0.6 | 15.6 | 20.1 | 12.90 ± 1.58 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 15.5 | 19.9 | 12.92 ± 1.60 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 15.8 | 19.8 | 12.93 ± 1.59 |
| mattcl-py | input-lanjian | 16.9 ± 0.7 | 15.7 | 19.8 | 12.93 ± 1.60 |
| mattcl-py | input-chancalan | 16.9 ± 0.6 | 15.7 | 19.5 | 12.95 ± 1.59 |
| pting | input-pting | 17.4 ± 0.6 | 16.3 | 19.9 | 13.28 ± 1.62 |
| pting | input-chancalan | 17.5 ± 0.7 | 15.9 | 20.5 | 13.35 ± 1.66 |
| pting | input-mattcl | 17.5 ± 0.7 | 16.5 | 20.8 | 13.36 ± 1.66 |
| pting | input-kcen | 17.5 ± 0.8 | 15.8 | 20.6 | 13.36 ± 1.68 |
| pting | input-lanjian | 17.5 ± 0.8 | 16.4 | 21.1 | 13.39 ± 1.67 |
| kcen | input-mattcl | 20.7 ± 0.6 | 19.6 | 23.0 | 15.82 ± 1.91 |
| kcen | input-pting | 20.7 ± 0.6 | 19.6 | 23.2 | 15.83 ± 1.92 |
| kcen | input-lanjian | 20.7 ± 0.7 | 19.6 | 23.9 | 15.84 ± 1.92 |
| kcen | input-kcen | 20.8 ± 0.6 | 20.0 | 23.4 | 15.89 ± 1.92 |
| kcen | input-chancalan | 20.9 ± 3.3 | 19.7 | 59.8 | 15.99 ± 3.15 |
| chancalan | input-lanjian | 24.7 ± 0.8 | 23.4 | 27.8 | 18.92 ± 2.31 |
| chancalan | input-chancalan | 24.8 ± 0.9 | 23.6 | 27.9 | 18.96 ± 2.31 |
| chancalan | input-kcen | 24.9 ± 0.9 | 23.7 | 28.0 | 19.01 ± 2.32 |
| chancalan | input-pting | 24.9 ± 0.8 | 23.5 | 27.6 | 19.04 ± 2.32 |
| chancalan | input-mattcl | 25.4 ± 3.7 | 23.1 | 52.0 | 19.39 ± 3.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|