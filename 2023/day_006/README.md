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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.00 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.40 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.08 ± 0.41 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.09 ± 0.42 |
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.1 | 1.10 ± 0.44 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.3 | 1.5 | 1.10 ± 0.40 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.14 ± 0.42 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.4 | 1.5 | 1.14 ± 0.41 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.0 | 1.16 ± 0.42 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.0 | 1.17 ± 0.41 |
| mattcl-ts | input-chancalan | 9.8 ± 0.4 | 8.7 | 11.9 | 13.34 ± 4.19 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 8.9 | 10.9 | 13.35 ± 4.19 |
| mattcl-ts | input-mikofo | 9.8 ± 0.4 | 8.9 | 10.8 | 13.36 ± 4.19 |
| mattcl-ts | input-lanjian | 9.8 ± 0.4 | 8.8 | 10.7 | 13.39 ± 4.21 |
| mattcl-ts | input-mattcl | 9.8 ± 0.4 | 8.9 | 11.0 | 13.40 ± 4.20 |
| chancalan | input-kcen | 14.0 ± 0.5 | 13.0 | 16.9 | 19.06 ± 5.97 |
| chancalan | input-mikofo | 14.0 ± 0.5 | 13.2 | 17.4 | 19.09 ± 5.99 |
| chancalan | input-chancalan | 14.1 ± 0.6 | 13.2 | 17.2 | 19.13 ± 6.01 |
| mattcl-py | input-mattcl | 14.1 ± 0.7 | 12.9 | 17.3 | 19.13 ± 6.03 |
| mattcl-py | input-kcen | 14.1 ± 0.6 | 12.9 | 17.3 | 19.14 ± 6.01 |
| chancalan | input-mattcl | 14.1 ± 0.7 | 12.9 | 17.6 | 19.17 ± 6.04 |
| chancalan | input-lanjian | 14.1 ± 0.7 | 13.4 | 18.4 | 19.18 ± 6.05 |
| pting | input-lanjian | 14.1 ± 0.5 | 13.2 | 17.7 | 19.20 ± 6.03 |
| kcen | input-mattcl | 14.1 ± 0.6 | 12.9 | 17.2 | 19.22 ± 6.04 |
| mattcl-py | input-mikofo | 14.1 ± 0.7 | 12.9 | 17.2 | 19.23 ± 6.06 |
| mattcl-py | input-chancalan | 14.1 ± 0.7 | 13.0 | 17.0 | 19.25 ± 6.06 |
| kcen | input-chancalan | 14.1 ± 0.6 | 13.3 | 17.3 | 19.25 ± 6.06 |
| kcen | input-kcen | 14.2 ± 0.7 | 13.0 | 17.3 | 19.26 ± 6.09 |
| kcen | input-mikofo | 14.2 ± 0.7 | 13.3 | 17.4 | 19.29 ± 6.08 |
| kcen | input-lanjian | 14.2 ± 0.6 | 13.3 | 17.3 | 19.30 ± 6.07 |
| pting | input-mattcl | 14.2 ± 0.7 | 12.9 | 17.4 | 19.33 ± 6.10 |
| pting | input-kcen | 14.2 ± 0.7 | 13.1 | 18.3 | 19.35 ± 6.10 |
| pting | input-chancalan | 14.2 ± 0.8 | 13.1 | 17.9 | 19.36 ± 6.12 |
| pting | input-mikofo | 14.2 ± 0.8 | 13.1 | 17.9 | 19.36 ± 6.13 |
| mattcl-py | input-lanjian | 14.7 ± 5.2 | 12.8 | 65.6 | 20.03 ± 9.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|