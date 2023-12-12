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
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.37 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.36 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.34 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.37 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.36 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.08 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.1 | 1.08 ± 0.34 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 8.9 | 10.8 | 12.27 ± 3.30 |
| mattcl-ts | input-lanjian | 10.1 ± 0.3 | 8.9 | 11.1 | 12.31 ± 3.31 |
| mattcl-ts | input-mattcl | 10.1 ± 0.3 | 9.1 | 10.9 | 12.33 ± 3.32 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.2 | 11.2 | 12.35 ± 3.32 |
| mattcl-ts | input-pting | 10.2 ± 0.3 | 9.1 | 10.9 | 12.37 ± 3.33 |
| mattcl-py | input-lanjian | 14.1 ± 0.4 | 13.2 | 17.4 | 17.22 ± 4.63 |
| chancalan | input-lanjian | 14.1 ± 0.6 | 13.2 | 16.8 | 17.23 ± 4.66 |
| mattcl-py | input-kcen | 14.2 ± 0.5 | 13.0 | 16.9 | 17.26 ± 4.65 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.2 | 17.0 | 17.26 ± 4.67 |
| chancalan | input-pting | 14.2 ± 0.5 | 13.3 | 16.9 | 17.26 ± 4.66 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.3 | 17.2 | 17.28 ± 4.67 |
| chancalan | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.5 | 17.28 ± 4.67 |
| chancalan | input-kcen | 14.2 ± 0.4 | 13.4 | 15.8 | 17.29 ± 4.65 |
| chancalan | input-chancalan | 14.2 ± 0.6 | 13.1 | 17.7 | 17.30 ± 4.68 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.1 | 17.7 | 17.32 ± 4.69 |
| pting | input-kcen | 14.2 ± 0.7 | 13.2 | 18.3 | 17.35 ± 4.72 |
| pting | input-chancalan | 14.2 ± 0.6 | 13.0 | 17.8 | 17.35 ± 4.70 |
| kcen | input-lanjian | 14.3 ± 0.6 | 13.0 | 17.7 | 17.36 ± 4.70 |
| pting | input-pting | 14.3 ± 0.6 | 13.2 | 17.4 | 17.36 ± 4.69 |
| kcen | input-kcen | 14.3 ± 0.7 | 13.3 | 17.9 | 17.41 ± 4.73 |
| mattcl-py | input-chancalan | 14.3 ± 0.7 | 13.2 | 17.9 | 17.42 ± 4.74 |
| kcen | input-pting | 14.3 ± 0.8 | 12.9 | 18.6 | 17.43 ± 4.76 |
| pting | input-mattcl | 14.3 ± 0.8 | 13.0 | 18.1 | 17.43 ± 4.75 |
| kcen | input-mattcl | 14.3 ± 0.8 | 13.3 | 17.6 | 17.47 ± 4.76 |
| kcen | input-chancalan | 14.3 ± 0.7 | 13.1 | 17.2 | 17.47 ± 4.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|