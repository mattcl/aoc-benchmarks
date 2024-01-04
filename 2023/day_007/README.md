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
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 1.6 | 1.01 ± 0.24 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.23 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.05 ± 0.25 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.7 | 2.0 | 1.08 ± 0.24 |
| mattcl | input-chancalan | 1.2 ± 1.8 | 0.3 | 25.9 | 1.09 ± 1.59 |
| mattcl-ts | input-pting | 14.7 ± 0.3 | 13.8 | 16.0 | 13.16 ± 2.35 |
| mattcl-ts | input-chancalan | 14.7 ± 0.3 | 13.8 | 15.9 | 13.21 ± 2.36 |
| mattcl-ts | input-mattcl | 14.7 ± 0.3 | 13.9 | 15.7 | 13.21 ± 2.36 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 14.0 | 15.9 | 13.23 ± 2.36 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 13.8 | 16.0 | 13.23 ± 2.37 |
| mattcl-py | input-lanjian | 16.4 ± 0.6 | 15.7 | 19.4 | 14.69 ± 2.65 |
| mattcl-py | input-mattcl | 16.4 ± 0.6 | 15.5 | 19.4 | 14.70 ± 2.66 |
| mattcl-py | input-chancalan | 16.4 ± 0.5 | 15.7 | 19.2 | 14.70 ± 2.64 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.5 | 20.1 | 14.72 ± 2.67 |
| mattcl-py | input-pting | 16.7 ± 3.3 | 15.5 | 60.0 | 14.92 ± 3.96 |
| pting | input-pting | 16.9 ± 0.6 | 15.7 | 20.0 | 15.11 ± 2.74 |
| pting | input-kcen | 16.9 ± 0.7 | 15.8 | 20.0 | 15.12 ± 2.74 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.0 | 19.8 | 15.13 ± 2.74 |
| pting | input-chancalan | 16.9 ± 0.6 | 16.1 | 19.4 | 15.16 ± 2.73 |
| pting | input-lanjian | 16.9 ± 0.7 | 15.8 | 20.7 | 15.16 ± 2.76 |
| kcen | input-chancalan | 20.2 ± 0.7 | 19.1 | 22.5 | 18.07 ± 3.25 |
| kcen | input-pting | 20.2 ± 0.7 | 19.3 | 23.2 | 18.11 ± 3.27 |
| kcen | input-kcen | 20.2 ± 0.7 | 19.4 | 23.2 | 18.12 ± 3.26 |
| kcen | input-mattcl | 20.2 ± 0.8 | 19.0 | 23.1 | 18.14 ± 3.30 |
| kcen | input-lanjian | 20.3 ± 0.8 | 19.1 | 23.6 | 18.19 ± 3.31 |
| chancalan | input-pting | 24.2 ± 0.7 | 22.9 | 27.6 | 21.64 ± 3.89 |
| chancalan | input-chancalan | 24.3 ± 0.8 | 23.0 | 26.9 | 21.76 ± 3.91 |
| chancalan | input-mattcl | 24.3 ± 0.8 | 23.1 | 27.0 | 21.78 ± 3.93 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.5 | 27.6 | 21.86 ± 3.94 |
| chancalan | input-lanjian | 24.5 ± 0.8 | 23.1 | 27.2 | 21.94 ± 3.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|