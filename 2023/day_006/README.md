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
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.1 | 1.03 ± 0.30 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.3 | 1.1 | 1.04 ± 0.31 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.3 | 1.3 | 1.05 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.2 | 1.05 ± 0.34 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.31 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.06 ± 0.29 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.7 | 1.08 ± 0.34 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.2 | 1.09 ± 0.33 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.09 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.7 | 1.11 ± 0.32 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.7 | 1.12 ± 0.33 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 8.9 | 10.9 | 11.39 ± 2.74 |
| mattcl-ts | input-mikofo | 10.1 ± 0.3 | 9.1 | 11.2 | 11.44 ± 2.75 |
| mattcl-ts | input-lanjian | 10.1 ± 0.4 | 9.2 | 11.6 | 11.44 ± 2.76 |
| mattcl-ts | input-chancalan | 10.2 ± 0.3 | 9.2 | 11.2 | 11.51 ± 2.77 |
| mattcl-ts | input-kcen | 10.2 ± 0.3 | 9.4 | 11.5 | 11.51 ± 2.77 |
| mattcl-ts | input-mattcl | 10.6 ± 4.9 | 8.9 | 68.2 | 12.01 ± 6.24 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.3 | 17.5 | 16.06 ± 3.88 |
| chancalan | input-chancalan | 14.2 ± 0.6 | 13.0 | 17.3 | 16.06 ± 3.88 |
| chancalan | input-mikofo | 14.2 ± 0.6 | 13.2 | 17.3 | 16.07 ± 3.89 |
| chancalan | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.4 | 16.09 ± 3.89 |
| pting | input-chancalan | 14.2 ± 0.7 | 13.1 | 18.1 | 16.10 ± 3.91 |
| pting | input-mattcl | 14.3 ± 0.5 | 13.3 | 16.6 | 16.12 ± 3.87 |
| pting | input-kcen | 14.3 ± 0.7 | 13.3 | 17.9 | 16.13 ± 3.92 |
| mattcl-py | input-chancalan | 14.3 ± 0.5 | 13.3 | 17.3 | 16.13 ± 3.89 |
| kcen | input-kcen | 14.3 ± 0.7 | 13.1 | 17.7 | 16.13 ± 3.93 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.3 | 17.9 | 16.16 ± 3.91 |
| mattcl-py | input-mikofo | 14.3 ± 0.7 | 13.0 | 17.8 | 16.16 ± 3.94 |
| chancalan | input-lanjian | 14.3 ± 0.6 | 13.3 | 17.5 | 16.16 ± 3.91 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.2 | 17.2 | 16.16 ± 3.94 |
| kcen | input-mikofo | 14.3 ± 0.7 | 13.0 | 18.0 | 16.17 ± 3.92 |
| pting | input-mikofo | 14.3 ± 0.7 | 13.3 | 18.2 | 16.17 ± 3.93 |
| chancalan | input-kcen | 14.3 ± 0.7 | 13.4 | 17.2 | 16.18 ± 3.93 |
| mattcl-py | input-pting | 14.3 ± 0.7 | 13.4 | 17.6 | 16.19 ± 3.94 |
| kcen | input-mattcl | 14.3 ± 0.7 | 13.3 | 17.6 | 16.20 ± 3.94 |
| kcen | input-lanjian | 14.3 ± 0.7 | 13.3 | 17.7 | 16.22 ± 3.94 |
| pting | input-pting | 14.4 ± 0.6 | 13.6 | 17.4 | 16.24 ± 3.92 |
| chancalan | input-pting | 14.4 ± 2.0 | 13.4 | 40.9 | 16.27 ± 4.46 |
| kcen | input-pting | 14.4 ± 0.6 | 13.2 | 17.4 | 16.32 ± 3.95 |
| kcen | input-chancalan | 14.5 ± 2.4 | 13.2 | 46.7 | 16.42 ± 4.74 |
| mattcl-py | input-mattcl | 15.2 ± 5.4 | 13.4 | 53.7 | 17.13 ± 7.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|