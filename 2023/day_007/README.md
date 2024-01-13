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
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.00 ± 0.20 |
| mattcl | input-kcen | 1.3 ± 0.1 | 0.7 | 1.8 | 1.02 ± 0.19 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.19 |
| lanjian | input-lanjian | 1.3 ± 0.1 | 0.4 | 1.8 | 1.02 ± 0.18 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.19 |
| mattcl | input-lanjian | 1.3 ± 0.1 | 0.8 | 1.8 | 1.04 ± 0.19 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 2.1 | 1.04 ± 0.20 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.1 | 1.04 ± 0.23 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.7 | 1.8 | 1.04 ± 0.19 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.0 | 16.1 | 11.64 ± 1.73 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.4 | 16.1 | 11.68 ± 1.72 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.1 | 16.2 | 11.68 ± 1.73 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.1 | 16.4 | 11.69 ± 1.73 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.0 | 16.1 | 11.69 ± 1.73 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 16.0 | 20.0 | 13.02 ± 1.97 |
| mattcl-py | input-kcen | 16.9 ± 0.6 | 15.7 | 19.3 | 13.06 ± 1.97 |
| mattcl-py | input-mattcl | 17.0 ± 0.8 | 16.0 | 20.5 | 13.13 ± 2.01 |
| mattcl-py | input-pting | 17.0 ± 0.8 | 15.8 | 20.7 | 13.15 ± 2.01 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.4 | 20.9 | 13.44 ± 2.04 |
| pting | input-pting | 17.4 ± 0.7 | 16.3 | 20.7 | 13.45 ± 2.03 |
| mattcl-py | input-lanjian | 17.4 ± 3.8 | 15.6 | 52.8 | 13.45 ± 3.52 |
| pting | input-kcen | 17.5 ± 0.7 | 16.3 | 20.6 | 13.50 ± 2.05 |
| pting | input-chancalan | 17.5 ± 0.7 | 16.3 | 20.4 | 13.52 ± 2.05 |
| pting | input-lanjian | 17.5 ± 0.8 | 16.2 | 20.7 | 13.54 ± 2.07 |
| kcen | input-chancalan | 20.7 ± 0.8 | 19.6 | 23.4 | 15.97 ± 2.41 |
| kcen | input-kcen | 20.7 ± 0.9 | 19.5 | 24.5 | 16.01 ± 2.43 |
| kcen | input-mattcl | 20.7 ± 0.9 | 19.3 | 23.4 | 16.01 ± 2.43 |
| kcen | input-pting | 20.8 ± 0.8 | 19.8 | 24.4 | 16.06 ± 2.43 |
| kcen | input-lanjian | 20.9 ± 0.8 | 19.8 | 23.9 | 16.14 ± 2.44 |
| chancalan | input-pting | 24.6 ± 0.7 | 23.1 | 27.5 | 19.05 ± 2.84 |
| chancalan | input-chancalan | 24.8 ± 0.7 | 23.4 | 27.3 | 19.14 ± 2.85 |
| chancalan | input-mattcl | 24.8 ± 0.9 | 23.6 | 28.0 | 19.16 ± 2.88 |
| chancalan | input-kcen | 24.8 ± 1.0 | 23.3 | 28.0 | 19.17 ± 2.90 |
| chancalan | input-lanjian | 24.8 ± 0.7 | 23.5 | 27.4 | 19.19 ± 2.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|