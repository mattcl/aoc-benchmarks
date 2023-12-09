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

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 0.9 ± 0.4 | 0.3 | 3.5 | 1.00 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.27 ± 0.60 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.29 ± 0.60 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.3 | 1.30 ± 0.60 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.3 | 1.30 ± 0.60 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.33 ± 0.62 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.34 ± 0.62 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.37 ± 0.64 |
| mattcl-ts | input-lanjian | 14.6 ± 0.4 | 13.7 | 15.5 | 16.83 ± 7.34 |
| mattcl-ts | input-kcen | 14.6 ± 0.4 | 13.7 | 16.0 | 16.84 ± 7.35 |
| mattcl-ts | input-pting | 14.6 ± 0.3 | 13.7 | 15.8 | 16.84 ± 7.34 |
| mattcl-ts | input-mattcl | 14.6 ± 0.3 | 13.7 | 15.7 | 16.93 ± 7.38 |
| mattcl-py | input-pting | 16.5 ± 0.5 | 15.5 | 19.1 | 19.09 ± 8.34 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.6 | 19.8 | 19.17 ± 8.38 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.3 | 19.6 | 19.19 ± 8.40 |
| mattcl-py | input-kcen | 16.6 ± 0.7 | 15.4 | 19.5 | 19.20 ± 8.40 |
| pting | input-mattcl | 17.0 ± 0.6 | 15.9 | 20.7 | 19.60 ± 8.57 |
| pting | input-kcen | 17.0 ± 0.5 | 16.0 | 20.3 | 19.63 ± 8.57 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.3 | 19.8 | 19.68 ± 8.60 |
| pting | input-pting | 17.1 ± 0.6 | 16.2 | 20.3 | 19.72 ± 8.62 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.4 | 23.0 | 23.40 ± 10.21 |
| kcen | input-pting | 20.3 ± 0.7 | 19.1 | 22.7 | 23.45 ± 10.25 |
| kcen | input-mattcl | 20.3 ± 0.5 | 19.4 | 22.4 | 23.51 ± 10.26 |
| kcen | input-lanjian | 20.4 ± 0.7 | 19.4 | 23.4 | 23.60 ± 10.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|