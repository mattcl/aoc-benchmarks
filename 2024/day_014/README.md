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
| mattcl | input-mattcl | 1.4 ± 0.1 | 0.8 | 2.1 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.1 | 0.7 | 2.1 | 1.01 ± 0.14 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.6 | 1.02 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.1 | 1.0 | 2.3 | 1.03 ± 0.15 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.5 | 2.6 | 1.05 ± 0.19 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.4 | 1.05 ± 0.20 |
| kcen | input-mattcl | 25.9 ± 0.9 | 24.7 | 29.2 | 18.99 ± 2.04 |
| kcen | input-lanjian | 29.0 ± 0.8 | 27.4 | 31.8 | 21.23 ± 2.24 |
| kcen | input-kcen | 32.7 ± 0.7 | 31.5 | 35.3 | 23.98 ± 2.50 |
| mattcl-py | input-mattcl | 56.8 ± 1.1 | 55.0 | 59.7 | 41.59 ± 4.30 |
| mattcl-py | input-lanjian | 61.2 ± 1.2 | 59.2 | 64.3 | 44.84 ± 4.64 |
| mattcl-py | input-kcen | 66.6 ± 1.3 | 64.5 | 71.0 | 48.81 ± 5.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|