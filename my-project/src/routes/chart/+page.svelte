<!-- <script>
	import Table from './Table.svelte';
	import countrysArray from './countryDataStore.js';
	
	let redStyle = "redTable";
</script>

<div>
	
</div>

<Table tableData={$countrysArray} style={redStyle}/> -->


<script>
	export let tableData = [
			{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},
			{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},
			{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},
			{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},
			{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},
			{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},
			{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			},{
				"Flag":"https://mainfacts.com/media/images/coats_of_arms/mr.png",
                "Name" : "Mauritania",
		        "Population" : 4649660,
                "CIOC" : "MTN",
                "UN Member Status":"YES",
                "Currencies":"UM",
                "Language":["Arabic"]
			},
			{
				"Flag":"https://flagcdn.com/w320/er.png",
                "Name" : "Eritrea",
		        "Population" :  5352000,
		        "CIOC" : "ERI",
                "UN Member Status":"YES",
                "Currencies":"Nfk",
                "Language":["Arabic","English","Tigrinya"]
			}
		];
	export let style;
</script>
<main>
	<h1><b>ChartTable :</b></h1>
	<div class="chart-table">
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
	</div>
	
</main>



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
	.chart-table>div{
		max-width: min-content;
	}


</style>