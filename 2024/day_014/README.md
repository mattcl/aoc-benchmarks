# Day 14 benchmarks

[link to problem](https://adventofcode.com/2024/day/14)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 14)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.5 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.4 ± 0.1 | 0.8 | 2.3 | 1.00 ± 0.20 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.00 ± 0.20 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.7 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.5 | 1.04 ± 0.24 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.6 | 2.7 | 1.06 ± 0.28 |
| kcen | input-mattcl | 25.8 ± 0.7 | 24.3 | 28.6 | 18.44 ± 3.12 |
| kcen | input-lanjian | 28.8 ± 0.9 | 27.5 | 33.1 | 20.58 ± 3.49 |
| kcen | input-kcen | 32.7 ± 0.9 | 30.8 | 35.4 | 23.43 ± 3.96 |
| mattcl-py | input-mattcl | 56.5 ± 1.2 | 54.3 | 60.4 | 40.44 ± 6.80 |
| mattcl-py | input-lanjian | 61.2 ± 1.2 | 59.2 | 65.7 | 43.80 ± 7.35 |
| mattcl-py | input-kcen | 66.2 ± 1.2 | 64.0 | 68.7 | 47.35 ± 7.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|