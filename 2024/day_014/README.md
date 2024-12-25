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
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.3 | 1.00 ± 0.17 |
| lanjian | input-kcen | 1.4 ± 0.1 | 0.9 | 2.0 | 1.01 ± 0.14 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.8 | 2.6 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.7 | 2.2 | 1.02 ± 0.17 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.9 | 1.03 ± 0.20 |
| kcen | input-mattcl | 25.6 ± 0.8 | 24.5 | 28.8 | 17.86 ± 2.22 |
| kcen | input-lanjian | 28.2 ± 0.9 | 26.9 | 31.3 | 19.72 ± 2.45 |
| kcen | input-kcen | 32.2 ± 1.0 | 31.0 | 35.2 | 22.46 ± 2.78 |
| mattcl-py | input-mattcl | 56.7 ± 1.4 | 54.9 | 61.6 | 39.61 ± 4.86 |
| mattcl-py | input-lanjian | 60.7 ± 1.2 | 59.2 | 64.4 | 42.40 ± 5.17 |
| mattcl-py | input-kcen | 66.3 ± 1.1 | 64.3 | 69.2 | 46.29 ± 5.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|