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
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.28 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.27 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.27 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.27 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 2.6 | 1.03 ± 0.31 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.5 | 1.06 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.5 | 1.07 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.07 ± 0.29 |
| mattcl-ts | input-chancalan | 12.4 ± 0.3 | 11.3 | 13.1 | 12.75 ± 2.55 |
| mattcl-ts | input-mattcl | 12.4 ± 0.3 | 11.3 | 13.3 | 12.76 ± 2.55 |
| mattcl-ts | input-lanjian | 12.4 ± 0.3 | 11.5 | 13.3 | 12.76 ± 2.55 |
| mattcl-ts | input-aspidites | 12.4 ± 0.3 | 11.2 | 13.5 | 12.79 ± 2.56 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.7 | 13.3 | 12.84 ± 2.56 |
| mikofo | input-mattcl | 12.5 ± 0.3 | 11.5 | 13.4 | 12.87 ± 2.57 |
| mikofo | input-lanjian | 12.5 ± 0.3 | 11.6 | 13.7 | 12.88 ± 2.57 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.6 | 13.5 | 12.91 ± 2.58 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.5 | 13.4 | 12.92 ± 2.58 |
| mikofo | input-aspidites | 12.6 ± 0.3 | 11.4 | 13.4 | 12.96 ± 2.59 |
| aspidites | input-kcen | 12.6 ± 0.4 | 11.6 | 13.8 | 12.96 ± 2.60 |
| aspidites | input-mattcl | 12.6 ± 0.5 | 11.6 | 13.9 | 12.98 ± 2.61 |
| aspidites | input-aspidites | 12.7 ± 0.4 | 11.6 | 13.8 | 13.03 ± 2.62 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.7 | 14.9 | 13.11 ± 2.64 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.5 | 13.12 ± 2.64 |
| pting | input-chancalan | 15.6 ± 0.5 | 14.5 | 18.2 | 16.00 ± 3.22 |
| pting | input-kcen | 15.7 ± 0.7 | 14.6 | 19.0 | 16.11 ± 3.27 |
| pting | input-mattcl | 15.7 ± 0.7 | 14.7 | 18.7 | 16.12 ± 3.27 |
| pting | input-aspidites | 15.7 ± 0.6 | 14.3 | 18.3 | 16.16 ± 3.27 |
| pting | input-lanjian | 15.7 ± 0.6 | 14.7 | 18.5 | 16.17 ± 3.27 |
| chancalan | input-kcen | 15.8 ± 0.6 | 14.7 | 19.4 | 16.25 ± 3.28 |
| mattcl-py | input-chancalan | 15.8 ± 0.5 | 14.4 | 18.6 | 16.28 ± 3.27 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.8 | 18.8 | 16.32 ± 3.30 |
| mattcl-py | input-kcen | 15.9 ± 0.7 | 14.5 | 19.1 | 16.33 ± 3.33 |
| chancalan | input-aspidites | 15.9 ± 0.7 | 14.7 | 19.1 | 16.35 ± 3.32 |
| mattcl-py | input-aspidites | 15.9 ± 0.7 | 14.7 | 18.9 | 16.36 ± 3.31 |
| chancalan | input-lanjian | 15.9 ± 0.6 | 14.5 | 18.6 | 16.36 ± 3.31 |
| chancalan | input-chancalan | 16.0 ± 0.7 | 14.6 | 19.5 | 16.41 ± 3.33 |
| mattcl-py | input-lanjian | 16.0 ± 0.7 | 14.8 | 18.6 | 16.41 ± 3.34 |
| chancalan | input-mattcl | 16.3 ± 3.6 | 14.7 | 52.2 | 16.80 ± 4.97 |
| kcen | input-lanjian | 16.4 ± 0.5 | 15.4 | 19.4 | 16.82 ± 3.38 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.4 | 19.6 | 16.88 ± 3.42 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.3 | 19.4 | 16.89 ± 3.40 |
| kcen | input-aspidites | 16.5 ± 0.8 | 15.1 | 20.1 | 16.97 ± 3.46 |
| kcen | input-mattcl | 16.6 ± 2.2 | 15.3 | 44.1 | 17.10 ± 4.07 |


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