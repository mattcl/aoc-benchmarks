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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.6 | 1.00 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.8 | 1.00 ± 0.24 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.7 | 1.6 | 1.04 ± 0.21 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.7 | 1.8 | 1.04 ± 0.22 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.23 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.7 | 1.04 ± 0.23 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 2.0 | 1.05 ± 0.24 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 13.9 | 16.1 | 12.29 ± 2.19 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.8 | 15.8 | 12.30 ± 2.19 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 14.0 | 15.7 | 12.31 ± 2.20 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 13.9 | 16.0 | 12.34 ± 2.20 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 14.0 | 16.1 | 12.36 ± 2.21 |
| mattcl-py | input-mattcl | 16.4 ± 0.5 | 15.5 | 19.1 | 13.65 ± 2.45 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.5 | 18.9 | 13.67 ± 2.46 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.3 | 19.6 | 13.69 ± 2.47 |
| mattcl-py | input-lanjian | 16.6 ± 0.8 | 15.6 | 20.0 | 13.76 ± 2.51 |
| pting | input-mattcl | 16.9 ± 0.6 | 15.9 | 20.2 | 13.99 ± 2.53 |
| pting | input-kcen | 16.9 ± 0.7 | 16.0 | 19.8 | 14.05 ± 2.54 |
| pting | input-chancalan | 16.9 ± 0.8 | 15.8 | 20.6 | 14.06 ± 2.56 |
| mattcl-py | input-pting | 17.0 ± 4.7 | 15.4 | 61.2 | 14.09 ± 4.63 |
| pting | input-pting | 17.0 ± 0.7 | 16.1 | 20.7 | 14.09 ± 2.55 |
| pting | input-lanjian | 17.1 ± 0.8 | 16.1 | 19.7 | 14.17 ± 2.58 |
| kcen | input-kcen | 20.1 ± 0.7 | 18.9 | 22.7 | 16.71 ± 3.01 |
| kcen | input-chancalan | 20.2 ± 0.7 | 18.9 | 22.4 | 16.77 ± 3.01 |
| kcen | input-mattcl | 20.2 ± 0.6 | 19.2 | 23.3 | 16.79 ± 3.01 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.3 | 23.7 | 16.85 ± 3.04 |
| kcen | input-pting | 20.6 ± 3.0 | 18.9 | 55.7 | 17.06 ± 3.93 |
| chancalan | input-pting | 24.3 ± 0.7 | 23.3 | 27.5 | 20.19 ± 3.62 |
| chancalan | input-mattcl | 24.3 ± 0.8 | 23.3 | 27.1 | 20.19 ± 3.62 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.4 | 27.3 | 20.26 ± 3.64 |
| chancalan | input-lanjian | 24.4 ± 0.8 | 23.1 | 27.1 | 20.26 ± 3.64 |
| chancalan | input-chancalan | 25.3 ± 7.0 | 23.0 | 83.0 | 21.02 ± 6.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|