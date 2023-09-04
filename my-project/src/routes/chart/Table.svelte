<script>
	export let tableData = [
			{
				"Flag":"",
                "Name" : "Maria",
		        "Population" : "Math",
		        "CIOC" : 14,
                "UN Member Status":"",
                "Currencies":"NOK",
                "Language":[""]
			},
			{
				"Flag":"",
                "Name" : "Maria",
		        "Population" : "Math",
		        "CIOC" : 14,
                "UN Member Status":"",
                "Currencies":"NOK",
                "Language":[""]
			}
		];
	export let style;
</script>

<table class={style}>
	<thead>
		<tr>
			{#each Object.keys(tableData[0]) as columnHeading}
				<th>{columnHeading}</th>
			{/each}
		<tr/>
	</thead>
	<tbody>
		{#each Object.values(tableData) as row}
			<tr>
				{#each Object.values(row) as cell}
					<td>{cell}</td>
				{/each}
			</tr>
		{/each}
	</tbody>
</table>

<style>
	table, th, td {
		border: 1px solid;
		border-collapse: collapse;
		margin-bottom: 10px;
	}
	
	table.redTable {
		border: 2px solid #221e1e;
		background-color: #EEE7DB;
		width: 100%;
		text-align: center;
		border-collapse: collapse;
	}

</style>