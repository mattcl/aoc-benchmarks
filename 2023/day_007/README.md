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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.23 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.21 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.20 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.8 | 1.05 ± 0.20 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.9 | 1.05 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 2.1 | 1.06 ± 0.25 |
| mattcl-ts | input-chancalan | 13.9 ± 0.4 | 12.7 | 15.2 | 11.90 ± 1.87 |
| mattcl-ts | input-pting | 13.9 ± 0.4 | 12.8 | 15.0 | 11.91 ± 1.87 |
| mattcl-ts | input-mattcl | 13.9 ± 0.4 | 13.0 | 15.1 | 11.96 ± 1.88 |
| mattcl-ts | input-kcen | 13.9 ± 0.4 | 12.9 | 15.0 | 11.97 ± 1.88 |
| mattcl-ts | input-lanjian | 14.0 ± 0.4 | 12.9 | 15.1 | 12.02 ± 1.89 |
| mattcl-py | input-chancalan | 16.4 ± 0.5 | 15.4 | 19.3 | 14.10 ± 2.23 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.3 | 19.4 | 14.13 ± 2.25 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.7 | 19.3 | 14.13 ± 2.25 |
| mattcl-py | input-kcen | 16.5 ± 0.7 | 15.3 | 19.5 | 14.18 ± 2.27 |
| mattcl-py | input-pting | 16.5 ± 0.7 | 15.6 | 19.4 | 14.20 ± 2.27 |
| pting | input-mattcl | 16.9 ± 0.5 | 16.2 | 19.7 | 14.52 ± 2.29 |
| pting | input-chancalan | 16.9 ± 0.6 | 16.0 | 20.4 | 14.54 ± 2.31 |
| pting | input-kcen | 17.0 ± 0.6 | 16.0 | 20.3 | 14.58 ± 2.32 |
| pting | input-pting | 17.0 ± 0.6 | 16.0 | 19.9 | 14.62 ± 2.32 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.7 | 20.1 | 14.62 ± 2.34 |
| kcen | input-chancalan | 20.0 ± 0.4 | 19.3 | 22.2 | 17.20 ± 2.69 |
| kcen | input-lanjian | 20.1 ± 0.6 | 19.2 | 22.4 | 17.31 ± 2.73 |
| kcen | input-kcen | 20.2 ± 0.7 | 19.3 | 23.5 | 17.34 ± 2.75 |
| kcen | input-pting | 20.2 ± 0.7 | 19.1 | 22.8 | 17.34 ± 2.75 |
| kcen | input-mattcl | 20.2 ± 0.6 | 19.3 | 23.2 | 17.35 ± 2.74 |
| chancalan | input-chancalan | 24.2 ± 0.7 | 23.2 | 27.2 | 20.75 ± 3.26 |
| chancalan | input-pting | 24.3 ± 0.8 | 23.1 | 27.6 | 20.91 ± 3.31 |
| chancalan | input-kcen | 24.4 ± 0.9 | 23.0 | 27.7 | 20.92 ± 3.32 |
| chancalan | input-mattcl | 24.4 ± 0.8 | 23.1 | 27.2 | 20.95 ± 3.31 |
| chancalan | input-lanjian | 24.4 ± 0.9 | 23.4 | 27.1 | 20.98 ± 3.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|