Benchmark

Benchmark run from 2026-10-01 17:04:51.310318Z UTC

## System

Benchmark suite executing on the following system:

<table style="width: 1%">
  <tr>
    <th style="width: 1%; white-space: nowrap">Operating System</th>
    <td>Linux</td>
  </tr><tr>
    <th style="white-space: nowrap">CPU Information</th>
    <td style="white-space: nowrap">Intel(R) Core(TM) Ultra 9 185H</td>
  </tr><tr>
    <th style="white-space: nowrap">Number of Available Cores</th>
    <td style="white-space: nowrap">22</td>
  </tr><tr>
    <th style="white-space: nowrap">Available Memory</th>
    <td style="white-space: nowrap">62.24 GB</td>
  </tr><tr>
    <th style="white-space: nowrap">Elixir Version</th>
    <td style="white-space: nowrap">1.18.4</td>
  </tr><tr>
    <th style="white-space: nowrap">Erlang Version</th>
    <td style="white-space: nowrap">28.5.0.4</td>
  </tr>
</table>

## Configuration

Benchmark suite executing with the following configuration:

<table style="width: 1%">
  <tr>
    <th style="width: 1%">:time</th>
    <td style="white-space: nowrap">5 s</td>
  </tr><tr>
    <th>:parallel</th>
    <td style="white-space: nowrap">1</td>
  </tr><tr>
    <th>:warmup</th>
    <td style="white-space: nowrap">2 s</td>
  </tr>
</table>

## Statistics



Run Time

<table style="width: 1%">
  <tr>
    <th>Name</th>
    <th style="text-align: right">IPS</th>
    <th style="text-align: right">Average</th>
    <th style="text-align: right">Deviation</th>
    <th style="text-align: right">Median</th>
    <th style="text-align: right">99th&nbsp;%</th>
  </tr>

  <tr>
    <td style="white-space: nowrap">Formatter performance</td>
    <td style="white-space: nowrap; text-align: right">51.16</td>
    <td style="white-space: nowrap; text-align: right">19.55 ms</td>
    <td style="white-space: nowrap; text-align: right">&plusmn;15.50%</td>
    <td style="white-space: nowrap; text-align: right">19.33 ms</td>
    <td style="white-space: nowrap; text-align: right">26.01 ms</td>
  </tr>

  <tr>
    <td style="white-space: nowrap">Lexer performance</td>
    <td style="white-space: nowrap; text-align: right">26.27</td>
    <td style="white-space: nowrap; text-align: right">38.07 ms</td>
    <td style="white-space: nowrap; text-align: right">&plusmn;14.61%</td>
    <td style="white-space: nowrap; text-align: right">37.92 ms</td>
    <td style="white-space: nowrap; text-align: right">54.94 ms</td>
  </tr>

  <tr>
    <td style="white-space: nowrap">Lexer + Formatter</td>
    <td style="white-space: nowrap; text-align: right">17.00</td>
    <td style="white-space: nowrap; text-align: right">58.81 ms</td>
    <td style="white-space: nowrap; text-align: right">&plusmn;11.68%</td>
    <td style="white-space: nowrap; text-align: right">57.82 ms</td>
    <td style="white-space: nowrap; text-align: right">74.57 ms</td>
  </tr>

  <tr>
    <td style="white-space: nowrap">Lexer compilation time</td>
    <td style="white-space: nowrap; text-align: right">2.36</td>
    <td style="white-space: nowrap; text-align: right">423.54 ms</td>
    <td style="white-space: nowrap; text-align: right">&plusmn;5.19%</td>
    <td style="white-space: nowrap; text-align: right">418.41 ms</td>
    <td style="white-space: nowrap; text-align: right">471.30 ms</td>
  </tr>

</table>


Run Time Comparison

<table style="width: 1%">
  <tr>
    <th>Name</th>
    <th style="text-align: right">IPS</th>
    <th style="text-align: right">Slower</th>
  <tr>
    <td style="white-space: nowrap">Formatter performance</td>
    <td style="white-space: nowrap;text-align: right">51.16</td>
    <td>&nbsp;</td>
  </tr>

  <tr>
    <td style="white-space: nowrap">Lexer performance</td>
    <td style="white-space: nowrap; text-align: right">26.27</td>
    <td style="white-space: nowrap; text-align: right">1.95x</td>
  </tr>

  <tr>
    <td style="white-space: nowrap">Lexer + Formatter</td>
    <td style="white-space: nowrap; text-align: right">17.00</td>
    <td style="white-space: nowrap; text-align: right">3.01x</td>
  </tr>

  <tr>
    <td style="white-space: nowrap">Lexer compilation time</td>
    <td style="white-space: nowrap; text-align: right">2.36</td>
    <td style="white-space: nowrap; text-align: right">21.67x</td>
  </tr>

</table>



Memory Usage

<table style="width: 1%">
  <tr>
    <th>Name</th>
    <th style="text-align: right">Average</th>
    <th style="text-align: right">Factor</th>
  </tr>
  <tr>
    <td style="white-space: nowrap">Formatter performance</td>
    <td style="white-space: nowrap">6.95 MB</td>
    <td>&nbsp;</td>
  </tr>
    <tr>
    <td style="white-space: nowrap">Lexer performance</td>
    <td style="white-space: nowrap">40.88 MB</td>
    <td>5.88x</td>
  </tr>
    <tr>
    <td style="white-space: nowrap">Lexer + Formatter</td>
    <td style="white-space: nowrap">47.83 MB</td>
    <td>6.88x</td>
  </tr>
    <tr>
    <td style="white-space: nowrap">Lexer compilation time</td>
    <td style="white-space: nowrap">0.0300 MB</td>
    <td>0.0x</td>
  </tr>
</table>