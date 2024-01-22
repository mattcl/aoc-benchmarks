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
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.26 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.9 | 1.02 ± 0.27 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.6 | 1.7 | 1.04 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.5 | 1.7 | 1.05 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.25 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.8 | 15.8 | 12.84 ± 2.32 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 13.8 | 15.9 | 12.87 ± 2.33 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 13.7 | 15.8 | 12.88 ± 2.33 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 14.1 | 15.6 | 12.89 ± 2.33 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 14.1 | 15.9 | 12.90 ± 2.33 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.6 | 19.3 | 14.42 ± 2.63 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.3 | 19.9 | 14.42 ± 2.64 |
| mattcl-py | input-mattcl | 16.7 ± 0.6 | 15.7 | 20.3 | 14.45 ± 2.64 |
| mattcl-py | input-kcen | 16.8 ± 0.8 | 15.7 | 19.8 | 14.48 ± 2.68 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.4 | 20.1 | 14.55 ± 2.68 |
| pting | input-lanjian | 17.2 ± 0.6 | 16.2 | 20.1 | 14.88 ± 2.72 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.0 | 20.1 | 14.96 ± 2.75 |
| pting | input-pting | 17.3 ± 0.6 | 16.2 | 20.6 | 14.97 ± 2.74 |
| pting | input-mattcl | 17.5 ± 0.8 | 16.0 | 20.5 | 15.09 ± 2.79 |
| pting | input-kcen | 17.5 ± 0.8 | 16.4 | 20.6 | 15.09 ± 2.80 |
| kcen | input-chancalan | 20.5 ± 0.6 | 19.4 | 23.2 | 17.67 ± 3.21 |
| kcen | input-kcen | 20.5 ± 0.6 | 19.0 | 22.9 | 17.73 ± 3.22 |
| kcen | input-mattcl | 20.5 ± 0.8 | 19.4 | 23.7 | 17.74 ± 3.25 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.3 | 22.5 | 17.76 ± 3.23 |
| kcen | input-pting | 20.6 ± 0.7 | 19.4 | 23.4 | 17.79 ± 3.24 |
| chancalan | input-mattcl | 24.5 ± 0.9 | 22.8 | 27.8 | 21.13 ± 3.86 |
| chancalan | input-lanjian | 24.6 ± 0.7 | 23.5 | 27.0 | 21.25 ± 3.86 |
| chancalan | input-kcen | 24.6 ± 0.7 | 23.4 | 28.0 | 21.27 ± 3.86 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.2 | 27.4 | 21.30 ± 3.87 |
| chancalan | input-chancalan | 24.7 ± 0.7 | 23.0 | 29.1 | 21.30 ± 3.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|