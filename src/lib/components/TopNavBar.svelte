<script>
	const items = [
		{
			icon: 'linkedin',
			url: 'https://www.linkedin.com/in/eric-muckley/'
		},
		{
			icon: 'github',
			url: 'https://github.com/ericmuckley'
		},
		{
			icon: 'google',
			url: 'https://scholar.google.com/citations?hl=en&user=KnSc4mMAAAAJ'
		},
		{
			icon: 'stack-overflow',
			url: 'https://stackoverflow.com/users/9325130/eric-m'
		},
		{
			icon: 'qr-code',
			url: 'https://orcid.org/my-orcid?orcid=0000-0001-7114-5424'
		},
		{
			icon: 'bitcoin',
			url: 'https://etherscan.io/nft/0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85/16561330396975658982490556095357067459272494376517736647370872103408124334768'
		}
	];
</script>

<nav class="flex px-4 py-3 space-x-2 justify-between">
    <p class="font-mono">eric muckley</p>
	<div class="flex space-x-4">
		{#each items as item}
			<a href={item.url} target="_blank">
				<i class="bi bi-{item.icon}" />
			</a>
		{/each}
	</div>
</nav>
