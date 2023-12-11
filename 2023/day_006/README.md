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

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.5 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.4 | 1.03 ± 0.36 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.36 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.35 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.5 | 1.10 ± 0.34 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.5 | 1.0 | 1.10 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.5 | 1.12 ± 0.34 |
| mattcl-ts | input-lanjian | 10.1 ± 0.3 | 9.1 | 11.0 | 12.88 ± 3.34 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.3 | 10.8 | 12.89 ± 3.33 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 9.1 | 11.1 | 12.89 ± 3.34 |
| mattcl-ts | input-mattcl | 10.4 ± 3.8 | 9.2 | 60.6 | 13.25 ± 5.94 |
| pting | input-pting | 14.2 ± 0.5 | 13.2 | 17.1 | 18.10 ± 4.69 |
| mattcl-py | input-lanjian | 14.2 ± 0.4 | 13.2 | 16.8 | 18.15 ± 4.69 |
| pting | input-kcen | 14.2 ± 0.6 | 13.2 | 17.2 | 18.15 ± 4.72 |
| pting | input-lanjian | 14.2 ± 0.5 | 13.5 | 17.2 | 18.16 ± 4.71 |
| mattcl-py | input-kcen | 14.3 ± 0.7 | 13.3 | 17.7 | 18.20 ± 4.75 |
| mattcl-py | input-pting | 14.3 ± 0.7 | 13.3 | 17.7 | 18.20 ± 4.75 |
| kcen | input-lanjian | 14.3 ± 0.6 | 13.3 | 17.2 | 18.21 ± 4.73 |
| kcen | input-pting | 14.3 ± 0.5 | 13.3 | 17.3 | 18.21 ± 4.72 |
| kcen | input-mattcl | 14.3 ± 0.6 | 13.3 | 17.5 | 18.24 ± 4.75 |
| pting | input-mattcl | 14.3 ± 0.7 | 13.0 | 17.8 | 18.27 ± 4.78 |
| kcen | input-kcen | 14.3 ± 0.6 | 13.1 | 17.7 | 18.28 ± 4.76 |
| mattcl-py | input-mattcl | 14.5 ± 2.5 | 13.3 | 48.7 | 18.45 ± 5.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|