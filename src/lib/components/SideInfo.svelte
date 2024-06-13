<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from './ui/button';
</script>

<Card.Root class="border-2 bg-slate-100  dark:bg-slate-800">
	<Card.Header>
		<Card.Title>Colorful Pinata</Card.Title>
	</Card.Header>
	<Card.Content>
		<div>€49.99</div>
		<Button>Add to cart</Button>
	</Card.Content>
</Card.Root>
