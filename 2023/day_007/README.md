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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.03 ± 0.22 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.20 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.3 | 1.9 | 1.05 ± 0.23 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.9 | 1.06 ± 0.22 |
| mattcl | input-pting | 1.3 ± 4.3 | 0.3 | 61.6 | 1.11 ± 3.60 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.4 | 15.9 | 12.59 ± 1.90 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.3 | 16.5 | 12.61 ± 1.91 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.1 | 16.4 | 12.61 ± 1.91 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.2 | 16.1 | 12.64 ± 1.91 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.2 | 16.1 | 12.65 ± 1.91 |
| mattcl-py | input-lanjian | 16.9 ± 0.9 | 15.5 | 20.6 | 14.08 ± 2.22 |
| mattcl-py | input-kcen | 16.9 ± 0.9 | 15.4 | 21.1 | 14.08 ± 2.22 |
| mattcl-py | input-chancalan | 16.9 ± 0.7 | 15.9 | 19.9 | 14.08 ± 2.19 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 15.8 | 19.7 | 14.09 ± 2.17 |
| mattcl-py | input-pting | 17.3 ± 3.7 | 15.5 | 60.6 | 14.42 ± 3.78 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.4 | 20.6 | 14.43 ± 2.24 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.3 | 20.7 | 14.45 ± 2.23 |
| pting | input-mattcl | 17.3 ± 0.8 | 16.3 | 20.5 | 14.46 ± 2.25 |
| pting | input-kcen | 17.3 ± 0.8 | 16.1 | 19.9 | 14.48 ± 2.25 |
| pting | input-pting | 17.3 ± 0.6 | 16.1 | 20.5 | 14.48 ± 2.22 |
| kcen | input-pting | 20.5 ± 0.7 | 19.2 | 23.5 | 17.09 ± 2.63 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.6 | 24.3 | 17.21 ± 2.63 |
| kcen | input-chancalan | 20.6 ± 0.7 | 19.5 | 23.5 | 17.23 ± 2.64 |
| kcen | input-kcen | 20.7 ± 0.8 | 19.5 | 24.2 | 17.26 ± 2.67 |
| kcen | input-lanjian | 20.7 ± 0.8 | 19.5 | 24.0 | 17.29 ± 2.66 |
| chancalan | input-kcen | 24.6 ± 0.6 | 23.7 | 27.2 | 20.55 ± 3.11 |
| chancalan | input-lanjian | 24.7 ± 0.8 | 23.6 | 27.3 | 20.67 ± 3.16 |
| chancalan | input-mattcl | 24.8 ± 0.7 | 23.6 | 28.0 | 20.69 ± 3.15 |
| chancalan | input-chancalan | 24.8 ± 0.8 | 23.7 | 27.6 | 20.74 ± 3.17 |
| chancalan | input-pting | 25.2 ± 2.4 | 23.5 | 44.5 | 21.09 ± 3.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|