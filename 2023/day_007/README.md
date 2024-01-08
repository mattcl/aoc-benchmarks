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
| mattcl | input-chancalan | 1.1 ± 0.3 | 0.3 | 1.7 | 1.00 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.05 ± 0.35 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.08 ± 0.34 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.4 | 1.08 ± 0.34 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.9 | 1.10 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.5 | 1.6 | 1.10 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.11 ± 0.33 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.11 ± 0.33 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.8 | 1.11 ± 0.33 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 14.0 | 16.0 | 13.33 ± 3.56 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.9 | 15.9 | 13.36 ± 3.57 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 14.0 | 15.7 | 13.37 ± 3.57 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 13.8 | 15.9 | 13.38 ± 3.58 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 14.0 | 15.9 | 13.39 ± 3.58 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.6 | 19.6 | 14.86 ± 4.00 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.4 | 20.1 | 14.91 ± 4.01 |
| mattcl-py | input-pting | 16.6 ± 0.7 | 15.6 | 19.9 | 14.95 ± 4.03 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.5 | 19.7 | 14.95 ± 4.03 |
| pting | input-kcen | 17.0 ± 0.7 | 15.9 | 20.3 | 15.25 ± 4.11 |
| pting | input-mattcl | 17.1 ± 0.7 | 15.8 | 19.9 | 15.40 ± 4.15 |
| pting | input-chancalan | 17.1 ± 0.7 | 16.0 | 20.3 | 15.41 ± 4.15 |
| pting | input-lanjian | 17.2 ± 0.8 | 15.9 | 20.7 | 15.44 ± 4.17 |
| pting | input-pting | 17.2 ± 0.8 | 16.2 | 19.9 | 15.48 ± 4.18 |
| mattcl-py | input-chancalan | 17.3 ± 4.7 | 15.7 | 62.1 | 15.56 ± 5.91 |
| kcen | input-pting | 20.3 ± 0.7 | 19.5 | 23.4 | 18.30 ± 4.91 |
| kcen | input-chancalan | 20.3 ± 0.7 | 19.2 | 23.2 | 18.31 ± 4.92 |
| kcen | input-lanjian | 20.4 ± 0.7 | 19.4 | 24.1 | 18.32 ± 4.92 |
| kcen | input-mattcl | 20.4 ± 0.8 | 19.4 | 23.0 | 18.38 ± 4.94 |
| kcen | input-kcen | 20.6 ± 3.2 | 19.1 | 58.5 | 18.50 ± 5.72 |
| chancalan | input-mattcl | 24.4 ± 0.5 | 23.5 | 26.6 | 21.96 ± 5.87 |
| chancalan | input-kcen | 24.5 ± 0.9 | 23.3 | 27.6 | 22.02 ± 5.91 |
| chancalan | input-chancalan | 24.5 ± 0.8 | 23.2 | 27.1 | 22.03 ± 5.91 |
| chancalan | input-pting | 24.5 ± 0.8 | 23.5 | 27.5 | 22.06 ± 5.91 |
| chancalan | input-lanjian | 24.6 ± 0.9 | 23.4 | 27.2 | 22.16 ± 5.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|