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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.6 | 1.00 ± 0.21 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.21 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.01 ± 0.21 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.20 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.6 | 1.7 | 1.02 ± 0.19 |
| mattcl | input-aspidites | 1.2 ± 0.1 | 0.7 | 1.7 | 1.03 ± 0.19 |
| lanjian | input-aspidites | 1.2 ± 0.1 | 0.6 | 1.7 | 1.03 ± 0.19 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.7 | 1.06 ± 0.19 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.9 | 13.5 | 10.99 ± 1.62 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.5 | 13.4 | 11.00 ± 1.62 |
| mattcl-ts | input-aspidites | 12.7 ± 0.3 | 11.7 | 13.4 | 11.00 ± 1.62 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.8 | 13.4 | 11.03 ± 1.62 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.6 | 11.04 ± 1.62 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 12.0 | 14.1 | 11.13 ± 1.64 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 11.9 | 14.5 | 11.13 ± 1.64 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.9 | 14.4 | 11.13 ± 1.67 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.8 | 14.2 | 11.14 ± 1.67 |
| mikofo | input-kcen | 12.9 ± 0.3 | 12.0 | 13.8 | 11.16 ± 1.65 |
| aspidites | input-aspidites | 12.9 ± 0.5 | 11.9 | 14.6 | 11.19 ± 1.67 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 11.6 | 14.1 | 11.19 ± 1.68 |
| mikofo | input-aspidites | 12.9 ± 0.3 | 12.0 | 13.9 | 11.25 ± 1.66 |
| aspidites | input-lanjian | 13.0 ± 0.4 | 11.9 | 14.4 | 11.25 ± 1.68 |
| mikofo | input-mattcl | 14.2 ± 7.7 | 11.9 | 78.6 | 12.32 ± 6.94 |
| pting | input-lanjian | 15.6 ± 0.5 | 14.6 | 18.4 | 13.54 ± 2.01 |
| pting | input-kcen | 15.6 ± 0.6 | 14.5 | 18.1 | 13.58 ± 2.04 |
| pting | input-aspidites | 15.7 ± 0.7 | 14.8 | 19.3 | 13.59 ± 2.06 |
| pting | input-mattcl | 15.7 ± 0.6 | 14.5 | 18.7 | 13.61 ± 2.05 |
| pting | input-chancalan | 15.7 ± 0.6 | 14.7 | 18.6 | 13.62 ± 2.06 |
| chancalan | input-aspidites | 15.8 ± 0.6 | 14.7 | 19.0 | 13.75 ± 2.06 |
| chancalan | input-mattcl | 15.9 ± 0.7 | 15.0 | 19.2 | 13.78 ± 2.08 |
| chancalan | input-kcen | 15.9 ± 0.7 | 14.9 | 19.0 | 13.81 ± 2.09 |
| chancalan | input-lanjian | 15.9 ± 0.6 | 14.8 | 18.7 | 13.82 ± 2.08 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.9 | 19.2 | 13.85 ± 2.08 |
| mattcl-py | input-lanjian | 16.0 ± 0.7 | 14.8 | 18.6 | 13.88 ± 2.12 |
| mattcl-py | input-chancalan | 16.0 ± 0.7 | 15.0 | 19.0 | 13.90 ± 2.10 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.9 | 18.9 | 13.91 ± 2.12 |
| chancalan | input-chancalan | 16.2 ± 2.5 | 14.9 | 43.6 | 14.09 ± 2.98 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.3 | 18.7 | 14.22 ± 2.12 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.5 | 19.1 | 14.28 ± 2.14 |
| mattcl-py | input-aspidites | 16.5 ± 4.0 | 15.0 | 59.4 | 14.29 ± 4.03 |
| kcen | input-aspidites | 16.5 ± 0.7 | 15.3 | 19.9 | 14.36 ± 2.18 |
| kcen | input-mattcl | 16.6 ± 0.7 | 15.4 | 19.6 | 14.39 ± 2.19 |
| kcen | input-chancalan | 16.6 ± 2.6 | 15.2 | 50.9 | 14.43 ± 3.09 |


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