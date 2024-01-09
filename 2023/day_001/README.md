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
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 ± 0.28 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.3 | 1.02 ± 0.24 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.25 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.4 | 1.6 | 1.03 ± 0.25 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.8 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 1.1 ± 0.1 | 0.5 | 1.8 | 1.04 ± 0.24 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.25 |
| lanjian | input-kcen | 1.1 ± 0.1 | 0.5 | 1.5 | 1.07 ± 0.24 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.9 | 13.6 | 11.84 ± 2.22 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.7 | 13.4 | 11.86 ± 2.22 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.5 | 13.5 | 11.88 ± 2.22 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.9 | 13.4 | 11.89 ± 2.22 |
| mattcl-ts | input-aspidites | 12.7 ± 0.3 | 11.9 | 14.1 | 11.89 ± 2.23 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.2 | 14.3 | 12.00 ± 2.27 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.1 | 12.01 ± 2.28 |
| mikofo | input-kcen | 12.8 ± 0.3 | 11.9 | 14.6 | 12.02 ± 2.25 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.8 | 14.5 | 12.03 ± 2.28 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 12.1 | 13.7 | 12.03 ± 2.25 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.9 | 14.6 | 12.05 ± 2.28 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 12.1 | 14.0 | 12.05 ± 2.26 |
| mikofo | input-aspidites | 12.8 ± 0.3 | 12.0 | 13.8 | 12.06 ± 2.26 |
| aspidites | input-aspidites | 12.9 ± 2.9 | 11.3 | 53.4 | 12.14 ± 3.55 |
| mikofo | input-lanjian | 13.5 ± 6.1 | 11.8 | 70.5 | 12.70 ± 6.20 |
| pting | input-chancalan | 15.5 ± 0.5 | 14.8 | 17.8 | 14.58 ± 2.75 |
| pting | input-kcen | 15.6 ± 0.6 | 14.9 | 18.5 | 14.63 ± 2.77 |
| pting | input-aspidites | 15.6 ± 0.7 | 14.5 | 18.5 | 14.64 ± 2.79 |
| chancalan | input-lanjian | 15.7 ± 0.6 | 14.7 | 19.2 | 14.78 ± 2.80 |
| pting | input-lanjian | 15.7 ± 1.7 | 14.4 | 36.4 | 14.79 ± 3.18 |
| mattcl-py | input-lanjian | 15.8 ± 0.5 | 14.8 | 19.1 | 14.85 ± 2.80 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.8 | 19.1 | 14.88 ± 2.83 |
| chancalan | input-mattcl | 15.9 ± 0.7 | 14.7 | 18.6 | 14.90 ± 2.85 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.7 | 18.7 | 14.92 ± 2.84 |
| chancalan | input-chancalan | 15.9 ± 0.7 | 14.6 | 18.6 | 14.93 ± 2.86 |
| mattcl-py | input-aspidites | 15.9 ± 0.7 | 14.7 | 18.6 | 14.94 ± 2.85 |
| chancalan | input-kcen | 15.9 ± 0.8 | 14.8 | 19.3 | 14.94 ± 2.87 |
| pting | input-mattcl | 15.9 ± 3.3 | 14.6 | 51.4 | 14.95 ± 4.15 |
| mattcl-py | input-chancalan | 16.0 ± 0.7 | 14.8 | 19.3 | 15.00 ± 2.86 |
| chancalan | input-aspidites | 16.2 ± 4.0 | 14.6 | 60.8 | 15.21 ± 4.67 |
| kcen | input-aspidites | 16.4 ± 0.7 | 15.2 | 19.9 | 15.41 ± 2.93 |
| kcen | input-chancalan | 16.4 ± 0.5 | 15.5 | 18.9 | 15.41 ± 2.90 |
| kcen | input-mattcl | 16.4 ± 0.6 | 15.3 | 19.7 | 15.42 ± 2.93 |
| kcen | input-kcen | 16.5 ± 0.7 | 15.2 | 19.7 | 15.46 ± 2.94 |
| kcen | input-lanjian | 16.6 ± 0.8 | 15.3 | 19.7 | 15.55 ± 2.99 |


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