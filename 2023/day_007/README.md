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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.3 | 1.8 | 1.00 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.12 ± 0.36 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.8 | 1.12 ± 0.35 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.8 | 1.13 ± 0.36 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 1.13 ± 0.35 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.13 ± 0.35 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 1.14 ± 0.35 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.15 ± 0.35 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.8 | 1.8 | 1.15 ± 0.34 |
| lanjian | input-mattcl | 1.5 ± 4.4 | 0.4 | 63.0 | 1.36 ± 3.87 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.0 | 16.1 | 13.28 ± 3.69 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.1 | 16.2 | 13.30 ± 3.69 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.1 | 16.0 | 13.32 ± 3.70 |
| mattcl-ts | input-mattcl | 15.4 ± 4.5 | 14.2 | 76.6 | 13.54 ± 5.45 |
| mattcl-ts | input-lanjian | 16.2 ± 5.6 | 14.3 | 55.5 | 14.28 ± 6.29 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.9 | 20.4 | 14.70 ± 4.10 |
| mattcl-py | input-lanjian | 16.8 ± 0.6 | 15.7 | 19.9 | 14.80 ± 4.14 |
| mattcl-py | input-pting | 16.8 ± 0.5 | 15.6 | 19.4 | 14.83 ± 4.13 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 16.0 | 19.9 | 14.84 ± 4.15 |
| pting | input-pting | 17.2 ± 0.6 | 16.1 | 20.4 | 15.14 ± 4.22 |
| mattcl-py | input-mattcl | 17.2 ± 3.7 | 15.3 | 56.6 | 15.18 ± 5.33 |
| pting | input-kcen | 17.3 ± 0.8 | 15.9 | 20.8 | 15.24 ± 4.27 |
| pting | input-chancalan | 17.4 ± 0.7 | 15.9 | 20.9 | 15.29 ± 4.28 |
| pting | input-lanjian | 17.4 ± 0.6 | 16.4 | 20.0 | 15.33 ± 4.28 |
| pting | input-mattcl | 17.6 ± 0.8 | 16.5 | 21.0 | 15.47 ± 4.34 |
| kcen | input-chancalan | 20.5 ± 0.8 | 19.3 | 24.1 | 18.05 ± 5.04 |
| kcen | input-lanjian | 20.5 ± 0.6 | 19.5 | 24.4 | 18.06 ± 5.03 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.6 | 23.8 | 18.23 ± 5.09 |
| kcen | input-kcen | 20.7 ± 0.9 | 19.4 | 24.4 | 18.24 ± 5.12 |
| kcen | input-pting | 20.7 ± 0.7 | 19.8 | 23.5 | 18.25 ± 5.09 |
| chancalan | input-kcen | 24.5 ± 0.9 | 22.9 | 27.2 | 21.61 ± 6.03 |
| chancalan | input-pting | 24.8 ± 0.8 | 23.5 | 27.8 | 21.81 ± 6.08 |
| chancalan | input-lanjian | 24.8 ± 0.8 | 23.4 | 27.5 | 21.81 ± 6.09 |
| chancalan | input-mattcl | 24.8 ± 0.9 | 23.6 | 28.0 | 21.83 ± 6.09 |
| chancalan | input-chancalan | 24.9 ± 0.9 | 23.6 | 29.1 | 21.95 ± 6.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|