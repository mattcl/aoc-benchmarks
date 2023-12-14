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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.25 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 2.0 | 1.01 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 2.0 | 1.03 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.3 | 1.4 | 1.03 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.25 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.7 | 1.8 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.8 | 1.8 | 1.08 ± 0.24 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.1 | 15.9 | 12.67 ± 2.47 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.0 | 16.5 | 12.70 ± 2.48 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.3 | 12.70 ± 2.48 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.2 | 16.5 | 12.70 ± 2.48 |
| mattcl-ts | input-lanjian | 15.3 ± 2.5 | 14.1 | 48.7 | 12.88 ± 3.24 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.6 | 19.9 | 14.08 ± 2.78 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.9 | 19.8 | 14.17 ± 2.81 |
| mattcl-py | input-pting | 16.8 ± 0.6 | 15.5 | 19.9 | 14.17 ± 2.80 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 15.8 | 19.8 | 14.24 ± 2.81 |
| mattcl-py | input-lanjian | 17.0 ± 0.7 | 15.8 | 20.0 | 14.30 ± 2.84 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.0 | 20.5 | 14.62 ± 2.90 |
| pting | input-kcen | 17.4 ± 0.6 | 16.5 | 20.8 | 14.64 ± 2.89 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.3 | 20.7 | 14.66 ± 2.90 |
| pting | input-pting | 17.4 ± 0.9 | 16.0 | 20.8 | 14.70 ± 2.94 |
| pting | input-chancalan | 17.5 ± 0.8 | 16.2 | 20.8 | 14.74 ± 2.93 |
| kcen | input-chancalan | 20.5 ± 0.8 | 19.5 | 23.6 | 17.31 ± 3.42 |
| kcen | input-pting | 20.5 ± 0.7 | 19.5 | 23.5 | 17.32 ± 3.41 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.5 | 23.2 | 17.33 ± 3.41 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.4 | 23.5 | 17.40 ± 3.43 |
| kcen | input-kcen | 20.8 ± 1.0 | 19.2 | 24.3 | 17.52 ± 3.49 |
| chancalan | input-mattcl | 24.6 ± 0.7 | 23.3 | 27.7 | 20.78 ± 4.07 |
| chancalan | input-lanjian | 24.7 ± 0.7 | 23.2 | 27.0 | 20.82 ± 4.08 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.6 | 27.8 | 20.85 ± 4.09 |
| chancalan | input-kcen | 24.7 ± 0.7 | 23.6 | 27.4 | 20.86 ± 4.09 |
| chancalan | input-chancalan | 24.8 ± 0.8 | 23.6 | 28.5 | 20.88 ± 4.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|