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
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.5 | 1.01 ± 0.28 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.5 | 1.01 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.27 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.27 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.27 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 2.5 | 1.03 ± 0.30 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.3 | 1.03 ± 0.26 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.6 | 1.05 ± 0.26 |
| mattcl-ts | input-lanjian | 12.5 ± 0.3 | 11.7 | 13.3 | 12.22 ± 2.51 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.6 | 13.2 | 12.22 ± 2.51 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.4 | 13.2 | 12.25 ± 2.51 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.8 | 13.3 | 12.25 ± 2.51 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.8 | 13.4 | 12.28 ± 2.52 |
| mattcl-ts | input-aspidites | 12.6 ± 0.3 | 11.8 | 13.8 | 12.28 ± 2.52 |
| mikofo | input-lanjian | 12.6 ± 0.4 | 11.6 | 13.9 | 12.30 ± 2.53 |
| mikofo | input-mattcl | 12.6 ± 0.3 | 11.8 | 13.7 | 12.32 ± 2.53 |
| mikofo | input-aspidites | 12.7 ± 0.3 | 11.6 | 13.9 | 12.33 ± 2.53 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.7 | 13.7 | 12.34 ± 2.54 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.8 | 14.5 | 12.36 ± 2.56 |
| aspidites | input-chancalan | 12.7 ± 0.4 | 11.5 | 14.1 | 12.39 ± 2.56 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.8 | 15.1 | 12.39 ± 2.57 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.4 | 14.3 | 12.39 ± 2.57 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.6 | 13.7 | 12.42 ± 2.57 |
| pting | input-lanjian | 15.4 ± 0.5 | 14.8 | 17.8 | 15.04 ± 3.11 |
| pting | input-chancalan | 15.5 ± 0.6 | 14.4 | 18.4 | 15.07 ± 3.13 |
| pting | input-mattcl | 15.5 ± 0.7 | 14.6 | 18.9 | 15.11 ± 3.15 |
| pting | input-aspidites | 15.5 ± 0.7 | 14.8 | 19.0 | 15.13 ± 3.17 |
| pting | input-kcen | 15.7 ± 1.6 | 14.3 | 35.1 | 15.27 ± 3.48 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.8 | 18.6 | 15.31 ± 3.17 |
| chancalan | input-mattcl | 15.7 ± 0.7 | 14.7 | 19.2 | 15.33 ± 3.19 |
| chancalan | input-chancalan | 15.7 ± 0.5 | 14.7 | 18.5 | 15.33 ± 3.17 |
| chancalan | input-lanjian | 15.7 ± 0.6 | 14.7 | 18.6 | 15.34 ± 3.18 |
| mattcl-py | input-aspidites | 15.7 ± 0.7 | 14.6 | 18.6 | 15.35 ± 3.20 |
| chancalan | input-kcen | 15.8 ± 0.7 | 14.7 | 18.8 | 15.37 ± 3.20 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.9 | 18.6 | 15.40 ± 3.21 |
| mattcl-py | input-mattcl | 15.8 ± 0.8 | 14.7 | 19.3 | 15.40 ± 3.23 |
| chancalan | input-aspidites | 15.8 ± 0.7 | 14.7 | 19.0 | 15.40 ± 3.21 |
| mattcl-py | input-chancalan | 15.8 ± 0.7 | 14.6 | 19.5 | 15.41 ± 3.22 |
| kcen | input-mattcl | 16.3 ± 0.5 | 15.4 | 18.6 | 15.90 ± 3.28 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.6 | 18.9 | 15.94 ± 3.31 |
| kcen | input-aspidites | 16.4 ± 0.7 | 15.1 | 19.4 | 15.97 ± 3.33 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.1 | 19.7 | 15.98 ± 3.32 |
| kcen | input-chancalan | 16.4 ± 0.8 | 15.1 | 19.7 | 16.01 ± 3.35 |


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