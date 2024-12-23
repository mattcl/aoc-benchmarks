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
| lanjian | input-mattcl | 0.9 ± 0.4 | 0.2 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.4 | 0.3 | 1.8 | 1.16 ± 0.69 |
| lanjian | input-lanjian | 1.4 ± 0.1 | 0.8 | 2.2 | 1.63 ± 0.77 |
| mattcl | input-lanjian | 1.4 ± 0.1 | 0.7 | 1.8 | 1.64 ± 0.76 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.64 ± 0.78 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.4 | 1.65 ± 0.78 |
| kcen | input-mattcl | 25.6 ± 0.9 | 24.5 | 29.0 | 29.67 ± 13.65 |
| kcen | input-lanjian | 28.5 ± 0.8 | 27.3 | 30.9 | 33.03 ± 15.19 |
| kcen | input-kcen | 32.3 ± 0.9 | 31.0 | 34.9 | 37.42 ± 17.20 |
| mattcl-py | input-mattcl | 57.1 ± 1.5 | 55.1 | 65.0 | 66.17 ± 30.41 |
| mattcl-py | input-lanjian | 61.5 ± 1.2 | 59.6 | 65.4 | 71.33 ± 32.75 |
| mattcl-py | input-kcen | 66.9 ± 1.5 | 64.6 | 72.0 | 77.55 ± 35.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|