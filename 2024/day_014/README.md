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
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.4 | 2.3 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.01 ± 0.22 |
| mattcl | input-kcen | 1.4 ± 0.1 | 0.8 | 1.7 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.2 | 1.03 ± 0.22 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.3 | 1.04 ± 0.22 |
| kcen | input-mattcl | 25.6 ± 1.0 | 24.4 | 29.2 | 18.61 ± 3.31 |
| kcen | input-lanjian | 28.3 ± 0.8 | 27.4 | 31.2 | 20.57 ± 3.62 |
| kcen | input-kcen | 32.3 ± 0.9 | 31.0 | 35.1 | 23.44 ± 4.13 |
| mattcl-py | input-mattcl | 56.8 ± 1.2 | 54.8 | 60.3 | 41.23 ± 7.21 |
| mattcl-py | input-lanjian | 61.7 ± 1.6 | 59.6 | 67.3 | 44.83 ± 7.87 |
| mattcl-py | input-kcen | 66.5 ± 1.2 | 64.5 | 69.2 | 48.30 ± 8.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|