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
| mattcl | input-kcen | 1.3 ± 0.3 | 0.2 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.4 | 1.14 ± 0.35 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.14 ± 0.35 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.7 | 1.16 ± 0.35 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.5 | 3.0 | 1.17 ± 0.38 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.5 | 2.7 | 1.19 ± 0.40 |
| kcen | input-mattcl | 25.7 ± 0.8 | 24.4 | 29.7 | 20.44 ± 5.66 |
| kcen | input-lanjian | 28.7 ± 0.9 | 27.5 | 31.4 | 22.80 ± 6.31 |
| kcen | input-kcen | 32.8 ± 0.9 | 31.5 | 35.7 | 26.07 ± 7.21 |
| mattcl-py | input-mattcl | 56.7 ± 1.4 | 54.6 | 61.0 | 45.06 ± 12.45 |
| mattcl-py | input-lanjian | 60.8 ± 1.4 | 58.9 | 65.4 | 48.30 ± 13.33 |
| mattcl-py | input-kcen | 66.1 ± 1.4 | 63.5 | 71.4 | 52.53 ± 14.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|