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
| mattcl | input-mattcl | 1.4 ± 0.1 | 0.7 | 2.3 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.3 | 2.1 | 1.01 ± 0.17 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.2 | 1.01 ± 0.17 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.3 | 1.04 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.6 | 1.04 ± 0.19 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.7 | 2.5 | 1.10 ± 0.26 |
| kcen | input-mattcl | 25.7 ± 0.9 | 24.7 | 29.2 | 18.92 ± 1.92 |
| kcen | input-lanjian | 28.5 ± 0.7 | 27.2 | 31.1 | 21.01 ± 2.06 |
| kcen | input-kcen | 32.7 ± 1.1 | 31.3 | 36.1 | 24.13 ± 2.42 |
| mattcl-py | input-mattcl | 56.3 ± 1.5 | 54.2 | 61.8 | 41.52 ± 4.09 |
| mattcl-py | input-lanjian | 60.6 ± 1.2 | 58.8 | 64.3 | 44.68 ± 4.34 |
| mattcl-py | input-kcen | 66.2 ± 1.8 | 63.5 | 72.6 | 48.80 ± 4.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|