<link href="readme.css" type="text/css">

# Neural-Primatives
Description of some neural network primitives to build into larger network. I focus on time series but use it if it will be helpful to you.

## TL;DR

<table>
<thead>
    <th></th>
    <th>Produces</th>
    <th>Encoding</th>
</thead>
<tbody>
<tr>
    <th rowspan="2">MXNet</th>
    <td>.json</td>
    <td>text</td>
</tr>
<tr>
    <td>.param</td>
    <td>binary</td>
</tr>
<tr>
    <th>ONNx</th>
    <td>.onnx</td>
    <td>binary</td>
</tr>
<tr>
    <th>WMLF</th>
    <td>.wmlf</td>
    <td>binary</td>
</tr>
<tr>
    <th>WLNet</th>
    <td>.wlnet</td>
    <td>binary</td>
</tr>
</tbody>
<tfoot></tfoot>
</table>

## Formats

### MXNet

A network specified in MXNet will normally be specified by a <code>.json</code> file, and if the network has at least 
been initialized with weights and biases, then you will get a second, <code>.param</code> file.


### ONNX

### WMLF

### WLNet
