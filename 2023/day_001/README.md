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
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.6 | 1.00 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.27 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.28 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.27 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.2 | 1.05 ± 0.25 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.6 | 1.06 ± 0.26 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.27 |
| mikofo | input-aspidites | 12.4 ± 0.3 | 11.4 | 13.3 | 12.81 ± 2.46 |
| mikofo | input-kcen | 12.4 ± 0.4 | 11.3 | 13.2 | 12.81 ± 2.46 |
| mikofo | input-lanjian | 12.4 ± 0.4 | 11.4 | 13.7 | 12.83 ± 2.47 |
| mikofo | input-chancalan | 12.5 ± 0.4 | 11.3 | 14.1 | 12.85 ± 2.48 |
| mattcl-ts | input-aspidites | 12.5 ± 0.3 | 11.6 | 13.6 | 12.87 ± 2.47 |
| mattcl-ts | input-chancalan | 12.5 ± 0.3 | 11.5 | 13.6 | 12.88 ± 2.47 |
| mikofo | input-mattcl | 12.5 ± 0.3 | 11.4 | 13.6 | 12.88 ± 2.47 |
| mattcl-ts | input-lanjian | 12.5 ± 0.3 | 11.6 | 13.4 | 12.89 ± 2.47 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.7 | 13.3 | 12.89 ± 2.47 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.3 | 13.1 | 12.89 ± 2.47 |
| aspidites | input-kcen | 12.5 ± 0.4 | 11.6 | 14.1 | 12.92 ± 2.50 |
| aspidites | input-aspidites | 12.6 ± 0.5 | 11.7 | 14.3 | 12.98 ± 2.51 |
| aspidites | input-chancalan | 12.6 ± 0.5 | 11.6 | 14.7 | 13.02 ± 2.52 |
| aspidites | input-mattcl | 12.6 ± 0.5 | 11.8 | 14.3 | 13.04 ± 2.52 |
| aspidites | input-lanjian | 12.7 ± 3.9 | 10.9 | 66.7 | 13.07 ± 4.72 |
| pting | input-chancalan | 15.3 ± 0.6 | 14.3 | 18.4 | 15.81 ± 3.07 |
| pting | input-mattcl | 15.4 ± 0.6 | 14.3 | 18.3 | 15.84 ± 3.08 |
| pting | input-kcen | 15.4 ± 0.6 | 14.4 | 17.8 | 15.88 ± 3.08 |
| pting | input-aspidites | 15.4 ± 0.7 | 14.4 | 18.5 | 15.90 ± 3.11 |
| pting | input-lanjian | 15.4 ± 0.7 | 14.5 | 18.5 | 15.92 ± 3.11 |
| chancalan | input-chancalan | 15.6 ± 0.6 | 14.7 | 18.5 | 16.11 ± 3.13 |
| mattcl-py | input-mattcl | 15.6 ± 0.5 | 14.6 | 18.4 | 16.14 ± 3.11 |
| mattcl-py | input-aspidites | 15.7 ± 0.6 | 14.7 | 18.6 | 16.16 ± 3.14 |
| chancalan | input-aspidites | 15.7 ± 0.7 | 14.7 | 18.8 | 16.18 ± 3.14 |
| mattcl-py | input-lanjian | 15.7 ± 0.7 | 14.5 | 18.8 | 16.19 ± 3.15 |
| chancalan | input-mattcl | 15.7 ± 0.7 | 14.7 | 18.8 | 16.23 ± 3.15 |
| chancalan | input-kcen | 15.7 ± 0.7 | 14.6 | 18.7 | 16.23 ± 3.17 |
| mattcl-py | input-kcen | 15.8 ± 0.8 | 14.7 | 18.9 | 16.30 ± 3.20 |
| mattcl-py | input-chancalan | 15.9 ± 3.1 | 14.5 | 56.9 | 16.44 ± 4.45 |
| chancalan | input-lanjian | 16.0 ± 2.8 | 14.8 | 51.0 | 16.48 ± 4.25 |
| kcen | input-mattcl | 16.2 ± 0.6 | 15.0 | 18.6 | 16.71 ± 3.23 |
| kcen | input-kcen | 16.2 ± 0.5 | 15.1 | 19.0 | 16.73 ± 3.21 |
| kcen | input-aspidites | 16.3 ± 0.5 | 15.1 | 18.2 | 16.77 ± 3.22 |
| kcen | input-chancalan | 16.3 ± 0.7 | 15.2 | 19.4 | 16.80 ± 3.28 |
| kcen | input-lanjian | 16.4 ± 2.0 | 15.2 | 41.1 | 16.95 ± 3.81 |


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