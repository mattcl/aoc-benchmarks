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
| mattcl | input-lanjian | 1.4 ± 0.1 | 0.7 | 2.2 | 1.00 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.7 | 1.02 ± 0.20 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.3 | 1.02 ± 0.18 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.02 ± 0.16 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.1 | 1.02 ± 0.17 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.5 | 1.03 ± 0.19 |
| kcen | input-mattcl | 25.8 ± 0.9 | 24.6 | 29.2 | 18.35 ± 2.02 |
| kcen | input-lanjian | 28.5 ± 0.7 | 27.3 | 31.5 | 20.22 ± 2.17 |
| kcen | input-kcen | 32.4 ± 0.9 | 31.0 | 35.4 | 23.03 ± 2.48 |
| mattcl-py | input-mattcl | 56.3 ± 1.3 | 54.2 | 61.4 | 39.99 ± 4.27 |
| mattcl-py | input-lanjian | 61.4 ± 1.6 | 58.5 | 66.6 | 43.60 ± 4.69 |
| mattcl-py | input-kcen | 66.1 ± 1.4 | 63.8 | 68.8 | 46.94 ± 4.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|