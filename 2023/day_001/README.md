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
| mattcl | input-aspidites | 0.9 ± 0.3 | 0.3 | 1.4 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.3 | 1.17 ± 0.40 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.18 ± 0.40 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.5 | 1.18 ± 0.39 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.9 | 1.19 ± 0.41 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.39 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.19 ± 0.40 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.20 ± 0.40 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.7 | 1.25 ± 0.40 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 2.1 | 1.25 ± 0.42 |
| mikofo | input-mattcl | 12.1 ± 0.5 | 11.0 | 13.1 | 12.77 ± 3.83 |
| mikofo | input-kcen | 12.2 ± 0.5 | 11.1 | 13.9 | 12.80 ± 3.84 |
| mikofo | input-lanjian | 12.2 ± 0.4 | 11.2 | 13.1 | 12.83 ± 3.84 |
| mattcl-ts | input-lanjian | 12.2 ± 0.4 | 11.1 | 13.2 | 12.83 ± 3.84 |
| mattcl-ts | input-kcen | 12.2 ± 0.5 | 11.0 | 13.4 | 12.83 ± 3.85 |
| mikofo | input-chancalan | 12.2 ± 0.4 | 11.0 | 13.4 | 12.86 ± 3.85 |
| mikofo | input-aspidites | 12.2 ± 0.4 | 11.2 | 13.1 | 12.88 ± 3.85 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.1 | 13.0 | 12.89 ± 3.86 |
| mattcl-ts | input-aspidites | 12.3 ± 0.4 | 11.1 | 13.4 | 12.90 ± 3.86 |
| mattcl-ts | input-chancalan | 12.3 ± 0.4 | 10.8 | 13.3 | 12.94 ± 3.87 |
| aspidites | input-aspidites | 12.6 ± 0.4 | 11.6 | 13.7 | 13.28 ± 3.97 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.6 | 14.4 | 13.36 ± 4.01 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.7 | 14.2 | 13.36 ± 3.99 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.6 | 15.1 | 13.42 ± 4.02 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.9 | 14.3 | 13.47 ± 4.03 |
| pting | input-lanjian | 15.8 ± 0.6 | 14.6 | 18.5 | 16.60 ± 4.98 |
| pting | input-aspidites | 15.8 ± 0.6 | 15.0 | 19.2 | 16.60 ± 4.98 |
| pting | input-chancalan | 15.9 ± 0.7 | 15.0 | 18.4 | 16.68 ± 5.01 |
| pting | input-kcen | 15.9 ± 0.6 | 14.9 | 18.5 | 16.73 ± 5.01 |
| pting | input-mattcl | 15.9 ± 0.7 | 15.0 | 18.8 | 16.74 ± 5.03 |
| mattcl-py | input-lanjian | 16.0 ± 0.6 | 14.7 | 19.1 | 16.87 ± 5.06 |
| mattcl-py | input-mattcl | 16.1 ± 0.7 | 14.7 | 18.8 | 16.93 ± 5.09 |
| chancalan | input-mattcl | 16.1 ± 0.6 | 15.2 | 18.6 | 16.93 ± 5.07 |
| chancalan | input-aspidites | 16.1 ± 0.7 | 15.1 | 19.5 | 16.93 ± 5.09 |
| chancalan | input-lanjian | 16.1 ± 0.6 | 14.8 | 19.0 | 16.94 ± 5.08 |
| mattcl-py | input-kcen | 16.1 ± 0.8 | 14.7 | 19.1 | 16.95 ± 5.11 |
| chancalan | input-kcen | 16.1 ± 0.8 | 14.8 | 19.5 | 16.95 ± 5.10 |
| mattcl-py | input-aspidites | 16.1 ± 0.5 | 15.0 | 18.6 | 16.95 ± 5.07 |
| chancalan | input-chancalan | 16.1 ± 0.7 | 14.7 | 19.3 | 16.98 ± 5.10 |
| mattcl-py | input-chancalan | 16.1 ± 0.6 | 14.8 | 18.8 | 16.98 ± 5.09 |
| kcen | input-kcen | 16.5 ± 0.6 | 15.3 | 19.6 | 17.34 ± 5.19 |
| kcen | input-mattcl | 16.5 ± 0.7 | 15.6 | 20.4 | 17.39 ± 5.22 |
| kcen | input-lanjian | 16.6 ± 0.7 | 15.3 | 19.8 | 17.46 ± 5.25 |
| kcen | input-chancalan | 16.6 ± 0.8 | 15.3 | 19.9 | 17.48 ± 5.26 |
| kcen | input-aspidites | 16.7 ± 0.8 | 15.4 | 19.7 | 17.59 ± 5.29 |


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