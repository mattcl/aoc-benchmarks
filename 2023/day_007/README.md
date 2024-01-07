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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.8 | 1.00 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.26 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.27 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.26 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.26 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.07 ± 0.26 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 2.0 | 1.07 ± 0.27 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.07 ± 0.25 |
| lanjian | input-chancalan | 1.3 ± 0.1 | 0.7 | 1.7 | 1.09 ± 0.24 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.0 | 1.09 ± 0.27 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 14.0 | 16.1 | 13.07 ± 2.60 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.3 | 16.3 | 13.07 ± 2.60 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.2 | 15.9 | 13.07 ± 2.60 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.1 | 16.2 | 13.08 ± 2.60 |
| mattcl-ts | input-pting | 15.3 ± 4.2 | 14.1 | 73.2 | 13.34 ± 4.53 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.6 | 19.9 | 14.56 ± 2.93 |
| mattcl-py | input-lanjian | 16.8 ± 0.6 | 15.3 | 19.6 | 14.59 ± 2.93 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.7 | 19.8 | 14.61 ± 2.94 |
| mattcl-py | input-kcen | 16.8 ± 0.8 | 15.8 | 19.9 | 14.62 ± 2.96 |
| mattcl-py | input-mattcl | 16.9 ± 0.8 | 15.7 | 19.8 | 14.67 ± 2.97 |
| pting | input-chancalan | 17.2 ± 0.6 | 16.0 | 20.9 | 14.93 ± 3.00 |
| pting | input-mattcl | 17.2 ± 0.6 | 15.9 | 20.0 | 14.93 ± 3.00 |
| pting | input-lanjian | 17.2 ± 0.7 | 15.8 | 20.4 | 15.00 ± 3.02 |
| pting | input-pting | 17.3 ± 0.7 | 16.4 | 20.7 | 15.01 ± 3.03 |
| pting | input-kcen | 17.3 ± 0.7 | 15.9 | 20.3 | 15.01 ± 3.03 |
| kcen | input-lanjian | 20.5 ± 0.6 | 19.3 | 23.2 | 17.79 ± 3.55 |
| kcen | input-chancalan | 20.5 ± 0.7 | 19.4 | 23.3 | 17.83 ± 3.57 |
| kcen | input-mattcl | 20.5 ± 0.8 | 19.1 | 24.6 | 17.84 ± 3.58 |
| kcen | input-kcen | 20.6 ± 0.8 | 19.3 | 23.4 | 17.88 ± 3.59 |
| kcen | input-pting | 20.7 ± 0.9 | 19.0 | 23.8 | 17.98 ± 3.63 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 23.1 | 27.5 | 21.36 ± 4.27 |
| chancalan | input-chancalan | 24.6 ± 0.8 | 23.0 | 27.7 | 21.39 ± 4.28 |
| chancalan | input-lanjian | 24.6 ± 0.8 | 23.6 | 27.6 | 21.41 ± 4.28 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.6 | 28.2 | 21.43 ± 4.29 |
| chancalan | input-kcen | 24.8 ± 0.9 | 23.7 | 27.6 | 21.60 ± 4.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|