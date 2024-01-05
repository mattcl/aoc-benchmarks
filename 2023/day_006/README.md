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
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.6 | 1.01 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.31 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.33 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.0 | 1.04 ± 0.30 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.36 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.09 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.1 | 1.11 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.5 | 1.12 ± 0.31 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 8.9 | 10.8 | 12.16 ± 2.79 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 8.9 | 11.3 | 12.16 ± 2.79 |
| mattcl-ts | input-mikofo | 10.1 ± 0.3 | 9.1 | 10.7 | 12.18 ± 2.78 |
| mattcl-ts | input-lanjian | 10.1 ± 0.3 | 8.9 | 11.4 | 12.27 ± 2.79 |
| mattcl-ts | input-kcen | 10.3 ± 3.6 | 9.0 | 60.4 | 12.48 ± 5.17 |
| chancalan | input-lanjian | 14.1 ± 0.6 | 13.1 | 16.7 | 17.08 ± 3.92 |
| pting | input-chancalan | 14.1 ± 0.5 | 13.3 | 17.2 | 17.09 ± 3.90 |
| chancalan | input-kcen | 14.1 ± 0.6 | 12.9 | 17.5 | 17.09 ± 3.94 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.1 | 17.3 | 17.11 ± 3.93 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.0 | 17.3 | 17.11 ± 3.94 |
| mattcl-py | input-mikofo | 14.1 ± 0.6 | 13.1 | 17.6 | 17.13 ± 3.94 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.0 | 17.4 | 17.15 ± 3.95 |
| chancalan | input-mikofo | 14.2 ± 0.6 | 13.2 | 17.4 | 17.18 ± 3.96 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.3 | 17.8 | 17.18 ± 3.98 |
| pting | input-mikofo | 14.2 ± 0.6 | 13.1 | 18.0 | 17.18 ± 3.96 |
| kcen | input-mattcl | 14.2 ± 0.7 | 13.0 | 18.1 | 17.19 ± 3.98 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.1 | 17.4 | 17.20 ± 3.97 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.7 | 17.22 ± 3.95 |
| kcen | input-lanjian | 14.2 ± 0.7 | 13.3 | 17.1 | 17.23 ± 3.98 |
| kcen | input-mikofo | 14.2 ± 0.7 | 13.4 | 17.5 | 17.24 ± 3.98 |
| kcen | input-chancalan | 14.2 ± 0.6 | 13.4 | 17.6 | 17.25 ± 3.98 |
| pting | input-lanjian | 14.3 ± 0.8 | 13.2 | 17.6 | 17.27 ± 4.02 |
| mattcl-py | input-mattcl | 14.3 ± 0.7 | 13.2 | 17.8 | 17.29 ± 4.01 |
| pting | input-kcen | 14.4 ± 2.9 | 13.1 | 53.9 | 17.50 ± 5.30 |
| kcen | input-kcen | 14.5 ± 2.5 | 13.1 | 48.9 | 17.54 ± 5.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|