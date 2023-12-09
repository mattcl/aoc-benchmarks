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
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.38 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.37 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.5 | 1.04 ± 0.38 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.35 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.07 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.35 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.08 ± 0.37 |
| mattcl-ts | input-kcen | 9.5 ± 0.4 | 8.6 | 10.7 | 12.68 ± 3.33 |
| mattcl-ts | input-pting | 9.5 ± 0.4 | 8.5 | 10.7 | 12.71 ± 3.34 |
| mattcl-ts | input-lanjian | 9.5 ± 0.4 | 8.4 | 10.7 | 12.72 ± 3.34 |
| mattcl-ts | input-mattcl | 9.5 ± 0.4 | 8.6 | 10.4 | 12.74 ± 3.35 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 13.0 | 16.9 | 18.62 ± 4.88 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.1 | 17.6 | 18.67 ± 4.91 |
| kcen | input-lanjian | 14.0 ± 0.5 | 13.2 | 17.2 | 18.67 ± 4.89 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.2 | 17.0 | 18.68 ± 4.91 |
| pting | input-lanjian | 14.0 ± 0.5 | 13.2 | 16.9 | 18.68 ± 4.90 |
| pting | input-pting | 14.0 ± 0.5 | 13.1 | 17.0 | 18.68 ± 4.90 |
| mattcl-py | input-mattcl | 14.0 ± 0.5 | 13.4 | 17.2 | 18.70 ± 4.91 |
| kcen | input-mattcl | 14.0 ± 0.7 | 13.1 | 18.3 | 18.72 ± 4.95 |
| pting | input-kcen | 14.0 ± 0.6 | 12.9 | 17.1 | 18.74 ± 4.94 |
| kcen | input-pting | 14.1 ± 0.7 | 13.2 | 17.0 | 18.77 ± 4.96 |
| mattcl-py | input-pting | 14.2 ± 2.7 | 12.9 | 50.8 | 18.94 ± 6.07 |
| pting | input-mattcl | 14.3 ± 3.1 | 13.0 | 56.3 | 19.07 ± 6.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|