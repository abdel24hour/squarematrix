<p>Given a square matrix m[3x3], create a java code to calculate the value of its SECONDARY Diagonal. See example below.</p>
<p><strong>Hint:</strong>&nbsp;In order to better understand the concepts involved in this exercises, research the terms &ldquo;square matrix&rdquo; and &ldquo;secondary diagonal of a matrix&rdquo; using your favourite search engine.</p>
<p>Example given matrix m[3x3] shown below:</p>
<div class="responsive">
<table class="table table-condensed">
<tbody>
<tr>
<td>(0,0) (0,1) (0,2)</td>
<td>|</td>
<td>10 &emsp; 12 &emsp;11</td>
</tr>
<tr>
<td>(1,0) (1,1) (1,2)</td>
<td>|</td>
<td>9 &emsp; 8 &emsp; 31</td>
</tr>
<tr>
<td>(2,0) (2,1) (2,2)</td>
<td>|</td>
<td>2 &emsp; 16 &emsp;24</td>
</tr>
</tbody>
</table>
</div>
<p>Secondary Diagonal (generic m[3x3]) = m[0,2] + m[1,1] + m[2,0]<br />Secondary Diagonal (as in the example above) = 11 + 8 + 2 = 21</p>
<p><strong>Note 1:</strong>&nbsp;Your java code MUST be GENERIC to calculate the secondary diagonal of ANY square matrix [2x2], [3x3],[4x4], etc. (Use a constant in your code to set the values of numberOfRows and numberOfColumns of your matrix.</p>
<p><strong>Note 2:</strong>&nbsp;Your matrix m may be hardcoded (no need of user interaction)</p>
<p><strong>Note 3:</strong>&nbsp;In case numberOfRows and numberOfColumns ar differents, your program must display the following message: &ldquo;This is not a square matrix.&rdquo;</p>
