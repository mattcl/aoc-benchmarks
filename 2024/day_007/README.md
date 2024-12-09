# Day 7 benchmarks

[link to problem](https://adventofcode.com/2024/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.0 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.9 | 2.4 | 1.00 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.16 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.3 | 2.85 ± 0.34 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.9 | 5.4 | 3.32 ± 0.36 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.7 | 5.6 | 3.58 ± 0.35 |
| lanjian | input-lanjian | 6.2 ± 0.2 | 5.7 | 6.9 | 4.45 ± 0.45 |
| mattcl-py | input-kcen | 47.7 ± 0.6 | 46.4 | 49.1 | 34.03 ± 3.19 |
| mattcl-py | input-lanjian | 47.9 ± 0.6 | 46.5 | 49.8 | 34.20 ± 3.21 |
| mattcl-py | input-mikofo | 48.0 ± 0.6 | 46.3 | 49.6 | 34.26 ± 3.22 |
| mattcl-py | input-mattcl | 48.2 ± 0.9 | 46.7 | 51.6 | 34.43 ± 3.27 |
| kcen | input-mattcl | 174.4 ± 2.2 | 171.2 | 179.7 | 124.49 ± 11.69 |
| kcen | input-mikofo | 213.6 ± 1.6 | 210.5 | 217.0 | 152.49 ± 14.23 |
| kcen | input-kcen | 222.3 ± 1.5 | 219.8 | 224.4 | 158.72 ± 14.81 |
| kcen | input-lanjian | 360.5 ± 3.4 | 356.3 | 365.6 | 257.42 ± 24.07 |
| mikofo | input-mattcl | 523.7 ± 6.5 | 515.2 | 530.3 | 373.90 ± 35.09 |
| mikofo | input-mikofo | 583.7 ± 13.4 | 565.6 | 601.7 | 416.72 ± 39.93 |
| mikofo | input-kcen | 682.4 ± 11.1 | 666.9 | 692.4 | 487.25 ± 46.02 |
| mikofo | input-lanjian | 986.6 ± 8.9 | 980.0 | 996.7 | 704.40 ± 65.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|