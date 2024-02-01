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
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.5 | 1.8 | 1.01 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.25 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.25 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.24 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.24 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.27 |
| lanjian | input-kcen | 1.1 ± 0.1 | 0.6 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.24 |
| mattcl-ts | input-aspidites | 12.4 ± 0.4 | 11.2 | 13.3 | 12.07 ± 2.11 |
| mattcl-ts | input-kcen | 12.4 ± 0.3 | 11.4 | 13.2 | 12.09 ± 2.11 |
| mattcl-ts | input-lanjian | 12.4 ± 0.3 | 11.1 | 13.2 | 12.09 ± 2.11 |
| mikofo | input-lanjian | 12.4 ± 0.4 | 11.3 | 13.6 | 12.12 ± 2.12 |
| mattcl-ts | input-mattcl | 12.4 ± 0.3 | 11.0 | 13.7 | 12.13 ± 2.12 |
| mattcl-ts | input-chancalan | 12.5 ± 0.3 | 11.3 | 13.3 | 12.13 ± 2.12 |
| mikofo | input-aspidites | 12.5 ± 0.4 | 11.5 | 13.7 | 12.15 ± 2.13 |
| mikofo | input-mattcl | 12.5 ± 0.3 | 11.5 | 13.3 | 12.16 ± 2.12 |
| mikofo | input-kcen | 12.5 ± 0.3 | 11.7 | 13.3 | 12.17 ± 2.12 |
| mikofo | input-chancalan | 12.5 ± 0.3 | 11.4 | 13.3 | 12.18 ± 2.13 |
| aspidites | input-mattcl | 12.6 ± 0.5 | 11.7 | 14.2 | 12.28 ± 2.16 |
| aspidites | input-kcen | 12.6 ± 0.4 | 11.8 | 13.8 | 12.30 ± 2.16 |
| aspidites | input-aspidites | 12.6 ± 0.5 | 11.6 | 14.8 | 12.30 ± 2.17 |
| aspidites | input-lanjian | 12.6 ± 0.5 | 11.4 | 13.8 | 12.30 ± 2.17 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.7 | 14.6 | 12.39 ± 2.19 |
| pting | input-chancalan | 15.6 ± 0.6 | 14.6 | 18.4 | 15.23 ± 2.69 |
| pting | input-lanjian | 15.6 ± 0.7 | 14.7 | 19.2 | 15.23 ± 2.71 |
| pting | input-kcen | 15.6 ± 0.7 | 14.6 | 18.8 | 15.24 ± 2.71 |
| pting | input-aspidites | 15.7 ± 0.9 | 14.6 | 19.3 | 15.31 ± 2.77 |
| pting | input-mattcl | 15.7 ± 0.7 | 14.6 | 19.5 | 15.33 ± 2.74 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.8 | 19.8 | 15.51 ± 2.76 |
| chancalan | input-aspidites | 15.9 ± 0.8 | 14.9 | 19.2 | 15.51 ± 2.78 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 15.0 | 19.1 | 15.56 ± 2.77 |
| mattcl-py | input-aspidites | 16.0 ± 0.7 | 14.6 | 18.7 | 15.57 ± 2.77 |
| chancalan | input-lanjian | 16.0 ± 0.7 | 14.6 | 19.2 | 15.58 ± 2.77 |
| mattcl-py | input-lanjian | 16.0 ± 0.8 | 14.6 | 18.8 | 15.58 ± 2.80 |
| chancalan | input-mattcl | 16.0 ± 0.7 | 14.5 | 19.5 | 15.59 ± 2.78 |
| chancalan | input-kcen | 16.0 ± 0.6 | 14.8 | 19.3 | 15.60 ± 2.76 |
| chancalan | input-chancalan | 16.0 ± 0.8 | 14.8 | 19.6 | 15.61 ± 2.80 |
| mattcl-py | input-mattcl | 16.1 ± 0.7 | 15.0 | 19.2 | 15.65 ± 2.78 |
| kcen | input-mattcl | 16.3 ± 0.5 | 15.4 | 19.8 | 15.92 ± 2.79 |
| kcen | input-lanjian | 16.5 ± 0.7 | 15.1 | 19.2 | 16.04 ± 2.84 |
| kcen | input-aspidites | 16.5 ± 0.6 | 15.2 | 19.6 | 16.05 ± 2.84 |
| kcen | input-kcen | 16.5 ± 0.8 | 15.5 | 19.7 | 16.08 ± 2.88 |
| kcen | input-chancalan | 16.5 ± 0.7 | 15.5 | 19.5 | 16.09 ± 2.86 |


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