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
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.33 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.31 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.32 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.4 | 1.05 ± 0.34 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.3 | 1.06 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.33 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.4 | 1.10 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.4 | 1.10 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.4 | 1.11 ± 0.30 |
| mattcl-ts | input-chancalan | 10.0 ± 0.3 | 9.1 | 11.2 | 12.12 ± 2.86 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.2 | 11.5 | 12.20 ± 2.88 |
| mattcl-ts | input-mikofo | 10.1 ± 0.3 | 9.0 | 11.1 | 12.24 ± 2.89 |
| mattcl-ts | input-mattcl | 10.1 ± 0.3 | 8.9 | 11.6 | 12.25 ± 2.89 |
| mattcl-ts | input-lanjian | 10.3 ± 2.2 | 9.0 | 32.1 | 12.45 ± 3.95 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.0 | 17.3 | 17.07 ± 4.05 |
| mattcl-py | input-chancalan | 14.2 ± 0.5 | 12.9 | 17.4 | 17.09 ± 4.04 |
| chancalan | input-mikofo | 14.2 ± 0.7 | 13.2 | 17.3 | 17.13 ± 4.08 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.2 | 17.6 | 17.13 ± 4.08 |
| pting | input-chancalan | 14.2 ± 0.5 | 13.4 | 16.9 | 17.13 ± 4.05 |
| chancalan | input-mattcl | 14.2 ± 0.6 | 13.3 | 16.9 | 17.14 ± 4.06 |
| chancalan | input-lanjian | 14.2 ± 0.6 | 13.2 | 17.1 | 17.17 ± 4.07 |
| chancalan | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.2 | 17.17 ± 4.08 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.2 | 17.8 | 17.18 ± 4.08 |
| pting | input-kcen | 14.2 ± 0.7 | 13.3 | 17.8 | 17.18 ± 4.10 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.5 | 17.4 | 17.21 ± 4.08 |
| kcen | input-mikofo | 14.2 ± 0.6 | 13.1 | 17.3 | 17.21 ± 4.09 |
| pting | input-mattcl | 14.3 ± 0.6 | 13.0 | 17.1 | 17.22 ± 4.09 |
| kcen | input-kcen | 14.3 ± 0.8 | 13.3 | 17.9 | 17.23 ± 4.13 |
| kcen | input-lanjian | 14.3 ± 0.7 | 13.2 | 18.0 | 17.24 ± 4.11 |
| mattcl-py | input-mikofo | 14.3 ± 0.7 | 13.4 | 17.8 | 17.24 ± 4.11 |
| kcen | input-mattcl | 14.3 ± 0.5 | 13.1 | 17.2 | 17.25 ± 4.08 |
| mattcl-py | input-kcen | 14.3 ± 0.7 | 13.2 | 17.5 | 17.26 ± 4.11 |
| pting | input-mikofo | 14.3 ± 0.8 | 13.3 | 17.5 | 17.30 ± 4.15 |
| kcen | input-chancalan | 14.5 ± 2.6 | 13.4 | 50.6 | 17.52 ± 5.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|