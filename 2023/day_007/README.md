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
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.6 | 1.6 | 1.05 ± 0.21 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.8 | 1.05 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 2.0 | 1.07 ± 0.26 |
| lanjian | input-kcen | 1.3 ± 3.7 | 0.2 | 52.8 | 1.13 ± 3.26 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.8 | 15.7 | 13.08 ± 2.13 |
| mattcl-ts | input-kcen | 14.8 ± 0.3 | 14.0 | 15.9 | 13.10 ± 2.13 |
| mattcl-ts | input-pting | 14.8 ± 0.3 | 14.0 | 16.0 | 13.11 ± 2.13 |
| mattcl-ts | input-lanjian | 14.8 ± 0.3 | 14.0 | 15.8 | 13.12 ± 2.13 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 14.0 | 15.7 | 13.12 ± 2.13 |
| mattcl-py | input-pting | 16.4 ± 0.6 | 15.4 | 19.5 | 14.50 ± 2.40 |
| mattcl-py | input-lanjian | 16.4 ± 0.5 | 15.5 | 19.8 | 14.51 ± 2.38 |
| mattcl-py | input-mattcl | 16.4 ± 0.6 | 15.3 | 19.7 | 14.51 ± 2.39 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.2 | 19.8 | 14.52 ± 2.39 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.3 | 19.5 | 14.54 ± 2.40 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.0 | 19.7 | 14.93 ± 2.46 |
| pting | input-pting | 16.9 ± 0.7 | 15.8 | 20.1 | 14.95 ± 2.47 |
| pting | input-chancalan | 16.9 ± 0.6 | 15.9 | 19.5 | 14.96 ± 2.47 |
| pting | input-lanjian | 17.0 ± 0.5 | 16.2 | 19.5 | 14.99 ± 2.46 |
| pting | input-kcen | 17.0 ± 0.7 | 16.0 | 20.0 | 15.02 ± 2.49 |
| kcen | input-mattcl | 20.2 ± 0.7 | 19.2 | 22.9 | 17.89 ± 2.93 |
| kcen | input-pting | 20.3 ± 0.8 | 19.1 | 23.5 | 17.91 ± 2.96 |
| kcen | input-chancalan | 20.3 ± 0.8 | 18.9 | 23.0 | 17.92 ± 2.96 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.5 | 23.0 | 17.95 ± 2.96 |
| kcen | input-kcen | 20.4 ± 2.3 | 19.3 | 42.6 | 18.01 ± 3.53 |
| chancalan | input-mattcl | 24.3 ± 0.6 | 23.2 | 26.9 | 21.46 ± 3.49 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.3 | 27.3 | 21.48 ± 3.50 |
| chancalan | input-kcen | 24.4 ± 0.9 | 23.3 | 27.9 | 21.60 ± 3.55 |
| chancalan | input-pting | 24.4 ± 0.8 | 23.4 | 27.8 | 21.60 ± 3.54 |
| chancalan | input-chancalan | 24.5 ± 0.9 | 23.3 | 27.3 | 21.67 ± 3.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|