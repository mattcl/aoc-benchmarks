# Day 6 benchmarks

[link to problem](https://adventofcode.com/2023/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.29 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.5 | 1.04 ± 0.28 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.6 | 1.06 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.4 | 1.06 ± 0.30 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.5 | 1.1 | 1.08 ± 0.27 |
| mattcl-ts | input-mikofo | 10.1 ± 0.4 | 8.8 | 11.3 | 11.62 ± 2.53 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.1 | 11.2 | 11.66 ± 2.53 |
| mattcl-ts | input-lanjian | 10.1 ± 0.3 | 9.3 | 11.3 | 11.66 ± 2.54 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 9.1 | 11.2 | 11.68 ± 2.53 |
| mattcl-ts | input-mattcl | 11.2 ± 6.3 | 9.0 | 54.7 | 12.93 ± 7.78 |
| chancalan | input-chancalan | 14.2 ± 0.4 | 13.3 | 16.2 | 16.34 ± 3.55 |
| pting | input-mikofo | 14.2 ± 0.5 | 13.4 | 17.2 | 16.35 ± 3.56 |
| chancalan | input-kcen | 14.2 ± 0.6 | 13.4 | 17.5 | 16.36 ± 3.57 |
| pting | input-chancalan | 14.2 ± 0.5 | 13.2 | 17.4 | 16.37 ± 3.56 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 12.9 | 17.4 | 16.38 ± 3.59 |
| pting | input-kcen | 14.3 ± 0.5 | 13.2 | 17.0 | 16.42 ± 3.57 |
| chancalan | input-mattcl | 14.3 ± 0.6 | 13.2 | 17.2 | 16.42 ± 3.60 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.4 | 18.2 | 16.42 ± 3.63 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.5 | 17.3 | 16.43 ± 3.60 |
| chancalan | input-lanjian | 14.3 ± 0.7 | 12.9 | 17.6 | 16.43 ± 3.62 |
| mattcl-py | input-chancalan | 14.3 ± 0.7 | 13.2 | 17.6 | 16.45 ± 3.63 |
| kcen | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.2 | 16.47 ± 3.62 |
| kcen | input-kcen | 14.3 ± 0.6 | 13.0 | 17.5 | 16.48 ± 3.61 |
| kcen | input-mikofo | 14.3 ± 0.6 | 13.3 | 17.1 | 16.49 ± 3.62 |
| mattcl-py | input-kcen | 14.3 ± 0.7 | 13.4 | 17.7 | 16.49 ± 3.62 |
| kcen | input-mattcl | 14.3 ± 0.7 | 13.2 | 17.6 | 16.49 ± 3.63 |
| kcen | input-lanjian | 14.3 ± 0.6 | 13.4 | 17.2 | 16.51 ± 3.62 |
| mattcl-py | input-mikofo | 14.4 ± 0.6 | 13.5 | 17.3 | 16.54 ± 3.63 |
| pting | input-mattcl | 14.5 ± 2.6 | 13.4 | 49.8 | 16.66 ± 4.67 |
| chancalan | input-mikofo | 14.6 ± 3.4 | 12.9 | 53.6 | 16.81 ± 5.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|