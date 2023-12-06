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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 ± 0.28 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.3 | 1.01 ± 0.28 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.3 | 1.3 | 1.01 ± 0.27 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.26 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.1 | 1.05 ± 0.25 |
| lanjian | input-chancalan | 1.9 ± 0.2 | 1.1 | 3.5 | 2.06 ± 0.47 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.3 | 2.5 | 2.10 ± 0.43 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.3 | 2.5 | 2.10 ± 0.43 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.1 | 3.2 | 2.10 ± 0.44 |
| lanjian | input-pting | 1.9 ± 0.1 | 1.4 | 2.9 | 2.11 ± 0.44 |
| lanjian | input-aspidites | 1.9 ± 3.4 | 0.9 | 49.3 | 2.11 ± 3.70 |
| mattcl-ts | input-aspidites | 11.8 ± 0.4 | 10.7 | 12.8 | 12.81 ± 2.51 |
| mattcl-ts | input-lanjian | 11.9 ± 0.4 | 10.7 | 13.1 | 12.91 ± 2.55 |
| mattcl-ts | input-chancalan | 11.9 ± 0.4 | 10.9 | 12.7 | 12.91 ± 2.53 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 11.1 | 12.9 | 12.96 ± 2.54 |
| mattcl-ts | input-pting | 11.9 ± 0.4 | 11.0 | 12.9 | 12.97 ± 2.54 |
| mattcl-ts | input-mattcl | 11.9 ± 0.4 | 10.8 | 13.1 | 13.00 ± 2.55 |
| aspidites | input-chancalan | 12.7 ± 0.4 | 11.6 | 13.9 | 13.83 ± 2.72 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.8 | 14.4 | 13.91 ± 2.74 |
| aspidites | input-mattcl | 12.8 ± 1.6 | 11.2 | 34.4 | 13.94 ± 3.23 |
| aspidites | input-pting | 12.8 ± 0.4 | 11.6 | 13.9 | 13.94 ± 2.74 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 12.0 | 14.0 | 13.95 ± 2.75 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.9 | 14.2 | 13.96 ± 2.75 |
| pting | input-aspidites | 15.4 ± 0.6 | 14.2 | 18.3 | 16.71 ± 3.30 |
| pting | input-kcen | 15.4 ± 0.6 | 14.5 | 18.4 | 16.75 ± 3.32 |
| pting | input-mattcl | 15.4 ± 0.7 | 14.5 | 18.5 | 16.76 ± 3.33 |
| pting | input-lanjian | 15.4 ± 0.6 | 14.5 | 18.6 | 16.80 ± 3.32 |
| pting | input-pting | 15.5 ± 0.6 | 14.4 | 18.4 | 16.83 ± 3.33 |
| pting | input-chancalan | 15.5 ± 0.8 | 14.4 | 19.2 | 16.85 ± 3.36 |
| mattcl-py | input-aspidites | 15.5 ± 0.4 | 14.9 | 17.7 | 16.89 ± 3.31 |
| mattcl-py | input-lanjian | 15.6 ± 0.6 | 14.9 | 18.5 | 17.00 ± 3.35 |
| mattcl-py | input-mattcl | 15.7 ± 0.6 | 14.7 | 18.4 | 17.04 ± 3.36 |
| mattcl-py | input-kcen | 15.7 ± 0.6 | 14.8 | 18.7 | 17.07 ± 3.37 |
| chancalan | input-kcen | 15.8 ± 0.5 | 14.8 | 17.9 | 17.15 ± 3.36 |
| mattcl-py | input-chancalan | 15.8 ± 0.7 | 14.8 | 18.6 | 17.15 ± 3.41 |
| mattcl-py | input-pting | 15.8 ± 0.7 | 14.8 | 19.0 | 17.20 ± 3.43 |
| chancalan | input-aspidites | 15.8 ± 0.7 | 14.6 | 18.7 | 17.24 ± 3.43 |
| chancalan | input-chancalan | 15.9 ± 0.6 | 14.9 | 18.7 | 17.26 ± 3.41 |
| chancalan | input-lanjian | 15.9 ± 0.6 | 14.9 | 18.7 | 17.32 ± 3.42 |
| chancalan | input-pting | 15.9 ± 0.8 | 14.8 | 19.4 | 17.33 ± 3.46 |
| chancalan | input-mattcl | 16.1 ± 1.9 | 14.9 | 40.3 | 17.47 ± 3.97 |
| kcen | input-pting | 16.3 ± 0.6 | 15.1 | 19.9 | 17.72 ± 3.49 |
| kcen | input-chancalan | 16.3 ± 0.7 | 15.2 | 19.5 | 17.76 ± 3.51 |
| kcen | input-mattcl | 16.3 ± 0.6 | 15.2 | 19.7 | 17.78 ± 3.50 |
| kcen | input-lanjian | 16.3 ± 0.6 | 15.0 | 19.4 | 17.79 ± 3.52 |
| kcen | input-kcen | 16.5 ± 0.8 | 15.1 | 19.9 | 17.90 ± 3.57 |
| kcen | input-aspidites | 16.6 ± 4.1 | 15.2 | 60.6 | 18.11 ± 5.66 |
| mikofo | input-aspidites | 31.4 ± 0.6 | 30.4 | 34.5 | 34.14 ± 6.64 |
| mikofo | input-kcen | 31.4 ± 0.5 | 30.3 | 32.8 | 34.14 ± 6.63 |
| mikofo | input-lanjian | 31.4 ± 0.5 | 30.0 | 32.4 | 34.17 ± 6.64 |
| mikofo | input-mattcl | 31.4 ± 0.4 | 30.2 | 32.3 | 34.18 ± 6.63 |
| mikofo | input-chancalan | 31.5 ± 0.6 | 30.3 | 33.8 | 34.27 ± 6.67 |
| mikofo | input-pting | 31.5 ± 0.5 | 30.7 | 33.4 | 34.32 ± 6.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|