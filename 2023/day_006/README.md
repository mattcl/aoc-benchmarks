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
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.39 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.39 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.37 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.7 | 1.03 ± 0.39 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 0.9 | 1.04 ± 0.34 |
| lanjian | input-lanjian | 0.7 ± 0.1 | 0.1 | 0.9 | 1.05 ± 0.34 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.38 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.37 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.3 | 1.2 | 1.09 ± 0.34 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 9.1 | 11.0 | 14.25 ± 3.74 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 8.8 | 10.8 | 14.27 ± 3.75 |
| mattcl-ts | input-pting | 10.0 ± 0.3 | 9.0 | 10.9 | 14.29 ± 3.74 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.1 | 11.0 | 14.32 ± 3.75 |
| mattcl-ts | input-chancalan | 10.0 ± 0.3 | 9.0 | 11.1 | 14.34 ± 3.75 |
| chancalan | input-mattcl | 14.0 ± 0.7 | 13.1 | 17.8 | 20.05 ± 5.30 |
| kcen | input-chancalan | 14.0 ± 0.5 | 12.9 | 17.2 | 20.07 ± 5.27 |
| chancalan | input-pting | 14.0 ± 0.6 | 13.2 | 17.4 | 20.09 ± 5.30 |
| chancalan | input-lanjian | 14.0 ± 0.7 | 12.9 | 17.9 | 20.09 ± 5.31 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.0 | 17.3 | 20.10 ± 5.29 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.1 | 17.4 | 20.10 ± 5.29 |
| chancalan | input-chancalan | 14.1 ± 0.6 | 13.1 | 17.0 | 20.12 ± 5.30 |
| pting | input-pting | 14.1 ± 0.5 | 12.8 | 17.7 | 20.13 ± 5.28 |
| mattcl-py | input-kcen | 14.1 ± 0.7 | 12.9 | 17.4 | 20.15 ± 5.32 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 13.1 | 17.3 | 20.15 ± 5.31 |
| chancalan | input-kcen | 14.1 ± 0.7 | 13.0 | 17.3 | 20.16 ± 5.32 |
| pting | input-chancalan | 14.1 ± 0.6 | 13.2 | 17.6 | 20.17 ± 5.32 |
| mattcl-py | input-pting | 14.1 ± 0.6 | 13.3 | 17.2 | 20.19 ± 5.32 |
| pting | input-kcen | 14.1 ± 0.7 | 13.0 | 17.6 | 20.19 ± 5.33 |
| pting | input-lanjian | 14.1 ± 0.7 | 13.3 | 17.4 | 20.22 ± 5.34 |
| mattcl-py | input-mattcl | 14.1 ± 0.7 | 13.2 | 17.5 | 20.23 ± 5.35 |
| pting | input-mattcl | 14.1 ± 0.6 | 13.1 | 18.1 | 20.24 ± 5.33 |
| kcen | input-kcen | 14.2 ± 0.7 | 13.3 | 18.3 | 20.27 ± 5.36 |
| kcen | input-pting | 14.2 ± 0.7 | 12.9 | 17.3 | 20.27 ± 5.36 |
| kcen | input-mattcl | 14.3 ± 3.0 | 13.0 | 49.0 | 20.50 ± 6.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|