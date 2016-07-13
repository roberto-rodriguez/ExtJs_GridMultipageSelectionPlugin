<br>
<h1>Ext.ux.grid.GridMultipageSelection</h1>

<br>
   Grid plugin that keeps the selection across the pages in the pagination grid.
   Also includes a function named: getSelection() to the grid, which returns the 
   an array with the ids of the selected rows.
<br>   
   The plugin assumes there is a column with  dataIndex: 'id'
<br>
<br>
  Copyright 2016 Roberto Rodriguez
<br>

<img src="http://res.cloudinary.com/titorobe/image/upload/v1468372258/ExtJs_GridMultipageSelectionPlugin_ct7yjh.jpg"></img>

<br>
 
  Example:
var grid = new Ext.grid.GridMultipageSelection({
	 columns: [
		 {
			 text: "User ID",
			 dataIndex: 'id', 
			 filter: true
		 },
		 {
			 text: "First Name",
			 dataIndex: 'firstName', 
			 filter: true
		 },
		 {
			 text: "First Name",
			 dataIndex: 'firstName', 
			 filter: lastName
		 }
	 ], 
	 selModel: {
	 selType: 'checkboxmodel' 
	 }
	 plugins: [ 
		{ptype: "gridMultipageSelection"}
	 ]
	 ...
 });
</code></pre>


<br>

<p2>Change Logs</p2>
<ul>
<li><p>0.1 version</p>

<ul>
	<li>Initial Commit</li>
</ul>

</ul>