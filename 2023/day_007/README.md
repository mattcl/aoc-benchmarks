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
| lanjian | input-kcen | 1.1 ± 0.3 | 0.2 | 1.4 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.7 | 1.07 ± 0.34 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.7 | 1.07 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.2 | 1.6 | 1.09 ± 0.32 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.5 | 1.7 | 1.10 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.10 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.6 | 1.6 | 1.10 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.10 ± 0.33 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 2.0 | 1.14 ± 0.34 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.3 | 15.9 | 14.14 ± 3.60 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.2 | 16.0 | 14.18 ± 3.60 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 13.9 | 16.1 | 14.22 ± 3.62 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.0 | 16.5 | 14.25 ± 3.63 |
| mattcl-ts | input-pting | 15.5 ± 0.5 | 14.4 | 18.2 | 14.61 ± 3.73 |
| mattcl-py | input-lanjian | 16.8 ± 0.6 | 15.9 | 19.4 | 15.81 ± 4.04 |
| mattcl-py | input-chancalan | 16.9 ± 0.7 | 15.9 | 20.7 | 15.90 ± 4.08 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 15.7 | 19.7 | 15.92 ± 4.08 |
| mattcl-py | input-mattcl | 16.9 ± 0.8 | 15.8 | 19.9 | 15.92 ± 4.10 |
| pting | input-lanjian | 17.3 ± 0.7 | 15.9 | 20.1 | 16.29 ± 4.18 |
| pting | input-chancalan | 17.3 ± 0.6 | 16.4 | 20.5 | 16.31 ± 4.17 |
| mattcl-py | input-kcen | 17.3 ± 4.4 | 15.5 | 65.0 | 16.34 ± 5.89 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.2 | 20.5 | 16.36 ± 4.18 |
| pting | input-kcen | 17.4 ± 0.6 | 16.5 | 21.6 | 16.39 ± 4.20 |
| pting | input-pting | 18.1 ± 0.4 | 16.7 | 19.3 | 17.07 ± 4.34 |
| kcen | input-lanjian | 20.4 ± 0.5 | 19.3 | 22.5 | 19.23 ± 4.90 |
| kcen | input-chancalan | 20.5 ± 0.7 | 19.0 | 24.1 | 19.32 ± 4.94 |
| kcen | input-pting | 20.5 ± 0.8 | 19.4 | 23.8 | 19.35 ± 4.95 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.4 | 23.5 | 19.38 ± 4.95 |
| kcen | input-kcen | 20.9 ± 2.9 | 19.5 | 54.1 | 19.68 ± 5.67 |
| chancalan | input-chancalan | 24.5 ± 0.6 | 23.4 | 26.7 | 23.14 ± 5.89 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 23.0 | 27.7 | 23.22 ± 5.93 |
| chancalan | input-pting | 24.7 ± 0.9 | 23.6 | 27.8 | 23.30 ± 5.97 |
| chancalan | input-lanjian | 24.7 ± 0.8 | 23.5 | 27.2 | 23.34 ± 5.95 |
| chancalan | input-kcen | 25.0 ± 2.5 | 23.0 | 51.0 | 23.60 ± 6.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|