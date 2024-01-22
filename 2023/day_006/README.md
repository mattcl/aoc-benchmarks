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
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.33 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.34 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.6 | 1.04 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.36 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.33 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.07 ± 0.34 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.3 | 1.07 ± 0.32 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.4 | 1.4 | 1.09 ± 0.33 |
| mattcl-ts | input-kcen | 10.0 ± 0.4 | 9.0 | 11.2 | 12.09 ± 3.05 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 8.8 | 11.9 | 12.10 ± 3.05 |
| mattcl-ts | input-mikofo | 10.0 ± 0.3 | 9.1 | 10.9 | 12.11 ± 3.05 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.2 | 11.0 | 12.17 ± 3.06 |
| mattcl-ts | input-chancalan | 10.1 ± 0.4 | 9.2 | 11.3 | 12.21 ± 3.07 |
| mattcl-py | input-kcen | 14.1 ± 0.5 | 13.2 | 17.1 | 17.05 ± 4.29 |
| chancalan | input-kcen | 14.1 ± 0.5 | 12.9 | 17.1 | 17.06 ± 4.29 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.0 | 17.0 | 17.07 ± 4.31 |
| chancalan | input-lanjian | 14.1 ± 0.7 | 13.1 | 17.3 | 17.08 ± 4.33 |
| chancalan | input-chancalan | 14.1 ± 0.5 | 12.9 | 17.3 | 17.09 ± 4.30 |
| chancalan | input-mikofo | 14.1 ± 0.6 | 13.1 | 17.2 | 17.11 ± 4.31 |
| pting | input-kcen | 14.1 ± 0.7 | 13.1 | 17.7 | 17.14 ± 4.36 |
| chancalan | input-mattcl | 14.2 ± 0.7 | 13.2 | 17.1 | 17.17 ± 4.36 |
| kcen | input-kcen | 14.2 ± 0.7 | 13.0 | 18.3 | 17.18 ± 4.37 |
| mattcl-py | input-mikofo | 14.2 ± 0.6 | 13.4 | 17.8 | 17.18 ± 4.34 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.2 | 17.1 | 17.19 ± 4.35 |
| kcen | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.5 | 17.21 ± 4.34 |
| mattcl-py | input-lanjian | 14.2 ± 0.7 | 13.3 | 17.5 | 17.21 ± 4.37 |
| pting | input-mattcl | 14.2 ± 0.7 | 13.0 | 17.0 | 17.23 ± 4.37 |
| kcen | input-mikofo | 14.2 ± 0.7 | 12.8 | 18.3 | 17.23 ± 4.38 |
| pting | input-lanjian | 14.2 ± 0.7 | 13.1 | 17.5 | 17.24 ± 4.37 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.0 | 17.3 | 17.24 ± 4.37 |
| pting | input-chancalan | 14.2 ± 0.7 | 13.2 | 18.2 | 17.26 ± 4.39 |
| mattcl-py | input-chancalan | 14.3 ± 0.6 | 13.3 | 17.5 | 17.31 ± 4.38 |
| pting | input-mikofo | 14.3 ± 0.7 | 13.4 | 17.6 | 17.31 ± 4.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|