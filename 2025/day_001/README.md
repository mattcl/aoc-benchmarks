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
| whyando | input-mattcl | 710.7 ± 156.3 | 175.7 | 1229.2 | 1.00 |
| whyando | input-lanjian | 748.7 ± 150.9 | 231.2 | 1311.3 | 1.05 ± 0.31 |
| whyando | input-whyando | 749.4 ± 148.3 | 0.0 | 1398.2 | 1.05 ± 0.31 |
| kcen | input-mattcl | 815.1 ± 182.5 | 12.6 | 1600.2 | 1.15 ± 0.36 |
| kcen | input-lanjian | 823.7 ± 158.8 | 0.0 | 1303.3 | 1.16 ± 0.34 |
| kcen | input-whyando | 905.3 ± 167.3 | 69.6 | 1411.2 | 1.27 ± 0.37 |
| mattcl | input-lanjian | 1027.5 ± 146.2 | 234.1 | 1616.1 | 1.45 ± 0.38 |
| mattcl | input-whyando | 1058.0 ± 166.0 | 566.4 | 1788.3 | 1.49 ± 0.40 |
| mattcl | input-mattcl | 1084.7 ± 193.2 | 514.1 | 1786.7 | 1.53 ± 0.43 |
| lanjian | input-whyando | 1304.0 ± 201.5 | 239.2 | 2072.5 | 1.83 ± 0.49 |
| lanjian | input-lanjian | 1345.6 ± 216.4 | 168.6 | 2118.7 | 1.89 ± 0.52 |
| lanjian | input-mattcl | 1359.5 ± 217.7 | 474.7 | 2073.4 | 1.91 ± 0.52 |
| mattcl-py | input-mattcl | 18083.2 ± 643.6 | 17000.4 | 20860.2 | 25.44 ± 5.67 |
| mattcl-py | input-whyando | 18128.3 ± 648.8 | 17143.7 | 21441.6 | 25.51 ± 5.68 |
| mattcl-py | input-lanjian | 18191.8 ± 753.5 | 16648.3 | 21572.3 | 25.60 ± 5.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|