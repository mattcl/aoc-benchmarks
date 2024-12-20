# Day 9 benchmarks

[link to problem](https://adventofcode.com/2024/day/9)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 9)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 1.8 ± 0.4 | 1.0 | 2.7 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.5 | 0.8 | 2.9 | 1.11 ± 0.39 |
| mattcl | input-mattcl | 2.2 ± 0.3 | 1.4 | 3.1 | 1.27 ± 0.36 |
| mattcl | input-kcen | 2.3 ± 0.4 | 1.3 | 3.4 | 1.27 ± 0.37 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.6 | 3.9 | 1.39 ± 0.38 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.5 | 4.5 | 1.40 ± 0.39 |
| kcen | input-lanjian | 3.7 ± 0.4 | 2.6 | 6.8 | 2.09 ± 0.56 |
| kcen | input-mattcl | 3.7 ± 0.5 | 2.9 | 6.9 | 2.10 ± 0.58 |
| kcen | input-kcen | 4.1 ± 0.5 | 3.1 | 7.6 | 2.30 ± 0.63 |
| mattcl-py | input-lanjian | 31.6 ± 1.1 | 29.9 | 35.8 | 17.82 ± 4.38 |
| mattcl-py | input-kcen | 31.7 ± 0.9 | 30.2 | 34.8 | 17.85 ± 4.37 |
| mattcl-py | input-mattcl | 31.8 ± 1.0 | 30.3 | 34.8 | 17.92 ± 4.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|