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
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.27 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.27 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.6 | 1.03 ± 0.27 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.27 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.04 ± 0.27 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.27 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.28 |
| lanjian | input-pting | 1.1 ± 0.1 | 0.5 | 1.6 | 1.07 ± 0.26 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.0 | 15.9 | 13.92 ± 2.95 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 14.0 | 15.7 | 13.94 ± 2.96 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 13.9 | 16.2 | 13.96 ± 2.96 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 13.8 | 16.1 | 13.98 ± 2.97 |
| mattcl-ts | input-pting | 15.2 ± 3.6 | 13.9 | 65.3 | 14.15 ± 4.50 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.9 | 19.9 | 15.56 ± 3.34 |
| mattcl-py | input-lanjian | 16.7 ± 0.7 | 15.5 | 19.7 | 15.59 ± 3.36 |
| mattcl-py | input-mattcl | 16.7 ± 0.7 | 15.5 | 20.4 | 15.61 ± 3.36 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.7 | 19.9 | 15.62 ± 3.35 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.8 | 19.8 | 15.64 ± 3.37 |
| pting | input-kcen | 17.2 ± 0.7 | 16.1 | 20.1 | 16.09 ± 3.45 |
| pting | input-mattcl | 17.3 ± 0.6 | 15.8 | 20.5 | 16.12 ± 3.44 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.3 | 20.6 | 16.12 ± 3.46 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.5 | 16.13 ± 3.46 |
| pting | input-pting | 17.4 ± 0.8 | 16.3 | 20.8 | 16.20 ± 3.50 |
| kcen | input-lanjian | 20.5 ± 0.7 | 19.4 | 23.3 | 19.11 ± 4.09 |
| kcen | input-pting | 20.5 ± 0.8 | 19.5 | 23.3 | 19.16 ± 4.11 |
| kcen | input-kcen | 20.6 ± 0.8 | 19.3 | 23.7 | 19.20 ± 4.13 |
| kcen | input-chancalan | 20.6 ± 2.0 | 19.4 | 43.0 | 19.23 ± 4.47 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.5 | 24.1 | 19.25 ± 4.12 |
| chancalan | input-kcen | 24.5 ± 0.6 | 23.5 | 27.7 | 22.86 ± 4.86 |
| chancalan | input-lanjian | 24.6 ± 0.7 | 23.5 | 27.2 | 22.93 ± 4.88 |
| chancalan | input-chancalan | 24.6 ± 0.7 | 23.1 | 26.8 | 22.99 ± 4.89 |
| chancalan | input-mattcl | 24.8 ± 0.9 | 23.3 | 28.0 | 23.11 ± 4.95 |
| chancalan | input-pting | 25.0 ± 3.6 | 23.6 | 63.6 | 23.29 ± 5.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|