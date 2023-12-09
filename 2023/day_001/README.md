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
| mattcl | input-kcen | 0.5 ± 0.2 | 0.2 | 1.0 | 1.00 |
| lanjian | input-kcen | 0.9 ± 0.3 | 0.3 | 1.3 | 1.86 ± 1.11 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 2.05 ± 1.13 |
| mattcl | input-mattcl | 1.0 ± 0.3 | 0.2 | 1.3 | 2.08 ± 1.17 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.2 | 2.09 ± 1.12 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.5 | 1.4 | 2.13 ± 1.08 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.5 | 2.13 ± 1.08 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.2 | 2.16 ± 1.09 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.4 | 1.2 | 2.17 ± 1.10 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.6 | 2.18 ± 1.11 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.3 | 2.19 ± 1.15 |
| lanjian | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.3 | 2.30 ± 1.18 |
| mattcl | input-lanjian | 1.3 ± 0.1 | 1.1 | 1.7 | 2.78 ± 1.36 |
| lanjian | input-lanjian | 1.3 ± 0.1 | 1.1 | 2.4 | 2.91 ± 1.42 |
| aspidites | input-pting | 11.6 ± 0.2 | 11.2 | 12.5 | 25.47 ± 12.25 |
| aspidites | input-mattcl | 11.8 ± 0.5 | 11.2 | 15.9 | 25.88 ± 12.48 |
| aspidites | input-mikofo | 11.9 ± 0.1 | 11.6 | 12.4 | 25.94 ± 12.48 |
| mattcl-ts | input-aspidites | 12.2 ± 0.4 | 11.2 | 13.1 | 26.59 ± 12.81 |
| aspidites | input-lanjian | 12.2 ± 1.2 | 10.8 | 21.8 | 26.64 ± 13.07 |
| mattcl-ts | input-mikofo | 12.3 ± 0.3 | 11.4 | 13.0 | 26.94 ± 12.97 |
| mattcl-ts | input-pting | 12.4 ± 0.4 | 11.2 | 14.2 | 27.07 ± 13.04 |
| mattcl-ts | input-chancalan | 12.6 ± 4.6 | 11.2 | 60.9 | 27.64 ± 16.68 |
| mikofo | input-aspidites | 12.6 ± 0.3 | 11.8 | 13.4 | 27.65 ± 13.31 |
| aspidites | input-kcen | 12.7 ± 2.0 | 11.0 | 25.5 | 27.69 ± 14.01 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.3 | 14.2 | 27.77 ± 13.40 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.8 | 14.6 | 27.96 ± 13.48 |
| mattcl-ts | input-mattcl | 12.9 ± 0.3 | 12.2 | 14.0 | 28.26 ± 13.61 |
| mikofo | input-mattcl | 13.7 ± 3.4 | 12.6 | 61.9 | 30.01 ± 16.27 |
| mattcl-ts | input-lanjian | 13.8 ± 1.2 | 12.1 | 20.2 | 30.27 ± 14.78 |
| mikofo | input-lanjian | 14.7 ± 2.9 | 13.0 | 42.3 | 32.20 ± 16.72 |
| mikofo | input-pting | 14.7 ± 7.3 | 12.2 | 57.2 | 32.20 ± 22.32 |
| mikofo | input-mikofo | 15.0 ± 7.9 | 12.3 | 59.3 | 32.86 ± 23.38 |
| pting | input-aspidites | 15.6 ± 1.1 | 14.4 | 25.7 | 34.12 ± 16.57 |
| mattcl-py | input-aspidites | 15.8 ± 0.7 | 14.7 | 19.2 | 34.54 ± 16.69 |
| chancalan | input-chancalan | 15.9 ± 0.6 | 14.7 | 18.9 | 34.71 ± 16.75 |
| chancalan | input-aspidites | 16.0 ± 0.7 | 14.9 | 19.1 | 34.95 ± 16.86 |
| pting | input-pting | 16.0 ± 0.6 | 14.9 | 18.2 | 35.09 ± 16.93 |
| mattcl-py | input-chancalan | 16.1 ± 4.2 | 14.7 | 72.1 | 35.21 ± 19.25 |
| mattcl-py | input-pting | 16.2 ± 0.4 | 15.1 | 19.0 | 35.34 ± 17.02 |
| mattcl-py | input-mikofo | 16.2 ± 0.5 | 15.2 | 18.7 | 35.47 ± 17.09 |
| pting | input-mikofo | 16.3 ± 0.6 | 15.1 | 18.8 | 35.55 ± 17.15 |
| kcen | input-aspidites | 16.4 ± 0.7 | 15.3 | 19.6 | 35.86 ± 17.30 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.2 | 19.7 | 35.90 ± 17.33 |
| chancalan | input-pting | 16.4 ± 0.5 | 15.4 | 18.9 | 35.96 ± 17.33 |
| pting | input-mattcl | 16.6 ± 0.5 | 15.9 | 18.7 | 36.41 ± 17.54 |
| kcen | input-mikofo | 16.9 ± 0.6 | 15.7 | 19.0 | 36.98 ± 17.82 |
| pting | input-kcen | 16.9 ± 1.0 | 15.7 | 22.7 | 37.00 ± 17.92 |
| chancalan | input-mikofo | 17.0 ± 0.5 | 15.9 | 19.2 | 37.09 ± 17.87 |
| mattcl-py | input-mattcl | 17.1 ± 0.6 | 16.2 | 19.3 | 37.36 ± 18.01 |
| pting | input-chancalan | 17.2 ± 1.8 | 15.3 | 29.4 | 37.71 ± 18.54 |
| kcen | input-pting | 18.0 ± 2.9 | 15.7 | 26.3 | 39.28 ± 19.92 |
| chancalan | input-mattcl | 18.0 ± 1.3 | 17.1 | 29.6 | 39.32 ± 19.12 |
| pting | input-lanjian | 18.1 ± 3.7 | 15.3 | 35.4 | 39.48 ± 20.67 |
| kcen | input-mattcl | 18.2 ± 0.6 | 17.2 | 20.6 | 39.88 ± 19.22 |
| mikofo | input-chancalan | 20.6 ± 10.2 | 12.1 | 72.3 | 45.07 ± 31.06 |
| mattcl-py | input-kcen | 20.7 ± 7.8 | 16.6 | 58.7 | 45.20 ± 27.68 |
| mikofo | input-kcen | 21.3 ± 9.9 | 13.5 | 55.6 | 46.54 ± 31.07 |
| mattcl-py | input-lanjian | 25.5 ± 5.9 | 20.3 | 37.1 | 55.69 ± 29.69 |
| mattcl-ts | input-kcen | 28.0 ± 15.4 | 12.3 | 104.6 | 61.20 ± 44.64 |
| chancalan | input-kcen | 31.0 ± 6.9 | 18.5 | 38.6 | 67.81 ± 35.95 |
| kcen | input-kcen | 33.5 ± 7.8 | 19.2 | 43.6 | 73.24 ± 39.12 |
| chancalan | input-lanjian | 35.4 ± 3.0 | 30.3 | 53.0 | 77.39 ± 37.79 |
| kcen | input-lanjian | 36.4 ± 1.3 | 33.0 | 39.2 | 79.62 ± 38.39 |


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