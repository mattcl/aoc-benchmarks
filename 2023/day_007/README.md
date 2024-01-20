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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.21 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.9 | 1.01 ± 0.21 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.7 | 1.02 ± 0.19 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.5 | 1.7 | 1.02 ± 0.20 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.21 |
| mattcl-ts | input-lanjian | 14.2 ± 0.4 | 13.2 | 15.5 | 12.22 ± 1.87 |
| mattcl-ts | input-mattcl | 14.2 ± 0.4 | 13.0 | 16.0 | 12.23 ± 1.88 |
| mattcl-ts | input-chancalan | 14.2 ± 0.4 | 13.2 | 15.1 | 12.24 ± 1.87 |
| mattcl-ts | input-kcen | 14.3 ± 0.4 | 13.2 | 15.2 | 12.28 ± 1.88 |
| mattcl-ts | input-pting | 14.3 ± 0.4 | 13.1 | 15.7 | 12.33 ± 1.89 |
| mattcl-py | input-lanjian | 16.7 ± 0.7 | 15.3 | 20.4 | 14.38 ± 2.25 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.6 | 19.4 | 14.42 ± 2.23 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.4 | 19.9 | 14.42 ± 2.25 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.5 | 19.7 | 14.43 ± 2.25 |
| mattcl-py | input-mattcl | 16.8 ± 0.6 | 16.0 | 19.2 | 14.47 ± 2.23 |
| pting | input-kcen | 17.3 ± 0.6 | 15.9 | 20.2 | 14.90 ± 2.30 |
| pting | input-pting | 17.4 ± 0.6 | 16.3 | 20.1 | 14.96 ± 2.30 |
| pting | input-chancalan | 17.4 ± 0.7 | 16.3 | 20.6 | 14.98 ± 2.33 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.2 | 20.7 | 14.99 ± 2.34 |
| pting | input-lanjian | 17.5 ± 0.8 | 16.3 | 20.7 | 15.06 ± 2.36 |
| kcen | input-pting | 20.5 ± 0.8 | 19.1 | 24.0 | 17.62 ± 2.73 |
| kcen | input-kcen | 20.5 ± 0.7 | 19.5 | 23.8 | 17.66 ± 2.72 |
| kcen | input-lanjian | 20.5 ± 0.8 | 19.2 | 23.4 | 17.67 ± 2.73 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.5 | 24.0 | 17.72 ± 2.74 |
| kcen | input-chancalan | 20.7 ± 0.8 | 19.5 | 24.2 | 17.81 ± 2.76 |
| chancalan | input-lanjian | 24.5 ± 0.7 | 23.1 | 27.3 | 21.08 ± 3.23 |
| chancalan | input-chancalan | 24.5 ± 0.6 | 23.0 | 27.2 | 21.08 ± 3.21 |
| chancalan | input-pting | 24.5 ± 0.7 | 23.0 | 26.4 | 21.09 ± 3.22 |
| chancalan | input-kcen | 24.6 ± 0.7 | 23.5 | 28.1 | 21.20 ± 3.25 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 23.1 | 27.5 | 21.21 ± 3.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|