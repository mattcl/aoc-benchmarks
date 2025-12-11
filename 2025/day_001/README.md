# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 506.0 ± 185.0 | 0.0 | 738.7 | 1.00 |
| mattcl | input-whyando | 537.2 ± 158.2 | 0.0 | 770.5 | 1.06 ± 0.50 |
| whyando | input-whyando | 549.6 ± 164.1 | 0.0 | 807.3 | 1.09 ± 0.51 |
| mattcl | input-lanjian | 563.0 ± 180.0 | 0.0 | 855.7 | 1.11 ± 0.54 |
| mattcl | input-mattcl | 583.7 ± 151.9 | 0.0 | 824.2 | 1.15 ± 0.52 |
| whyando | input-lanjian | 596.1 ± 150.4 | 0.0 | 814.9 | 1.18 ± 0.52 |
| kcen | input-whyando | 876.2 ± 136.8 | 295.7 | 1096.2 | 1.73 ± 0.69 |
| lanjian | input-whyando | 885.5 ± 160.0 | 76.6 | 1154.4 | 1.75 ± 0.71 |
| kcen | input-lanjian | 895.3 ± 161.5 | 97.4 | 1097.7 | 1.77 ± 0.72 |
| kcen | input-mattcl | 910.3 ± 158.7 | 0.0 | 1778.2 | 1.80 ± 0.73 |
| lanjian | input-mattcl | 940.7 ± 167.9 | 285.7 | 1809.3 | 1.86 ± 0.76 |
| lanjian | input-lanjian | 945.2 ± 163.1 | 370.2 | 1192.2 | 1.87 ± 0.76 |
| mattcl-py | input-whyando | 18743.9 ± 495.5 | 17815.1 | 21774.9 | 37.05 ± 13.58 |
| mattcl-py | input-lanjian | 20026.2 ± 418.7 | 19299.5 | 21786.6 | 39.58 ± 14.50 |
| mattcl-py | input-mattcl | 20176.2 ± 3427.7 | 17675.0 | 30698.0 | 39.88 ± 16.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|