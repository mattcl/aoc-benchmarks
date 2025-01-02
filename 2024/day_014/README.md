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
| lanjian | input-kcen | 1.3 ± 0.3 | 0.4 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.6 | 2.5 | 1.05 ± 0.37 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.3 | 1.11 ± 0.30 |
| mattcl | input-lanjian | 1.4 ± 0.1 | 0.7 | 2.3 | 1.11 ± 0.29 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.3 | 1.12 ± 0.30 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.4 | 1.12 ± 0.30 |
| kcen | input-mattcl | 25.7 ± 0.8 | 24.5 | 29.0 | 20.21 ± 4.96 |
| kcen | input-lanjian | 28.5 ± 0.9 | 27.3 | 31.7 | 22.42 ± 5.50 |
| kcen | input-kcen | 32.4 ± 0.8 | 31.0 | 34.7 | 25.49 ± 6.24 |
| mattcl-py | input-mattcl | 56.4 ± 1.5 | 54.3 | 63.0 | 44.39 ± 10.87 |
| mattcl-py | input-lanjian | 60.3 ± 1.3 | 58.8 | 65.1 | 47.51 ± 11.60 |
| mattcl-py | input-kcen | 66.1 ± 2.1 | 64.0 | 75.9 | 52.04 ± 12.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|