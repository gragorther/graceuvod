<script>
	let name = 'cat';
	let clicks = 0;
	function clicker() {
		clicks = clicks + 1;
	}
</script>

<div
	class="items-center flex-col flex font-black text-2xl p-5 border-red-300 border-2 rounded-md bg-green-700 m-12"
>
	<h1 class="text-5xl">{name} x {clicks}</h1>
	<img on:click={clicker} src="macek.jpg" alt="a cat" width="30%" height="30%" class="my-5" />
	<p>
		The cat (Felis catus), also referred to as domestic cat or house cat, is a small domesticated
		carnivorous mammal. It is the only domesticated species of the family Felidae. Advances in
		archaeology and genetics have shown that the domestication of the cat occurred in the Near East
		around 7500 BC. It is commonly kept as a house pet and farm cat, but also ranges freely as a
		feral cat avoiding human contact. Valued by humans for companionship and its ability to kill
		vermin, the cat's retractable claws are adapted to killing small prey like mice and rats. It has
		a strong, flexible body, quick reflexes, and sharp teeth, and its night vision and sense of
		smell are well developed. It is a social species, but a solitary hunter and a crepuscular
		predator. Cat communication includes vocalizations—including meowing, purring, trilling,
		hissing, growling, and grunting–as well as body language. It can hear sounds too faint or too
		high in frequency for human ears, such as those made by small mammals. It secretes and perceives
		pheromones.
	</p>
	<a
		href="https://en.wikipedia.org/wiki/Cat"
		class="bg-yellow-400 text-white rounded-3xl hover:bg-yellow-800 px-20 shadow-xl"
		>More about cats</a
	>
</div>
