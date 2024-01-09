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
| mattcl | input-chancalan | 1.2 ± 1.8 | 0.4 | 26.3 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 1.50 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.8 | 1.01 ± 1.50 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.3 | 1.7 | 1.03 ± 1.53 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 1.53 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.04 ± 1.54 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.8 | 1.04 ± 1.54 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.0 | 1.04 ± 1.54 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.05 ± 1.56 |
| mattcl | input-kcen | 1.3 ± 0.1 | 0.6 | 1.8 | 1.06 ± 1.56 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.2 | 16.5 | 12.32 ± 18.22 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.0 | 16.0 | 12.33 ± 18.23 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.1 | 15.9 | 12.33 ± 18.23 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.2 | 16.0 | 12.34 ± 18.24 |
| mattcl-ts | input-chancalan | 15.3 ± 3.0 | 14.3 | 55.8 | 12.51 ± 18.64 |
| mattcl-py | input-lanjian | 16.8 ± 0.7 | 15.4 | 20.0 | 13.69 ± 20.24 |
| mattcl-py | input-chancalan | 16.8 ± 0.6 | 15.7 | 19.0 | 13.75 ± 20.33 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 15.7 | 19.5 | 13.79 ± 20.39 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 15.8 | 19.7 | 13.80 ± 20.40 |
| mattcl-py | input-kcen | 16.9 ± 0.7 | 15.8 | 20.2 | 13.80 ± 20.41 |
| pting | input-mattcl | 17.3 ± 0.7 | 16.3 | 20.5 | 14.13 ± 20.89 |
| pting | input-kcen | 17.3 ± 0.7 | 16.2 | 20.8 | 14.14 ± 20.91 |
| pting | input-pting | 17.3 ± 0.6 | 16.1 | 20.0 | 14.15 ± 20.92 |
| pting | input-lanjian | 17.4 ± 0.8 | 16.0 | 20.6 | 14.19 ± 20.99 |
| pting | input-chancalan | 17.7 ± 2.7 | 16.4 | 50.1 | 14.45 ± 21.46 |
| kcen | input-kcen | 20.5 ± 0.6 | 19.4 | 22.9 | 16.75 ± 24.76 |
| kcen | input-chancalan | 20.6 ± 0.8 | 19.2 | 23.6 | 16.81 ± 24.86 |
| kcen | input-mattcl | 20.7 ± 0.9 | 19.0 | 24.6 | 16.90 ± 24.99 |
| kcen | input-lanjian | 20.7 ± 0.8 | 19.1 | 24.0 | 16.90 ± 24.99 |
| kcen | input-pting | 20.8 ± 0.8 | 19.7 | 23.7 | 17.00 ± 25.13 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 23.5 | 27.9 | 20.08 ± 29.69 |
| chancalan | input-pting | 24.8 ± 0.9 | 23.5 | 27.7 | 20.22 ± 29.90 |
| chancalan | input-chancalan | 24.8 ± 0.8 | 23.4 | 28.0 | 20.25 ± 29.93 |
| chancalan | input-lanjian | 24.8 ± 0.8 | 23.2 | 27.6 | 20.26 ± 29.96 |
| chancalan | input-kcen | 24.9 ± 0.9 | 23.9 | 28.1 | 20.33 ± 30.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|