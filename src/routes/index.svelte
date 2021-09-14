<script>
	import { NotificationDisplay, notifier } from '@beyonk/svelte-notifications';

	function someFunction() {
		notifier.success('Notifications work!', 5000);
		console.log('click');
	}
</script>

<NotificationDisplay />

<button on:click={someFunction}>Show message</button>
