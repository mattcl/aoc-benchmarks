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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.9 | 1.00 ± 0.24 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.22 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.22 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.24 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.22 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.6 | 1.6 | 1.04 ± 0.19 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.22 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.6 | 15.7 | 13.25 ± 2.04 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.9 | 15.9 | 13.26 ± 2.04 |
| mattcl-ts | input-mattcl | 14.8 ± 0.3 | 13.9 | 15.7 | 13.28 ± 2.04 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 14.0 | 15.9 | 13.29 ± 2.04 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 13.8 | 15.8 | 13.34 ± 2.05 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.8 | 19.7 | 14.79 ± 2.30 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.4 | 19.5 | 14.82 ± 2.32 |
| mattcl-py | input-chancalan | 16.5 ± 0.7 | 15.5 | 19.1 | 14.83 ± 2.33 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.9 | 19.5 | 14.83 ± 2.31 |
| mattcl-py | input-kcen | 16.6 ± 0.8 | 15.3 | 19.7 | 14.90 ± 2.36 |
| pting | input-lanjian | 16.9 ± 0.6 | 16.0 | 20.7 | 15.18 ± 2.36 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.0 | 20.0 | 15.22 ± 2.37 |
| pting | input-kcen | 17.0 ± 0.7 | 16.2 | 20.2 | 15.23 ± 2.39 |
| pting | input-chancalan | 17.0 ± 0.7 | 15.8 | 20.1 | 15.27 ± 2.41 |
| pting | input-pting | 17.1 ± 0.7 | 15.8 | 20.1 | 15.31 ± 2.40 |
| kcen | input-kcen | 20.2 ± 0.5 | 19.3 | 22.6 | 18.08 ± 2.78 |
| kcen | input-chancalan | 20.4 ± 0.8 | 19.0 | 23.4 | 18.24 ± 2.85 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.2 | 23.0 | 18.26 ± 2.83 |
| kcen | input-lanjian | 20.5 ± 0.8 | 19.4 | 23.1 | 18.36 ± 2.89 |
| kcen | input-pting | 20.8 ± 3.4 | 19.3 | 61.0 | 18.60 ± 4.18 |
| chancalan | input-lanjian | 24.3 ± 0.6 | 23.2 | 26.2 | 21.79 ± 3.35 |
| chancalan | input-pting | 24.4 ± 0.7 | 23.2 | 27.3 | 21.88 ± 3.38 |
| chancalan | input-mattcl | 24.5 ± 0.7 | 23.4 | 27.2 | 21.96 ± 3.39 |
| chancalan | input-chancalan | 24.6 ± 1.0 | 23.7 | 27.7 | 22.06 ± 3.46 |
| chancalan | input-kcen | 25.2 ± 5.9 | 23.2 | 74.9 | 22.61 ± 6.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|