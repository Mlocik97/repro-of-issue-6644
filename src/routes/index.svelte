<script>
	let person = {};
	
	(person.adresse ??= {}).city ??= "New York";
</script>

<h1>Hello {person?.adresse?.city}!</h1>