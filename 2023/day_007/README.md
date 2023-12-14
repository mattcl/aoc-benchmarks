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
| mattcl | input-pting | 1.1 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.8 | 1.00 ± 0.24 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.24 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.1 | 0.5 | 1.6 | 1.04 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 2.0 | 1.05 ± 0.25 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.6 | 1.07 ± 0.23 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.5 | 1.6 | 1.07 ± 0.24 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.08 ± 0.26 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 14.0 | 15.9 | 13.73 ± 2.52 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.0 | 16.2 | 13.76 ± 2.52 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.1 | 15.7 | 13.76 ± 2.52 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.1 | 16.1 | 13.77 ± 2.53 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.2 | 16.0 | 13.78 ± 2.52 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.8 | 19.0 | 15.30 ± 2.83 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.7 | 19.6 | 15.36 ± 2.85 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.4 | 20.1 | 15.42 ± 2.88 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.5 | 20.9 | 15.43 ± 2.88 |
| mattcl-py | input-pting | 16.8 ± 0.6 | 15.7 | 20.5 | 15.43 ± 2.86 |
| pting | input-kcen | 17.3 ± 0.6 | 16.1 | 20.0 | 15.87 ± 2.94 |
| pting | input-pting | 17.3 ± 0.8 | 16.1 | 20.8 | 15.88 ± 2.97 |
| pting | input-lanjian | 17.3 ± 0.8 | 16.3 | 20.5 | 15.94 ± 2.98 |
| pting | input-mattcl | 17.3 ± 0.8 | 16.2 | 20.1 | 15.94 ± 2.99 |
| pting | input-chancalan | 17.6 ± 3.0 | 16.2 | 53.5 | 16.18 ± 4.04 |
| kcen | input-kcen | 20.5 ± 0.7 | 19.0 | 23.2 | 18.83 ± 3.48 |
| kcen | input-chancalan | 20.5 ± 0.7 | 19.5 | 23.8 | 18.84 ± 3.48 |
| kcen | input-lanjian | 20.5 ± 0.7 | 19.1 | 23.8 | 18.86 ± 3.49 |
| kcen | input-pting | 20.5 ± 0.7 | 19.3 | 23.3 | 18.87 ± 3.48 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.3 | 23.3 | 18.96 ± 3.51 |
| chancalan | input-pting | 24.5 ± 0.8 | 23.1 | 27.6 | 22.52 ± 4.15 |
| chancalan | input-chancalan | 24.5 ± 0.7 | 23.3 | 26.9 | 22.52 ± 4.14 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 23.4 | 27.7 | 22.66 ± 4.19 |
| chancalan | input-lanjian | 24.6 ± 0.7 | 23.5 | 27.4 | 22.67 ± 4.18 |
| chancalan | input-kcen | 24.8 ± 0.8 | 23.5 | 27.0 | 22.79 ± 4.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|