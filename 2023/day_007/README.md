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
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.26 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.6 | 1.01 ± 0.24 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.25 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.6 | 1.03 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.5 | 1.7 | 1.04 ± 0.23 |
| mattcl-ts | input-lanjian | 14.4 ± 0.4 | 13.3 | 15.9 | 12.76 ± 2.45 |
| mattcl-ts | input-mattcl | 14.5 ± 0.4 | 13.5 | 15.8 | 12.78 ± 2.45 |
| mattcl-ts | input-chancalan | 14.5 ± 0.4 | 13.5 | 15.8 | 12.79 ± 2.45 |
| mattcl-ts | input-pting | 14.5 ± 0.4 | 13.6 | 15.6 | 12.79 ± 2.45 |
| mattcl-ts | input-kcen | 14.5 ± 0.4 | 13.5 | 15.6 | 12.84 ± 2.45 |
| mattcl-py | input-mattcl | 16.4 ± 0.4 | 15.6 | 18.6 | 14.46 ± 2.77 |
| mattcl-py | input-lanjian | 16.4 ± 0.7 | 15.2 | 19.9 | 14.50 ± 2.81 |
| mattcl-py | input-pting | 16.4 ± 0.6 | 15.5 | 19.5 | 14.50 ± 2.79 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.4 | 19.5 | 14.51 ± 2.80 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.4 | 19.0 | 14.52 ± 2.80 |
| pting | input-chancalan | 16.7 ± 0.6 | 15.6 | 19.6 | 14.79 ± 2.86 |
| pting | input-lanjian | 16.8 ± 0.6 | 15.8 | 19.7 | 14.83 ± 2.87 |
| pting | input-kcen | 16.8 ± 0.6 | 15.6 | 20.0 | 14.85 ± 2.87 |
| pting | input-mattcl | 16.9 ± 0.7 | 16.1 | 20.3 | 14.95 ± 2.91 |
| pting | input-pting | 16.9 ± 0.8 | 16.0 | 20.4 | 14.98 ± 2.92 |
| kcen | input-kcen | 20.0 ± 0.6 | 19.0 | 23.8 | 17.72 ± 3.41 |
| kcen | input-chancalan | 20.1 ± 0.7 | 18.8 | 22.9 | 17.74 ± 3.42 |
| kcen | input-mattcl | 20.2 ± 0.7 | 19.0 | 23.1 | 17.86 ± 3.44 |
| kcen | input-lanjian | 20.2 ± 0.8 | 19.1 | 23.8 | 17.90 ± 3.47 |
| kcen | input-pting | 20.3 ± 0.8 | 19.3 | 22.9 | 17.91 ± 3.47 |
| chancalan | input-chancalan | 24.2 ± 0.8 | 23.2 | 27.5 | 21.40 ± 4.12 |
| chancalan | input-pting | 24.2 ± 0.8 | 23.2 | 27.2 | 21.41 ± 4.12 |
| chancalan | input-kcen | 24.3 ± 0.8 | 23.1 | 27.3 | 21.44 ± 4.13 |
| chancalan | input-mattcl | 24.3 ± 0.7 | 23.2 | 27.7 | 21.47 ± 4.12 |
| chancalan | input-lanjian | 24.8 ± 4.8 | 23.0 | 65.0 | 21.92 ± 5.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|