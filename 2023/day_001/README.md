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
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.7 | 1.00 ± 0.28 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.26 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.25 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.25 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.24 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 3.1 | 1.07 ± 0.25 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.6 | 1.8 | 1.07 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.6 | 2.0 | 1.10 ± 0.24 |
| mattcl-ts | input-aspidites | 12.6 ± 0.3 | 11.6 | 13.9 | 12.03 ± 2.12 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.7 | 13.6 | 12.06 ± 2.12 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.8 | 13.7 | 12.06 ± 2.12 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.8 | 13.8 | 12.07 ± 2.13 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.8 | 14.0 | 12.09 ± 2.12 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.5 | 14.6 | 12.10 ± 2.15 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.5 | 14.3 | 12.11 ± 2.16 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.9 | 14.3 | 12.21 ± 2.18 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.9 | 14.5 | 12.22 ± 2.17 |
| mikofo | input-lanjian | 12.9 ± 0.3 | 11.9 | 13.8 | 12.26 ± 2.16 |
| aspidites | input-lanjian | 12.9 ± 0.5 | 11.9 | 14.3 | 12.28 ± 2.18 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 12.1 | 14.0 | 12.30 ± 2.16 |
| mikofo | input-chancalan | 12.9 ± 0.3 | 12.2 | 13.9 | 12.31 ± 2.16 |
| mikofo | input-kcen | 12.9 ± 0.3 | 12.0 | 13.9 | 12.31 ± 2.17 |
| mikofo | input-aspidites | 12.9 ± 0.4 | 11.8 | 14.7 | 12.32 ± 2.17 |
| pting | input-lanjian | 15.7 ± 0.7 | 14.6 | 19.6 | 14.97 ± 2.69 |
| pting | input-chancalan | 15.7 ± 0.6 | 14.7 | 18.7 | 14.99 ± 2.67 |
| pting | input-mattcl | 15.8 ± 0.6 | 14.5 | 18.4 | 15.05 ± 2.68 |
| pting | input-kcen | 15.8 ± 0.6 | 14.8 | 18.9 | 15.05 ± 2.68 |
| chancalan | input-aspidites | 16.0 ± 0.5 | 14.7 | 18.1 | 15.20 ± 2.70 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 14.9 | 18.3 | 15.21 ± 2.71 |
| chancalan | input-lanjian | 16.0 ± 0.6 | 14.8 | 18.6 | 15.23 ± 2.71 |
| pting | input-aspidites | 16.0 ± 0.8 | 15.1 | 19.3 | 15.24 ± 2.75 |
| chancalan | input-chancalan | 16.0 ± 0.6 | 14.7 | 18.9 | 15.26 ± 2.72 |
| chancalan | input-kcen | 16.1 ± 0.8 | 15.0 | 19.4 | 15.31 ± 2.76 |
| mattcl-py | input-chancalan | 16.1 ± 0.6 | 15.0 | 18.6 | 15.32 ± 2.72 |
| mattcl-py | input-aspidites | 16.1 ± 1.0 | 14.6 | 26.3 | 15.34 ± 2.85 |
| mattcl-py | input-kcen | 16.1 ± 0.8 | 14.8 | 19.3 | 15.36 ± 2.77 |
| mattcl-py | input-lanjian | 16.1 ± 0.8 | 15.0 | 19.0 | 15.36 ± 2.78 |
| chancalan | input-mattcl | 16.2 ± 2.9 | 14.9 | 54.9 | 15.45 ± 3.87 |
| kcen | input-aspidites | 16.5 ± 0.6 | 15.7 | 20.0 | 15.69 ± 2.79 |
| kcen | input-lanjian | 16.5 ± 0.6 | 15.1 | 19.8 | 15.70 ± 2.80 |
| kcen | input-mattcl | 16.5 ± 0.6 | 15.4 | 19.1 | 15.76 ± 2.80 |
| kcen | input-kcen | 16.6 ± 0.7 | 15.2 | 19.2 | 15.79 ± 2.82 |
| kcen | input-chancalan | 16.6 ± 0.7 | 15.4 | 19.3 | 15.86 ± 2.83 |


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