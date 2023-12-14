# Day 14 benchmarks

[link to problem](https://adventofcode.com/2023/day/14)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 14)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 5.5 ± 0.5 | 4.7 | 9.2 | 1.00 |
| mattcl | input-kcen | 6.2 ± 3.8 | 5.0 | 59.0 | 1.12 ± 0.69 |
| mattcl | input-mattcl | 6.3 ± 0.5 | 5.5 | 9.2 | 1.14 ± 0.13 |
| lanjian | input-lanjian | 19.5 ± 0.9 | 18.2 | 23.4 | 3.52 ± 0.34 |
| lanjian | input-kcen | 22.0 ± 0.9 | 21.0 | 25.3 | 3.96 ± 0.38 |
| lanjian | input-mattcl | 24.2 ± 0.9 | 23.1 | 28.1 | 4.38 ± 0.41 |
| pting | input-lanjian | 230.6 ± 3.0 | 225.9 | 236.5 | 41.63 ± 3.61 |
| pting | input-kcen | 268.2 ± 4.8 | 260.2 | 276.7 | 48.41 ± 4.24 |
| pting | input-mattcl | 287.3 ± 5.3 | 279.2 | 293.2 | 51.86 ± 4.55 |
| kcen | input-lanjian | 633.3 ± 3.5 | 630.1 | 638.0 | 114.34 ± 9.82 |
| kcen | input-kcen | 733.2 ± 13.8 | 722.0 | 753.2 | 132.37 ± 11.61 |
| kcen | input-mattcl | 810.6 ± 14.2 | 795.4 | 823.4 | 146.35 ± 12.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|