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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.3 | 1.02 ± 0.25 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.25 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.5 | 1.05 ± 0.26 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.26 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.26 |
| lanjian | input-chancalan | 1.1 ± 0.1 | 0.5 | 1.6 | 1.06 ± 0.25 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.07 ± 0.30 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.5 | 1.8 | 1.07 ± 0.27 |
| mattcl-ts | input-aspidites | 12.5 ± 0.3 | 11.6 | 13.6 | 12.05 ± 2.37 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.7 | 13.2 | 12.07 ± 2.37 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.2 | 13.3 | 12.07 ± 2.37 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.7 | 12.10 ± 2.37 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.7 | 13.5 | 12.10 ± 2.37 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.8 | 14.0 | 12.24 ± 2.42 |
| aspidites | input-lanjian | 12.8 ± 0.4 | 11.7 | 14.0 | 12.26 ± 2.43 |
| mikofo | input-kcen | 12.8 ± 0.3 | 11.9 | 13.6 | 12.30 ± 2.42 |
| aspidites | input-mattcl | 12.8 ± 0.4 | 11.8 | 14.2 | 12.31 ± 2.43 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.9 | 14.3 | 12.32 ± 2.44 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 11.9 | 13.6 | 12.33 ± 2.42 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 11.9 | 13.9 | 12.33 ± 2.42 |
| mikofo | input-aspidites | 12.8 ± 0.4 | 12.0 | 15.3 | 12.34 ± 2.43 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 12.1 | 14.0 | 12.36 ± 2.43 |
| aspidites | input-kcen | 12.9 ± 0.4 | 11.9 | 14.1 | 12.39 ± 2.45 |
| pting | input-lanjian | 15.5 ± 0.6 | 14.5 | 18.8 | 14.94 ± 2.98 |
| pting | input-mattcl | 15.6 ± 0.6 | 14.3 | 18.5 | 14.96 ± 2.98 |
| pting | input-chancalan | 15.6 ± 0.6 | 14.6 | 18.9 | 14.96 ± 2.98 |
| pting | input-kcen | 15.6 ± 0.6 | 14.5 | 18.4 | 14.99 ± 2.97 |
| pting | input-aspidites | 15.6 ± 0.8 | 14.8 | 19.0 | 15.01 ± 3.02 |
| chancalan | input-aspidites | 15.8 ± 0.7 | 14.6 | 18.8 | 15.19 ± 3.04 |
| mattcl-py | input-aspidites | 15.8 ± 0.7 | 14.8 | 18.9 | 15.22 ± 3.03 |
| chancalan | input-kcen | 15.8 ± 0.6 | 14.7 | 18.7 | 15.22 ± 3.03 |
| mattcl-py | input-mattcl | 15.8 ± 0.6 | 14.9 | 18.2 | 15.23 ± 3.02 |
| chancalan | input-mattcl | 15.9 ± 0.7 | 15.0 | 19.1 | 15.25 ± 3.05 |
| chancalan | input-chancalan | 15.9 ± 0.7 | 14.8 | 19.0 | 15.30 ± 3.06 |
| chancalan | input-lanjian | 15.9 ± 0.7 | 15.0 | 18.5 | 15.31 ± 3.06 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 15.0 | 19.0 | 15.33 ± 3.07 |
| mattcl-py | input-chancalan | 16.0 ± 0.8 | 15.1 | 19.3 | 15.34 ± 3.08 |
| mattcl-py | input-lanjian | 16.0 ± 2.8 | 14.6 | 52.6 | 15.36 ± 4.05 |
| kcen | input-aspidites | 16.3 ± 0.5 | 15.3 | 18.8 | 15.70 ± 3.10 |
| kcen | input-mattcl | 16.4 ± 0.6 | 15.2 | 19.5 | 15.78 ± 3.12 |
| kcen | input-chancalan | 16.4 ± 0.6 | 15.3 | 19.7 | 15.79 ± 3.14 |
| kcen | input-lanjian | 16.5 ± 0.6 | 15.7 | 19.3 | 15.82 ± 3.14 |
| kcen | input-kcen | 16.5 ± 0.7 | 15.4 | 20.0 | 15.83 ± 3.16 |


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