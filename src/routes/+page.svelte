<script>
	let core = ''

	const inserircore = ()=>{
		core='❤'
	}


	const tirarcore = ()=>{
		core=''
	}




</script>
<button class= 'w-12 h-6 m-3 rounded-md text-white bg-red-700' on:click={inserircore} >
	click 		
</button>
<button class= 'w-12 h-6 m-3 rounded-md text-white bg-red-700' on:click={tirarcore}>
	click 2 		
</button>
<div class='w-36 h-36 bg-blue-600 flex justify-center items-center'>
	<div class='w-24 h-24 bg-gray-200 flex justify-center items-center animate'>
		<div class= 'w-12 h-12 bg-pink-500 flex justify-center items-center animate'>
			<div   class='w-8 h-8 animate text-white bg-black flex justify-center items-center' >
				{core}
			</div>
		</div>
	</div>
</div>




