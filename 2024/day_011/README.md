# Day 11 benchmarks

[link to problem](https://adventofcode.com/2024/day/11)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 11)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 3.3 ± 0.4 | 2.5 | 5.6 | 1.00 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.6 | 6.3 | 1.05 ± 0.18 |
| mattcl | input-mattcl | 3.6 ± 0.5 | 2.7 | 5.9 | 1.08 ± 0.19 |
| lanjian | input-lanjian | 11.0 ± 0.5 | 9.9 | 13.7 | 3.34 ± 0.44 |
| lanjian | input-mattcl | 11.2 ± 0.6 | 10.1 | 14.5 | 3.41 ± 0.46 |
| lanjian | input-kcen | 11.3 ± 0.5 | 10.3 | 15.0 | 3.42 ± 0.46 |
| kcen | input-lanjian | 19.0 ± 0.5 | 18.0 | 21.2 | 5.75 ± 0.73 |
| kcen | input-kcen | 20.4 ± 0.6 | 19.2 | 23.1 | 6.19 ± 0.79 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.4 | 23.2 | 6.20 ± 0.80 |
| mattcl-py | input-lanjian | 63.2 ± 1.1 | 61.1 | 66.2 | 19.18 ± 2.41 |
| mattcl-py | input-kcen | 69.6 ± 1.5 | 67.1 | 72.6 | 21.12 ± 2.66 |
| mattcl-py | input-mattcl | 69.9 ± 1.4 | 67.3 | 74.1 | 21.21 ± 2.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>194782</pre>|<pre>233007586663131</pre>|
|input-lanjian|<pre>218956</pre>|<pre>259593838049805</pre>|
|input-mattcl|<pre>189547</pre>|<pre>224577979481346</pre>|