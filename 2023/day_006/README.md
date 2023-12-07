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
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.36 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.34 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.33 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.03 ± 0.31 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.0 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.4 | 1.06 ± 0.31 |
| mattcl-ts | input-kcen | 9.4 ± 0.4 | 8.3 | 10.6 | 11.65 ± 2.78 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.2 | 10.3 | 11.65 ± 2.78 |
| mattcl-ts | input-pting | 9.4 ± 0.4 | 8.4 | 10.7 | 11.69 ± 2.79 |
| mattcl-ts | input-lanjian | 9.5 ± 0.3 | 8.7 | 10.3 | 11.77 ± 2.80 |
| pting | input-kcen | 14.0 ± 0.6 | 12.9 | 17.3 | 17.37 ± 4.15 |
| kcen | input-pting | 14.0 ± 0.4 | 13.0 | 16.8 | 17.38 ± 4.12 |
| mattcl-py | input-mattcl | 14.0 ± 0.5 | 13.0 | 17.2 | 17.38 ± 4.13 |
| kcen | input-lanjian | 14.0 ± 0.5 | 13.1 | 17.0 | 17.39 ± 4.14 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 13.2 | 17.2 | 17.39 ± 4.14 |
| pting | input-lanjian | 14.0 ± 0.5 | 13.1 | 17.4 | 17.40 ± 4.15 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.4 | 17.41 ± 4.17 |
| pting | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.6 | 17.42 ± 4.16 |
| kcen | input-kcen | 14.0 ± 0.7 | 12.9 | 17.4 | 17.42 ± 4.18 |
| kcen | input-mattcl | 14.1 ± 0.7 | 13.0 | 18.1 | 17.44 ± 4.18 |
| mattcl-py | input-pting | 14.1 ± 0.6 | 12.9 | 17.8 | 17.46 ± 4.18 |
| pting | input-pting | 14.1 ± 0.6 | 13.1 | 16.9 | 17.46 ± 4.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|