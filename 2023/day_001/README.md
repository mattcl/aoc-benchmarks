# Day 1 benchmarks

[link to problem](https://adventofcode.com/2023/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [aspidites](https://github.com/aspidites/aoc2023) (haskell)
- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.6 | 1.00 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.5 | 1.00 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.25 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.4 | 1.03 ± 0.25 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 2.7 | 1.04 ± 0.28 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.5 | 1.6 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.04 ± 0.25 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.6 | 1.05 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.9 | 1.07 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.7 | 1.07 ± 0.25 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.7 | 13.6 | 12.14 ± 2.14 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.6 | 14.0 | 12.15 ± 2.14 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.6 | 13.2 | 12.18 ± 2.14 |
| mattcl-ts | input-aspidites | 12.6 ± 0.3 | 11.7 | 13.4 | 12.20 ± 2.15 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.8 | 14.6 | 12.21 ± 2.15 |
| mikofo | input-aspidites | 12.7 ± 0.3 | 11.5 | 13.5 | 12.28 ± 2.16 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.6 | 13.6 | 12.28 ± 2.16 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.9 | 14.0 | 12.29 ± 2.18 |
| mikofo | input-kcen | 12.7 ± 0.3 | 11.7 | 13.7 | 12.30 ± 2.17 |
| mikofo | input-lanjian | 12.7 ± 0.3 | 11.8 | 14.0 | 12.31 ± 2.17 |
| mikofo | input-mattcl | 12.7 ± 0.3 | 11.7 | 14.4 | 12.33 ± 2.17 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.6 | 14.4 | 12.37 ± 2.21 |
| aspidites | input-mattcl | 12.8 ± 0.4 | 11.7 | 14.0 | 12.37 ± 2.20 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.5 | 14.2 | 12.38 ± 2.21 |
| aspidites | input-kcen | 12.9 ± 3.6 | 11.1 | 49.7 | 12.51 ± 4.13 |
| pting | input-lanjian | 15.4 ± 0.5 | 14.5 | 18.1 | 14.92 ± 2.65 |
| pting | input-aspidites | 15.4 ± 0.5 | 14.6 | 17.9 | 14.96 ± 2.65 |
| pting | input-mattcl | 15.4 ± 0.6 | 14.4 | 18.6 | 14.96 ± 2.67 |
| pting | input-kcen | 15.4 ± 0.6 | 14.7 | 19.2 | 14.98 ± 2.68 |
| chancalan | input-aspidites | 15.6 ± 0.5 | 14.7 | 18.5 | 15.12 ± 2.67 |
| pting | input-chancalan | 15.6 ± 2.6 | 14.3 | 50.5 | 15.17 ± 3.66 |
| mattcl-py | input-mattcl | 15.7 ± 0.6 | 14.7 | 18.7 | 15.23 ± 2.72 |
| chancalan | input-lanjian | 15.7 ± 0.7 | 14.7 | 18.5 | 15.25 ± 2.74 |
| chancalan | input-mattcl | 15.7 ± 0.7 | 14.7 | 18.6 | 15.26 ± 2.73 |
| mattcl-py | input-lanjian | 15.8 ± 0.8 | 14.6 | 19.1 | 15.28 ± 2.77 |
| chancalan | input-chancalan | 15.8 ± 0.6 | 14.7 | 19.0 | 15.29 ± 2.73 |
| mattcl-py | input-chancalan | 15.8 ± 0.7 | 14.8 | 19.0 | 15.31 ± 2.76 |
| chancalan | input-kcen | 15.8 ± 0.7 | 14.8 | 18.9 | 15.32 ± 2.75 |
| mattcl-py | input-aspidites | 15.8 ± 0.7 | 14.7 | 18.6 | 15.33 ± 2.76 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.7 | 18.9 | 15.37 ± 2.77 |
| kcen | input-lanjian | 16.2 ± 0.5 | 15.2 | 19.8 | 15.72 ± 2.79 |
| kcen | input-kcen | 16.3 ± 0.6 | 15.2 | 18.8 | 15.85 ± 2.82 |
| kcen | input-chancalan | 16.4 ± 0.6 | 15.3 | 19.1 | 15.87 ± 2.82 |
| kcen | input-aspidites | 16.4 ± 0.6 | 15.2 | 19.8 | 15.89 ± 2.83 |
| kcen | input-mattcl | 16.5 ± 0.9 | 15.2 | 19.7 | 15.97 ± 2.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-mikofo|<pre>55538</pre>|<pre>54875</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|