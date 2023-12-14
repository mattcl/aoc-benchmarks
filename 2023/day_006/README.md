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
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.36 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.37 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.38 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.2 | 1.06 ± 0.34 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.1 | 1.06 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.3 | 1.07 ± 0.36 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.37 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.08 ± 0.37 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.08 ± 0.37 |
| mattcl-ts | input-mattcl | 9.5 ± 0.3 | 8.7 | 10.5 | 12.36 ± 3.33 |
| mattcl-ts | input-chancalan | 9.5 ± 0.4 | 8.6 | 10.4 | 12.40 ± 3.35 |
| mattcl-ts | input-kcen | 9.5 ± 0.4 | 8.6 | 10.5 | 12.40 ± 3.35 |
| mattcl-ts | input-pting | 9.5 ± 0.4 | 8.2 | 10.3 | 12.44 ± 3.36 |
| mattcl-ts | input-lanjian | 9.6 ± 0.4 | 8.7 | 10.8 | 12.51 ± 3.38 |
| mattcl-py | input-pting | 13.9 ± 0.4 | 13.0 | 16.6 | 18.15 ± 4.88 |
| chancalan | input-kcen | 14.0 ± 0.6 | 13.0 | 17.3 | 18.21 ± 4.93 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 12.9 | 17.2 | 18.21 ± 4.93 |
| kcen | input-kcen | 14.0 ± 0.5 | 13.2 | 17.1 | 18.23 ± 4.91 |
| chancalan | input-pting | 14.0 ± 0.5 | 13.2 | 17.0 | 18.23 ± 4.92 |
| pting | input-lanjian | 14.0 ± 0.5 | 13.1 | 17.3 | 18.23 ± 4.91 |
| mattcl-py | input-chancalan | 14.0 ± 0.5 | 12.9 | 16.9 | 18.24 ± 4.93 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 16.8 | 18.25 ± 4.94 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 13.1 | 17.3 | 18.25 ± 4.95 |
| kcen | input-lanjian | 14.0 ± 0.6 | 13.1 | 17.2 | 18.26 ± 4.94 |
| kcen | input-pting | 14.0 ± 0.6 | 13.1 | 17.6 | 18.27 ± 4.95 |
| chancalan | input-chancalan | 14.0 ± 0.7 | 13.0 | 17.4 | 18.27 ± 4.96 |
| pting | input-mattcl | 14.0 ± 0.6 | 13.1 | 17.0 | 18.27 ± 4.95 |
| kcen | input-mattcl | 14.0 ± 0.5 | 12.9 | 17.5 | 18.28 ± 4.94 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 13.3 | 17.3 | 18.28 ± 4.93 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 13.1 | 17.7 | 18.28 ± 4.96 |
| chancalan | input-mattcl | 14.0 ± 0.7 | 12.9 | 17.4 | 18.30 ± 4.97 |
| kcen | input-chancalan | 14.1 ± 0.6 | 13.0 | 17.2 | 18.34 ± 4.97 |
| pting | input-chancalan | 14.1 ± 0.7 | 12.9 | 17.4 | 18.41 ± 5.01 |
| pting | input-pting | 14.4 ± 4.0 | 13.1 | 59.4 | 18.81 ± 7.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|