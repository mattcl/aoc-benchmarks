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
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.6 | 1.07 ± 0.32 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.5 | 1.09 ± 0.33 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.09 ± 0.33 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.09 ± 0.33 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.7 | 1.09 ± 0.34 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.6 | 1.10 ± 0.36 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.10 ± 0.33 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.11 ± 0.34 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.8 | 1.12 ± 0.34 |
| mattcl-ts | input-aspidites | 12.6 ± 0.3 | 11.7 | 13.3 | 13.14 ± 3.41 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.7 | 13.7 | 13.14 ± 3.41 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.7 | 13.17 ± 3.42 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.9 | 13.9 | 13.22 ± 3.43 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.8 | 14.1 | 13.22 ± 3.44 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.6 | 14.7 | 13.32 ± 3.49 |
| aspidites | input-mattcl | 12.8 ± 0.4 | 11.8 | 14.1 | 13.34 ± 3.48 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 11.9 | 13.6 | 13.36 ± 3.47 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.8 | 14.1 | 13.36 ± 3.49 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 11.6 | 13.9 | 13.37 ± 3.48 |
| mikofo | input-aspidites | 12.8 ± 0.3 | 11.8 | 13.7 | 13.38 ± 3.48 |
| aspidites | input-lanjian | 12.8 ± 0.4 | 11.8 | 14.1 | 13.40 ± 3.49 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.8 | 14.5 | 13.40 ± 3.50 |
| mikofo | input-kcen | 12.8 ± 0.3 | 11.8 | 13.7 | 13.43 ± 3.49 |
| mikofo | input-chancalan | 12.9 ± 0.4 | 11.8 | 13.8 | 13.46 ± 3.50 |
| pting | input-chancalan | 15.7 ± 0.6 | 14.5 | 19.0 | 16.48 ± 4.31 |
| pting | input-kcen | 15.8 ± 0.6 | 14.6 | 18.7 | 16.51 ± 4.32 |
| pting | input-lanjian | 15.8 ± 0.7 | 14.6 | 18.8 | 16.52 ± 4.33 |
| pting | input-mattcl | 15.8 ± 0.8 | 14.8 | 18.7 | 16.55 ± 4.35 |
| pting | input-aspidites | 15.9 ± 0.9 | 14.5 | 19.1 | 16.65 ± 4.40 |
| chancalan | input-mattcl | 15.9 ± 0.7 | 14.7 | 19.5 | 16.65 ± 4.36 |
| mattcl-py | input-aspidites | 16.0 ± 0.7 | 14.9 | 18.8 | 16.70 ± 4.38 |
| mattcl-py | input-lanjian | 16.0 ± 0.6 | 14.9 | 19.3 | 16.72 ± 4.37 |
| chancalan | input-lanjian | 16.0 ± 0.6 | 15.1 | 18.8 | 16.76 ± 4.37 |
| chancalan | input-kcen | 16.0 ± 0.7 | 14.8 | 18.6 | 16.76 ± 4.40 |
| mattcl-py | input-chancalan | 16.0 ± 0.7 | 14.9 | 18.9 | 16.78 ± 4.39 |
| chancalan | input-aspidites | 16.0 ± 0.7 | 14.8 | 19.6 | 16.79 ± 4.41 |
| mattcl-py | input-kcen | 16.1 ± 0.7 | 14.9 | 19.2 | 16.82 ± 4.42 |
| chancalan | input-chancalan | 16.1 ± 1.1 | 14.8 | 26.5 | 16.89 ± 4.51 |
| mattcl-py | input-mattcl | 16.3 ± 2.8 | 14.7 | 52.7 | 17.10 ± 5.28 |
| kcen | input-mattcl | 16.5 ± 0.6 | 15.6 | 19.8 | 17.24 ± 4.50 |
| kcen | input-aspidites | 16.5 ± 0.6 | 15.5 | 19.6 | 17.27 ± 4.51 |
| kcen | input-lanjian | 16.5 ± 0.6 | 15.1 | 19.2 | 17.29 ± 4.52 |
| kcen | input-chancalan | 16.6 ± 0.7 | 15.8 | 19.9 | 17.33 ± 4.54 |
| kcen | input-kcen | 16.6 ± 0.7 | 15.6 | 19.6 | 17.38 ± 4.55 |


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